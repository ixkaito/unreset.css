# Unreset CSS [![npm](https://img.shields.io/npm/v/unreset-css.svg)](https://www.npmjs.com/package/unreset-css)

Unreset CSS restores browsers' default element styles which are reset by [Eric Meyer's Reset CSS](http://meyerweb.com/eric/tools/css/reset/), [YUI 3 Reset CSS](http://yuilibrary.com/yui/docs/cssreset/), [HTML5 Reset Stylesheet of HTML5 Doctor](http://html5doctor.com/html-5-reset-stylesheet/), or [Tim Murtaugh's HTML5 Reset](http://html5reset.org/).

Unreset CSS is based on browsers' default styles:

- [Firefox (Gecko)](https://dxr.mozilla.org/mozilla-central/source/layout/style/res/html.css) or browse to `resource://gre-resources/html.css` on your Firefox.
- [Chrome (Chromium Blink)](https://chromium.googlesource.com/chromium/blink/+/master/Source/core/css/html.css)
- [Safari (WebKit)](http://trac.webkit.org/browser/trunk/Source/WebCore/css/html.css)
- [Internet Explorer 9](http://www.iecss.com/ie-9.css)
- [Edge](http://www.iecss.com/edgehtml-13.10586.css)
- [Opera](http://www.iecss.com/opera-10.51.css)

The sources are in the `[defaults](https://github.com/ixkaito/unreset-css/tree/master/defaults)` directory.

## Install

**With npm:**

```shell
$ npm install --save unreset-css
```

**Or, download manually:**

[![unreset.css](https://img.shields.io/badge/Download-unreset.css-brightgreen.svg)](https://raw.githubusercontent.com/ixkaito/unreset-css/master/unreset.css) [![unreset.min.css](https://img.shields.io/badge/Download-unreset.min.css-brightgreen.svg)](https://raw.githubusercontent.com/ixkaito/unreset-css/master/unreset.min.css)

## Import

**Sass:**

```scss
.unreset {
    @import 'node_modules/unreset-css/unreset';
}
```

**CSS:**

```html
<link rel="stylesheet" href="unreset.css">
```

or 

```html
<link rel="stylesheet" href="unreset.min.css">
```

## Usage

Add a `unreset` class to the container of the elements needing to be unreset.

```html
<div class="unreset">
    <h1>This is an H1</h1>
    <p>This is a paragraph.</p>
    <ul>
        <li>This is a list item.</li>
        <li>This is a list item.</li>
    </ul>
</div>
```

## License

MIT © [Kite](https://github.com/ixkaito)
