rails-frontperf
===============

[WIP] provides a bunch of best practices to speed rails frontend, in one gem.

- inline JS/CSS
- inline images (Data URI)
- ImageOptim / produce multiple sizes.
- load images async (to avoid blocking onload)
- load partials async (avoid bottle-neck)
- activate Deflate
- tiny indicator for Turbolink
- WebP fallback & converter
- provide jQuery alternative (avoid 100KB)
- provide FastClick alternative (lighter one)
- provide Analytics helpers to do well with Turbolink
- prefetch the next page for Turbolink.
- page transition (like Medium)
- omit unnecessary CSS (uncss)
- load JS/CSS async
- minify html
- compress/minimize images before upload (using Canvas)
- sort css style to improve compress rate (csscomb)

Helpers
=====
- provides a indicator to check whether rails cache (Russian Doll) is hit.

Offline Support
=====
- provides a way to handle AppCache easier
- localStorage & sync
- helper: provides a way to simulate ugly network. (always slow and often stops)

Future
======

- omit unnecessary JS
- inline font
- make a subset of font to reduce its size
- zopfli gzipping
- compress image before upload (with webworker)
- leverage webworker to avoid evaluating JS in UI thread. (Models should be.)
