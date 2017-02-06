# 分享你的IDE设置


在这个页面中：

* [介绍](#介绍)
* [必备条件](#必备条件)
* [配置设置仓库](#配置设置仓库)
* [身份认证](#身份认证)
* [配置只读源](#配置只读源)


## <span id='介绍'>介绍</span>

PhpStorm允许你在不同的电脑上安装的不同的PhpStorm(或者其他IntelliJ平台)产品实例之间分享你的IDE设置。

这很有用当你使用若干PhpStorm设备，或者想在你的队伍成员或公司中实施相同的设置。


## <span id='必备条件'>必备条件</span>

在你开始使用Settings Repository工作之前，确保**Settings Repository**插件已经启用。这个插件是PhpStorm默认绑定和激活的。如果它没有激活，按照[启用和禁用插件](/如何使用/常规指南/管理插件/启用和禁用插件.md)章节的描述启用这个插件。


## <span id='配置设置仓库'>配置设置仓库</span>

如果你想分享你的IDE设置，执行以下步骤：

1. 在[GitHub](https://github.com/)创建一个仓库
2. 在你想分享的PhpStorm设置的电脑上，当你已经安装好了PhpStorm实例，跳转到**File | Settings Repository**。指定你创建的仓库的URL并点击**Overwrite Remote**
3. 在每个你想应用设置的电脑上，在[设置参数对话框](/参考/设置参数对话框/README.md)，展开**Tools**节点并选择[Settings Repository](/)，指定你创建的仓库的URL，并点击**Overwrite Local**。
    
    你可以点击**Merge**如果你想保存远程设置和本地设置的组合。如果发现冲突，你可以在显示的对话框中解决这些冲突。
    
    如果你想用本地设置覆盖远程设置，点击**Overwrite Remote**
    
在每次运行**Update Project**或**Push**操作，或关闭项目或退出PhpStorm时，储存在仓库的设置将自动同步你的本地设置。

如果你想禁用自动同步设置，跳转到**File | Settings | Tools | Settings Repository**并取消勾选**Auto Sync**选项。你将可以手动的更新设置通过在主菜单中选择**VCS | Sync Settings**。


## <span id='身份认证'>身份认证</span>

在第一次同步时，你会被提示指定一个用户名和密码。

推荐你使用GitHub用户校验的[访问令牌](https://help.github.com/articles/creating-an-access-token-for-command-line-use/)。如果，出于一些原因，你想使用用户名密码而不是访问令牌，或者你的Git主机不提供它，推荐你配置[Git凭证助手](https://help.github.com/articles/caching-your-github-password-in-git/)。

注意，支持[OS X 钥匙链](https://support.apple.com/kb/PH20093)，这意味着你可以在所有IntelliJ平台产品之间分享你的凭证（当原始IDE和请求IDE不同时将提示你允许授权）。


## <span id='配置只读源'>配置只读源</span>

除了**Settings Repository**之外，你也可以配置任意数量的额外仓库包含你想储存的想分享的任意类型的设置，包括动态模板，文件模板，方案，部署选项等。

这些仓库被作为只读源，并且他们不能被覆盖或分支，仅用于当做设置源。

要配置这种仓库，按下面的做：

1. 在[设置参数对话框](/参考/设置参数对话框/README.md)，展开**Tools**节点并选择[Settings Repository](/参考/设置参数对话框/工具/设置仓库.md)。
2. 点击![新增](http://image.jellychen.cn/uploads/2016/11/new.png)并添加包含你想分享的设置的GitHub仓库的URL。

执行只读源同步的方法与[配置设置仓库](#配置设置仓库)的方法相同。




# 另请参阅：

参考：

* [设置仓库](/参考/设置参数对话框/工具/设置仓库.md)