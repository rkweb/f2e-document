# f2e新手指引  

欢迎你来到f2e的大家庭，请详细阅读以下内容以便快速高效的展开工作:bowtie:

## Get Started
- 安装网易popo、Adobe Photoshop CC 2017、自己熟悉的编辑代码软件及常用插件、TortoiseSVN  
参考安装地址:  
popo:http://popo.163.com/  
Photoshop CC 2017:http://www.adobe.com/cn/downloads.html  
TortoiseSVN: https://tortoisesvn.net/downloads.zh.html  
sublime: https://www.sublimetext.com/3  

- 关于Photoshop的破解 （文件资源请向上查找 **Photoshop.rar**）  
①打开**photoshop破解** 文件夹，将里面的资源复制到你的Photoshop文件安装目录下  
②双击**激活注册软件.exe**，选择倒数第二项后再次点击破解即可完成配置；如下图  
<img src="http://test.go.163.com/go/2017/0101/f2eGuide/poujie.png" style="width:300">

- 关于Photoshop插件的安装（文件资源请向上查找 **Photoshop.rar**）  
①**拆分-V3.1.atn** 直接双击即可完成安装; 用于在psd图中快速截取图片资源 (默认快捷键为**F2**)  
②**TinyPNG 插件** 进入 TinyPNG插件 文件夹，打开 Readme.txt 文档，根据里面的操作流程进行操作   
注意：  
在 Readme.txt 文档中第一步操作中，首先需要修改 1.Registry Entry 目录下的 **PhothoshopCC.reg** 配置文件，将里面默认的Photoshop的路径地址都改为你的安装地址，然后保存文件后双击该文件即可完成第一步操作!下图中红框内是需要修改的地方。  
该插件用于将.png图片进行压缩；打开Photoshop——>文件——>脚本——>TinyPNG,然后找到图片文件的目录即可进行图片压缩  
<img src="http://test.go.163.com/go/2017/0101/f2eGuide/Tiny.png" style="width:300">  
  


## 关于svn的使用  

### svn地址目录
- svn://61.135.254.16/go/go/2017/  (常规专题)  
- svn://61.135.254.16/auto/2017/  (汽车专题)
- 注意：  
①svn的账号是由后台的**张立**为您开通。打开网易popo找到机器人，在网易小泡助手里输入张立后将其添加为您的好友，请他来帮您开通svn账号  
②找到一个空的本地磁盘，创建名为**auto** 和 **go**这两个文件夹；单击右键通过svn地址目录**Checkout(检出)**项目专题  
下图为检出go（常规类专题）目录下的2017年的项目专题；auto(汽车类专题)同理  
<img src="http://test.go.163.com/go/2017/0101/f2eGuide/checked.png?sdf" style="width:300">

### 创建svn时的注意事项
1. 创建项目链接地址时, 按照 **专题类型/年份/上线日期/项目名称** 去创建
 
2. 创建项目链接时, 依次向**执行（PM）**询问如下内容：  
①项目类型（汽车或是常规专题）  
②项目上线日期  
③链接后缀有无特殊要求, 没有再创建, 一般手机端页面后缀写上"-wap"  
④项目是否涉及到后台功能, 是的话让执行（PM）直接找后台沟通  
例如：  
svn://61.135.254.16（存放检出项目的本地磁盘）/auto/2017/0105/jade-spirior/  当创建完成后, 把jade-spirior文件夹提交到svn上  
注意：每次提交或更新项目时，要先右键——>**SVN Update** 后再进行 **SVN Commit**操作  
<img src="http://test.go.163.com/go/2017/0101/f2eGuide/auto.png?sdf" style="width:300">

3. 然后根据所创建的项目文件夹给执行（PM）专题的测试链接和正式链接地址  
例如：  
汽车专题的测试链接地址为: http://test.go.163.com/auto/2017/0105/jade-spirior/  
汽车专题的正式链接地址为: http://s.auto.163.com/2017/0105/jade-spirior/

4. 生成的__常规专题__测试链接地址为: http://test.go.163.com/go/年份/日期/项目名称/  
常规专题测试地址可以再这个网站中找到： http://test.go.163.com/go/2016/nomo.php
 
5. 生成的__汽车专题__测试链接地址为: http://test.go.163.com/auto/年份/日期/项目名称/  
汽车专题测试地址可以再这个网站中找到： http://test.go.163.com/auto/2016/nomo.php
 
6. 生成的__常规专题__正式链接地址为: http://go.163.com/年份/日期/项目名称/
   
7. 生成的__汽车专题__正式链接地址为: http://s.auto.163.com/年份/日期/项目名称/
  
8. 建议将以上的专题的链接地址收藏到chrome的书签中
 
9. 不要用svn上传视频文件到服务器 (需要找任科帮忙上传)
 
10. 在复制专题文件夹的时候不要把php文件一起复制过去  
 
11. 更加快速的同步到正式服务器的方法: 因为服务器会有缓存, 当修改完成后, 先提交svn, 再在html加版本号  



## 每周工作
- 每周一早上10点之前提交给赵杰沫上周工作总结, 用ppt的形式, 每一页一个项目说明, 二维码尽量放大一些便于大家扫描, 链接做成可点击的形式, 具体参考ppt示例__weekly-submit.ppt__  （文件地址请向上查找，ppt命名：姓名+日期）

- 每周二早上10点之前更新上周项目, 地址为http://test.go.163.com/go/2015/public/manage/index.html

- 具体更新方法:  
①. 在svn://61.135.254.16/go/go/2015/public/manage/js/data/ 下创建有自己名字.js文件, 按照如下格式更新文件；  
②. 修改svn://61.135.254.16/go/go/2015/public/manage目录下的index.html，按照格式引入带有自己名字.js文件；  
③. 最后会自动显示在页面中，查看地址为http://test.go.163.com/go/2015/public/manage/index.html

		//js
        var ningbo = {
	    	20170103:[
				{
		    		"proName": "东方Honda品牌盛典", //项目名称
		    		"frontEnd": "宁勃", //前端
		    		"backEnd": "无", //后端
		    		"design": "欧文静", //设计
		    		"onlineTime": "2017-01-05", //上线时间
		    		"area": "华南", //项目归属地(华北, 华东, 华南)
		    		"platform": "手机端", //手机端 或 pc端
		    		"link": "http://test.go.163.com/auto/2017/0105/jade-spirior/", //项目测试地址
		    		"content": "完成" //完成 或 正在进行
	    		}
			]
    	}



## 常用代码

### 监测代码
http://test.go.163.com/go/2015/public/common/code_monitor.html  

### 移动端分享代码
http://test.go.163.com/go/2015/public/common/wap_share.html

### pc端分享代码
http://test.go.163.com/go/2015/public/common/pc_share.html

### loading代码
http://test.go.163.com/go/2015/public/common/loading.html  

## 常用工具
### 生成雪碧图工具
### 图片压缩工具

## 常用库

### zepto (已整合swiperup、touch等一些方法)
http://go.163.com/2015/public/common/js/zepto.min.js

### swiper
http://idangero.us/swiper/#.WASBwuB96Hs  

### 自定义scrollbar  
http://manos.malihu.gr/jquery-custom-content-scroller/  

### 移动端页面常用功能  
http://go.163.com/2015/public/common/js/common.js


## 代码要求
###PC端
- 浏览器兼容到ie8及以上版本

###Wap端
