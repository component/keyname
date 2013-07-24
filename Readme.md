
# keyname

  Keyboard event key name utility

## Installation

    $ component install component/keyname

or

    $ npm install keyname

## API

```js
var keyname = require('keyname');

keyname(27);
// => "esc"

keyname(23123123);
// => undefined
```

## Keys

  The following are supported:

  - backspace
  - tab
  - enter
  - shift
  - ctrl
  - alt
  - capslock
  - esc
  - space
  - pageup
  - pagedown
  - end
  - home
  - left
  - up
  - right
  - down
  - ins
  - del
  - meta

## License

  MIT
