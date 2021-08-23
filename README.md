# Welcome to moonsault!

* You can make perfect shadows on images you upload for non-designers!

# Installation

`npm i moonsault --save`

then...

```
const { moonsault } = require('moonsault');

moonsault({
  shadow_type: 'soft',
  padding: false
})
```

## Options

* *shadow_type* - _hard | soft_ (defaults to soft)
* *padding* - _boolean_ (defaults to false)