# \<bottom-nav\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/greenyouse/bottom-nav)

Bottom navigation for mobile that follows the [Material Design specification](https://material.io/guidelines/components/bottom-navigation.html).

<!-- 
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.min.js"></script>
    <link rel="import" href="../app-layout/demo/sample-content.html">
    <link rel="import" href="../iron-icons/av-icons.html">
    <link rel="import" href="../iron-icons/iron-icons.html">
    <link rel="import" href="../iron-icons/image-icons.html">
    <link rel="import" href="../iron-icons/notification-icons.html">
    <link rel="import" href="../paper-styles/paper-styles.html">
    <link rel="import" href="bottom-nav.html">
    <link rel="import" href="bottom-toolbar.html">
    <link rel="import" href="bottom-tab.html">
    <style is="custom-style">
     bottom-nav {
       background-color: var(--primary-color);
       color: #fff;
     }

     .grey {
       background-color: #465C64;
     }

     .green {
       background-color: #0E8767;
     }

     .brown {
       background-color: #8B6A65;
     }

     .darkbrown {
       background-color: #6C4845;
     }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
 -->

 ```html
    <bottom-nav shadow>
      <bottom-toolbar selected="0">
        <bottom-tab  selected-class="grey" label="Movies & TV" icon="notification:ondemand-video"></bottom-tab>
        <bottom-tab  selected-class="green"label="Music" icon="image:music-note"></bottom-tab>
        <bottom-tab  selected-class="brown"label="Books" icon="icons:book"></bottom-tab>
        <bottom-tab  selected-class="darkbrown" label="Newstand" icon="av:web"></bottom-tab>
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
