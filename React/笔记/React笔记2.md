<!--
 * @Autor: Twang
 * @Date: 2021-03-08 17:18:54
 * @Description: 
 * @Version: 1.0
 * @LastEditors: Twang
 * @LastEditTime: 2021-03-09 09:50:02
 * @FilePath: \React\笔记\React笔记2.md
 * Copyright (C) 2021 Twang. All rights reserved.
-->
# React技术全家桶
## 基本使用
    1、核心js库：
        （1）react.js：React核心库。
        （2）react-dom.js：提供操作DOM的react扩展库。
        （3）babel.min.js：解析JSX语法代码转为JS代码的库。
    2、创建虚拟DOM的两种方式：
        （1）纯JS创建
        （2）JSX创建

## JSX语法规则：
    1、定义虚拟DOM时，不要写引号
    2、标签中混入JS表达式时要用｛｝
        一定注意区分：【js语句（代码）】与【js表达式】
            1、表达式：一个表达式会产生一个值，可以放在任何一个需要值的地方
                下面这些都是表达式:
                    (1)a
                    (2)a+b
                    (3)demo(1)
                    (4)arr.map()
                    (5)funuction test(){}
            2、语句（代码）：
                下面这些都是语句（代码）：
                    (1)if(){}
                    (2)for(){}
                    (3)switch(){case:***}
    3、样式的类名指定不能用class，要用className
    4、内联样式格式：style={{key:value}}
    5、虚拟DOM只能有一个根标签
    6、标签必须闭合
    7、标签首字母
        （1）若小写字母开头，则将改标签为html中同名元素，若html中无该标签对应的同名元素，则报错
        （2）若大写字母开头，react就去渲染对应的组件，若组件没有定义，则报错。

