![Fomantic Logo](https://fomantic-ui.com/images/logo.png#128)

# Fomantic-UI

[![npm downloads](https://img.shields.io/npm/dm/fomantic-ui-sass.svg?label=npm%20downloads)](https://www.npmjs.com/package/fomantic-ui-sass)
[![npm version](https://img.shields.io/npm/v/fomantic-ui-sass)](https://www.npmjs.com/package/fomantic-ui-sass)

A community fork of the popular Semantic-UI framework.

The sass version of semantic ui. It is fully customizable with isolated variable names.
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
@import 'mycustom-variables.scss';
@import 'node-modules/fomantic-ui-sass/src/semantic-ui.scss';
```

### Attention!

If you want to modify in your personalized file a variable which can generate derivatives like the colors and their variants please do it and put in front your personalized file in order to have conforming derivatives.

## CSS Usage

```css
@import 'node-modules/fomantic-ui-sass/dist/semantic-ui.css';
```

# Customization and choice of components and their variants (Coming soon)
