<p>
<a href="https://github.com/youzan/"><img alt="有赞logo" width="36px" src="https://img.yzcdn.cn/public_files/2017/02/09/e84aa8cbbf7852688c86218c1f3bbf17.png" alt="youzan">
</p></a>
<p align="center">
    <img src="http://gitlab.qima-inc.com/qa/UIAutomation/raw/hotfix/output/src/main/resources/img/bee-project.png?raw=true" alt="bee logo" srcset="http://gitlab.qima-inc.com/qa/UIAutomation/raw/hotfix/output/src/main/resources/img/bee-project.png?raw=true 1x, 
    http://gitlab.qima-inc.com/qa/UIAutomation/raw/hotfix/output/src/main/resources/img/bee-project.png?raw=true 2x, 
    http://gitlab.qima-inc.com/qa/UIAutomation/raw/hotfix/output/src/main/resources/img/bee-project.png?raw=true" width="210" height="210"">
</p>
<p align="center">Bee是由有赞QA开发的UI自动化工具，并以此实现了web端&wap端的核心业务的自动化。</p>
 
## 概述
* Bee是基于对Selenide和Selenium进行的二次封装，旨在简化接口，方便使用。
* Bee支持Web和Wap页面的元素操作，其中Selenide用来支持Web页面，Selenium用来支持Wap页面。
* Bee目前支持的环境为：mac、chrome，可扩展

## 功能 
* Bee接口解决了方法调用过程中元素加载、页面加载等常见问题
* Bee在框架层实现失败用例重试，提高用例结果的可靠性
* Bee对Selenide和Selenium常用接口二次封装，使调用更简便
* 使用reportng收集测试数据，可结合jenkins的插件呈现测试报告

## 框架简介
* driver层二次封装Selenide和Selenium的接口，是操作页面元素的核心
* pageObject层用于封装业务流程中需要使用的每一个页面元素，是业务流程实现的核心
* dataprovider层自定义测试数据，实现测试数据的隔离
* service层用于定义各模块之间的公共业务流程，实现模块间业务的调用

## 环境配置
* 被测环境添加  127.0.0.1   localhost

## 开源协议
* 本项目基于 [MIT](https://zh.wikipedia.org/wiki/MIT%E8%A8%B1%E5%8F%AF%E8%AD%89) 协议，请自由地享受和参与开源。

