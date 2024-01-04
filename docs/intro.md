---
sidebar_position: 1
---

# 初识 Fabric.js

## Fabric.js 简介

[Fabric.js](http://fabricjs.com/) 是一个十分老牌的 2d Canvas 库，项目在 2010 年左右启动，已经有十多年的时间了，甚至比我工作的时间都长的多，翻翻源码也是很老派的写法，能让你瞬间回忆起一些八股文。🫡

不过难能可贵的是项目还在积极更新，现在的稳定版本是 5.x，本系列也会基于这个版本编写。官方正在积极开发 [6.0 版本](https://github.com/fabricjs/fabric.js/issues/8299)，从给出的 issue 上看，能力上基本保持一致，使用 TS 和 ES6 重写，对一些类 和 API 进行变更，等正式发布，本教程也会第一时间更新。

要了解 Fabric.js 的全貌，其实看一下他的官网首页就好了。官网首页就是一个在线 DEMO，将 Fabric.js 的主要特性做了一个展示：

![](@site/static/img/docs/intro/intro.png)

这里我们对照上图整理出 Fabric.js 主要特性：
1. 内置对象模型，可以创建常见几何图形。
2. 支持动态处理文字，支持文字常见样式处理。
3. 图片以及图片滤镜
4. 内置 Path 支持复杂图形
5. 特效：阴影、渐变、裁剪、pattern 填充
6. 对象成组
7. 自由绘制
8. 支持导入导出 SVG 和 JSON
9. 内置动画

后面我们这个系列也会围绕这些特性展开，那我们先从一个最简单的案例开始吧。

## 从画一个矩形开始


