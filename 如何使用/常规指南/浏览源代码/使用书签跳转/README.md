# 使用书签跳转


在这个页面中：

* [介绍](#介绍)
* [在当前文件中跳转](#在当前文件中跳转)
* [在项目中跳转](#在项目中跳转)


## <span id='介绍'>介绍</span>

PhpStorm的编辑器提供两种类型的书签：

* **Anonymous bookmarks**，由左侧槽中的复选标记![匿名书签标记](http://image.jellychen.cn/uploads/2016/12/bookmarkCheck.png)指示。匿名书签的数量是无限的。
* **Bookmarks with mnemonics**，由左槽中的![数字标签](http://image.jellychen.cn/uploads/2016/12/bookmarkNumber.png)或![字母标签](http://image.jellychen.cn/uploads/2016/12/bookmarkMnemonic.png)图标指示。项目中只能有10个编号和26个字母书签。

所有书签都以标记栏中的黑色条纹表示：

![编辑器中书签表示](http://image.jellychen.cn/uploads/2016/12/wi_bookmarkStripe.png)

[创建后](/如何使用/常规指南/浏览源代码/使用书签跳转/管理书签.md)，书签使您能够轻松地跳转到文件中或整个项目中的所需位置。

## <span id='在当前文件中跳转'>在当前文件中跳转</span>

**要在当前文件中通过书签跳转，请执行以下操作之一**

* 在主菜单，选择**Navigate | Bookmarks | Next/Previous Bookmark**。访问书签的顺序取决于[书签对话框](/参考/对话框/书签对话框.md)中收藏书签的顺序。
* 单击标记栏中的黑色条纹。


## <span id='在项目中跳转'>在项目中跳转</span>

**使用数字书签在项目中跳转**

* 使用`Ctrl+Number`，其中\<number\>对应于所需的书签。


**要在项目中的所有书签之间跳转，请执行以下操作之一**

* 在主菜单，选择**Navigate | Bookmarks | Show Bookmarks**，或按`Shift+F11`。
    
    在[书签](/参考/对话框/书签对话框.md)对话框中，选择目标书签，然后按Enter键。
    
    为方便起见，目标代码预览显示在对话框的右窗格中。
    
* 在[收藏夹工具窗](/参考/工具窗参考/收藏工具窗.md)中，在书签列表中选择所需的书签，然后双击书签条目，或按`F4`。相应的文件在编辑器中打开，插入符号位于加书签行的开头。



# 另请参阅：

入门指南：

* [PhpStorm编辑器](/如何使用/常规指南/PhpStorm编辑器/README.md)

参考：

* [书签对话框](/参考/对话框/书签对话框.md)