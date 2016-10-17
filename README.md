# f2e新手指引  
欢迎来到f2e大家庭  
## Get Started
- 安装photoshop, 自己熟悉的编辑代码软件, TortoiseSVN  
参考:  
TortoiseSVN: https://tortoisesvn.net/downloads.zh.html
sublime: https://www.sublimetext.com/3

## 关于svn  

### svn地址目录
- svn://61.135.254.16/go/ (常规专题)  
- svn://61.135.254.16/auto/ (汽车专题)

### 创建svn时的注意事项
- 创建目录时, 按照/年份/日期/ 创建, 例如svn://61.135.254.16/auto/2016/0731/toyota-wap  
- 专题地址创建的时候,日期写成上线日期  
- 创建活动链接时, 先问执行链接后缀有无特殊要求, 没有再创建, 一般手机端页面后缀写上"-wap"  
- 不要用svn上传视频文件到服务器 (需要找任科帮忙上传)  
- 涉及到后台功能, 让执行直接找后台沟通  
- 在复制专题文件夹的时候不要把php文件一起复制过去  
- 更加快速的同步到正式服务器的方法: 因为服务器会有缓存, 当修改完成后, 先提交svn, 再在html加版本号  
- 生成的__常规专题__测试链接地址为: http://test.go.163.com/go/年份/日期/项目名称/  
- 生成的__汽车专题__测试链接地址为: http://test.go.163.com/auto/年份/日期/项目名称/
- 生成的__常规专题__正式链接地址为: http://go.163.com/年份/日期/项目名称/  
- 生成的__汽车专题__正式链接地址为: http://s.auto.163.com/年份/日期/项目名称/  

## 每周工作
- 每周一早上10点之前提交给赵杰沫上周工作总结, 用ppt的形式, 每一页一个项目说明, 二维码尽量放大一些便于大家扫描, 链接做成可点击的形式, 具体参考ppt示例__weekly-submit.ppt__  
- 每周二早上10点之前更新上周项目, 地址为http://test.go.163.com/go/2015/public/manage/index.html,  
具体更新方法: 在svn://61.135.254.16/go/2015/public/manage/js/data/ 中有自己名字.js文件, 按照格式更新文件, 最后会自动显示在页面中  
```js
20161010:[
	{
		"proName": "态度星际趴预热插画全景", //项目名称
		"frontEnd": "孔德建", //前端
		"backEnd": "", //后端
		"pm": "赵艺婷", //执行
		"onlineTime": "2016-10-14", //上线时间
		"area": "华北", //项目归属地(华北, 华东, 华南)
		"platform": "wap端", //手机端, pc端
		"link": "http://test.go.163.com/go/2016/1008/taidu/3d.html", //项目地址
		"content": "正在进行" //完成, 正在进行
	}
]
```

## 常用代码

### 监测代码
http://test.go.163.com/go/2015/public/common/code_monitor.html  

### 移动端分享代码
http://test.go.163.com/go/2015/public/common/wap_share.html

### pc端分享代码
http://test.go.163.com/go/2015/public/common/pc_share.html

### loading代码
http://test.go.163.com/go/2015/public/common/loading.html
