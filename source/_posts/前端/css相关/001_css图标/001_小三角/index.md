---
title: 小三角
date: 2020-10-21 15:56:54
categories:
	-前端
	-css相关
	-css图标
tags:
---

## 向左
向左，上下边框透明，右边框有颜色
```css
display: inline-block;
border-top: 6px solid transparent;
border-bottom: 6px solid transparent;
border-right: 6px solid #000;
```
<span class="to-left"></span>

## 向右
向右，上下边框透明，左边框有颜色
```css
display: inline-block;
border-top: 6px solid transparent;
border-bottom: 6px solid transparent;
border-left: 6px solid #000;
```
<span class="to-right"></span>

## 向上
向上，左右边框透明，下边框有颜色
```css
display: inline-block;
border-left: 6px solid transparent;
border-right: 6px solid transparent;
border-bottom: 6px solid #000;
```
<span class="to-top"></span>

## 向下
向下，左右边框透明，上边框有颜色
```css
display: inline-block;
border-left: 6px solid transparent;
border-right: 6px solid transparent;
border-top: 6px solid #000;
```
<span class="to-bottom"></span>

<style>
.group {
	position: relative;
	width: 300px;
	height: 300px;
	border: 1px solid #000;
}
.group * {
	margin: 0;
	padding: 0;
}

.to-left {
	margin-left: 50px;
	display: inline-block;
	border-top: 6px solid transparent;
	border-bottom: 6px solid transparent;
	border-right: 6px solid #000;
}
.to-right {
	margin-left: 50px;
	display: inline-block;
	border-top: 6px solid transparent;
	border-bottom: 6px solid transparent;
	border-left: 6px solid #000;
}
.to-top {
	margin-left: 50px;
	display: inline-block;
	border-left: 6px solid transparent;
	border-right: 6px solid transparent;
	border-bottom: 6px solid #000;
}
.to-bottom {
	margin-left: 50px;
	display: inline-block;
	border-left: 6px solid transparent;
	border-right: 6px solid transparent;
	border-top: 6px solid #000;
}

</style>
