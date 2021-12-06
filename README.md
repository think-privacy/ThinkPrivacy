# ThinkPrivacy

[![](https://img.shields.io/badge/Made%20With-Jekyll-green.svg)](https://jekyllrb.com/)

# Contributing

It's important for a website like ThinkPrivacy.ch to be up-to-date and easy to use for new users. Keep an eye on software updates of the applications listed here. Follow recent news about providers that are recommended. We try our best to keep up but we're not perfect and the internet is changing fast. So if you find an error, or you think a provider should not be listed here, or a qualified service provider is missing or a browser plugin is not the best choice anymore or anything else.

**Please see our [contributing guidelines](.github/CONTRIBUTING.md) to learn more.**

**Chat with us.** Find us on [Twitter](https://www.twitter.com/ThinkPrivacy_) or visit the [contact page](https://thinkprivacy.ch/contact/) and contact the administrator, Dan Arel. This is becoming a community project, and we're aiming to deliver the best information available for better privacy for all.

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

Copyright 2018-2021 Dan Arel and contributors, and licensed under Creative Commons Attribution-Share Alike 4.0.