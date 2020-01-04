# hello-es6

ES6 各种新语法 入门了解  石川blue讲解

- [b站：深入解读ES6系列](https://www.bilibili.com/video/av20327829/)

看视频整理要点笔记:

----

- [hello-es6](#hello-es6)
    - [1.ES6怎么来的](#1es6%E6%80%8E%E4%B9%88%E6%9D%A5%E7%9A%84)
    - [2.ES6兼容性](#2es6%E5%85%BC%E5%AE%B9%E6%80%A7)
    - [3.变量 let 和 常量 const](#3%E5%8F%98%E9%87%8F-let-%E5%92%8C-%E5%B8%B8%E9%87%8F-const)
    - [4.函数-箭头函数](#4%E5%87%BD%E6%95%B0-%E7%AE%AD%E5%A4%B4%E5%87%BD%E6%95%B0)
    - [5.函数-参数](#5%E5%87%BD%E6%95%B0-%E5%8F%82%E6%95%B0)
    - [6.解构赋值](#6%E8%A7%A3%E6%9E%84%E8%B5%8B%E5%80%BC)
    - [7.数组](#7%E6%95%B0%E7%BB%84)
    - [8.字符串](#8%E5%AD%97%E7%AC%A6%E4%B8%B2)
    - [9.面向对象-基础](#9%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1-%E5%9F%BA%E7%A1%80)
    - [10.面向对象应用](#10%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1%E5%BA%94%E7%94%A8)
    - [11.json](#11json)
    - [12.Promise](#12promise)
    - [13.generator-认识生成器函数](#13generator-%E8%AE%A4%E8%AF%86%E7%94%9F%E6%88%90%E5%99%A8%E5%87%BD%E6%95%B0)
    - [14.generator-yield是啥](#14generator-yield%E6%98%AF%E5%95%A5)
    - [15.generator-实例](#15generator-%E5%AE%9E%E4%BE%8B)
    - [16.ES7 预览](#16es7-%E9%A2%84%E8%A7%88)

----

## 1.ES6怎么来的
- ECMAScript 和 JavaScript
    - ECMA 是标准，JS 是实现
    - ECMAScript 简称 ECMA 或 ES
- 历史版本
    - 1996.11  ES1.0  Netscape将JS提交给ECMA组织，ES正式出现
    - 1998.06  ES2.0  正式发布
    - 1999.12  ES3.0  ES3被广泛支持
    - 2007.10  ES4.0  由于太激进被废了
    - 2009.12  ES5.0  ES5正式发布，同时公布了JavaScript.net也就是后来的ES6.0
    - 2011.06  ES5.1  ES5.1正式成为了ISO国际标准
    - 2015.06  ES6.0  ES6.0预计发布正式版，JavaScript开始指向ES.7.0
    
## 2.兼容性（ES2015）
- ES6(ES2015)
    - IE10+
    - Chrome
    - FireFox
    - 移动端
    - NodeJS
- 解决不兼容的办法:编译、转换
    - 在线转换
    - 提前编译
- Babel编译器
    - Babel是一个JavaScript的编译器
    - 一个广泛使用的转码器，能将ES6代码转换为ES5代码，使得能做现在的环境运行
    - 使用后，就不用担心ES6不兼容问题
## 3.变量
- var
    - 可以重复申明变量
    - 无法限制修改
    - 没有块级作用域
- let
    - 不能重复申明
    - 变量——可以修改
    - 块级作用域
- const
    -不能重复申明变量
    - 常量——不能修改
    - 块级作用域
    
## 4.函数——箭头函数
- 若只有一个参数，（）可以省
- 若只有一个return，{}可以省

## 5.函数的参数
- 参数扩展/数组展开
    - 收集参数
```js
 function show(a,b, ...args){}
 *Rest parameter必须是最后一个
```
   - 展开数组
```js
  ...arr   =>   1,2,3
 *展开后的效果，跟直接把数组的内容写在这儿一样
```
- 默认参数
   - 你给我设置值，那我接收，不设置值，我自己默认也有值
```js
 $('#div1').animate({width:'200px'})
 $('#div1').annimate({width:'200px'},1000)
```
  
   
    
