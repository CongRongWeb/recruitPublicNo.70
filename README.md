<p><h1 align="center">基于Java+Springboot+Vue的招聘系统</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>

## 一、系统介绍
本系统前后端分离

本系统分为管理员、HR、用户三种角色

用户角色包含以下功能：
- 登录、注册、简历(搜索、投递和收藏)、hr联系、我的关注、我的收藏、我的简历、简历投递管理、面试管理、个人中心、密码修改

HR角色包含以下功能：
- 登录、注册、职位管理、职位申请管理(筛选简历)、面试管理、我的企业管理、我的沟通、个人中心、密码修改

管理员角色包含以下功能：
- 包括用户和HR所有功能、日志管理、用户管理、角色管理、企业认证管理、职位认证管理、职位类别管理、个人中心、密码修改

## 二、所用技术

后端技术栈：
- Springboot
- mybatisPlus
- mysql
- JWT
- websocket
- redis
- SpringMvc

前端技术栈：
- Vue
- Vue-router
- axios
- element-ui



## 三、环境介绍

基础环境 :IDEA/eclipse, JDK 1.8, Mysql5.7及以上,tomcat8,Node.js(14.21),Maven3.6

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户页面
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
### 2、HR后台
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
### 3、管理员后台
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
## 五、浏览地址
- 前台访问路径：http://localhost:8080/#/index
- 后台访问路径：http://localhost:8080/#/about
  账号密码：
- 管理员  root/123456
- HR    hr/123456
- 用户    user/123456

## 六、安装教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件里面的sql；
2. 使用IDEA/Eclipse导入recruit-sys项目，导入时，若为maven项目请选择maven; 等待依赖下载完成；
3. 修改application.yml里面的mail配置和redis配置,application-dev.yml里面的数据库配置
4. vscode或idea打开recruit-web项目，
5. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址





