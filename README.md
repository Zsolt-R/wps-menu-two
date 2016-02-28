# wps-menu-two
WPS Theme Module - Full-Screen Pop-Out Navigation

**Add module to your child theme**

1) link module  in functions.php

`require get_stylesheet_directory() . '/theme-modules/wps-menu-one/wps-module-mt-init.php';`


2) Copy .scss component from assets/sass/project to SCSS project: `_components.main-nav-two.scss`


3) Import into style.scss:  `@import "project/components.main-nav-two";`


4) Extend default component, copy the style from assets/sass/project/: `_components.page-head.scss`

```css
// Adjust logo
.brand-logo{
    @include media-query(palm){
    display: block;
    max-height:45px;
    float:left;
    }
}
```
****

ref: https://codyhouse.co/gem/full-screen-pop-out-navigation/

