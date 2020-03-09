[![ThinkPrivacy](https://www.thinkprivacy.ch/assets/images/2019_logo.png)](https://www.thinkprivacy.ch/)

[![](https://img.shields.io/badge/Made%20With-Jekyll-green.svg)](https://jekyllrb.com/) [![Netlify Status](https://api.netlify.com/api/v1/badges/2cff0d22-54e5-45ca-9350-305b5258c551/deploy-status)](https://app.netlify.com/sites/inspiring-cray-be7eef/deploys)

# Contributing

It's important for a website like ThinkPrivacy.ch to be up-to-date and easy to use for new users. Keep an eye on software updates of the applications listed here. Follow recent news about providers that are recommended. We try our best to keep up but we're not perfect and the internet is changing fast. So if you find an error, or you think a provider should not be listed here, or a qualified service provider is missing or a browser plugin is not the best choice anymore or anything else.

**Please see our [contributing guidelines](.gitlab/CONTRIBUTING.md) to learn more.**

**Chat with us.** Find us on [Twitter](https://www.twitter.com/ThinkPrivacyIO) or visit the [contact page](https://thinkprivacy.ch/contact.html) and contact the administrator, Dan Arel. This is becoming a community project, and we're aiming to deliver the best information available for better privacy for all.

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
$ npm install -g n

$ sudo n 11.15.0

$ npm install gulp@^3.9.1
$ npm install 
$ npm rebuild node-sass
```

This will install node v11.15.0 and gulp v3.9.1, newer versions are not compatibile with this compiler script. 

# Support ThinkPrivacy.ch

- [Donate.](https://thinkprivacy.ch/donate.html)
- [Make suggestions on Twitter.](https://www.twitter.com/ThinkPrivacyIO)
- View and edit our website source code here on GitLab.

# Information and License

Copyright 2018-2019 Dan Arel and contributors, and licensed under Creative Commons Attribution-Share Alike 4.0.
