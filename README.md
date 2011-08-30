# About

A clean concise theme for your GitHub projects from [Fublo](http://fublo.net). You can see a working example [here](http://fublo.github.com/gh-pages-theme).

The theme uses skeleton to provide an adaptive layout so even looks great on mobile devices!

It comes with a download button, syntax highlighting and a section at the bottom to credit your self with.

# Installation

To install the theme to the `gh-pages` branch of your repository just run the following line. Remember, this will create a new branch called `gh-pages` wiping any current branch called `gh-pages`.

    git remote add gh-pages-theme git@github.com:fublo/gh-pages-theme.git; git fetch gh-pages-theme; git checkout -b gh-pages gh-pages-theme/master; git submodule update --init

So this will add the remote `gh-pages-theme` which points to the themes repository.

Fetch the repository.

Create the new branch `gh-pages` from the fetched data.

And finally update the submodules which will download skeleton.

# Configuration

You will need to configure the following elements.

 * The GitHub ribbons - Located near the bottom of the HTML. You can change the colour and link
 * The download button link
 * The pages title tag
 * All content, examples, descriptions etc. Leaving lorum ipsum laying about does not look good. This includes the first part of the footer, please leave the very last line.
