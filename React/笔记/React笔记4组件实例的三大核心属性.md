<!--
 * @Autor: Twang
 * @Date: 2021-03-09 14:18:31
 * @Description: 
 * @Version: 1.0
 * @LastEditors: Twang
 * @LastEditTime: 2021-03-09 16:16:38
 * @FilePath: \React\笔记\React笔记3组件.md
 * Copyright (C) 2021 Twang. All rights reserved.
-->
# React技术全家桶
## 组件实例的三大核心属性

### 1、state

	#### 理解

1. state是组件对象最重要的属性, 值是对象(可以包含多个key-value的组合)

2. 组件被称为"状态机", 通过更新组件的state来更新对应的页面显示(重新渲染组件)

#### 强烈建议：

1. 组件中render方法中的this为组件实例对象

2. 组件自定义的方法中this为undefined，如何解决？

   a) 强制绑定this: 通过函数对象的bind()	

   b) 箭头函数

3. 状态数据，不能直接修改或更新，必须是通过setState进行更新,且更新是一种合并不是替换

### 2、`props`

​	（待更新）



### 3、refs

​	（待更新）



