# 快速上手

## Introduce
> jhb-Element-UI, 一个神奇的UI组件, 由一群神秘的小伙伴开发完成

## What it is

本项目基于 Vue，对 Element-UI 常用组件进行二次封装，提供后台管理系统中常用组件的开箱即用

## How to use

```bash
	npm install jhb-element-ui
```

```js
	import JHBElement from "jhb-element-ui";
    import ElementUI from 'element-ui';
    import "element-ui/lib/theme-chalk/index.css";
    import "jhb-element-ui/lib/jhb-element-ui.css";

    Vue.use(ElementUI);
    Vue.use(JHBElement);
```