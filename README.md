![](https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/logo.png)

## 一款跨平台的开源Github客户端App，提供更丰富的功能，更好体验，旨在更好的日常管理和维护个人Github，提供更好更方便的驾车体验～～Σ(￣。￣ﾉ)ﾉ。在开发学习过程中，提供丰富的同款对比：

* ### 同款Weex版 （ https://github.com/CarGuo/GSYGithubAppWeex ）
* ### 同款ReactNative版 （ https://github.com/CarGuo/GSYGithubApp ）


```
基于Flutter开发，适配Android与IOS。目前初版，持续完善中。

项目的目的是为方便个人日常维护和查阅Github，更好的沉浸于码友之间的互基，Github就是你的家。

项目同时适合Flutter的练手学习，覆盖了各种框架的使用，与原生的交互等。

随着项目的使用情况和反馈，将时不时根据更新并完善用户体验与功能优化吗，欢迎提出问题。
```
-----

[![GitHub stars](https://img.shields.io/github/stars/CarGuo/GSYGithubAppFlutter.svg)](https://github.com/CarGuo/GSYGithubAppFlutter/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/CarGuo/GSYGithubAppFlutter.svg)](https://github.com/CarGuo/GSYGithubAppFlutter/network)
[![GitHub issues](https://img.shields.io/github/issues/CarGuo/GSYGithubAppFlutter.svg)](https://github.com/CarGuo/GSYGithubAppFlutter/issues)
[![GitHub license](https://img.shields.io/github/license/CarGuo/GSYGithubAppFlutter.svg)](https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/LICENSE)

### 编译运行流程

1、配置好Flutter开发环境(目前Flutter SDK 版本 v0.5.7 的 Tag )，可参阅 [【搭建环境】](https://flutterchina.club)。

2、clone代码，执行`Packages get`安装第三方包。(因为某些不可抗力原因，国内可能需要设置代理: [代理环境变量](https://flutterchina.club/setup-windows/))

>### 3、重点：你需要自己在lib/common/config/目录下 创建一个`ignoreConfig.dart`文件，然后输入你申请的Github client_id 和 client_secret。

     class NetConfig {
       static const CLIENT_ID = "xxxx";
     
       static const CLIENT_SECRET = "xxxxxxxxxxx";
     }

     
   [      注册 Github APP 传送门](https://github.com/settings/applications/new)，当然，前提是你现有一个github账号(～￣▽￣)～ 。

4、运行



### 下载

#### Apk下载链接： [Apk下载链接](https://www.pgyer.com/vj2B)

#### Apk二维码

![](https://raw.githubusercontent.com/CarGuo/GSYGithubAppFlutter/master/download.png)

  
### 常见问题

* 如果包同步失败，一般都是因为没设置包代理，可以参考：[环境变量问题](https://github.com/CarGuo/GSYGithubAppFlutter/issues/13)


### 相关文章

* [Flutter 完整开发实战详解(一、Dart 语言和 Flutter 基础)](https://juejin.im/entry/5b631e3e51882519861c2ef1 )
* [Flutter 完整开发实战详解(二、快速实战篇)](https://juejin.im/entry/5b685bd4e51d451994602cae )



### 示例图片

<img src="https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/1.jpg" width="426px"/>

<img src="https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/2.jpg" width="426px"/>

<img src="https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/3.jpg" width="426px"/>


### 第三方框架

当前 Flutter SDK 版本 v0.5.7

库 | 功能
-------- | ---
**dio**|**网络框架**
**shared_preferences**|**本地数据缓存**
**fluttertoast**|**toast**
**flutter_redux**|**redux**
**device_info**|**设备信息**
**connectivity**|**网络链接**
**flutter_markdown**|**markdown解析**
**json_annotation**|**json模板**
**json_serializable**|**json模板**
**url_launcher**|**启动外部浏览器**
**iconfont**|**字库图标**
**share**|**系统分享**
**flutter_spinkit**|**加载框样式**
**get_version**|**版本信息**
**flutter_webview_plugin**|**全屏的webview**
**sqflite**|**数据库**


### 进行中：

[版本更新说明](https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/VERSION.md)


<img src="https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/thanks.jpg" width="426px"/>


### LICENSE
```
CarGuo/GSYGithubAppFlutter is licensed under the
Apache License 2.0

A permissive license whose main conditions require preservation of copyright and license notices. 
Contributors provide an express grant of patent rights. 
Licensed works, modifications, and larger works may be distributed under different terms and without source code.
```



    
