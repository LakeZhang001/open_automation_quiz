# Open Automation Quiz
[![Build Status](https://github.com/alaahong/open_automation_quiz/workflows/CI/badge.svg)](https://github.com/alaahong/open_automation_quiz)
[![Code Quality Score](https://www.code-inspector.com/project/4050/score/svg)](https://www.code-inspector.com/project/4050/score/svg)

## 任务要求
* 请**Fork**本项目到您自己的Github账号下
* 以下内容均基于**Java**进行考察  
* 网页端内容需同时对**Chrome**和**IE**两种浏览器进行实现  
* 手机端内容可以基于Android或iOS平台二选一  
* 请尽量完成更多的任务，有余力的话可以针对**项目结构**和**代码质量**进行完善  
* 请于完成后，将项目源码更新至候选者的Github，将项目设置为Public后提供项目链接 
* 默认期望候选者提交的项目可以直接运行，若担心环境问题，可以将运行结果的截图添加至项目资源目录内，并声明截图路径 

******
## 1. 必应搜索(Selenium)  

请使用Selenium打开[**微软Bing搜索**](https://cn.bing.com/)，在搜索栏内输入关键词 "**Bing**" 并执行搜索操作，请基于搜索结果的**第二页**内容，请打印每个结果的标题以及链接，同时统计并打印每个顶级域名出现的次数。  
完成后请在上一步的搜索结果页，继续基于关键词 "**SC**" 执行同样的打印操作。

 例：若得到以下的搜索结果   
 [Bing Translator](www.bing.com/Translator)   
 [Bing](https://cn.bing.com/?setmkt=de-de&setlang=de-de)   
 [bing（搜索引擎）_百度百科](https://baike.baidu.com/item/bing/5994319)   
 
 则应输出  
```   
结果列表  
Bing Translator  --> www.bing.com/Translator   
Bing  --> https://cn.bing.com/?setmkt=de-de&setlang=de-de    
bing（搜索引擎）_百度百科  --> https://baike.baidu.com/item/bing/5994319   

结果统计 
bing.com  --> 2
baidu.com  --> 1  
```
  ******
## 2. 企业复工申请资料提交表(Cucumber)    

请基于**Cucumber**，以**BDD**的形式，自行实现所需的**Feature**和**Gherkin**，用于以下操作  
打开网页 [**企业复工申请资料提交表**](https://templates.jinshuju.net/detail/Dv9JPD)  
请在第一页填写以下内容  
“**请选择贵单位情况**”的选项组中选择 “**连续生产/开工类企事业单位**”  
将**第一页**进行**截图**  
点击**下一页**按钮  
请在第二页填写以下内容  
|栏位|内容|
|:-|:-:|
|申请日期|输入框填写程序运行的当天日期| 
|申请人|自动化| 
|联系方式|1388888888|    

点击**下一页**按钮  
将**第二页**进行**截图**  
请在第三页填写以下内容  
|栏位|内容|
|:-|:-:|
|报备单位|测试公司| 
|在岗人数|99| 
|报备日期|执行测试的日期| 
|湖北籍员工、前往湖北以及与湖北人员密切接触的员工（人数）|0| 
|单位负责人|CEO| 
|联系方式|13888888888| 
|疫情防控方案|测试内容|   

将**第三页**进行**截图**  
点击**提交**按钮  
判断**提交成功**  
将**提交结果页**进行**截图**  

测试完成后，应生成相应的**HTML**格式的**测试报告**  
  ******
  
## 3. 手机APP(Appium)  
  
请基于 **Appium**  完成任意一款APP的自动化测试，请附带可下载的测试APP样例链接  
测试内容需包括以下操作  
* 点击按钮
* 文本框输入
* 清除指定文本框的内容  
* 断言页面指定内容
* 滑动页面