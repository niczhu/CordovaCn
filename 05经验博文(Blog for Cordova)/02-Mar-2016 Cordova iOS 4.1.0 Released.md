# Cordova iOS 4.1.0 
### By: Steve Gill(02 Mar 2016)
[原文连接](https://cordova.apache.org/announcements/2016/03/02/ios-4.1.0.html)

我们非常高兴的宣布Cordova iOS 4.1.0正式发布了.
此次更新修正了[issue CB-10530](https://issues.apache.org/jira/browse/CB-10530),一个在启动App以后偶尔无法响应用户操作的bug.

在新的Cordova-cli版本中,当用户使用Cordova platform add/update的时候,会将Cordova-iOS@4.1.0作为默认版本.
如果你现在就想用iOS@4.1.0,那么在使用Cordova platform add/update的时候记得指定版本号.

##### 现有工程升级
```sh
cordova platform update ios@4.1.0
```

##### 在新项目中使用
```sh
cordova platform add ios@4.1.0
```

针对iOS平台的新内容:<br>
[CB-10693](https://issues.apache.org/jira/browse/CB-10693) added missing header license<br>
[CB-10530](https://issues.apache.org/jira/browse/CB-10530) App freezes sometimes directly after starting on iOS<br>
[CB-10668](https://issues.apache.org/jira/browse/CB-10668) checked in node_modules<br>
[CB-10668](https://issues.apache.org/jira/browse/CB-10668) removed bin/node_modules<br>
[CB-10668](https://issues.apache.org/jira/browse/CB-10668) updated create.js to grab node_modules from root, updated package.json<br>
[CB-10138](https://issues.apache.org/jira/browse/CB-10138) Adds missing plugin metadata to plugin_list module<br>
[CB-10493](https://issues.apache.org/jira/browse/CB-10493) iOS Missing icon.png<br>
[CB-10184](https://issues.apache.org/jira/browse/CB-10184) Images.xcassets: A 83.5x83.5@2x app icon is required for iPad apps targeting iOS 9.0 and later<br>
Disable ios-deploy wifi mode when deploying to a device<br>
[CB-10272](https://issues.apache.org/jira/browse/CB-10272) Improve <allow-intent> and <allow-navigation> error logs<br>
Updated bundled ios-sim to 5.0.6<br>
[CB-10233](https://issues.apache.org/jira/browse/CB-10233) Support different config.xml file per CDVViewController instance<br>
Add additional valid targets for simulation<br>
Updated CDV version macro to 4.0.1<br>
[CB-10185](https://issues.apache.org/jira/browse/CB-10185) Update CordovaLib.xcodeproj to recommended settings in Xcode 7.2<br>
[CB-10171](https://issues.apache.org/jira/browse/CB-10171) WebKit Error after migration to iOS@4.0.0<br>
[CB-10155](https://issues.apache.org/jira/browse/CB-10155) DisallowOverscroll not working<br>
[CB-10168](https://issues.apache.org/jira/browse/CB-10168) CDVViewController appURL is nil if wwwFolderName is the path to a resource bundle<br>
[CB-10162](https://issues.apache.org/jira/browse/CB-10162) update reference url for icon images<br>
[CB-10162](https://issues.apache.org/jira/browse/CB-10162) correct the paths for iOS icon and splashscreen resources<br>
