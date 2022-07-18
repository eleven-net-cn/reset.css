# [reset.css](https://www.npmjs.com/package/@eleven.fe/reset.css)

[![NPM version][npm-image]][npm-url] [![Downloads][downloads-image]][npm-url]

[npm-url]:https://npmjs.org/package/@eleven.fe/reset.css
[downloads-image]:https://img.shields.io/npm/dt/@eleven.fe/reset.css.svg
[npm-image]:https://img.shields.io/npm/v/@eleven.fe/reset.css.svg

CSS Reset, PC & Mobile.

在 [Normalize.css](https://github.com/necolas/normalize.css) 基础上增加 mobile 需要的 reset，这份 reset 同时适用移动端、PC 端。

## Installation

#### NPM

```bash
npm i @eleven.fe/reset.css
```

#### Yarn

```bash
yarn add @eleven.fe/reset.css
```

## Getting Started

### css
```js
// 建议放到样式第一位最先导入（别忘记安装 postcss-import）
@import '@eleven.fe/reset.css';

// 在 CRA 创建的项目中如果提示错误，你可能需要在引入时添加 ~
@import '~@xmly/reset.css';
```

### js

```js
// js 方式导入，也没啥问题（不推荐）
import '@eleven.fe/reset.css';
```