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
 修改WEB-INF/classes/config/properties/other.properties文件中site.filePath的值为您的publiccms数据目录所在的绝对路径

 ##更新记录
V2016.0423更新

1. 前台站点增加登陆注册功能，友情链接提交功能

1. 网站模板取消使用SSI与不使用SSI的差异化

1. 后台删除模板时元数据未被删除bug修复

1. 后台任务计划生成静态化失败bug修复

V2016新增功能：

1. 新增动态模板在线编辑功能

1. 新增内容推荐

1. 新增内容附件列表

1. 新增内容移动功能

1. 新增内容刷新功能

1. 新增分类移动功能

1. 新增分类生成多页功能

1. 新增分类标签类型管理

1. 新增分类SEO优化设置

1. 新增页面元数据扩展功能

1. 新增支持FreeMarker与HTML语法混合的模板编辑器

1. 新增动态页面管理功能

1. 新增推荐位数据扩展功能

1. 新增动态模板可接受参数配置功能

1. 新增用户登录授权管理功能

1. 新增部门数据权限功能：页面权限，分类权限

1. 新增角色只读权功能，修复权限授权bug

1. 新FTP服务、FTP用户在线管理功能

1. 新增动态域名绑定管理功能

1. 新增站点管理功能

1. 新增分类，模块等排序功能

1. 新增应用授权功能

1. 新增定制接口及测试页面

1. 新增客户端管理

优化修改:

1. 任务计划脚本改为文件

1. 推荐位数据改为数据库存储

1. UI列表样式修改，性能优化

1. UI美观度提升，图标优化

1. 模板与工程彻底分离

1. 登陆超时改为弹出登陆对话框

1. 指令简化