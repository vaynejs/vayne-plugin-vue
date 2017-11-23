# vayne-plugin-vue
> vayne vue 插件

## Installation
```
yarn add vayne-plugin-vue -D
npm i vayne-plugin-vue -D
```
## Usage
在__.vaynerc.js__ 引入
```js
module.exports = {
  plugins: [
    'vayne-plugin-vue' // 获取简写 vue
  ]
}
```

## include
> 因为 __vue-template-compiler__ 依赖 __vue__ 版本 所以占不依赖 请使用 vue 时手动安装 vue-template-compiler
* __vue-loader__ ^13.5.0
* __vue-style-loader__ ^3.0.3