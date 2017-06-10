# Demo
Selenium automation test framework

Use Selenium 3.x  + testng + Jenkins + Maven 

Use Page object model

Use log4j

如何使用：
1. 安装maven配置环境变量
2. git clone  https://github.com/tobecrazy/Demo.git 
3. mvn test
也可以直接使用jenkins，触发mvn test

使用interface 处理不同版本的页面，
使用java反射机制实现页面跳转
使用java 注解实现不同类反射初始化
使用单例模式实现初始化唯一driver对象
已废弃Ant
引入Spring


Roadmap
1. 使用Builder设计模式(Done)
2. 优化测试报告 (in-progress)
3. 使用容器，抽象出单独的截图服务
4. Refactor 页面元素加载功能
5. 加入预判环境功能，通过http response code判断环境
6. Selenium UI自动化优化测试脚本心得整理
7. 加入图像对比，实现处理拖拽验证码
8. 使用Jacoco 做code coverage
![Alt text](https://github.com/tobecrazy/SeleniumDemo/blob/master/code%20coverage.png "Snapshot")

![Alt text](https://github.com/tobecrazy/Demo/blob/master/jenkins.png  "Snapshot")

微信公共账号：

![Alt text](https://github.com/tobecrazy/Demo/blob/master/weixin.gif  "weixin")
