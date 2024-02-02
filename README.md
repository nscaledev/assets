# NSCALE Assets

![NSCALE Logo](./img/nscale/blue/logo.svg#gh-light-mode-only)
![NSCALE Logo](./img/nscale/white/logo.svg#gh-dark-mode-only)

This repository contains all static assets used for company branding in various applications.
These include, but are not limited to, images and CSS.

## Use in Your Web Application

For now, these assets are served with GitHub pages.
To use them, use the following prefix, then the path as illustrated below:

```
https://assets.nscale.com/<path>
```

## Conventions

Files, where appropriate, are intuitively named:

* `adaptive` - for use on any background, the image will use the `currentColor` for black/white elements. However this requires the SVG contents to be in the DOM, so you must inject the SVG and not use an `<img>` tag.  You can use [svg-inject](https://github.com/iconfu/svg-inject) to perform this task.
