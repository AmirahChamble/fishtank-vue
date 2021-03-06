# Fishtank Vue

Fish Tank VueJS Component Module

## Installation

``` sh
npm install @fishtank/fishtank-vue
```

## [Available Components](src/components/Readme.md)

* [Cards](src/components/Card.md)
* [Modals](src/components/Modals.md)
* [Buttons](src/components/Buttons.md)
* [Button Group](src/components/ButtonGroup.md)
* [Radios](src/components/Radios.md)
* [Switches](src/components/Switches.md)
* [Loaders](src/components/Loaders.md)
* [Text Input](src/components/InputText.md)
* [Checkboxes](src/components/Checkboxes.md)
* [Tags](src/components/Tags.md)

## Usage

### ESM Module

Import the component from the library module
``` js
import { Card } from @fishtank/fishtank-vue

extend default {
  components:{
    Card
  }
}
```
### CommonJS Module
Import the component library module, and reference the desired component

``` js
const fishtank = require(“@fishtank-vue”)

extend default {
  components:{
    fishtank.Card
  }
}
```

### Component CSS

Fishtank-vue provides styles as:
  * _dist/fishtank-vue.css_: a single CSS file of all component styles
  * _dist/styles_: component specific stylesheets

Import the full library, or per component styles, into your project as necessary.

## Contributing

[Contributing Documentation](.github/CONTRIBUTING.md)

## Dev Environment Setup

``` bash
# install dependencies
npm install

# or
yarn

# serve with hot reload at localhost:8080
npm run serve 

#or
yarn serve
```
