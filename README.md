# The Equalizer
[![npm](https://img.shields.io/npm/v/@frontend-army/equalizer.svg)](https://www.npmjs.com/package/@frontend-army/equalizer)
[![FEArmy](./assets/FEA_icon.png)](https://github.com/frontend-army)

## Features

- Reset the default styles of the browser.

## Installation

#### npm
```bash
npm i equalizer
```

#### yarn
```bash
yarn add equalizer
```

#### pnpm
```bash
pnpm add equalizer
```

## Usage

Include the equalizer.css before **any** file of your CSS/SCSS. You can do it by simply using the import statement on top of your root `scss` or `css` file:

```scss
@import '~equalizer/equalizer';
```

Or you can also do the following trick to simply import it with it's name:

```scss
@import 'equalizer';
```

## Base Styles

All the text have the base style:
```css
color: #717171;
font-family: sans-serif;
font-size: 14px;
line-height: 14px;
```

And input placeholders:
```css
color: #999
```

## Feedback

We are open to feedback! Feel free to open an Issue.

Please, if you wish to help developing these or other open source tools let us know via our social media:

- [Twitter](twitter.com/frontend_army)
- [Discord](https://t.co/Y46bYpwExU)

## License

Copyright 2024 Frontend Army

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

