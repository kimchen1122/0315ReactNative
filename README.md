# 0315ReactNative
##简介
    __`React Native`__：`React Native` (简称`RN`)是`Facebook`于2015年4月开源的跨平台移动应用开发框架，是`Facebook`早先开源的UI框架 `React` 在原生移动应用平台的衍生
                产物，目前支持`iOS`和`安卓`两大平台。`RN`使用`Javascript`语言，类似于`HTML`的`JSX`，以及`CSS`来开发移动应用，因此熟悉Web前端开发的技术人员只需很
                少的学习就可以进入移动应用开发领域。
###原理
    `JS`(`React`)-->`JS Bridge`-->`Native Bridge`-->`Native`(`IOS`/`Android`) <br>
    `JS`脚本通过`bridge`实现了对`native`的`UI控件`和`模块方法`的直接调用
    ![alt](http://blog.cnbang.net/wp-content/uploads/2015/03/ReactNative1.png)
###比较
####与Hybrid
* __`Hybrid`__ :基于`H5`的`css`,使用`Native`运行`H5`的网页，展现方便，交互复杂，资源占用大。实际是运行的是`web网页`，速度慢，体验一般。`write once,use anywhere`。 
* __`RN`__ :实现了对`native`的`UI控件`和`模块方法`的直接调用，速度接近原生体验。`learn once,write anywhere`。 

####与Native
* __`Native`__ :开发学习成本高，体验好。 
* __`RN`__ :90%的展现可用`RN`开发完成，`Web`/`IOS`/`Android`大量代码可重用。

###技术栈
>__`React.js`__<br>
	`Facebook`前端框架
>>JSX DOM
	    区别于HTML+CSS
>>ES6/7
    新JS标准
>Node.js
	Google V8引擎,JS运行环境
>>npm生态
