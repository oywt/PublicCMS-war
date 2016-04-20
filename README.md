#PublicCMS 2016


##获取源码

http://git.oschina.net/sanluan/PublicCMS

https://github.com/sanluan/PublicCMS

##参与研发(预览版)

http://git.oschina.net/sanluan/PublicCMS-preview

https://github.com/sanluan/PublicCMS-preview

##相关下载及文档(知识库)

https://github.com/sanluan/PublicCMS-lib

https://git.oschina.net/sanluan/PublicCMS-lib

##使用帮助

1. 在您的MYSQL数据库中创建数据库：public_cms，字符集选择：utf8_general_ci
1. 导入database/Mysql Database Init文件到数据库
1. 修改配置
 修改WEB-INF/classes/config/properties/dbconfig.properties文件中jdbc.url,jdbc.username,jdbc.password的值为您的publiccms数据库连接
 修改WEB-INF/classes/config/properties/dbconfig.propertiesother.properties文件中site.filePath的值为您的publiccms数据目录所在的绝对路径