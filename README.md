[![Deploy
Status](https://github.com/spencerkclark/website/workflows/deploy/badge.svg?branch=master)](https://github.com/spencerkclark/website/actions)

Personal website
----------------

This repository contains both the source code for building, and the actual
content of my personal website.  I use the [static site generator `lektor`](https://www.getlektor.com) for
generating the pages of this website and
the [`hyde` theme](https://github.com/poole/hyde) for the layout (which I
adapted for use with `lektor`).  Upon pushing updates to the master branch of
this repository, things are configured such that the website is automatically
re-built using GitHub Actions, and the updates are pushed to the gh-pages branch.
- For more on `lektor`, see
  this [introductory blog post](http://lucumr.pocoo.org/2015/12/21/introducing-lektor/).
- For more on automating `lektor` builds for GitHub pages with GitHub Actions see    [here](https://github.com/lektor/lektor-website/pull/302) and [here](https://github.com/marketplace/actions/deploy-to-github-pages).
