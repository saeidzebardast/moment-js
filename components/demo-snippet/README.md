# demo-snippet
This is simple element that will render both the source and demo of a
code snippet. It can be used for both native elements and
Polymer elements.

<img width="693" alt="screen shot 2015-10-29 at 3 41 20 pm" src="https://cloud.githubusercontent.com/assets/1369170/10834051/881910ae-7e53-11e5-834e-c65aacb91c0a.png">

# Example
You can use native elements and custom elements in your demo:
```html
<demo-snippet>
  <input type="date">
  <paper-checkbox checked>Checkbox</paper-checkbox>
</demo-snippet>
```

## Usage
Install with bower:
```
mkdir demo-snippet-shenanigans && cd demo-snippet-shenanigans
bower install demo-snippet
```
Drop it in a page, next to the newly created `bower_components` folder. If you'll
be using it to render (for example) Polymer elements, make sure that the elements
you are demo-ing are included correctly:

```html
<!doctype html>
<html>
  <head>
    <meta charset="utf-8">
    <title>zomg deos</title>
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bower_components/paper-checkbox/paper-checkbox.html">
    <link rel="import" href="bower_components/demo-snippet/demo-snippet.html">
  </head>
  <body>
    <demo-snippet>
      <input type="date">
      <paper-checkbox checked>Checkbox</paper-checkbox>
    </demo-snippet>
  </body>
</html>
```
