# 创建和运行你的第一个Web项目

熟悉PhpStorm建议你从头开始创建你的第一个项目,实现最基本的功能。

先创建并运行您的Web项目:

1. 创建一个项目，对于这个，在主菜单中选择** File | New | Project** ,[新建项目](/参考/对话框/新建项目对话框/README.md)对话框被打开。
2. 在左边的窗格中，选择**Empty Project**。
3. 在右边的窗格中,指定文件夹的路径来创建项目，例如：**C:\MY_PROJECTS\JAVA_SCRIPT_PROJECTS\MyFirstWebProject** ，在**Location** 文本框手动输入或者点击文本框旁边的**Browse** 按钮![浏览](http://image.jellychen.cn/uploads/2016/10/browseButton.png)。在[打开的对话框](/参考/对话框/选择路径对话框.md)选择目标文件夹。PhpStorm组成项目文件夹的路径如下:

    ![创建Web项目](http://image.jellychen.cn/uploads/2016/10/webstdcreateNewProject.png)
    
    点击**Create**，然后就好了。

4. 创建一个HTML文件，对于这个，在[项目工具窗](/参考/工具窗参考/项目工具窗.md)中右键点击项目目录，指向右键菜单上的**New**，然后选择**HTML File**

    ![新建HTML文件](http://image.jellychen.cn/uploads/2016/10/webstdcreateHtmlFile.png)
    
5. 在打开的**新建HTML文件**对话框中输入**MyFile** 然后点击**OK**。PhpStorm将为您创建存根文件,在专门的编辑器选项卡中打开它。
6. 在`<html />`标签中输入示例代码:
    
    ```html
    <html>
    <head>
        <script src="http://api-maps.yandex.ru/2.0/?load=package.full&lang=ru-RU"></script>
        <title>Your first Web project</title>
    </head>
    <body>
    <div id="map" style="width: 400px; height: 300px"></div>
    <label for="latitude">Latitude:</label>
    <input type="text" id="latitude" value="59.942402"/><br/>
    <label for="longitude">Longitude:</label>
    <input type="text" id="longitude" value="30.293661"/><br/>
    <input type="submit" value="Show map" onclick=" showMap(document.getElementById('latitude').value,document.getElementById('longitude').value);"/>
        <script type="text/javascript">
            function showMap (latitude, longitude) {
                var myMap = new ymaps.Map('map',{
                            center:[latitude, longitude],
                            zoom:16
                        });
                     }
        </script>
    </body>
    </html>
    ```

7. 保存文件，选择**File | Save All** 或者按 `Ctrl+S`。
8. 运行你的程序，按照以下之一去做：
    
    * 选中**View | Open in Browser**，然后从列表中选择想用的浏览器。
    * 在浏览器工具栏点击想用的浏览器:
        
        ![浏览器图标](http://image.jellychen.cn/uploads/2016/10/browserIcons.png)
        
9. 这个页面在浏览器中已经打开了，点击**Show Map**按钮，Yandex地图显示出来了，显示在圣彼得堡IntelliJLabs办公室的位置。

    ![Web测试页面](http://image.jellychen.cn/uploads/2016/10/web_storm_first_project_output.png)


# 另请参阅：

规程：

* [在浏览器中预览页面Web内容](/如何使用/常规指南/查看页面Web内容/README.md)

参考:

* [新建项目对话框](/参考/对话框/新建项目对话框/README.md)

入门指南：

* [用户界面引导](/如何使用/常规指南/用户界面引导/README.md)
