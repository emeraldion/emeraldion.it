# haley

A static build of the emeraldion.it blog with markdown based on jekyll, gulp, Sass, and browsersync.

## Setup

To use this project, you'll need the following things installed on your machine.

1. [Bundler](http://bundler.io/) - `$ gem install bundler`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `$ bundle install && npm install`.

## Usage

Launching gulp will give you file watching, browser synchronization, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

Moreover, as this is just a Jekyll project, any of the commands listed in the [docs](http://jekyllrb.com/docs/usage/) can be used.

## Deploy to `gh-pages`

This project can deploy the site build to the `gh-pages` branch using the `gulp-gh-pages` plugin:

```shell
$ gulp deploy
```

# Acknowledgements

Based on [shakyShane/jekyll-gulp-sass-browser-sync](https://github.com/shakyShane/jekyll-gulp-sass-browser-sync).

# License

Code is released under [MIT](http://opensource.org/licenses/MIT) license.

Content is released as [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)

Copyright (c) Claudio Procida 2015
