# PhpStorm工具窗

在这个章节中：

* PhpStorm工具窗
    * [概述](#概述)
    * [快速访问工具窗](#快速访问工具窗)
    * [工具窗栏和按钮](#工具窗栏和按钮)
    * [通用工具窗布局](#通用工具窗布局)
    * [访问工具窗菜单](#访问工具窗菜单)
* [操作工具窗](/如何使用/常规指南/PhpStorm工具窗/操作工具窗.md)
* [指定工具窗的外观设置](/如何使用/常规指南/PhpStorm工具窗/指定工具窗的外观设置.md)
* [在工具窗快速搜索](/如何使用/常规指南/PhpStorm工具窗/在工具窗快速搜索.md)
* [查看模式](/如何使用/常规指南/PhpStorm工具窗/查看模式.md)
* [管理项目收藏夹](/如何使用/常规指南/PhpStorm工具窗/管理项目收藏夹.md)


## <span id='概述'>概述</span>

附加在工作区底部的是PhpStorm工具窗。这些第二窗口让你查看项目从不同的视角并提供访问特定的开发任务。这些包括项目管理，代码搜索和浏览，运行和调试，集成版本控制系统，和许多其它特殊任务。

![工具窗](http://image.jellychen.cn/uploads/2016/11/php_storm_tool_windows_new.png)

某些工具窗总是可用，换言之，在任何[项目](/参考/要点/项目.md)而不管项目性质，内容和配置，有些窗口总是可用的。有些工具窗仅在一些相关[插件](/如何使用/常规指南/管理插件/插件.md)启用时可用。还有一些窗口需要特定的动作才能显示（例如，要显示[查找工具窗](/参考/工具窗参考/查找工具窗.md)，你必须先搜索一些东西）。


## <span id='快速访问工具窗'>快速访问工具窗</span>

在工作区的左下角，有一个按钮开始开起来像![工作区显示按钮](http://image.jellychen.cn/uploads/2016/11/show_tool_window_bars.png)

如果你指到这个图标，一个菜单打开了，提供快速访问工具窗的入口。

![快速访问工具窗](http://image.jellychen.cn/uploads/2016/11/ToolWindowsQuickAccessPS.png)

菜单中选项的名字和工作区的名字一致。当你选择一个选项，相应的工具窗打开并被激活。

如果你点击这个按钮，工具窗栏和按钮显示出来了。与此同时这个按钮的外观变成![工具窗图标](http://image.jellychen.cn/uploads/2016/10/show_hide_tool_window_bars.png).如果你再次点击这个按钮，工具窗栏和按钮再次隐藏。


## <span id='工具窗栏和按钮'>工具窗栏和按钮</span>

当可见时，工具窗按钮栏(或者仅为工具窗栏)环绕在工具窗(或者[编辑器](/如何使用/常规指南/PhpStorm编辑器/README.md)区域，如果工具窗隐藏了)。这些栏包含按钮为显示或隐藏的工具窗(工具窗按钮)。

![工具窗栏和按钮](http://image.jellychen.cn/uploads/2016/11/tool_window_bar_and_buttons.png)

工具窗按钮也提供工具窗的上下文菜单入口，当在按钮上右键单击时显示。

![工具窗上下文菜单](http://image.jellychen.cn/uploads/2016/11/tool_window_button_context_menu.png)

上下文菜单让你可以控制工具窗[查看模式](/如何使用/常规指南/PhpStorm工具窗/查看模式.md)和工具窗其他方面的外观。

首先，有三个工具窗栏，两个在主窗口两侧，一个在底部。可以一次展示或隐藏所有按钮栏通过点击工作区左下角的![工具窗图标](http://image.jellychen.cn/uploads/2016/10/show_hide_tool_window_bars.png)

每个工具窗按钮上有相应工具窗的名字。在某些按钮，窗口名字可能以数字开头，例如**1: Project**，这意味着快捷键`Alt+<number>`可用来展示或隐藏这个窗口。你可以，例如，展示或隐藏项目工具窗通过按`Alt+1`。

你可以转换窗口访问数字的开关在[外观设置](/参考/设置参数对话框/外观行为/外观.md)中。

可见的工具窗和隐藏的工具窗的按钮外观不同

![工具栏按钮外观](http://image.jellychen.cn/uploads/2016/11/tool_window_buttons.png)

你可以重新排列工具窗通过拖放工具窗按钮到不同的工具窗栏(或者拖放到相同工具窗栏的不同角落)。作为结果，工具窗栏附加到你移动窗口按钮到的栏上。

![重新排列工具窗栏](http://image.jellychen.cn/uploads/2016/11/tool_window_buttons_drag.png)


## <span id='通用工具窗布局'>通用工具窗布局</span>

通常，所有的工具窗按照相同的方式组织：

![工具窗布局](http://image.jellychen.cn/uploads/2016/11/ps_tool_window_layout.png)

在所有窗口的顶端是一个小的标题栏，当右键单击标题栏，管理该窗口外观和内容的菜单展示出来了。

![工具窗菜单](http://image.jellychen.cn/uploads/2016/11/ps_tool_windows_title_bar.png)

标题栏的右手边包含两个按钮，第一个按钮(![工具栏设置按钮](http://image.jellychen.cn/uploads/2016/11/viewMode.png))打开菜单来管理工具窗的[查看模式](/如何使用/常规指南/PhpStorm工具窗/查看模式.md)。注意这个菜单选项是标题栏上下文菜单的子集。

![工具窗查看模式菜单](http://image.jellychen.cn/uploads/2016/11/tool_window_viewing_modes.png)


第二个按钮(![隐藏工具窗](http://image.jellychen.cn/uploads/2016/11/hideSide.png))是用来隐藏工具窗。当与`Alt`键结合使用时，点击这个按钮隐藏所有关联到相同工具窗栏的窗口。

在标题栏下方是工具栏和内容面板。取决于窗口，工具栏可能在内容面板的左边或上面。

工具栏按钮，通常，每个窗口都是特定的。然而，有相同目的的窗口可能在工具栏包含类似的操作。

大部分情况下，关联在工具栏按钮上的功能也可以从主菜单或上下文菜单中访问，或者有等价的快捷键。

内容面板可能是简单的或者包含两个或更多“图层”(视图)，例如，也许有工具窗的内容面板部分显示在编辑器区域的独立标签中。


## <span id='访问工具窗菜单'>访问工具窗菜单</span>

* 使用** View | Tool Windows**菜单显示或隐藏工具窗。

![访问工具窗菜单](http://image.jellychen.cn/uploads/2016/11/other_products_toolWindowMenu.png)


# 另请参阅：

规程：

* [操作工具窗](/如何使用/常规指南/PhpStorm工具窗/操作工具窗.md)
* [查看模式](/如何使用/常规指南/PhpStorm工具窗/查看模式.md)
* [在工具窗快速搜索](/如何使用/常规指南/PhpStorm工具窗/在工具窗快速搜索.md)
* [指定工具窗的外观设置](/如何使用/常规指南/PhpStorm工具窗/指定工具窗的外观设置.md)
* [配置快捷键](/如何使用/常规指南/配置项目和IDE设置/配置快捷键.md)

参考：

* [工具窗参考](/参考/工具窗参考/README.md)