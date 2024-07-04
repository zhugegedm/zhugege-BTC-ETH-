# 简介
开源交易所，基于laravel开发的区块链交易所 | 区块链BTC交易所 |区块链 ETH交易所 | 区块链交易所 | 区块链交易平台 | 区块链撮合交易引擎。区块链本项目有完整的撮合交易引擎源码、后台管理（后端+前端）、区块链前台（交易页面、活动页面
输入图片说明# 区块链项目

# 介绍
区块链源码后端总后台源码laravel代码

# 软件架构
laravel框架搭建源码，使用workerman作为k线系统。使用redis做为缓存技术支持

# 联系我们
qq 29980928
微信：19180580919
飞机：@zhugegekaifa

在线客服： 复制粘贴链接：(https://kf.sykeji.vip/index/index/home?visiter_id=&visiter_name=&avatar=&business_id=3&groupid=0&special=3） {在线时间10:00-22:00}

# 演示地址

前端h5： 
https://h5.zhugege.vip 
444555666 444555666

前端pc：
https://pc.zhugege.vip 
444555666 444555666

总后台 
https://admin.zhugege.vip/admin 
admin admin

代理端 
https://daili.zhugege.vip/admin 
444555666 444555666

# 界面展示
![微信截图_20230713220045](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/20eccd08-cf4a-493e-bfda-51537532b1a1)
![微信截图_20230713220054](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/0ee3e8c6-d159-4581-abc8-b7f520f0569b)
![微信截图_20230713220209](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/0533bb10-6b96-4295-988c-5c3ddd243406)
![微信截图_20230713220151](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/e784473a-dd60-434e-a784-9758b7d364f3)
![微信截图_20230713220223](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/51f0c481-7be2-4af5-b4b9-f68696ab3186)
![微信截图_20230713220139](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/8ca3fa62-e7e1-4252-9a22-c3e31e4f517e)
![微信截图_20230713220103](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/f61955ab-151a-4384-af8c-1881b93c2714)
![微信截图_20230713220400](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/c317e7fb-43c4-4b20-b3b9-c33d4de377c0)
![微信截图_20230713220348](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/a392f5af-5b15-4ddf-8381-73d3a2d92b3f)
![微信截图_20230713220315](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/f8ed9f93-3a91-433e-a864-8c99084f8732)
![微信截图_20230713220309](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/72270f86-46fe-47b5-8e08-9f92c7d0f8f7)
![微信截图_20230713220303](https://github.com/zhugegedm/-laravel-BTC-ETH-/assets/54832494/3a2068e1-0a63-4951-b045-1a95aea3956f)




# 功能说明 源码简介与安装说明：

开源交易所，基于laravel开发的交易所 | BTC交易所 | ETH交易所 | 交易所 | 交易平台 | 撮合交易引擎。本项目有完整的撮合交易引擎源码、后台管理（后端+前端）、前台（交易页面、活动页面、个人中心等）、安卓APP源码、苹果APP源码、币种钱包RPC源码。开源项目仅供学习参考，请勿用于非法用途。

特色：

1、基于内存撮合引擎，与传统基于数据库撮合更快

2、前后端分离，基于Token的Api授权机制

3、基于laravel服务架构，扩展更容易

4、MySQL、php、Redis多种数据存储方式，只为更快

5、主流币种对接区块链接口齐全，开箱即用

6、冷热钱包分离，两种提现方式，保证安全

7、机器人系统，同步行情，维护深度，防止搬砖

8、交易所设计者提供技术支持，部署+二开无忧

9、支持添加自定义平台币及其他币种

使用教程：

准备mysql数据库，创建名称为“xxxx”的数据库

准备redis缓存数据库

准备阿里云OSS（修改项目中需要配置的地方）

准备nginx，修改配置文件（可选，正式上线需配置）

修改framework代码中的配置文件为准备环境配置参数

打开mysql，导入framework代码中的sql文件夹中xxxxxxx.sql文件，注意，trigger的sql如果报错，需要针对wallet表添加trigger

运行前端vue项目

运行后端vue项目

运行钱包RPC

运行自动交易机器人程序（本部分代码未上传，但不影响）

运行Admin项目（该服务并不依赖其他服务，因此也可只运行此项目，直接查看后台）

核心功能说明（用户端）

注册/登录/实名认证/审核（目前仅支持手机，二次开发可加入邮件，很简单）

Banner/公告/帮助/定制页面（Banner支持PC与APP分开设置，帮助支持各种分类模式）

C2C交易/OTC交易（支持两种模式，项目早期可由平台承担C2C兑换，后期可开放OTC交易）

币币交易（支持限价委托、市价委托，二次开发可加入其它委托模式）

邀请注册/推广合伙人（支持对邀请推广人数、佣金进行以日、周、月的排行统计）

创新实验室（该部分支持功能较多，分项说明。另，APP暂不全部支持该功能）

6-1. 首发抢购活动模式（如发行新交易对时，可对交易对设置一定数量的币种进行抢购）

6-2. 首发分摊活动模式（如发行BTC/USDT交易对之前，官方拿出5BTC做活动，根据用户充值抵押的USDT多少进行均分BTC）

6-3. 控盘抢购模式（如发行ZZZ/USDT交易对之前，ZZZ币种价格为5USDT，官方发行活动价为0.5USDT，则可使用该模式）

6-4. 控盘均摊模式（如6-3，只不过平均分配）

6-5. 活动模式（支持用户抵押一定数量的币种，由官方承诺每月返还一定数量的币种）

红包功能（支持平台及官方发放一定数量币种的红包，此功能适合用户裂变）

用户资产管理、流水管理、委托管理、实名管理等各种基础管理

核心功能说明（管理端）

概要（查看平台运行数据，包含交易额、注册人数、充值等）

会员管理（会员信息管理、会员实名审核、会员实名管理、会员余额管理、会员充值/冻结余额等）

邀请管理（会员邀请信息、会员邀请排行管理）

CTC管理（CTC订单管理、流水管理、承兑商管理）

内容管理（PC广告管理、APP广告管理、公告管理、帮助管理）

财务管理（充值提现管理、财务流水管理、对账管理、币种钱包余额管理）

币币管理（新建交易对、管理交易对、新建交易机器人、设置交易机器人参数、设置行情引擎/交易引擎、撤销所有委托）

活动管理（新建活动、认购、抢购/瓜分管理）

红包管理（平台红包管理、用户红包管理）

系统管理（角色管理、部门管理、用户管理、权限管理、币种管理、RPC管理、版本管理）

保证金管理（此功能设计时考虑到，但实际运营期间未使用到）

系统运行环境：

Centos 6.8

MySQL 5.5.16

Redis-x64-3.2.100

nginx-1.16.0

Vue

# 展示界面
输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说明 输入图片说
