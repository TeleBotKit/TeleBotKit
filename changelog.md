# 1.4.2 2025-2-26
1. 更改登录界面按钮标题
2. 新增注销登录和删除数据按钮
3. 优化菜单中授权信息显示


# 1.4.2 2025-2-21
1. 增加签名验证机制，框架根目录下所有可执行文件都将使用数字签名来防止文件损坏或蠕虫病毒等修改
2. 优化插件例子，优化插件返回重试机制
3. 优化账号重复登录检测

# 1.4.2 2025-1-2
1. 增加插件目录，数据目录自定义路径功能，通过环境变量`TeleBotKitDirPlugin`，`TeleBotKitDirData`设置
2. 延长GetMe接口超时时间
3. 增加群成员禁言/解除，获取群成员详情接口
4. 增加账号重复登录检测

# 1.4.2 2024-12-25
1. 更新协议到目前最新版
2. 增加事件链管理器

# 1.4.2 2024-10-28
> add  
1. 优化框架窗口日志显示，当插件调用日志接口时没有传入clientId等参数时，日志中不再显示0
2. 优化框架窗口日志显示，当插件调用日志接口传入了accountId时，会自动替换为账号昵称
3. 优化框架窗口日志显示，去除了日期部分
4. 优化多账号下插件开关控制
5. 增加插件响应控制“pluginResult_重试”，将消息处理权重新投放到第一个插件
6. 优化接口传递机制

> fix  
1. 修复多账号登录时，插件系统串号的问题
2. 调整tdCore.dll加载路径，防止部分系统环境无法启动的问题
3. 修复Bot登录时的tdFrame.Api.TdOption.setOptionString错误
4. 修复登录时DirEscape错误


# 1.4.1 2024-07-26
1. 优化接口调用方式
2. 更新框架Json依赖
3. 增加多账号支持
4. sdk，增加重复初始化错误提示
5. 修复一些bug
6. 增加插件强制启用选项
7. 增加封禁，解封，踢人接口
8. 增加设置管理员，头衔，权限接口
9. 增加设置群成员限制接口
10. 增加插件简介字段
11. SDK增加框架版本参数
12. 增加复制消息接口 
13. 增加账号搜索类接口
14. 更新第三方库
15. 修复插件加载系统，加载错误位置的插件文件

# 1.3.9
1. 优化协议错误输出
2. 更改接口模板格式
3. 增加入群审核接口

# 1.3.6 2024-05-31
1. 增加启动动画
2. 去除旧版消息循环
3. 插件系统，增加设置事件

# 1.0.0 2023-11-16
1. 初始版本
