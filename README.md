# learning-notes
前端学习笔记
1、

```
Const obj = {xxx,xxx}

​	Const obj1 = {…obj} (将obj对象在obj1对象中展开)
```

2、对象的简写形式：
​	a:a才可简写成：a
​	a:’a’不可简写，因为key和value均为字符串

3、NaN：不合法的值

4、{{xxx}} ：
​	插值语法中不带括号也会传递参数：event

5、引入的语法
​	除了this.$store.dispatch以外，还可以使用this.$store.dispatch['xxx/xxx']

6、ES语法：模版字符串里面，添加表达式
​	`${m.xxx}`



7、解构赋值:
​	例：
​	可转化为:
​		props({query:{id, xxx}}){
​					return {id, xxx}
​		}

​	连续解构赋值：
​			const {xxx:{xxx}} = this
​			相当于：this.xxx.xxx
​	连续解构赋值并且重命名：
​			const {xxx:{xxx:重命名}} = this
​			相当于：this.xxx.重命名

8、path: 'detail/:id/:title', // node.js语法，使用占位符声明接收params参数

9、Object.is(NaN,NaN) --- true

