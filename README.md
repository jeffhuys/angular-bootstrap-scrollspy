# bootstrap.scrollspy

Pure AngularJS component replicating [Twitter Bootstrap's Scrollspy](http://twitter.github.io/bootstrap/javascript.html#scrollspy) component behavior.
The scrollspy behavior enables to automatically update nav targets based on scroll position.

## Getting Started

Download the [production version][min] or the [development version][max].

[min]: https://raw.github.com/mgcrea/jquery-bootstrap-scrollspy/master/dist/angular-bootstrap-scrollspy.min.js
[max]: https://raw.github.com/mgcrea/jquery-bootstrap-scrollspy/master/dist/angular-bootstrap-scrollspy.js

In your web page:

```html
<script src="bower_components/angular/angular.js"></script>
<script src="bower_components/angular-bootstrap-scrollspy/dist/angular-bootstrap-scrollspy.min.js"></script>
<script src="scripts/app.js"></script>
```

In your app.js:

```js
angular.module('myApp', ['mgcrea.bootstrap.scrollspy'])
```

## Documentation

+ To easily add scrollspy behavior to any element, just add `bs-scrollspy` to the body element with a `data-target` attribute of the element you want to spy on.

+ Check [Twitter Bootstrap's Scrollspy](http://twitter.github.io/bootstrap/javascript.html#scrollspy) docs.

## Examples

```html
<body ng-controller="MainCtrl" bs-scrollspy data-target=".bs-docs-main" data-offset="auto">
```
