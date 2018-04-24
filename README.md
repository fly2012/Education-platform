# 教育平台

---

## 前言

&emsp;&emsp;作为一个程序‘猿’，时曾在网上搜索各类的实战项目源码,大部分都是已经成型的企业的业务逻辑进行的二次分析，交互没有预期都是提前已经知晓的。但我们实际在工作中，经常会遇到随时更改的各类需求，所以对程序员逻辑严谨度要求高，处理特殊问题复杂，常常会让我们很头疼。既然这样，那不如自己来从源头分析一个产品。进行开发，希望站在研发的各个位置上，进行一次分析，对以后在项目中分析问题时，可以有一个更全面的眼光进行分析问题，我开源出来这次整体开发过程，希望对能看到的人会有帮助。

&emsp;&emsp;为啥是教育平台，而不是仿照现成的东西？原因很简单，业余时间，经常逛各类在线学习平台，每个网站都有各自的特点，但是又都有一些不好的交互，自己希望开发一个好的教育平台，方便大家学习。

&emsp;&emsp;这种功能性的项目很实用但是往往也很枯燥，没有音乐播放器那么看起来绚丽，思来想去发现饿了么是一个不错的素材，一来它足够复杂，开放的外卖平台比一般的公司独有商店更加复杂。二来 见到那么多美食，大家也不会感觉到厌烦

&emsp;&emsp;此项目估计不会少于50个页面，涉及注册、登陆、组织管理、班级管理等等，是一个完整的流程。一般公司即便是官网的单页面项目都没这么复杂，如果这个项目能驾驭的了，相信大部分公司的其他单页面应用也就不在话下，即便更复杂，也不会比这个高到哪里去。

&emsp;&emsp;因为利用业余时间来做，周期肯定有点长，项目从零布局开始到完成目前还不知道会多长时间，慢慢更新吧，会不断的进行一些页面的开发，增加详细的注释。

&emsp;&emsp;另外，这个项目为了开发迅速，使用Antd-pro进行构建，未自己重新构建，因为自己比较喜欢这个样式风格，哈哈~ 。

### 注：此项目纯属个人瞎搞，如有雷同纯属意外；

---

##主要进度

```gantt
    title 项目开发流程
    section 项目确定
        需求分析       :a1, 2018-04-24, 20d
        可行性报告     :after a1, 10d
        概念验证       : 10d
    section 项目实施
        概要设计      :2018-06-05  , 10d
        详细设计      :2018-06-18, 10d
        编码          :2018-06-30, 50d
        测试          :2018-08-22, 15d
    section 发布验收
        发布: 2d
        验收: 3d
```

## 技术栈
>React.js + dva.js + react-router + Redux + Ant.Design + Ant.Design.pro + WebPack + Less + Es6 + eS-lint

## 项目运行
注意：由于涉及 ES6/7 等新属性，nodejs 必须是 6.0 以上版本 ，node7是测试版，有可能会出问题，建议使用稳定版

>安装依赖
>&emsp;&emsp;npm install
>启动
>&emsp;&emsp;npm start

## 说明

>本项目主要用于熟悉如何用 React + dva 架构一个大型项目

>如果对您有帮助，您可以点右上角 “Star” 支持一下 谢谢！ 

>或者您可以 “follow” 一下，我会不断开源更多的有趣的项目

>开发环境 windows  Chrome 55

>开发工具 Eclipse + vscode 

>如有问题请直接在 Issues 中提，或者您发现问题并有非常好的解决方案，欢迎 PR 👍




