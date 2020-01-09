# user-interface

## HTML/CSS Weight Lifting Journal

###### How to Install

```
git clone
```
into any location

###### This project uses LESS!

Inside the index.less file is the imports to the individual LESS/CSS files in the following order

```
//VARIABLES & MIXINS
@import 'variables.less';
@import 'mixins.less';

// GENERAL STYLES
@import 'reset.less';
@import 'global.less';

// COMPONENTS
@import 'navigation.less';
@import 'home.less';
@import 'middle.less';
@import 'main.less';
@import 'footer.less';
@import 'about.less';
```

Only append LESS files. Do **NOT** change the order.