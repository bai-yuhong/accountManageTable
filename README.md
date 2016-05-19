# accountManageTable
面试之前的一个小demo
面试题目是这样的：
 前端工程师完成前端部分就好，如果能完成后端加分。
==============================================
具体题目如下：

-[] 账户管理
- 账户基本属性：编码；名称，备注；状态；创建时间；最后登录时间;账号类型
- 账户基本操作：增加；删除；修改；查询；封存；启封
	- 查询条件：编码(模糊匹配)；名称(模糊匹配)；注册时段(开始，结束时间)；账号类型
- 基本约束：编码不能相同，不能为空
- 技术栈
	项目管理：maven
		- 打包成spring-boot的embed jar形式(一个可以直接执行的jar包)
	代码管理：git(@github)
	前端：jquery+bootstrap
		账号类型，用select2控件
		注册时段，用daterangepicker
		账号列表，使用datatables
		状态，使用radiogroup
		前后端通讯，采用ajax
	后端：spring v4；mysql；freemarker
		持久化，使用spring jdbc template(namedparameterjdbctemplate)
	加分项：防止重复提交；nodejs+webpack/gulp
提交方式：提供github或者git.oschina.net的链接

我没有进行数据与后台的交互，而是自己模拟了一个数组数据。
