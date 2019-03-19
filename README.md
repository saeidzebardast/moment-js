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

## License

MIT © [Saeid Zebardast](http://zebardast.com)
