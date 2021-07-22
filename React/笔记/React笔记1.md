<!--
 * @Autor: Twang
 * @Date: 2021-03-08 17:18:54
 * @Description: 
 * @Version: 1.0
 * @LastEditors: Twang
 * @LastEditTime: 2021-07-19 14:00:51
 * @FilePath: \StudyNotes\React\笔记\React笔记1.md
 * Copyright (C) 2021 Twang. All rights reserved.
-->
# React技术全家桶

1、是什么？

​	React 是一个声明式，高效且灵活的用于构建用户界面的 JavaScript 库（是一个将数据渲染为HTML视图的开源JavaScript库）。使用 React 可以将一些简短、独立的代码片段组合成复杂的 UI 界面，这些代码片段被称作“组件”。
    用于动态构建用户界面的Javascript库（React只关注视图）。

2、为什么要学？

​	1、原生js操作DOM繁琐、效率低（DOM-API操作UI）

​	2、 使用js直接操作DOM，导致浏览器进行大量的重绘重排

​	3、原生js没有组件化编码方案，复用率低

3、React的特点：

​	1、采用组件化模式、声明式编码，提高开发效率及组件复用率
        React 高效的原因：
            （1）使用虚拟DOM，不总是直接操作页面的真实DOM
            （2）DOM Diffing算法，最小化页面重绘

​	2、在React Native中可以使用React语法进行移动端开发

​	3、使用虚拟DOM+优秀的Diffing算法，尽量减少与真实DOM的交互

4、学习React之前需要掌握的js基础知识

​	1、判断this的指向

​	2、class（类）

​	3、ES6语法规范

​	4、npm包管理器

​	5、原型、原链接

​	6、数组常用方法

​	7、模块化