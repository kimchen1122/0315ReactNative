# 0315ReactNative #
## 简介 #
>__`React Native`__：`React Native` (简称`RN`)是Facebook于2015年4月开源的跨平台移动应用开发框架，是Facebook早先开源的UI框架 `React` 在原生移动应用平台的衍生
>产物，目前支持`iOS`和`安卓`两大平台。`RN`使用`Javascript`语言，类似于`HTML`的`JSX`，以及`CSS`来开发移动应用，因此熟悉Web前端开发的技术人员只需很
>少的学习就可以进入移动应用开发领域。

### 原理 ###
    `JS`(`React`)-->`JS Bridge`-->`Native Bridge`-->`Native`(`IOS`/`Android`) <br>
    `JS`脚本通过`bridge`实现了对`native`的`UI控件`和`模块方法`的直接调用
    ![alt](http://blog.cnbang.net/wp-content/uploads/2015/03/ReactNative1.png)

## 比较 ##
### 与Hybrid ###
* __`Hybrid`__ :基于`H5`的`css`实现,使用`Native`运行`H5`的网页，展现方便，但交互复杂，资源占用大。实际是运行的是`web网页`，速度慢，体验一般。`write once,use anywhere`。 
* __`RN`__ :实现了对`native`的`UI控件`和`模块方法`的直接调用，速度接近原生体验。`learn once,write anywhere`。 

### 与Native ###
* __`Native`__ :开发学习成本高，体验好。 
* __`RN`__ :90%的展现可用`RN`开发完成，`Web`/`IOS`/`Android`大量代码可重用。

## 技术栈 ##

* __`React.js`__ <br>Facebook前端框架
	* `JSX` `DOM` `CSS`
		区别于`HTML`+`CSS`
* __`ES6/7`__ <br>新的JS标准
* __`Node.js`__ <br>Google V8引擎,JS运行环境
	* `npm生态`
	* `JS Runtime Server`
* __`RN`__ <br> 不多说了
	* `FlexBox`布局
	* 组件通信
	* ...
* __`Native`__ <br>`IOS` `Android`
	* 原生开发技术（应用打包等）
	* 混合开发
* __前端框架__<br>
	* `MVC`框架等
	* `Redux`
	* ...

### 技术学习 ###
* [从零学React Native](http://blog.csdn.net/column/details/react-native-study.html?&page=2) <br>
* [React-Native学习指南](https://github.com/reactnativecn/react-native-guide#%E5%9B%BE%E4%B9%A6) <br>
###组件收集
* [React-Native学习指南](https://github.com/reactnativecn/react-native-guide#%E5%9B%BE%E4%B9%A6) <br>
##DEMO显示
##总结
