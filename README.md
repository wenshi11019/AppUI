# AppUI自动化框架

基于 Appium 的 UI 自动化测试框架。

## 简介
使用 Java 语言编写的。基于开源的 Appium 开源自动化测试框架，该框架结合结合 Selenium、Appium、TestNG、Log4j、poi、extentreports、dom4j等工具。该框架实现了关键字驱动技术、数据驱动，使用 Excel 文件即可编写自动化测试用例，做到代码和数据分离，互不影响。当 APP 页面变动，只需要更变测试用例即可。可对测试失败点自动截图功能，并在测试完成后，生成一份测试报告。

## 主要功能
1、实现关键在驱动技术，编写自动化测试用例简单 <br>
2、实现数据驱动技术，减少用例代码量 <br>
3、测试用例采用 Excel 文件编写，页面元素信息与代码分离 <br>
4、Appium 服务从测试开始启动，测试完毕后，自动关闭 <br>
5、直接测试失败截图，且不影响用例后续执行 <br>
6、测试结果可直接输出到 Excel 用例文件 <br>
7、测试完毕，自动生成简洁美观的 html 报告(目前仅限使用关键字驱动时，才会生成) <br>

## 环境配置
详情请查看 doc 文件夹的 Start-Appium.md

## 更新日志

### V3.0正在构建中)
**为了与旧提交的版本区分，从3.0版本开始**
- 每次元素操作成功或失败时都会截图

### V1.1
- 修复 ios 真机测试例子
- pom.xml 增加将依赖库一起打包
- 去掉 Android 解锁的 API
- 更新 javadoc

### V1.0
- ~~修复Android 6.0或以上设备解锁失败的例子~~
- 更新 javadoc

### V1.0-beta
- 基于 Appium 自动化框架，进行二次封装，二次优化
- 采用 Log4j 框架进行日志输出
- 数据驱动，采用 Excel 文档为数据源，使用 POI 框架读写，测试的结果自动输入到 Excel 文档的相应位置中
- 增加可视化测试报告输出，测试失败后自动截图输出，采用 ExtentReport 框架
- 可根据设备号自动获取设备其他信息
- 增加 javadoc API 文档
- 支持 Android 测试多设备并发运行测试
- 测试框架、测试应用脚本、测试用例数据三层分离，互不影响，提高代码维护性

## Javadoc
查看源码 javadoc 文件夹

## 实例
请查看test 源码文件夹中的简单实例


