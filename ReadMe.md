# [reset.css](https://www.npmjs.com/package/@eleven.xi/reset.css)

H5 网页 reset 方案，PC&mobile。

基于[Normalize](https://github.com/necolas/normalize.css) 做了整合，Normalize 仅 reset 了 PC 浏览器的默认设置，缺少对移动端的处理，这份 reset 同时适用移动端和 PC 端。

## Installation

#### NPM

```js
npm i @eleven.xi/reset.css
```

#### Yarn

```js
yarn add @eleven.xi/reset.css
```

## Getting Started

### css
```js
// 建议放到样式第一位最先导入（别忘记安装 postcss-import）
@import '@eleven.xi/reset.css';
```

### js

```js
// js 方式导入，也没啥问题（不推荐）
import '@eleven.xi/reset.css';
```