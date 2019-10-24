# think-awesome

awesome for thinkphp5+

> 欢迎提交自己的基于ThinkPHP5.0/5.1/6.0版本开发的产品、扩展或者网站！由于版本历史和生态问题，暂不收录5.0之前的版本资源，请提交Issue

本文总结整理了`ThinkPHP`相关的资源，帮助开发者更好的学习和掌握`ThinkPHP5+`。

## 官网 http://thinkphp.cn

官网的历史比较悠久，主要作用为`ThinkPHP`的BUG反馈和建议，以及提问和交流，目前官网对移动端访问支持不好。基于6.0的新版官网重构中~

## 版本库

ThinkPHP`5.0+`版本全部使用`Git`进行代码版本管理，`5.1+`版本开始官方已经不再提供下载版本，`6.0+`版本开始必须使用`composer`安装，目前主要更新的版本库为`Github`，并同步更新到国内的码云。

> 目前`5.0`/`5.1`/`6.0`版本的版本库地址是相同，只是采用了不同的分支，目前主分支是`6.0`。

### `Github`

应用仓库：https://github.com/top-think/think
核心框架：https://github.com/top-think/framework

### `Gitee`

应用仓库：https://gitee.com/liu21st/thinkphp5
核心框架：https://gitee.com/liu21st/framework

## BUG反馈和建议

对于框架的BUG和建议，建议使用[`Issues`](https://github.com/top-think/framework/issues)功能，但不应该在`Issues`里面提问。

欢迎有能力的开发者贡献和提交PR给我们，帮助我们更好的完善和改进，但并不是所有的PR官方都会合并。请首先注意是否通过CI检测并注意代码规范，然后官方团队会评估该PR是否适合合并。

## 微信公众号

及时了解官方最新的资讯、活动和漏洞通知，以及每周原创的优秀内容，是目前官方的主要公告和推广渠道，如果还没有关注的话，不容错过。

![](https://box.kancloud.cn/d46f0e60ef4542902239cd6c082b6e05_258x258.png)

## 官方微博

官方（新浪）微博 [@thinkphp](https://weibo.com/thinkphp)，通常会同步更新官方活动和资讯，由于广告泛滥等其它原因，不再更新其它内容。

## 官方博客

官方博客（[https://blog.thinkphp.cn](https://blog.thinkphp.cn)）是独立于官网而设计的，专注于官方最新资讯、新功能和技巧和最佳实践等方面的文章，目前托管在看云平台，对移动端访问支持良好。

### 近期精选阅读

* [值得升级到5.1的18个理由](https://blog.thinkphp.cn/736203)
* [JSON字段类型在ORM中的使用](https://blog.thinkphp.cn/784281)
* [教你使用5.1的数组对象查询](https://blog.thinkphp.cn/778497)
* [你真的了解Db类和模型的正确使用姿势么？](https://blog.thinkphp.cn/810719)
* [模型三大利器之一：搜索器](https://blog.thinkphp.cn/783775)
* [模型三大利器之二：修改器](https://blog.thinkphp.cn/817548)
* [模型三大利器之三：获取器](https://blog.thinkphp.cn/825350)
* [ThinkPHP安全规范指引](https://blog.thinkphp.cn/789333)
* [让你少犯错的数据查询基本原则](https://blog.thinkphp.cn/833794)
* [如何有效提高ThinkPHP的应用性能](https://blog.thinkphp.cn/843679)
* [让你提高开发效率的查询技巧](https://blog.thinkphp.cn/848639)
* [模型关联查询不完全指南](https://blog.thinkphp.cn/852701)
* [ThinkPHP项目及代码规范指北](https://blog.thinkphp.cn/877574)

## 开发者周刊

![](https://box.kancloud.cn/f97f5aa846688eb4e44e80f5ea496828_194x259.png)

ThinkPHP[开发者周刊](https://www.kancloud.cn/thinkphp/weekly/content)旨在更好的鼓励和传播`ThinkPHP`生态的优秀内容和产品服务，于2018年国庆创刊，每周周一定时推送精选的优质内容。

周刊推送渠道包括官方QQ群、微博（[@thinkphp](https://weibo.com/thinkphp)）、微信公众号（thinkphp2012），以及[邮件订阅](https://tinyletter.com/thinkphp)。

## 完全开发手册

官方权威开发手册全部（并且只有）托管在看云文档平台，下面的各个版本的开发手册都可以导出`PDF`/`EPUB`到本地离线阅读，并支持发送到`Kindle`阅读，开发手册经常会保持更新，建议收藏随时以备查询。由于手册内容庞杂，不建议新手上来就看完全开发手册，容易摸不到北，最好通读下官方出品的[快速入门系列教程](https://www.kancloud.cn/special/thinkphp5_quickstart)。

* 6.0版本：https://www.kancloud.cn/manual/thinkphp6_0
* 5.1版本：https://www.kancloud.cn/manual/thinkphp5_1
* 5.0版本：https://www.kancloud.cn/manual/thinkphp5

> 所有的手册对移动端访问支持良好，也可以使用看云阅读小程序直接阅读。

## API速查表

速查表由官方团队成员维护，可能不一定及时同步更新，源码是最好的API手册。

5.0速查表：https://yangweijie.github.io/thinkphp-lts/index.html
5.1速查表：https://yangweijie.github.io/thinkphp-lts/index_tp5_1.html

## 官方教程

手册只是作为使用参考性质，不具备新手引导和教学作用。因此除了完全开发手册之外，官方还出品了一系列官方快速入门教程，作为完全开发手册的补充，这些都是对新手或者希望深入了解和学习框架细节的不可或缺，同时也是一种抛砖引玉，希望更多的第三方优秀教程涌现出来。

官方教程需要付费阅读（都是不到一杯咖啡的费用），写作不易请支持正版，主要包括：

* 《[ThinkPHP5快速入门](https://www.kancloud.cn/thinkphp/thinkphp5_quickstart)》
* 《[ThinkPHP5路由完全指南](https://www.kancloud.cn/thinkphp/route-master)》
* 《[ThinkPHP5.0控制器从入门到精通](https://www.kancloud.cn/thinkphp/controller-in-detail)》
* 《[掌握ThinkPHP5.0数据库和模型](https://www.kancloud.cn/thinkphp/master-database-and-model)》
* 《[笨办法学ThinkPHP5.1](https://www.kancloud.cn/thinkphp/thinkphp-the-hard-way)》

这些入门系列教程，虽然是为ThinkPHP5而写，但很多思想和用法，在后续版本中仍然适用，能够帮你更快速的入门和掌握ThinkPHP的精髓。

> 官方所有教程书籍都仅限[看云电子出版平台（官方旗下产品）](https://www.kancloud.cn)发布，其它任何平台均为盗版和假冒。


## 第三方教程（包含视频）

除了官方的系列教程之外，还有很多优秀的第三方教程和视频，都可以作为新手入门的帮助。（后续整理）

## 官方扩展

* 应用单元测试:[https://github.com/top-think/think-testing](https://github.com/top-think/think-testing)  
* 验证码:[https://github.com/top-think/think-captcha](https://github.com/top-think/think-captcha)  
* 消息队列:[https://github.com/top-think/think-queue](https://github.com/top-think/think-queue)  
* 计划任务:[https://github.com/yunwuxin/think-cron](https://github.com/yunwuxin/think-cron)  
* 页面Trace:[https://github.com/top-think/think-trace](https://github.com/top-think/think-trace)  
* DebugBar:[https://github.com/top-think/think-debugbar](https://github.com/top-think/think-debugbar)  
* MongoDb扩展:[https://github.com/top-think/think-mongo](https://github.com/top-think/think-mongo)  
* angular模板引擎扩展:[https://github.com/top-think/think-angular](https://github.com/top-think/think-angular)  
* thinkphp模板引擎扩展:[https://github.com/top-think/think-template](https://github.com/top-think/think-template)  
* Twig模板引擎扩展:[https://github.com/yunwuxin/think-twig](https://github.com/yunwuxin/think-twig)  
* Blade模板引擎扩展:[https://github.com/terranc/think-blade](https://github.com/terranc/think-blade)  
* 助手库:[https://github.com/top-think/think-helper](https://github.com/top-think/think-helper)  
* 数据库迁移工具:[https://github.com/top-think/think-migration](https://github.com/top-think/think-migration)  
* ORM类库:[https://github.com/top-think/think-orm](https://github.com/top-think/think-orm)  
* Oracle驱动:[https://github.com/top-think/think-oracle](https://github.com/top-think/think-oracle)  
* Swoole扩展:[https://github.com/top-think/think-swoole](https://github.com/top-think/think-swoole)  
* Workerman扩展:[https://github.com/top-think/think-worker](https://github.com/top-think/think-worker)  
* SeasLog日志扩展:[https://github.com/top-think/think-seaslog](https://github.com/top-think/think-seaslog)  
* 图像处理类:[https://github.com/top-think/think-image](https://github.com/top-think/think-image)  
* 图片动态裁剪缩放库:[https://github.com/top-think/think-glide](https://github.com/top-think/think-glide)  
* 缓存管理:[https://github.com/top-think/think-cache](https://github.com/top-think/think-cache)  
* Validate验证:[https://github.com/top-think/think-validate](https://github.com/top-think/think-validate)  
* Log扩展:[https://github.com/top-think/think-log](https://github.com/top-think/think-log)  
* TagLib编辑器:[https://github.com/top-think/think-editor](https://github.com/top-think/think-editor)  
* Container & Facade:[https://github.com/top-think/think-container](https://github.com/top-think/think-container)  
* 邮件发送扩展:[https://github.com/yunwuxin/think-mail](https://github.com/yunwuxin/think-mail)  
* 消息通知扩展:[https://github.com/yunwuxin/think-notification](https://github.com/yunwuxin/think-notification)  
* 自动生成模型注释:[https://github.com/yunwuxin/think-model-helper](https://github.com/yunwuxin/think-model-helper)  
* 社会化登录组件:[https://github.com/yunwuxin/think-social](https://github.com/yunwuxin/think-social)  
* ThinkPHP6注解扩展:[https://github.com/top-think/think-annotation](https://github.com/top-think/think-annotation)  
  
## 第三方扩展（陆续整理）

* 二维码生成类库:[https://github.com/endroid/qr-code](https://github.com/endroid/qr-code)  
* xml类库:[https://github.com/servo-php/fluidxml](https://github.com/servo-php/fluidxm%3Cx%3El)  
* 微信php-SDK:[https://github.com/overtrue/wechat](https://github.com/overtrue/wechat)  
* 支付宝php-SDK:[https://github.com/wi1dcard/alipay-sdk-php](https://github.com/wi1dcard/alipay-sdk-php)  
* 省市区(县)街道四级联动扩展:[https://github.com/yupoxiong/region](https://github.com/yupoxiong/region)  
* 访问控制库(Casbin)扩展:[https://github.com/php-casbin/think-casbin](https://github.com/php-casbin/think-casbin)  
* 权限认证:[https://github.com/zouxiang0639/thinkcms-auth](https://github.com/zouxiang0639/thinkcms-auth)  
* 代码生成器:[https://github.com/zhuanqianfish/ThinkphpHelper](https://github.com/zhuanqianfish/ThinkphpHelper)
* 钉钉机器人扩展:[https://github.com/hbh112233abc/ding-bot](https://github.com/hbh112233abc/ding-bot)
* 阿里云短信发送扩展:[https://github.com/hbh112233abc/ali-sms](https://github.com/hbh112233abc/ali-sms)
* 短地址扩展:[https://github.com/hbh112233abc/short-url](https://github.com/hbh112233abc/short-url)
* 用PHP负载均衡调度算法 [https://github.com/Tinywan/load-balancing](https://github.com/Tinywan/load-balancing)

## 产品/服务/网站

陆续整理中~

* [看云Kancloud](https://www.kancloud.cn) —— 基于Git和MD的文档在线写作和托管平台
* [Tinywan杂货摊](https://www.tinywan.com) —— 基于ThinkPHP5.1文档管理平台

## ThinkPHP安全守护者计划

为了应对今后的安全问题，ThinkPHP联合360安全团队和腾讯安全团队的成员成立了ThinkPHP安全守护者计划，成员共6名，分别来自360安全团队、腾讯安全团队以及ThinkPHP官方成员，共同致力于守护ThinkPHP核心框架的安全。

目前成员列表：

* [360代码卫士](http://codesafe.cn/)
* [360补天漏洞平台](https://butian.360.cn)
* [腾讯安全应急响应中心（TSRC）](https://security.tencent.com)
* [360 0KEE Team](https://0kee.360.cn)
* 360云影实验室

