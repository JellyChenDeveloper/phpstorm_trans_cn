# 创建和运行你的第一个PHP项目

熟悉PhpStorm建议你从头开始创建你的第一个项目,实现最基本的功能。

创建实时的PHP应用程序，你可以在自己选择的浏览器中查看结果，这些需要满足下列条件：

* 本地[Web服务器](https://en.wikipedia.org/wiki/Web_server)已经在你的电脑上安装、配置和运行了，或者已经配置访问远程服务器的权限。
    当前主题建议使用本地[Apache HTTP server](http://httpd.apache.org/)，它的根目录是`.\htdocs`
* [PHP引擎](http://php.net/downloads.php)已经安装配置完成。

你可以分别安装每个组件然后配置环境。作为选择，安装操作系统兼容的AMP包，它将自动安装所有组件和完整的环境配置，不用人工操作。

## 创建和运行你的第一个PHP项目

1. 创建一个项目，对于这个，在主菜单中选择** File | New | Project** 。
2. 在打开的[新建项目](/参考/对话框/新建项目对话框/README.md)对话框中在**Name** 文本框中指定项目的名字，例如：输入`MyFirstPhpProject`。
3. 点击**Location** 文本框旁边的**Browse** 按钮![浏览](http://image.jellychen.cn/uploads/2016/10/browseButton.png)。
4. 在[打开的对话框](/参考/对话框/选择路径对话框.md)中选择路径至`.\htdocs`文件夹中，然后点击**OK**。
    PhpStorm组成项目文件夹的路径如下：
    
    ![新建项目](http://image.jellychen.cn/uploads/2016/10/webphpcreateNewProject.png)
    
5. 创建PHP文件，对于这个，在[项目工具窗](/参考/工具窗参考/项目工具窗.md)中右键点击项目目录，指向右键菜单上的**New**，然后选择**PHP File**
    
    ![新建文件](http://image.jellychen.cn/uploads/2016/10/webphpcreatePhpFile.png)
    
6. 在打开的**新建PHP文件**对话框中输入**MyFile** 然后点击**OK**。PhpStorm将为您创建存根文件,在专门的编辑器选项卡中打开它。
7. 输入示例代码：

        echo phpinfo();

8. 保存文件，选择**File | Save All** 或者按 `Ctrl+S`。
9. 打开浏览器然后输入下面的URL地址：

        http://localhost:<port>/MyFirstPhpProject/MyFile.php

    PHP信息页面打开并显示电脑上PHP引擎的配置设置。
    
    ![phpinfo](http://image.jellychen.cn/uploads/2016/10/php_storm_first_project_output.png)


# 另请参阅：

规程：

* [PHP-具体指南](/如何使用/语言和框架-具体指南/PHP-具体指南/README.md)

参考:

* [新建项目对话框](/参考/对话框/新建项目对话框/README.md)

入门指南：

* [用户界面引导](/如何使用/常规指南/用户界面引导/README.md)
