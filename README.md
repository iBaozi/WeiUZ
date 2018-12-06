# WeiUZ CloudFlare Partners PHP版本
基于PHP的开源的 **CloudFlare Partners** 管理面板  
整个项目只有3个php文件和一个css文件，不依赖数据库，安装简单方便。
### 作者
hostloc 论坛的 @师太

### 使用说明
请先在cloudflare.class.php里设置你的Partners KEY  
### 注意事项
+ 添加域名时候不要加WWW
+ 回源地址不能直接写IP要写成域名
+ 需要SSL的要解析下那个长的
```
举例：_9546626e1e79dfa2945fa56a4b9af07e.weiuz.com
NAME解析到：_9546626e1e79dfa2945fa56a4b9af07e.weiuz.com.cdn.cloudflare.com
```
+ 编辑解析需要严格按照格式【 前缀:回源地址 】英文【 , 】隔开，一级域名@需要单独设置
+ 登录界面填写的是cloudflare个人账号，如果账号不存在会自动创建，请留意



