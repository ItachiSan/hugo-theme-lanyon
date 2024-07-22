# Lanyon - Hugo edition

This is the port of the original theme to [Hugo](https://gohugo.io).

Lanyon is an unassuming [Jekyll](http://jekyllrb.com) theme that places content
first by tucking away navigation in a hidden drawer.
It's based on [Poole](http://getpoole.com), the Jekyll butler.

## Features

- Minimal & responsive site
- Mobile friendly
- Blog oriented
- Baked in cookie warning via CookieConsent
- (Optional) Easy share via AddToAny
- (Optional) Comments via Disqus
- (Optional) Analytics via Google Analytics

## Installation

The best way to install this theme is via a Git submodule:
```console
git submodule add https://github.com/ItachiSan/hugo-theme-lanyon themes/lanyon
```
and then add the relevant theme keyword in your configuration file:
```yaml
theme: lanyon
```

If you wish to use the provided syntax highlight CSS, remember to add in your
configuration:
```yaml
markup:
  highlight:
    noClasses: false
```

## Configuration
The theme has many configuration options, all of them are present in
[config.yaml](config.yaml) within the `params` section.

All of them are documented.

## Quirks
Here are mentioned the various quirks of this theme:
* Since this was a Jekyll theme, pages and posts are handled slightly different compared to Hugo.
* RSS feeds are named `atom.xml` rather than `index.xml`.
