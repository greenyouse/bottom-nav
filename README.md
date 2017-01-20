# \<bottom-nav\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/greenyouse/bottom-nav)

Bottom navigation for mobile that follows the [Material Design specification](https://material.io/guidelines/components/bottom-navigation.html).

<!-- 
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="../app-layout/demo/sample-content.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <link rel="import" href="bottom-nav.html">
    <link rel="import" href="bottom-toolbar.html">
    <link rel="import" href="bottom-tab.html">
    <style is="custom-style">
     bottom-nav {
       background-color: var(--primary-color);
       color: #fff;
     }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
 -->

 ```html
    <bottom-nav>
      <bottom-toolbar selected="0">
        <bottom-tab label="home" icon="icons:home"></bottom-tab>
        <bottom-tab show-label label="lists" icon="icons:menu"></bottom-tab>
        <bottom-tab label="closers" icon="icons:close"></bottom-tab>
        <bottom-tab label="next" icon="icons:chevron-right"></bottom-tab>
      </bottom-toolbar>
    </bottom-nav>
    <sample-content size="10"></sample-content>
 ```

## Installation

```sh
$ bower install greenyouse/bottom-nav --save
```

## Import

```html
<link rel="import" href="/bower_components/bottom-nav/bottom-nav.html">
```

## Credits

This is a fork of [paper-tabs](https://www.webcomponents.org/element/PolymerElements/paper-tabs) and [app-layout](https://www.webcomponents.org/element/PolymerElements/app-layout).
