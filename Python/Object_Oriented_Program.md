# Object Oriented Program
## 1.dir内置函数
调用dir内置函数：

```
def demo():
  print("hello python")
dir(demo)
```
dir函数作用：查看对象内所有内置的属性和方法
## 2.定义简单的类
### 2.1.创建类
```
class ClassName(arg_list):
  def function_1(self,argument)：
    pass
  def function_2(self,argument):
    pass
```
类名要用大驼峰命名法
### 2.2.创建对象
```
obj = ClassName(arg_list)
```
## 3.引用
概念：在Python中使用类创建对象后，对象变量中存储的是对象在内存中的地址。使用print输出对象变量，输出着个变量引用的对象是由哪一个类创造的对象，以及其在内存中的地址（16进制表示）
%d输出10进制数字
%x输出16进制数字
## 4.给对象增加属性
注意：此方法不推荐使用
```
obj.attribute = "attribute_name"
