[![Build Status](https://travis-ci.org/spencerkclark/website.svg?branch=master)](https://travis-ci.org/spencerkclark/website)

Personal website
----------------

This repository contains both the source code for building, and the actual
content of my personal website.  I use the [static site generator `lektor`](https://www.getlektor.com) for
generating the pages of this website and
the [`hyde` theme](https://github.com/poole/hyde) for the layout (which I
adapted for use with `lektor`).  Upon pushing updates to the master branch of
this repository, things are configured such that the website is automatically
re-built using Travis CI, and the updates are pushed to the gh-pages branch.
- For more on `lektor`, see
  this [introductory blog post](http://lucumr.pocoo.org/2015/12/21/introducing-lektor/).
- For more on automating `lektor` builds for GitHub pages with Travis CI
  see [here](https://www.getlektor.com/docs/deployment/travisci/).
