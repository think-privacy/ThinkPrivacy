# ThinkPrivacy

[![](https://img.shields.io/badge/Made%20With-Jekyll-green.svg)](https://jekyllrb.com/)


## Building

1. Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
1. Install [bundler](https://bundler.ch/) by running `gem install bundler`.
1. Run `bundle install` to install the required dependencies.
1. Use `bundle exec jekyll build` to build the website. The output can be found in the `_site` directory.  Live preview is also possible by running `bundle exec jekyll serve`

### Compiling Styles

The current theme is based on Ghost's Casper and the CSS is compiled as [described here](https://github.com/tryghost/casper#development):

This site's styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need Node and Gulp installed globally. After that, from the theme's root directory:

```bash
$ npm install
$ gulp
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

If you have issues getting Gulp to run properly, run the following commands inside the directory:

```bash
$ sudo npm install -g n

$ sudo n 11.15.0

$ sudo npm install gulp@^3.9.1
$ sudo npm install 
$ sudo npm rebuild node-sass
```

This will install node v11.15.0 and gulp v3.9.1, newer versions are not compatibile with this compiler script. 

# Information and License

Copyright 2018-2021 ThinkPrivacy & Dan Arel.