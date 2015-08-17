# Grunt-LiveReload

建这个Git仓的目的，是因为总有小伙伴，通过各种方式给我留言，说自己配置出来运行报错。  
但通常都无法正确表述问题在哪，这让我很难帮到你什么。
另外，我也无法保证所有问题都能即时回复，所以大家可以首先通过以下3个步骤进行自查：
* 核对下各个插件是否都顺利安装。
* 检查一边是否有遗漏的步骤和地方。
* 我把本文的配置信息都上传至了Github，有需要的朋友可以下载下来进行对比

### Example 1: 

##### grunt-contrib-watch + grunt-livereload + Chrome Plug-in

安装命令：
> npm install --save-dev grunt-contrib-watch connect-livereload

由于Google被封，导致没有VPN的小或伙伴，无法安装Chrome LiveReload插件。  
所以，我把插件提取了出来打包在 `Example 1/ChromePlugins_LiveReload_2.1.0.rar` 。

Chrome Plugins离线安装方法：
* 解压至Chrome目录：C:\Users\\`Administration`\\AppData\Local\Google\Chrome\User Data\Default\Extensions
* 设置 - 扩展程序 - 启用LiveReload

### Example 2:

##### grunt-contrib-watch + grunt-contrib-connect + grunt-livereload

安装命令：
> npm install --save-dev grunt-contrib-watch grunt-contrib-connect connect-livereload

示例中所用到的插件版本：  
* connect-livereload 0.5.3  
* grunt-contrib-watch 0.6.1  
* grunt-contrib-connect 0.10.1

原文地址：[http://www.bluesdream.com/blog/grunt-plugin-livereload-wysiwyg-editor.html](http://www.bluesdream.com/blog/grunt-plugin-livereload-wysiwyg-editor.html)
