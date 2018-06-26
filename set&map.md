# Set

## 基本用法

ES6提供了新的数据结构Set，它类似于数组，但是成员的值都是唯一的，没有重复的值。

## Set实例的属性和方法

Set结构的实例有以下属性

　　-Set.prototype.constructor:构造函数，默认就是Set函数。

　　-Set.prototype.size:返回Set实例的成员总数。

Set 实例的方法分为两大类：操作方法（用于操作数据）和遍历方法（用于遍历成员）。

###操作方法

　　-add(value):添加某个值，返回Set本身结构。

　　-delete(value):删除某个值，返回一个布尔值，表示删除是否成功。

　　-has(value):返回一个布尔值，表示该值是否为Set成员。

　　-clear():清除所有成员，没有返回值。


### 遍历方法

　　-keys():返回键名的遍历器。

　　-values():返回键值的遍历器。

　　-entries():返回键值对的遍历器。

　　-forEach():使用回调函数遍历每个成员。




