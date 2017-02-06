# 定义TODO模式和过滤器


在这个页面中：

* [基础](#基础)
* [定义TODO模式](#定义TODO模式)
* [定义过滤器](#定义过滤器)

## <span id='基础'>基础</span>

TODO项在代码中被特定的模式定义。

当模式改变了，或者添加一个新的模式，PhpStorm扫描整个项目并重建TODO项目的索引。结果显示在[TODO工具窗](/参考/工具窗参考/TODO工具窗.md)，如[查看TODO项](/如何使用/常规指南/PhpStorm编辑器/使用TODO/查看TODO项.md)章节中所描述。

默认的，PhpStorm提供两种模式：

* `\btodo\b.*`
* `\bfixme\b.*`

常用的模式看起来像`todo.*`

你也许想查看特定类型的TODO注释，并且隐藏其它的。出于这个目的，PhpStorm建议使用**过滤器**。这样你可以展示仅匹配特定模式的项目。


## <span id='定义TODO模式'>定义TODO模式</span>

要定义一个TODO模式，一般遵循以下步骤：

1. 打开设置对话框的[TODO](/参考/设置参数对话框/编辑器/TODO/README.md)页面
2. 在**Patterns**部分，点击添加按钮![新增](http://image.jellychen.cn/uploads/2016/11/new.png)来创建新的模式或点击编辑按钮![修改](http://image.jellychen.cn/uploads/2016/11/editFlexLibraryNew.png)来更新存在的一个模式。然后[添加修改模式对话框](/参考/设置参数对话框/编辑器/TODO/添加修改模式对话框.md)打开了。
3. 在**Pattern**字段，输入用来描述模式的正则表达式
4. 在**Icon**列表，选择你想用来标记在[TODO工具窗](/参考/工具窗参考/TODO工具窗.md)中匹配的TODO项的图标。
5. 指定颜色和字体属性，PhpStorm将用来在源代码中高亮匹配的注释。
6. 选择**Case sensitive**复选框，如果你想让模式大小写敏感。


## <span id='定义过滤器'>定义过滤器</span>

**要定义过滤器用来显示指定类型的TODO项目，一般按照以下步骤：

1. 打开设置对话框的[TODO](/参考/设置参数对话框/编辑器/TODO/README.md)页面
2. 在**Filters**部分，点击添加按钮![新增](http://image.jellychen.cn/uploads/2016/11/new.png)来创建新的过滤器或点击编辑按钮![修改](http://image.jellychen.cn/uploads/2016/11/editFlexLibraryNew.png)来更新存在的一个过滤器
3. 在[添加修改过滤器对话框](/参考/设置参数对话框/编辑器/TODO/添加修改模式对话框.md)，指定过滤器的名称，然后选择要包含的模式。



# 另请参阅：

规程：

* [TODO工具窗](/参考/工具窗参考/TODO工具窗.md)
* [TODO](/参考/设置参数对话框/编辑器/TODO/README.md)
* [正则表达式语法参考](/参考/正则表达式语法参考.md)

教程和例子：

* [TODO例子](/教程/TODO例子.md)
* [在TODO注释中使用动态模板](/教程/在TODO注释中使用动态模板.md)