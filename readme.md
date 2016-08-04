Modal component
===============

[![NPM version](https://img.shields.io/npm/v/mag-component-modal.svg?style=flat-square)](https://www.npmjs.com/package/mag-component-modal)
[![Dependencies Status](https://img.shields.io/david/spasdk/component-modal.svg?style=flat-square)](https://david-dm.org/spasdk/component-modal)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/spasdk)


Modal is a component to build user interface, an instance of [Component](https://github.com/spasdk/component) module.


## Installation ##

```bash
npm install mag-component-modal
```


## Usage ##

Add the singleton to the scope:

```js
var Modal = require('mag-component-modal');

page.modal = new Modal({
    title: 'My Title',
    icon: 'star',
    children: [new Button({value: 'Create'})]
});

page.add(page.modal);
page.modal.show();
```


## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problem or suggestion please open an issue [here](https://github.com/spasdk/component-modal/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`mag-component-modal` is released under the [MIT License](license.md).
