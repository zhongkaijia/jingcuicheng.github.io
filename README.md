BlockX 系统设计

1. 数据中心 （DataManage.js) : 完成数据的统一存放以及交互 $DM 
	
	| 接口名        | 作用           | 备注  |
| ------------- |:-------------:| -----|
| `form` (keypath \<String>, valueae \<mixed>)| 存放表单元素值的地方 |  |
| `result` (keypath \<String>, value \<mixed>)| 存放结果返回的地方   |    |
| `config` (keypath \<String>, value \<mixed>) | 配置函数 | 1. 这是一个全局的修改；<br/>2. 只能写入不能修改|
| `cache` (keypath \<String>, value \<mixed>) |缓存函数||
| `get` (keypath \<String>)|获取数据||
| `put` (keypath \<String>, value \<mixed>) |设置或则修改数据||
| `remove` (keypath \<String>) |删除数据||
| `watch` (keypath \<String>, listen \<Function>) |设置数据修改的监听器 ||
| `unwatch` (keypath \<String>) |移除监听器||

2. API管理 (ApiManage.js) :通过apikey 管理 api接口地址 
3. Schema 管理 (SchemaManage.js)
2. 请求器，Request.js
2. 过滤器 Filter.js reqestFilter.js responseFilter.js
3. schema 配置管理
4. keypath 数据路由
5. 
