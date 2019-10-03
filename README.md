![Fomantic Logo](https://fomantic-ui.com/images/logo.png#128)
<img src="https://sass-lang.com/assets/img/logos/logo-b6e1ef6e.svg" alt="Sass Logo" height="128" />

# Fomantic-ui-sass

[![npm downloads](https://img.shields.io/npm/dm/fomantic-ui-sass.svg?label=npm%20downloads)](https://www.npmjs.com/package/fomantic-ui-sass)
[![npm version](https://img.shields.io/npm/v/fomantic-ui-sass)](https://www.npmjs.com/package/fomantic-ui-sass)

A community fork of the popular Semantic-UI framework.

The sass version of fomantic ui. It is fully customizable with isolated variable names.
Each component variable file is accompanied by a json file of the same name associating the name of the variable in the LESS version with its new name of the SASS version.

All variables of the original project are customizable. You can take a look at the source code on github.

Don't forget to manually copy the theme folder to the assets folder of your site. It's up to you to manage manually so that the icons fonts are downloaded by the browser.

# NOTE

The package only has the default theme.

# Installation and Usage

```sh
npm i -D fomantic-ui-sass
```

## SCSS Usage

```scss
@import 'node-modules/fomantic-ui-sass/src/variables.scss';
@import '???/custom.scss';
@import 'node-modules/fomantic-ui-sass/src/semantic-ui.scss';
```

### Attention!

If you want to modify in your personalized file a variable which can generate derivatives like the colors and their variants please do it and put in front your personalized file in order to have conforming derivatives.

## CSS Usage

```css
@import 'node-modules/fomantic-ui-sass/dist/semantic-ui.css';
```

# Customization and choice of components and their variants

## Button

```scss
$use-button: true !default;
//Types
$use-button-type-animated: true !default;
$use-button-type-labeled: true !default;
$use-button-type-basic: true !default;
$use-button-type-inverted: true !default;
$use-button-type-tertiary: true !default;
//Variations
$use-button-variation-social: 'facebook', 'twitter', 'google', 'google plus',
  'linkedin', 'youtube', 'instagram', 'pinterest', 'vk', 'whatsapp', 'telegram' !default;
$use-button-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
$use-button-variation-consequences: 'positive', 'negative' !default;
```

## Header

```scss
$use-header: true !default;
$use-header-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Input

```scss
$use-input: true !default;
//Variations
$use-input-variation-icon: true !default;
$use-input-variation-labeled: true !default;
$use-input-variation-action: true !default;
$use-input-variation-transparent: true !default;
$use-input-variation-inverted: true !default;
```

## Label

```scss
$use-label: true !default;
//Types
$use-label-type-image: true !default;
$use-label-type-pointing: true !default;
$use-label-type-corner: true !default;
$use-label-type-tag: true !default;
$use-label-type-ribbon: true !default;
$use-label-type-horizontal: true !default;
$use-label-type-attached: true !default;
$use-label-type-floating: true !default;
//Variations
$use-label-variation-circular: true !default;
$use-label-variation-basic: true !default;
$use-label-variation-inverted: true !default;
$use-label-variation-basic-pointing: true !default;
$use-label-variation-basic-tag: true !default;
$use-label-variation-colors: $colors-variations-names !default;
```

## List

```scss
$use-list: true !default;
//Types
$use-list-type-bulleted: true !default;
$use-list-type-link: true !default;
$use-list-type-ordered: true !default;
//Variations
$use-list-variation-horizontal: true !default;
$use-list-variation-inverted: true !default;
$use-list-variation-selection: true !default;
$use-list-variation-divided: true !default;
$use-list-variation-celled: true !default;
$use-list-variation-relaxed: true !default;
```

## Loader

```scss
//-------------- Loader ------------------*/
$use-loader: true !default;
//Variations
$use-loader-variation-inverted: true !default;
$use-loader-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Reveal

```scss
//-------------- Reveal ------------------*/
$use-reveal: true !default;
//Types
$use-reveal-type-fade: true !default;
$use-reveal-type-slide: true !default;
$use-reveal-type-move: true !default;
$use-reveal-type-rotate: true !default;
```

## Segment

```scss
//-------------- Segment ------------------*/
$use-segment: true !default;
//Types
$use-segment-type-placeholder: true !default;
$use-segment-type-piled: true !default;
$use-segment-type-stacked: true !default;
//Variations
$use-segment-variation-inverted: true !default;
$use-segment-variation-attached: true !default;
$use-segment-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Step

```scss
//-------------- Step ------------------*/
$use-step: true !default;
//Types
$use-step-type-ordered: true !default;
$use-step-type-vertical: true !default;
//Variations
$use-step-variation-inverted: true !default;
$use-step-variation-attached: true !default;
```

## Breadcrumb

```scss
//-------------- Breadcrumb ------------------*/
$use-breadcrumb: true !default;
//Variations
$use-breadcrumb-variation-inverted: true !default;
```

## Menu

```scss
//-------------- Menu ------------------*/
$use-menu: true !default;
//Types
$use-menu-type-secondary: true !default;
$use-menu-type-pointing: true !default;
$use-menu-type-tabular: true !default;
$use-menu-type-text: true !default;
$use-menu-type-vertical: true !default;
$use-menu-type-pagination: true !default;
//Variations
$use-menu-variation-inverted: true !default;
$use-menu-variation-attached: true !default;
$use-menu-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green', 'teal',
  'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Message

```scss
//-------------- Message ------------------*/
$use-message: true !default;
//Variations
$use-message-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
$use-message-variation-consequences: 'positive', 'negative' !default;
```

## Table

```scss
//-------------- Table ------------------*/
$use-table: true !default;
//Types
$use-table-type-definition: true !default;
$use-table-type-structured: true !default;
//Variations
$use-table-variation-basic: true !default;
$use-table-variation-celled: true !default;
$use-table-variation-padded: true !default;
$use-table-variation-compact: true !default;
$use-table-variation-inverted: true !default;
$use-table-variation-sortable: true !default;
$use-table-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Card

```scss
//-------------- Card ------------------*/
$use-card: true !default;
//Variations
$use-card-variation-inverted: true !default;
$use-card-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green', 'teal',
  'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Comment

```scss
//-------------- Comment ------------------*/
$use-comment: true !default;
//Variations
$use-comment-variation-inverted: true !default;
```

## Feed

```scss
//-------------- Feed ------------------*/
$use-feed: true !default;
//Variations
$use-feed-variation-inverted: true !default;
```

## Item

```scss
//-------------- Item ------------------*/
$use-item: true !default;
//Variations
$use-item-variation-inverted: true !default;
```

## Statistic

```scss
//-------------- Statistic ------------------*/
$use-statistic: true !default;
//Variations
$use-statistic-variation-inverted: true !default;
$use-statistic-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Checkbox

```scss
//-------------- Checkbox ------------------*/
$use-checkbox: true !default;
//Types
$use-checkbox-type-slider: true !default;
$use-checkbox-type-toggle: true !default;
//Variations
$use-checkbox-variation-fitted: true !default;
$use-checkbox-variation-inverted: true !default;
$use-checkbox-variation-size: 'mini', 'tiny', 'small', 'medium', 'large', 'big',
  'huge', 'massive' !default;
```

## Dimmer

```scss
//-------------- Dimmer ------------------*/
$use-dimmer: true !default;
//Variations
$use-dimmer-variation-inverted: true !default;
$use-dimmer-variation-blurring: true !default;
$use-dimmer-variation-partially: true !default;
$use-dimmer-variation-shades: true !default;
```

## Dropdown

```scss
//-------------- Dropdown ------------------*/
$use-dropdown: true !default;
//Types
$use-dropdown-type-selection: true !default;
$use-dropdown-type-multiple: true !default;
$use-dropdown-type-search: true !default;
$use-dropdown-type-clearable: true !default;
$use-dropdown-type-inline: true !default;
$use-dropdown-type-simple: true !default;
$use-dropdown-type-pointing: true !default;
//Variations
$use-dropdown-variation-inverted: true !default;
$use-dropdown-variation-columnar: true !default;
```

## Modal

```scss
//-------------- Modal ------------------*/
$use-modal: true !default;
//Types
$use-modal-type-inverted: true !default;
$use-modal-type-basic: true !default;
$use-modal-type-fullscreen: true !default;
```

## Popup

```scss
//-------------- Popup ------------------*/
$use-popup: true !default;
//Variations
$use-popup-variation-inverted: true !default;
```

## Progress

```scss
//-------------- Progress ------------------*/
$use-progress: true !default;
//Variations
$use-progress-variation-inverted: true !default;
$use-progress-variation-attached: true !default;
$use-progress-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Progress

```scss
//-------------- Rating ------------------*/
$use-rating: true !default;
//Variations
$use-rating-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Slider

```scss
//-------------- Slider ------------------*/
$use-slider: true !default;
//Variations
$use-slider-variation-inverted: true !default;
$use-slider-variation-vertical: true !default;
$use-slider-variation-reversed: true !default;
$use-slider-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```

## Toast

```scss
//-------------- Toast ------------------*/
$use-toast: true !default;
//Variations
$use-toast-variation-inverted: true !default;
$use-toast-variation-colors: 'red', 'orange', 'yellow', 'olive', 'green',
  'teal', 'blue', 'violet', 'purple', 'pink', 'brown', 'grey', 'black' !default;
```
