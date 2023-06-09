
修订记录 (REVISION RECORD)
日期
Date	修订版本
Revision version	修改描述
Change Description	作者
Author
2022年12月11日	V1	首次	杨宗源
			
			
			
			



目  录
一、引言	5

（一）编写目的	5

（二）项目背景	5

（三）术语定义	5

二、产品定义	5

（一）应用目标	5

（二）产品业务架构	5

三、应用环境	6

（一）系统运行的硬件环境	6

（二） 系统运行的软件环境	6

（三）系统运行的网络环境	6

（四）用户操作模式	6

四、功能规格	6

（一）功能需求清单	6

（二）业务功能：学生端	7

1.启动页功能模块	7

2.登录页功能模块	7

3.主界面功能模块	8

4.德育评分功能模块	9

4.评分列表功能模块	10

5.班级广播功能模块	11

6.设置页面功能模块	12

（二）业务功能：德育平台小程序（教师端、家长端）	13

1.公共引导与登录页面功能模块	13

2.公共身份选择页面功能模块	13

3.教师端主界面功能模块	14

4.教师端发布通知与布置作业功能模块	14

5.教师端我的班级功能模块	15

6.教师端班级广播台功能模块	20

7.教师端审核功能模块	20

8.教师端更多功能模块	21

9.家长端主界面功能模块	23

10.家长端孩子管理功能模块	24

11.家长端德育评分功能模块	25

12.家长端班级广播台功能模块	25

13.家长端更多功能模块	26

五、性能需求	27

六、产品提交	28

（一）产品提交方式	28

（三） 产品提交时间需求	28

（三）产品部署需求	28

（四）产品维护需求	28

七、外部接口说明	29

八、其他需求	29

九、在线演示	29




一、引言
（一）编写目的
编写本需求规格说明书的目的是为了详细呈现“发展性评价”管理系统的功能描述，以进一步定制开发的细节问题，便于与项目开发协调工作。本文档面向的读者主要是项目委托单位的管理人员、项目经理及项目组技术人员，希望能使本软件开发工作更明确、更具体。
（二）项目背景
本业务模型涉及的业务覆盖范围和组织覆盖范围。
1. 项目委托单位：凯里市第十三小学
2.开发单位：贵州电子信息职业技术学院信息与智能电子系
3.“发展性评价”管理系统项目是指利用新一代信息技术，以整合、系统的方式管理学生发展体系。中共中央、国务院发布的《关于全面加强新时代大中小学劳动教育的意见》指出，劳动教育是中国特色社会主义教育制度的重要内容，要紧密结合经济社会发展变化和学生生活实际，积极探索具有中国特色的劳动教育模式。
（三）术语定义

英文缩写	英文全称	中文名称
		
		
		
		


二、产品定义
（一）应用目标
1.产品定位：落实教育德智体美劳全面发展的管理系统。
2.适用行业：教育。
3.解决业务：健全学生德智体美劳综合评分。
（二）产品业务架构


图1 “发展性评价”管理系统主要功能业务架构

三、应用环境
（一）系统运行的硬件环境
服务器：2核心2G 内存5M带宽40G储存以上服务器。
学生端：HUAWEI MATE PAD SE平板电脑。
家长端：支持运行微信小程序的智能设备。
（二）系统运行的软件环境
服务器：Window Server 2008及以上系统 安装JDK 1.8。
学生端：Android6.0及以上系统平板电脑。
家长端：支持运行微信小程序的智能设备。
（三）系统运行的网络环境
4G或WIFI 上行下行不低于200K。
（四）用户操作模式
触控或鼠标点击操作。

四、功能规格
（一）功能需求清单
业务类	功能编码·功能项	重要性(10)	说明
学生端	{F2022001 德育评分}	10	
	{F2022002 评分排行}	8	
	{F2022003 班级通知}	9	
教师端	{F2022201 智慧课堂}	10	
	{F2022203 校园广播}	8	
	{F2022204 评分审核}	8	
	{F2022205 家长互动}	8	
	{F2022206 德育评分}	10	
家长端	{F2022301 孩子辅导}	8	
	{F2022302 校园广播}	9	
	{F2022303 德育评分}	10	


（二）业务功能：学生端
1.启动页功能模块
（1）模块功能描述
启动页是进入APP时的展示页面，该页面可在WEB后台添加引导页信息，例如近期通知与新闻等

（2）界面原型


2.登录页功能模块
（1）模块功能描述
登录页是学生登录时输入姓名与密码的界面，通过该界面登录成功后才能进入主界面

（2）界面原型



3.主界面功能模块
（1）模块功能描述
主界面为展示德育平台的主要功能模块，学生通过点击即可进入对应功能
（2）界面原型






五、性能需求
本节描述用户对系统的性能需求，可能的系统性能需求有：
要求	详细要求
响应时间	小于1000ms
性能、效率	高并发
开放性	开放
可靠性	可靠的
可移植性	可进行多端移植
安全性	数据加密
系统兼容性	兼容android，ios，windows
现有资源利用性	无
可扩展性	后续可根据需求进行扩展
系统要求	Android，ios，Windows

六、产品提交
（一）产品提交方式
以APK安装包与微信小程序进行交付
（三）产品提交时间需求
描述	时间需求
需求分析	3天
初步设计	7天
原型设计	7天
程序开发	30天
产品测试	7天
交付	1天


（三）产品部署需求	
本产品分为三端部署，具体部署方式如下：
学生端：需要部署在平板电脑，具体安装方式为下载APK安装包进行安装
教师端：需要部署在Web服务器，发布在微信小程序平台
家长端：需要部署在Web服务器，发布在微信小程序平台
（四）产品维护需求
产品后期根据教学需求进行定期维护，每年需按时缴纳租用服务器费用，具体如下：

维护项目	费用
服务器租赁	500~1000元
学生平板电脑维护	由平板售后公司决定

七、外部接口说明
接口方式类型：webservice
接口描述：接口数据来源于系统服务端
本系统学生端与家长端都对接到教师端，教师端进行统一管理。
八、其他需求
本系统开发符合法律需求，充分利用系统的复用性，遵守国际准则，从开发到交付流程都均符合程序开发标准。
九、在线演示
使用电脑端访问：https://share.lanhuapp.com/#/invite?sid=qxLaC18a
