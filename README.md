# WeChat
微信小程序
## Component的坑
  Component 无法使用 `wx:if` 进行条件渲染。如果使用该方式，会在 `setData()`方法改变其状态时报错。解决方法是使用 `<template></template>` 封装一个Componen 来解决。


