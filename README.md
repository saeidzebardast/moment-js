# \<moment-js\>

[![Build Status](https://travis-ci.org/saeidzebardast/moment-js.svg?branch=master)](https://travis-ci.org/saeidzebardast/moment-js)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/saeidzebardast/moment-js)

A [Polymer](https://www.polymer-project.org) element to parse, validate, manipulate, and display dates using [Moment.js](http://momentjs.com/).

## Install

```shell
bower install moment-js
```

## Usage

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="moment-js.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<moment-js></moment-js>
<moment-js format="YYYY-MM-DD HH:mm:ss"></moment-js>
<moment-js date="2016-01-10 14:30" date-format="YYYY-MM-DD HH:mm" format="LLLL"></moment-js>
<moment-js date="2012-09-21" date-format="YYYY-MM-DD" format="LLLL" formatted-date="{{myDate}}" hide></moment-js>
<moment-js date="2016-01-10 14:30" calendar-time></moment-js>
```

## Docs & Demo

See the [component page](http://saeidzebardast.github.io/moment-js) for docs and demo.

## Running demos and tests in a browser

1. Fork the `moment-js` repository and clone it locally.

2. Make sure you have [Bower](https://bower.io) installed.

3. When in the `moment-js` directory, `polymer install` to install dependencies.

4. Run `polymer analyze moment-* > analysis.json && polymer serve --port 3000 --open`, browser will automatically open the component API documentation.

5. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

- http://127.0.0.1:3000/components/moment-js/demo
- http://127.0.0.1:3000/components/moment-js/test

## License

MIT © [Saeid Zebardast](http://zebardast.com)
