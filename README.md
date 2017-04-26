# 天梯（tianti）

  简介：<br>
  
    1、天梯是一款使用Java编写的免费的轻量级CMS系统，目前提供了从后台管理到前端展现的整体解决方案。
    2、前端页面自适应，支持PC和H5端，采用前后端分离的机制实现。
    3、项目技术分层明显，用户可以根据自己的业务模块进行相应地扩展。
    4、同时提供了针对dao、service等的代码生成工具。
    5、同时用户可以选择后台样式，目前拥有天梯蓝和天梯红两种皮肤。皮肤偏清新风格。
    
  互动：<br>
  
    1、如果您在使用过程中遇到问题，可以通过以下方式进行互动：邮箱：xuzhexu@139.com或qq交流群：422039518
    2、天梯的版权属于开源作者，未经作者同意任何人不得用于商业用途。
    3、如果您觉得作者的开源天梯系统能帮助到您，您可以打赏作者一瓶汽水，并且留言。您的鼓励是我们前行的动力。微信昵称：许哲。
   ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/tianti_dashang_erweima.png)  
    
  技术架构：<br>
  
     1、技术选型：Spring Data JPA、Hibernate、Shiro、 Spring MVC、Layer、Mysql等。
     2、项目结构：
       2.1、tianti-common：系统基础服务抽象，包括entity、dao和service的基础抽象；
       2.2、tianti-org：用户权限模块服务实现；
       2.3、tianti-cms:资讯类模块服务实现；
       2.4、tianti-module-admin：天梯后台web项目实现；
       2.5、tianti-module-interface：天梯接口项目实现；
       2.6、tianti-module-gateway：天梯前端自适应项目实现（是一个静态项目，调用tianti-module-interface获取数据）；
     3、使用说明：
      3.0、本项目JDK默认显示的是1.7，用户可以自行选择1.7+。
      3.1、数据库使用mysql，初始化脚本位于tianti-module-admin中的src/main/webapp/scripts/tianti_stage.sql。
      3.2、后台的登陆路径为http://ip:端口/login,用户名为admin，初始密码为123456。
      3.3、后台中所用到的图标是从font文件夹里面选择copy进去的，font文件夹在聊天群里面拥有。
      3.4、编辑器的配置修改editor_config.js的var context_ = "http://127.0.0.1:8080/tianti-module-admin";
      3.5、前端项目（tianti-module-gateway）是一个静态项目，可以直接部署到web容器，支持多端自适应，采用前后端分离机制获取数    据，在/src/main/webapp/static/js/config.js文件里分别配置接口地址和后台项目地址;
  
  前端项目概览：<br>
     PC：
     ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/gateway/index.png)  
     ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/gateway/columnlist.png)  
     ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/gateway/detail.png)  
     H5:
       
  后台项目概览：<br>
     天梯登陆页面：
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/login.png)  
     天梯蓝风格（默认）：
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/userlist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/rolelist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/menulist.png)                                           
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/roleset.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/updatePwd.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/skin.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/lanmulist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/addlanmu.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/articlelist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/addarticle.png)  
   天梯红风格：
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/userlist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/rolelist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/menulist.png)                                       
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/roleSet.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/updatePwd.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/skin.png) 
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/lanmulist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/addlanmu.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/articlelist.png)
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/red/addarticle.png)  
    ![image](https://raw.githubusercontent.com/xujeff/tianti/master/screenshots/tianti_dashang_erweima.png)  
    
    