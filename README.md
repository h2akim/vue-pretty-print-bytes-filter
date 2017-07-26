# vue-pretty-print-bytes-filter

Fork of [james2doyle/vue-pretty-print-bytes-filter](https://github.com/james2doyle/vue-pretty-print-bytes-filter)

Add precision options to the filter

### Original README

A filter for Vue.js to format bytes into a nice human-readable format. I pretty (no pun intended) much just stole this from [sindresorhus/pretty-bytes](https://github.com/sindresorhus/pretty-bytes).

### Install

Available through npm as `vue-pretty-bytes-filter`, or include as an inline script.

### Usage

Template:

```html
<em>{{ 1337 | prettyBytes(3) }}</em>
```

Render:

```html
<em>1.34 kB</em>
```