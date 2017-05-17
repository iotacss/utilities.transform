**iotaCSS is now a monorepo and all individual repositories are part of it. Please open issues or PRs here: [https://github.com/iotacss/iotacss](https://github.com/iotacss/iotacss).**

# Transform Utility #

The transform utility contains helper classes for the CSS text transform property.


### Installation ###

```
npm install --save iotacss-utils-transform
```


### Options ###

```sass
$iota-utils-transform-namespace       : '' !default;
$iota-utils-transform-capitalize-name : 'capitalize' !default;
$iota-utils-transform-uppercase-name  : 'uppercase' !default;
$iota-utils-transform-lowercase-name  : 'lowercase' !default;

$iota-utils-transform-res             : false !default;
$iota-utils-transform-breakpoints     : $iota-global-breakpoints !default;
```


### Classes ###

```
.u-capitalize
.u-uppercase
.u-lowercase


// Responsive Class Syntax

.u-[name]@[breakpoint-name]  // Example: .u-capitalize@sm
```
