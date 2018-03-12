#浩睿风擎后端开发框架
依赖spring boot 1.5.10版本，http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/
## 包含以下几个子模块
###risinger-admin
与前端功能对接的模块
###risinger-etl(如果公司有成熟的ETL功能，此模块可以废除。直接部署成熟的产品)
浩睿风擎抽取、转换、加载数据的功能模块,可独立部署
###risinger-api
第三方接口模块,供第三方系统调用。可独立部署
###risinger-common
通用类都写在此工程中,供其它子模块依赖
		
