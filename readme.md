# scroll-info-css

Use css variables to describe the position, speed, direction, and state of the vertical scroll bar.

## Install

With [NPM](http://npmjs.com):

```command
$ npm install scroll-info-css
```

With [PNPM](http://npmjs.com):

```command
$ pnpm install scroll-info-css
```

With [Yarn](https://yarnpkg.com):

```command
$ yarn add scroll-info-css
```

With [Bower](http://bower.io):

```command
$ bower install scroll-info-css
```

## Usage

HTML:

```html
<link rel="stylesheet" href="/path/to/scroll-info-css/scroll-info.css" />
```

CSS:

```css
@import '/path/to/scroll-info-css/scroll-info.css';
```

Via PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'scroll-info-css';
```

Via webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import 'scroll-info-css';
```

## variables

```css
- `--scroll-position-normal`  This css variable describes the vertical scroll bar position of the page, with values ranging from 0 to 100.
- `--scroll-position-tardiness` This css variable has a delay relative to --scroll-position-normal.
- `--scroll-speed` (variable declared in body) Describes the speed of the vertical scroll bar.
- `--scroll-direction` (variable declared in body) Describes the orientation of the vertical scroll bar. (scope:(-1|0|1))-1 means move up, 0 means stop moving,1 means move down.
- `--scroll-state` (variable declared in body) Describes the state of the vertical scroll bar. (scope:(0|1))0 means stationary, 1 means moving.
```
