翻译自cordova官方文档（如果需要链接，请自行对照原文链接进行查看）： <br>
https://cordova.apache.org/#getstarted<br>

###1 安装Cordova
Cordova的命令行工具是运行在Nodejs上的,通过npm安装,后面的platform(平台)相关的部分会介绍如何安装对应的平台依赖<br>
打开一个命令行窗口,输入下面的命令:
```sh
$ npm install -g cordova 
```
###2 创建Cordova项目
通过Cordova的指令工具创建一个空的Cordova project.
Create a blank Cordova project using the command-line tool. 
Navigate to the directory where you wish to create your project and type cordova create <path>.

For a complete set of options, type cordova help create.
```sh
$ cordova create MyApp 
```
3 Add a platform
After creating a Cordova project, navigate to the project directory. From the project directory, you need to add a platform for which you want to build your app.

To add a platform, type cordova platform add <platform name>.

For a complete list of platforms you can add, run cordova platform.

Copy
```sh
$ cd MyApp

$ cordova platform add browser
```

cd MyApp cordova platform add browser
4 Run your app
From the command line, run cordova run <platform name>.

Copy $ cordova run browser cordova run browser
5 Common next steps
