
# keyname

  Keyboard event key name utility

## Installation

    $ component install component/keyname

## API

```js
var keyname = require('keyname');

keyname(27);
// => "esc"

keyname(23123123);
// => undefined

keyname(65);
// => "a"

keyname(49);
// => "1"
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
  - a-z
  - 0-9

## License

  MIT
