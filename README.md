# 0315ReactNative
##简介
    __React Native__：React Native (简称RN)是Facebook于2015年4月开源的跨平台移动应用开发框架，是Facebook早先开源的UI框架 React 在原生移动应用平台的衍生
                产物，目前支持iOS和安卓两大平台。RN使用Javascript语言，类似于HTML的JSX，以及CSS来开发移动应用，因此熟悉Web前端开发的技术人员只需很
                少的学习就可以进入移动应用开发领域。
###原理
    JS(React)-->JS Bridge-->Native Bridge-->Native(IOS/Android)
    RN(JS脚本通过bridge实现了对native的UI控件和模块方法的直接调用)
![alt](http://blog.cnbang.net/wp-content/uploads/2015/03/ReactNative1.png)
###比较
####与Hybrid
* __Hybrid__ :基于H5的css,使用Native运行H5的网页，展现方便，交互复杂，资源占用大。实际是运行的是web网页，速度慢，体验一般。write once,use anywhere。 *
* __RN__ :实现了对native的UI控件和模块方法的直接调用，速度接近原生体验。learn once,write anywhere。 *
####与Native
