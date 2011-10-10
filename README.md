# About

A clean concise theme for your GitHub projects from [Fublo](http://fublo.net). You can see a working example [here](http://fublo.github.com/gh-pages-theme).

The theme uses skeleton to provide a responsive layout so even looks great on mobile devices!

It comes with a download button, syntax highlighting and a section at the bottom to credit yourself with.

# Installation

To install the theme to the `gh-pages` branch of your repository just run the following line. Remember, this will create a new branch called `gh-pages` wiping any current branch called `gh-pages`.

    git remote add gh-pages-theme git@github.com:fublo/gh-pages-theme.git; git fetch gh-pages-theme; git checkout -b gh-pages gh-pages-theme/master;

Alternatively you can just [download and extract this zip](https://github.com/fublo/gh-pages-theme/zipball/master).

So this will:

 * Add the remote `gh-pages-theme` which points to the themes repository.
 * Fetch the repository.
 * Create the new branch `gh-pages` from the fetched data.

# Configuration

You will need to configure the following elements.

 * The GitHub ribbons - Located near the bottom of the HTML. You can change the colour and link
 * The download button link
 * The pages title tag
 * All content, examples, descriptions etc. Leaving lorum ipsum laying about does not look good. This includes the first part of the footer, please leave the very last line.

# Compatibility

Works perfectly in the following browsers.

 * Chrome
 * Firefox 4+ (syntax highlighting is broken below)
 * Safari
 * Opera
 * Internet Explorer 7+ (6 begins to break down with image transparency and alignment issues)

# Licence

A clean concise theme for your GitHub projects

Copyright (C) 2011 Fublo Ltd

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/gpl.html>.