[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/daKmoR/grain-ajax-app)
[![Polymer Version](https://img.shields.io/badge/polymer-v2-blue.svg)](https://www.polymer-project.org)

# \<grain-ajax-app\>

All local anchor hrefs will be loaded via ajax and content inside grain-ajax-app will be replaced.

## Demo
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="grain-ajax-app.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<grain-ajax-app>
  <h3>Part ONE</h3>
  <div>
    I am the first thing you will see.
    <a href="demo/page2.html">Part TWO will be here.</a>
  </div>
</grain-ajax-app>
```

## Installation

```sh
$ bower install --save daKmoR/grain-ajax-app
```

## Getting Started

Import the package.

```html
<link rel="import" href="/bower_components/grain-ajax-app/grain-ajax-app.html">
```

*For more information, see the API documentation.*

## Working on the Element

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed.
* View the Element via `polymer serve`
* Run tests via `polymer test`
