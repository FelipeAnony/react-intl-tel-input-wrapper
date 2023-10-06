# React-Intl-Tel-Input-wrapper

fork of [React Intl Tel Input by patw0929](https://github.com/patw0929/react-intl-tel-input)

Adds support for react >=15.4

## Demo & Examples

To build the examples locally, run:

```bash
yarn
yarn website:start
```

Then open [`localhost:3000`](http://localhost:3000) in a browser.

## Installation

```bash
yarn add react-intl-tel-input-wrapper
```

### TypeScript

`react-intl-tel-input` ships with official type declarations out of the box.

## Usage

```javascript
import IntlTelInput from 'react-intl-tel-input-wrapper'
import 'react-intl-tel-input-wrapper/dist/main.css'
;<IntlTelInput
  containerClassName="intl-tel-input"
  inputClassName="form-control"
/>
```

## Development (`src` and the build process)

To build, watch and serve the examples (which will also watch the component source), run `yarn website:start`.

You can prepare a distribution build using `yarn build`.

## Inspired by

[International Telephone Input](https://github.com/jackocnr/intl-tel-input) - [@jackocnr](https://github.com/jackocnr)

## License

MIT
