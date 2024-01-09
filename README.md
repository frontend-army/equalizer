# The Equalizer
[![npm](https://img.shields.io/npm/v/equalizer.svg)](https://www.npmjs.com/package/equalizer)
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

## About

This project is maintained by the [Frontend Army](https://github.com/frontend-army).
