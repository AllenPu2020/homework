# day03

---
### 练习1

变量、输入输出、类型转换、算数运算符

1. 怎样查看一个变量的数据类型
	- type(vars)

2. 下面几个变量名是否可以在 Python 里使用
    - `_hello` 可以
    - `2hello` 不可以
    - `hello Python` 不可以

### 练习2

if 语句

1. 分析下面代码的执行结果

```python
age = 18
if age >= 16:
    print("如花已经放弃你了")

else:
    print("隔壁的如花暗恋你好久了")
```

```python
>>> 如花已经放弃你了
```

2. 分析下面代码的执行结果（代码没有错误，给我分析结果就行!）

```python
age = 15
if age <= 16:
    print("隔壁的如花暗恋你好久了")

print("如花已经放弃你了")
```

```python
>>> 隔壁的如花暗恋你好久了
>>> 如花已经放弃你了
```

### 练习3

while 语句

1. break 的作用是什么
	- 终止while循环，执行循环以后的语句

2. continue 的作用是什么
	- 停止此次while循环，并跳转到循环条件判断处，如果条件成立，继续执行循环

### 练习4

函数

1. 提供函数返回值的关键字是什么
	- return

2. 什么情况下需要为函数提供返回值
	- 函数调用结束后，需要保存函数的执行结果

### 练习5

文件

1. 使用 r 模式打开文件是什么效果
	- 只读模式