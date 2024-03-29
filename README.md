#  星云IBMS智能建筑集成管理系统平台

#### 介绍
IBMS智能建筑系统平台,星云IBMS智能建筑管理系统，秉承开放理念的智能建筑管理平台。打破IBMS系统的神秘面纱，直接让软件开放给用户，采用敏捷开放框架，每日迭代，实时更新功能及其开发过程，让用户参与开发及其功能定制的过程，满足用户的需求;请访问http://ibms.xingzhoukeji.com 查看软件功能

#### 软件架构
星云IBMS智能建筑管理系统简介
IBMS 是 Intelligent Building Management System 的英文简称，中文意思是智能建筑管理系统。 IBMS是智能建筑的核心，是建筑物业管理软件和能耗分析软件的数据源头，是建筑的智能化设计在运行维护阶段的延伸，是智慧城市的节点和分支，是建筑的管理者与各种机电设备之间沟通的桥梁。如果把建筑比喻成人，那么 IBMS 就是人的大脑；如果把建筑比喻成个人电脑，那么 IBMS 就是建筑的操作系统。随着人工智能、云计算和大数据的发展，未来的 IBMS 会更聪明、更智能，从而让人们更便捷舒适的生活。 
IBMS 将建筑的各个智能化子系统有机的聚合在一起，协调各子系统间的相互关系和联动反应，把各种纷繁芜杂的操作界面和数据接口统一起来，让用户在一个平台上进行操作和管理，简化操作，集中精力在核心业务上，为用户创造更大的价值。 
 
#### 星云IBMS智能建筑管理系统是采用JAVA和VUE开发的一套完善的智能建筑管理系统，采用的框架和技术选型如下：
1、系统环境：Java EE 8，Servlet 3.0，Apache Maven 3
2、主框架：Spring Boot 2.2.x，Spring Framework 5.2.x，Spring Security、Redis & Jwt，RabbitMQ,Oauth2.0。
3、权限认证使用Jwt，支持多终端认证系统。
4、支持加载动态权限菜单，多方式轻松权限控制。

#### 功能特性：
	完善的权限管理
	开发支持多语言
	丰富的前端插件
	前后端分离模式
	强大代码生成器
	支持设备分布配置
	支持跨子系统的联动
	支持规则引擎
	支持钉钉系统集成
	支持时序数据库（TDengine）与消息队列RabbitMQ
	支持物联网网关及其协议
	支持组态页面
	支持多种图片格式SVG等
	支持BIM轻量化模型

#### 完全响应式布局：
	支持电脑、平板、手机等所有主流设备
	提供多种不同风格的皮肤
	使用最流行的的扁平化设计
	集成多款国内优秀插件；

#### 后端技术:
	SpringBoot
	Spring Security
	JWT
	MyBatis
	Druid
	Fastjson
	TDengine&RabbitMQ…….

#### 前端技术:
	Vue
	Vuex
	Element-ui
	Axios
	Sass
	Quill
	……..

#### 主要功能有：
* 系统管理、联动管理、项目配置、安防系统、门禁系统
* 人脸客流、自助访客、楼宇自控、电梯监控、智能照明
* 停车系统、环境监控、视频监控、信息发布、背景音乐
* 扩声系统、会议管理、巡更交班、消防管理、能效管理
* 固定资产、工单管理、报警管理、聚合支付、网关管理
* 系统监控、系统工具、星云物联、钉钉流程、钉钉管理
# 内置功能
1.	用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.	部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.	岗位管理：配置系统用户所属担任职务。
4.	菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.	角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.	字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.	参数管理：对系统动态配置常用参数。
8.	通知公告：系统通知公告信息发布维护。
9.	操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10.	登录日志：系统登录日志记录查询包含登录异常。
11.	在线用户：当前系统中活跃用户状态监控。
12.	定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13.	代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。
14.	系统接口：根据业务代码自动生成相关的api接口文档。
15.	服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16.	缓存监控：对系统的缓存信息查询，命令统计等。
17.	在线构建器：拖动表单元素生成相应的HTML代码。
18.	连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。
19.	拖拉拽式设备图标（SVG）分布图配置;使用者可以采用“拖放”的方法在开发平台完成电子地图制作，在设置图形和相应设备之间的对应关联后，
        使用者就可以很方便地在布防图上实现对建筑内各设备的监控。
20.	支持百度地图、BIM轻量模型渲染，地址树状结构配置、短信、邮件配置和消息订阅与推送功能。
21.	支持组态物联网网关进行楼宇智能化BA系统中的MODBUS\BACNET\OPC\MQTT协议的支持，
        对200多种工业控制设备的支持，涵盖冷暖空调、空气净化风机、智能电梯、智能照明设备、消防、背景音响等。
22.	采用高效的通用接口技术，通过特定的系统交换层面和标准的通讯协议，能无缝兼容不同子系统，
        可以转换多种协议，如：OPC、BACNET、MODBUS、 LONWORKS、API、TCP/IP、RS485/232、ODBC等;
23.	使用 OAuth2.0 的开放式认证和授权系统，提供基于角色的访问机制,实现全系统集中式的帐户管理、授权管理，
        其强大的安全管理机制为不同级别的人员赋予不同的操作权限，防止系统信息泄露和被非授权人员所干扰。 
24.	跨子系统的业务处理和联动, 可以根据需要建立联动关系。从而实现跨系统的控制流程，提高本项目的智能化管理和控制水平;
25.	智能策略控制（决策辅助功能）, IBMS 在采集数据的同时，应能向使用者提供历史数据智能分析功能，使用者可根据分析结果，
        在智能策略控制模块中设置联动控制策略，系统在适当条件下响应触发这些策略，达到系统优化和高效运行的目的。
26.	系统采用 REST-ful(Representational State Transfer)面向资源的信息集成平台框架。

#### 以资源模型为核心，对分布在各异构信息系统中的信息进行封装，将各种分散的异构资源映射到逻辑参照体系上，并通过定义统一的资源元模型和数据存取接口屏蔽各系统间的数据格式差异。通过基于任务分解的资源推送机制构造一个软件系统来开展资源服务提供，以实现不同应用系统之间的异构信息转换处理等过程级的交互操作，从而建立支持业务工作流的资源集成环境。采用 REST-ful框架软件接口架构, REST-ful架构风格是云服务软件开发的首选架构;

我们的软件平台通过持续集成和完善，为客户带来完美的使用体验，和深刻的数字化变革带来便利性。

#### 项目演示地址：
http://ibms.xingzhoukeji.com  demo演示网站
http://218.77.110.7:8000/   合作伙伴的案例

钉钉集成：

#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

联网以https://ibms.xingzhoukeji.com 和http://ibms.xingzhoukeji.com 两种访问URL进行演示，接口测试https://ibms.xingzhoukeji.com/v1/{模块名称}和http://ibms.xingzhoukeji.com/v1/{模块名称}

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


