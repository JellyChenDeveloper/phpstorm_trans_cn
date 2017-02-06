# 使用Yeoman生成器创建项目

PhpStorm支持集成[Yeoman](http://yeoman.io/)工具并提供接口来使用它生成框架特定项目。

在这个页面中：

* [开始之前](#开始之前)
* [安装Yeoman](#安装Yeoman)
* [配置项目存根生成列表](#配置项目存根生成列表)
* [通过生成器生成项目](#通过生成器生成项目)


## <span id='开始之前'>开始之前</span>

1. 下载和安装[Node.js](http://nodejs.org/)，需要这个运行时环境有以下两个原因：
    
    * Yeoman工具由**Node.js**启动
    * **NPM**，是运行时环境的一部分，也是下载Yeoman工具很方便的途径。

2. 如果你准备使用命令行模式，确保**Node.js**可执行文件父目录的路径和`npm`目录的路径添加到了`PATH`变量中。这可以让你在任意文件夹启动Yeoman工具和**npm**。
3. 确保**Yeoman**和**NodeJs**插件已经安装和启用。这些插件不是PhpStorm绑定的，但是你可以从**JetBrains plugin repository**中安装，参考[安装、更新和卸载库插件](/如何使用/常规指南/管理插件/安装、更新和卸载库插件.md)和[启用和禁用插件](/如何使用/常规指南/管理插件/启用和禁用插件.md)章节的描述。一旦启用，这些插件将在IDE级别可用，这意味着，你可以在所有的PhpStorm项目中使用。


## <span id='安装Yeoman'>安装Yeoman</span>

最简单安装**Yeoman**的方法是使用**Node Package Manager (npm)**，这是[Node.js](http://nodejs.org/)的一部分。**Yeoman**可以被全局的或本地的安装，在项目中，推荐你全局安装，因为在这种情况下你可以在任意目录运行而不仅仅是在它的安装目录中。

PhpStorm提供全局和本地安装的接口。可选的，你也可以通过命令行手动安装**Yeoman**。

要从PhpStorm安装**Yaomen**，在设置对话框使用**Node.js and NPM**页面：

1. 打开[设置参数对话框](/参考/设置参数对话框/README.md)通过按`Ctrl+Alt+S`或选择**File | Settings**（Windows/Linux）/**PhpStorm | Preferences**(OS X)，然后点击**Languages&Frameworks**下的**Node.js and NPM**
2. 在打开的**Node.js and NPM**页面，**Packages**区域显示当前电脑安装的Nodejs依赖包，包含全局的和项目级别的，点击![新增](http://image.jellychen.cn/uploads/2016/11/new.png)。
3. 在打开的**Available Packages**对话框，从列表中选择**yo**包。
4. 在全局安装，选择**Options**复选框并在旁边的文本框输入`-g`。
5. 点击**Install Package**启动安装。

要从命令行运行安装：

1. 通过将鼠标指针指向PhpStorm左下角的![工作区显示按钮](http://image.jellychen.cn/uploads/2016/11/show_tool_window_bars.png)并从菜单中并选择**Terminal**来启动内置**Terminal**(更多详情参见[使用嵌入式本地终端](/如何使用/常规指南/使用嵌入式本地终端.md))
2. 在命令行提示符处，输入以下命令：


        npm install -g yo
       
       
    `-g`意味着全局安装


## <span id='配置项目存根生成列表'>配置项目存根生成列表</span>

1. 在主菜单选择**File | New Project**或在欢迎界面点击**New Project**。[新建项目对话框](/参考/对话框/新建项目对话框.md)打开了:
2. 在左侧面板选择**Yeoman**。
3. 在右侧面板显示之前安装的[Yeoman生成器](http://yeoman.io/generators/)，点击**Install Generator**。
4. 在打开的对话框中展示所有可用的生成器包，选择在左侧面板选择所需的包并在右侧面板点击出现的**Install Generator**按钮。你可以不离开这个界面一个接着一个地安装若干个包。

    当安装完成后。点击**Close**来返回已经展开并显示新添加的包的生成器列表。


## <span id='通过生成器生成项目'>通过生成器生成项目</span>

1. 在主菜单选择**File | New Project**或在欢迎界面点击**New Project**。[新建项目对话框](/参考/对话框/新建项目对话框.md)打开了:
2. 在左侧面板选择**Yeoman**
3. 在右侧面板显示之前安装的[Yeoman生成器](http://yeoman.io/generators/)，要展开这个列表，点击**Install Generator**，参见上方的[配置项目存根生成列表](#配置项目存根生成列表)
    
    从列表中选择所需的生成器并点击**Next**
    
4. 在启动的**New Project**引导页面中指定所需的设置。这些页面和页面包含的内容基于选择的生成器。
5. 在引导的最后一个页面，选择或清除**Run npm install&bower install**复选框来指定你是否想运行**Node Package Manager**和**Bower**来安装开发新项目所需的包。
6. 点击**Click**并选择在当前窗口或新窗口打开这个新的项目。



# 另请参阅：

规程：

* [从框架模板生成项目](/如何使用/常规指南/创建和管理项目/从框架模板生成项目.md)

参考：

* [Yeoman](/参考/设置参数对话框/语言和框架/JavaScript/Yeoman.md)
* [新建项目：Yeoman](/参考/对话框/新建项目对话框/新建项目：Yeoman.md)
* [Node.js和NPM](/参考/设置参数对话框/语言和框架/NodeJs和NPM.md)
