# Visual Novel Reader Lite Server
使用`.NET Core`编写的轻量级`Visual Novel Reader`服务器，可以本地运行。
## 编译
1. 使用`Visual Studio 2019`打开项目
2. 还原所有`NuGet`包
3. 编译
4. 在`appsettings.json`中更改本地数据库文件的路径
5. 打开`Package Manager Console`控制台
6. 执行`Add-Migration Init`创建数据库构造代码
7. 执行`Update-Database`创建本地数据库文件
## 客户端配置
+ 使用`ClientFiles`中的文件替换掉VNR中对应的文件即可
+ 替换服务器之前请备份重要的辞书文件和人工字幕文件
## 其它备注
+ 已实现基本API
+ 未实现查询缓存
