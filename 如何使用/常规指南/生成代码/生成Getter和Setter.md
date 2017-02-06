# 生成Getter和Setter


在这个页面中：

* [介绍](#介绍)
* [生成生成器和访问器代码](#生成生产器和访问器代码)


## <span id='介绍'>介绍</span>

在PHP环境中，你可以生成访问器和生成器方法（getters和setters）为你的类的字段。PhpStorm生成getters和setters仅带有一个参数。

在PHP环境，getters和setters是用**PHP getter/setter**文件模板生成的。默认的，作为模板指定，setters被生成带有`set`前缀，同时getters被生成带有`set`或`get`前缀根据推测的字段类型是`bollean`或`con-bollean`。这些前缀值是在默认的getter模板中的变量`${GET_OR_IS}`。默认的模板在[设置参数对话框](/参考/设置参数对话框/README.md)的[文件和代码模板](/参考/设置参数对话框/编辑器/文件和代码模板.md)页面的**Code**标签中配置。


## <span id='生成生产器和访问器代码'>生成生产器和访问器代码</span>

1. 在主菜单，选择**Code | Generate**
    
    另一种选择，右键单击编辑器并在上下文菜单中选择**Generate**，或使用快捷键`Alt+Insert`。
    
2. 在编辑器显示的弹出列表中，选择下列选项之一：

    * **Getter**：访问获取当前字段的值的方法将在**Choose Fields to Generate Getters and Setters**对话框中选择。
    * **Setter**：生成器或方法对指定的字段的值。
    * **Getter和Setter**：两种方法都有。

3. 在**Choose Fields to Generate Getters and Setters**对话框，选择要生成生成器和获取器的字段。
4. 准备好后点击**OK**。


# 另请参阅：

参考：

* [Getter和Setter模板对话框](/参考/对话框/Getter和Setter模板对话框.md)