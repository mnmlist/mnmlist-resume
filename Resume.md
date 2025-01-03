<center>
		<h1>张腾飞-个人简历</h1>
		<div>
				<span>
						<img src="assets/phone-solid.svg" width="18px">
						151-1021-9397
				</span>
				·
				<span>
						<img src="assets/envelope-solid.svg" width="18px">
						mnmlist@163.com
				</span>
				·
				<span>
						<img src="assets/rss-solid.svg" width="18px">
						<a href="https://blog.csdn.net/mnmlist">个人博客</a>
				</span>
		</div>
</center>

## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息

- 男，1989 年出生
- 求职意向：Java 技术专家
- 工作经验：5 年

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 硕士，中国科学院大学，计算机应用技术 专业，2013.9~2016.7
- 学士，河南大学，计算机科学与技术 专业，2009.9~2013.7


## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **爱奇艺 公司，会员事业部 部门，资深研发工程师，2019.4~2021.10**

	- 负责 国际站会员收银台系统、智能定价系统和支付结果页系统的架构设计、开发和运维工作，系统owner
	- 负责 国际站会员交易系统、自动续费系统、用户网关系统和事件营销系统等系统的设计、开发和运维工作，核心开发

- **美团点评 公司，快驴进货事业部 部门，高级软件工程师，2016.7~2019.4**

	- 负责 面向各端提供快驴商城API服务，主要负责设计、开发和运维工作，核心开发
	- 负责 快驴商城运营管理系统下的BMS、PMS和CMS的设计与开发工作，主要开发

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **国际站会员智能定价系统 项目 （2021.5~2021.10）**
 *Spring Boot、Redis、MySQL*
	 国际站会员智能定价系统结合大数据标签为不同用户展示千人千面的价格，主要为收银台和交易系统提供价格计算服务。
	- 因套餐架构升级，独立设计和实现了国际站智能定价系统，涉及新数据库表8个
	- 使用自研并发调度框架提升价格查询接口性能，接口响应时间TP99为25ms
	- 由于设计新系统时兼顾运维，针对产品、测试或客诉反馈的价格不符合预期问题运维排查效率提升50%+


- **国际站会员收银台系统、国际站会员支付结果页系统 项目 （2019.9~2021.10）**
	*Spring Boot、Redis、MySQL*
	国际站会员收银台系统和国际站会员支付结果页系统主要功能为面向各端提供收银台展示API，为用户展示会员套餐、支付方式、权益、协议、营销位和购买结果等信息，供用户进行会员购买和展示购买结果。
	- 设计和实现了收银台AB测试技术方案，涉及12个新数据库表，实现了国际站收银台页面千人千面功能落地
	- 为进行配置提效，设计和实现了收银台CARD化配置和展示技术方案，降低了收银台整体技术复杂度，有助于收银台进行并行化改造，收银台进行改造后配置提效达到50%+
	- 主R了国际站收银台商品前台改造升级架构和设计任务，制定详细上线兼容方案，最终实现了200pd大需求高质量落地；创新提出新套餐兼容旧版本APP兼容方案，为产品和研发节省人力合计约15pd+
	- 为提升收银台接口性能，开发了一套并行调度框架，设计和实现了收银台并行化改造方案，使得收银台接口TP99由600ms降低至120ms
	- 开发交易排障工具，可供RD、QA、产品和客服同学根据用户ID可以快速定位用户反馈AB测试实验匹配、套餐或价格展示问题，预计提效60%+


- **会员交易系统 项目 （2019.4~2021.10）**
	*Spring Boot、RocketMQ、Redis、MySQL*
	会员交易系统为各端、各支付渠道提供购买会员下单功能API，与支付中心交互完成订单，进而为用户开通权益。
	- 在技术层面完成北京爱奇艺会员对上海侧FUN会员业务接收，独立设计和开发了技术迁移方案，完成FUN会员订单（2000W+）和会员签约关系（20W+）的迁移同步功能
	- 接入支付渠道11个，通过对会员交易系统改造，将实现接入新支付方式开发工作量从1.5pd降低至0.5pd
	- 设计和实现了针对新套餐结构导致的交易系统重构升级技术方案，创新提出新旧版本套餐兼容旧版本APP的技术实现方案，节省会员交易各方人力约5pd+
	- 完成商品前台改造，在新的前台商品结构下完成新的通用防刷单功能设计，排查防止刷单问题运维效率提升50%+
	- 完成交易系统在国际站支持使用优惠券购买会员功能落地
	- 开发交易排障工具，产品或客服根据用户ID可以快速定位下单历史记录或失败原因，排查下单失败问题运维效率预计提升70%


- **会员自动续费系统 项目 （2019.4~2020.12）**
 *Spring Boot、RocketMQ、Redis、MySQL、Cannal*
  会员自动续费系统为会员签约用户主动发起自动续费扣款和开通权益，主要包括续费job、续费task、续费worker、续费API模块。
  - 接入支付渠道11个，通过对会员自动续费系统改造，将实现接入新支付方式开发工作量从1pd降低至0.5pd
  - 开发自动续费排障工具，产品或客服根据用户ID可以查阅用户签约关系信息，快速定位用户下次续费时间或续费失败原因，预计提效50%

- **快驴、亚食联和经销商商城 项目 （2016.7~2019.3）**
 *Spring Boot、MTThrift、Redis*
  快驴商城项目，为各端提供商城API接口，主要包括商家、商品、活动、购物车、订单、售后、支付、充值和注册等模块

  - 负责购物车、订单和商品等复杂模块的设计和开发
  - 设计和实现了商城商品结构重构升级功能
  - 设计和实现了商城API不兼容升级时多版本控制功能
  - 设计和实现了多端多渠道登录验证功能、BD代下单和外面商家登录功能
  - 设计和实现了商城辅助排障工具，研发排查问题预计提效50%

- **配置信息管理系统（CMS） 项目 （2017.2~2019.3）**
 *Spring Boot、MTThrift、Redis、MySQL、databus*
  快驴CMS系统为商城提供分版本获取配置信息服务，使得变更配置信息与发版解耦

  - 负责CMS系统搭建与数据库表结构设计，设计和实现了商城分版本从CMS获取配置信息
  - 接入databus服务以将CMS数据变更同步至Redis

- **驼峰运营管理后台 项目 （2016.7~2017.1）**
 *Spring Boot、MTThrift、Redis*
   驼峰运营管理后台为快驴商城运营管理系统，主要负责采购系统（PMS）和商家管理系统（BMS）子系统

  - 设计和实现了采购单管理功能、低库存预警等功能
  - 设计和实现了抓取竞对商城商品、价格等信息数据实现比价功能，供采购或进行选品优化参考

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

 - ★★★★★ 熟练掌握常用的数据结构和算法
 - ★★★★★ 熟练掌握JVM、MySQL、Java多线程等基础原理以及运行机制
 - ★★★★☆ 熟练使用Spring, Spring Boot, Thrift等主流开源框架并了解其实现原理
 - ★★★★☆ 具有扎实的编程功底和良好的代码规范
 - ★★★★☆ 熟练掌握 git、maven 等开发工具
 - ★★★☆☆ 熟悉分布式理论、缓存和消息等机制，能够对分布式常用技术合理应用
 - ★★★☆☆ 熟悉Linux常用命令和Python语言，能快速分析和解决各类线上问题

## <img src="assets/tag.svg" width="36px"> 自我评价
 - 团队核心开发成员，具备良好的代码编程习惯及文档编写能力，主R国际站会员收银台系统、会员智能定价系统、支付结果页系统和会员优惠券系统等项目的核心部分代码设计、开发和维护
 - 能进行技术攻关，突破关键技术瓶颈，如自研并发调度框架解决会员收银台系统性能问题，优化接口TP99由600ms降低至120ms
 - 部门虚拟架构组成员，推动研发流程过程改进，能提升整个研发效能：a、协助基础架构部完善和推广了Octopus自动部署工具，提高团队的工作效率，事业部150+个系统每个需求可节省人力1h+，输出的接入文档被基础架构部在公司内部推广；b、与QA密切合作，将研发的联调环境由自定义环境迁移至环境平台，使研发联调效率提升30%+；c、借鉴公司业务部门开源服务工作流服务，与项目同学协助将复杂配置流程化
 - 在部门或小组内部完成多次技术或业务分享，主题包括 国际站会员收银台AB测试、国际站会员新商品中心建设、分布式链路追溯系统CAT、会员部署接入Octopus、分布式链路追踪系统Skywalking原理、分布式ID生成原理等
 - 带两实习生同学完成国际站管理后台搭建，平台具备的功能有：为产品或运营同学发送交易核心指标统计邮件，进行业务一致性校验报警，收银台、交易和自动续费问题排查工具，动态创建异常业务日志报警等功能，每月节省业务人力约40pd+
 - 乐于分享自己的经验和思考：总结各种技术wiki，经常被当做参考文档；为工作提效制定各种SOP，得到新同学、PM、QA和项目同学的一致好评

## <img src="assets/other.svg" width="36px"> 其它
 - CET6通过，能够无障碍阅读英文技术文档
 - 参加学校ACM竞赛并获奖
 - 对遗传算法、禁忌搜索算法等启发式算法有研究，对作业调度问题和路线规划问题等NP-Hard问题有研究
