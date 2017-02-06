# 创建PHP类接口和特性

> Trait:在这里被翻译为特性，有点不准确，但是在这边文件中暂时就先以特定来表示Trait。待有准确的描述词语再进行替换。
>> Trait是PHP5.4的新特性，为了解决PHP不能多重继承的一种代码复用的方法。
>> 详情参见：PHP官方手册[http://www.php.net/manual/zh/language.oop5.traits.php](http://www.php.net/manual/zh/language.oop5.traits.php)


在这个页面中：

* [基础](#基础)
* [创建PHP类](#创建PHP类)


## <span id='基础'>基础</span>

PhpStorm支持在项目中使用命名空间，服从[PSR0标准](http://phpmaster.com/autoloading-and-the-psr-0-standard/)并强制你按照这个标准保持目录结构个命名空间层级当创建类、接口和特性时。

当你指定要储存新类的目录，PhpStorm自动更新类的命名空间。


## <span id='创建PHP类'>创建PHP类</span>

1. 在项目工具窗，选择和命名空间相关的目录，在这你要创建一个新的类/接口/特性，并在选中项的上下文菜单中选择**New | PHP Class**。新建PHP类对话框将被打开。
2. 在**Name**文本框，输入要被创建的类/接口/特性的名称。PhpStorm在**File Name**字段自动填充指定的文件名。
3. 指定要创建类/接口/特性所在的命名空间。默认的，**Namespace***字段展示与目录相关的命名空间在这类/接口/特性被调用。
    
    你可以从下拉列表选择**Global namespace**或手动的指定命名空间，小心注意这可能导致一些问题比如命名空间不符合**PSR0**规范。
    
    你也可以改变保存新建的类/接口/特性文件的目录，这些改变也会反应到**Namespace**字段。
    
4. 在**Kind**下拉菜单，指定将创建什么，可用的选项有：

    * Class
    * [Interface](http://php.net/manual/en/language.oop5.interfaces.php)
    * [Trait](http://php.net/manual/en/language.oop5.traits.php)
    
5. 从下拉菜单选择文件扩展名。

当你点击**OK**，一个新的类根据PHP类模板被创建，并有自动添加指定的声明命名空间。



# 另请参阅：

规程：

* [从模板创建文件](/如何使用/常规指南/填充项目/从模板创建文件.md)