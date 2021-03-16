# React技术全家桶
## 组件实例的三大核心属性

### 1、`state`

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

#### 理解

1. 每个组件对象都会有props(properties的简写)属性

2. 组件标签的所有属性都保存在props中

#### 作用

1. 通过标签属性从组件外向组件内传递变化的数据

2. 注意: 组件内部不要修改props数据

#### 编码操作

1. 内部读取某个属性值

   ```
   this.props.name
   ```

   

2.  对props中的属性值进行类型限制和必要性限制

   第一种方式（React v15.5 开始已弃用）：

   ​	

   ```
   Person.propTypes = {
    name: React.PropTypes.string.isRequired,
    age: React.PropTypes.number
   }
   ```

   第二种方式（新）：使用prop-types库进限制（需要引入prop-types库）

   ​	

   ```
   Person.propTypes = {
     name: PropTypes.string.isRequired,
     age: PropTypes.number. 
   }
   ```

   

3. 扩展属性: 将对象的所有属性通过props传递

   ```
   <Person {...person}/>
   ```

   

4.  默认属性值：

   ```
   Person.defaultProps = {
     age: 18,
     sex:'男'
   }
   ```

   

5. 组件类的构造函数

   ```
   constructor(props){
     super(props)
     console.log(props)//打印所有属性
   }
   ```

   

### 3、`refs`

​	（待更新）



