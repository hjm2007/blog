# 告别A1P——如何申请免费Microsoft 365开发者订阅+白嫖5TOnedrive+续期

正如我们所知，巨硬的Onedrive使用方便，效率高。但巨硬不仅给普通用户只有5g容量（连学习资料都存不下），而且在中国无法访问在线版Onedrive（真是很撅ε(┬┬﹏┬┬)3）。

不过对于教育版和企业版的Microsoft 365不仅有1~5TOnedrive for Business，还可以在线编辑，且下载满速（这是因为教育版和企业版的Office 365订阅有Sharepoint Online且SPO可以在中国访问）。因此近几年开始有大量嫖Onedrive for Business的教程。其中最火的是嫖A1/A1P的和嫖E5(DEV)的。但巨硬封的A1/A1P很多，风险大。因此许多人开始嫖E5(DEV)今天，UP主教你嫖Microsoft 365 E5开发者订阅以及续订教程。 

**一.申请**          

0.准备：                     

  ①一个微软账号                     

  ②一台可上网的电脑                     

  ③（可选）科学上网工具（过验证码）             

1.进入[https://developer.microsoft.com/en-us/microsoft-365/dev-program](https://developer.microsoft.com/en-us/microsoft-365/dev-program "Microsoft 365开发者计划")

![开发者计划介绍及加入页面](../images/blog/bd531af8-6c13-46c5-9102-ec9d2ed3569f.jpg)

> 开发者计划介绍及加入页面

2.点击“立即加入”

3.用你的微软账户登录（没有就注册）

![登录微软账户（不可用开发者账户登录）](../images/blog/f69aada5-3cb1-4834-a17b-df3442c3fec9.jpg)

> 登录微软账户（不可用开发者账户登录）

4.配置开发者账户

![国家选China，公司名称随便填，语言选中文（简体）](../images/blog/eda209cf-ca9d-4521-9f82-5b67b5aff9af.jpg)

>国家选China，公司名称随便填，语言选中文（简体）

![随便选](../images/blog/a5ab7026-961b-4220-96b1-e776c4c99d4f.jpg)

>随便选

![建议全选，然后点保存](../images/blog/71a85b92-7d56-47c6-8799-611beabce113.jpg)

>建议全选，然后点保存


5.点击设置“E5订阅”

​![有可能提示请求过多，多点几下，或者换个时间重试](../images/blog/27f8b704-470e-4aa5-a606-a2a9bcf8560b.jpg)

>有可能提示请求过多，多点几下，或者换个时间重试

6.选可配置沙盒，点下一步

​
![可配置沙盒干净且可自定义域名](../images/blog/08940751-f83a-4765-b3c7-515f010c0f02.jpg)

>可配置沙盒干净且可自定义域名

![注意：域名要随机，尽量随机，且国家/地区一定要选中国（关系到数据中心的地点）](../images/blog/a7115475-89ed-4ca9-b21b-728a5bad5607.jpg)

>注意：域名要随机，尽量随机，且国家/地区一定要选中国（关系到数据中心的地点）

8.验证手机号（请做好应对谷歌验证码的准备）

​
![若无法发送，多点几下](../images/blog/2707b67a-7db2-4276-8591-4c0e3fe8ccf2.jpg)

>若无法发送，多点几下

![申请成功（注意是可续订 E5 的订阅）](../images/blog/98f1c60e-df30-4a36-a630-0ee1ad61833f.jpg)

>申请成功（注意是可续订 E5 的订阅）

注意，登录Office时用开发者账户（即类似xxxxx@xxxx.onmicrosoft.com的账户） 

接下来，开始自动续期。

​**二.续期**

​0.注意

①关闭多重验证

进入[https://account.activedirectory.windowsazure.com/UserManagement/MultifactorVerification.aspx?BrandContextID=O365](https://account.activedirectory.windowsazure.com/UserManagement/MultifactorVerification.aspx?BrandContextID=O365)关闭多重验证

选择所有账户，再点禁用即可。

![全选并点击禁用](../images/blog/515535dd-9d33-45f6-88ac-0422f306d753.jpg)
​
>全选并点击禁用

![点击是](../images/blog/4baa0396-adcd-425a-8c54-b9c01a0c30a7.jpg)

>点击是

②关闭安全值

​进入[https://aad.portal.azure.com/](https://aad.portal.azure.com/)关闭安全值如图:


![关闭安全值，理由随便选](../images/blog/47482282-cfed-473c-8bd2-ad669a80633f.jpg)​


>关闭安全值，理由随便选

1.进入[https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade](https://portal.azure.com/#blade/Microsoft_AAD_RegisteredApps/ApplicationsListBlade)注册应用


![](../images/blog/6ca05787-7c85-4dc2-95b8-63d5027f4c5d.jpg)

2.点击新注册

![名称随便填，受支持的帐户类型按如图选，然后点注册](../images/blog/d2b448db-c326-405c-9cb3-84f74f9f501f.jpg)​

>名称随便填，受支持的帐户类型按如图选，然后点注册

​3.先点击 “概述”，然后点击 “添加重定向 URL”，进入重定向 URL 配置界面，** 下图中的应用程序 (客户端) ID 即为” 客户端 ID”**

![名称随便填，受支持的帐户类型按如图选，然后点注册](../images/blog/f45fb9c5-cc9f-48d0-9daf-1eef6ae00645.jpg)​
​
​4. 点击 “添加平台”，再点击 “移动和桌面应用程序”
​
![名称随便填，受支持的帐户类型按如图选，然后点注册](../images/blog/1cc0f6db-d556-40c6-b0b4-b9544674217f.jpg)​

​5. 继续勾选中第一个 URL，最后点击底部的 “配置”，该 URL 为 “https://login.microsoftonline.com/common/oauth2/nativeclient”

​![点配置](../images/blog/5811db69-8450-4a16-9040-5b58df8a719f.jpg)​

>点配置

6.点击“启用以下移动和桌面流”后点击保存

![](../images/blog/c205ba14-f883-4b2c-825a-f758627c2b7a.jpg)​

​7.点击“API权限——添加权限——Microsoft Graph——委托的权限”并配置如下权限：

​BookingsAppointment.ReadWrite.All; Calendars.Read; Contacts.Read; Directory.Read.All;Files.Read.All; Files.ReadWrite.All; Group.Read.All; Mail.Read; Mail.Send; MailboxSettings.Read;Notes.Read.All; People.Read.All; Presence.Read.All; Sites.Read.All; Tasks.ReadWrite; User.Read.All;

![](../images/blog/62c2dbc8-9703-4811-ab37-ecca7052dab4.jpg)

![](../images/blog/268fb361-70fa-4ae4-801a-d9588018bb9a.jpg)

![](../images/blog/87cc9484-f3db-42fc-b3e2-d054ccd29ad7.jpg)

![](../images/blog/d0b11b93-3570-4a7b-bd4d-54cf3bb66e10.jpg)

![](../images/blog/93b126a4-e499-4c40-b26e-6272dc8fb3c5.jpg)

![](../images/blog/98590c7d-7d5a-4330-a0b9-5b6e1bbaa842.jpg)

![](../images/blog/e22fede4-c643-4df4-a3f8-f8009fa93426.jpg)

![](../images/blog/69e59f18-e504-455d-ad2f-c15650adf73d.jpg)

![](../images/blog/75665c6f-cf7b-4ebc-84de-ca4269bdc5fa.jpg)

![](../images/blog/c02c17d7-868a-461d-8cca-c966f75e5e21.jpg)

![](../images/blog/23a50c78-acfd-41a1-9dde-ce63fe0eda0a.jpg)

![](../images/blog/6e4f47f0-23ad-4607-a035-2abadb670311.jpg)

![](../images/blog/6bec9587-17e5-4f9b-9f53-25275ed805ed.jpg)

![](../images/blog/6eb6a960-7e9d-4eca-bf1b-77aebd703707.jpg)


8.点击代表xxx授予管理员同意，完成API配置

![](../images/blog/724dae44-7040-4e95-80f7-4801307156b1.jpg)​

​9.点击“证书和密码——新客户端密码”，添加客户端密钥并完成配置

![将截止时间设置最大值（不能永久差评）](../images/blog/7ff38470-e53d-44b0-9fc0-8f7fc7f939e5.jpg)

>将截止时间设置最大值（不能永久差评）

​
![](../images/blog/e3f13384-dbad-4842-b42e-bbacac16c0a1.jpg)


​至此，API权限就设置好了

​10.进入如下网址中任意一个：

https://e5.hm0420.cc

https://ms-e5.hm0420.cc

https://e5.xzh.gs

https://e5.tianli0.top

https://renew.lrize.cc

https://e5zh.xyz

https://e5.xxs.moe

https://e5.xda2.com

9.随便选一种方式登录

![](../images/blog/2e875edb-0df8-4d25-b198-af76843a8a6a.jpg)​

​10.阅读协议后点击“激活账户”（若没注册）

​11.点击“添加运行账号”

![](../images/blog/1363e31c-8984-48ff-a5ab-73f00e777211.jpg)​

​12.填写如下信息：

​MS365 E5账号：你的开发者账户

应用程序（客户端）ID

密码：开发者账户密码

![](../images/blog/6b10aafa-860b-4217-b858-69a5034020e8.jpg)

注意选中“是否为登录调用方式”

3.完成

​**三：Onedrive扩容5T**

​1.进入xxxxx-admin.sharepoint.com（其中xxxxx为你的开发者账户域名。比如你的开发者账户为admin@asdfg.onmicrosoft.com，则要进入asdfg-admin.sharepoint.com）

​2.点击“设置——存储限制”并将“默认存储限制”设置为5120GB

![](../images/blog/76a0201b-8447-4ac4-ba87-464fd5427e6f.jpg)

![](../images/blog/56d9b5c7-ccc3-4422-85de-3527bf41177a.jpg)​

​​3.点击“保存”

**四.关于续期的一些问题**

​E5续订执行是微软统一的具有一定时间周期的续订，如果你的E5订阅剩余天数少于等于30天、并收到了未检测到开发活动的警告邮件且仪表盘显示标红文字“此订阅处于非活动状态且即将过期”，请不要慌张。根据微软客服官方说法是：“订阅只有在剩余最后1天才给续期”，然而根据众多E5账号的续订情况来统计，大部分账号是在少于30天续期的，极少欧洲人是在大于30天的时候续期。

若你的E5账户收到过两次未活跃警告，据微软客服解释说，这种警告邮件属于系统自动发送的(邮件会在剩余第30天的时候发送)，无需理会它，至于出现文字标红文字“此订阅处于非活动状态且即将过期”，也为系统自动提示，只要保证仪表盘上的文字标注为“可续订 E5的订阅”就可以了，即便是真的过期了没有续上也是可以从仪表盘申诉的。

续期的时间段是还剩30天时续期，这是常态；少部分人会在31天时续期；还有部分人会在小于30天时续期。
总的来说，续期时间段是在过期前30天和过期后30天内，只要没被删除账号，仪表盘显示“可续期”，就有续期的可能性。
事实上，续期还是各种玄学。有人天天刷API还是没过，有人什么事都没做自动续期。

每次续期都是在剩余时间的基础上+90天，比如，还剩30天续期，续期后就是30+90=120天；还剩10天续期就是10+90=100；过期10续期就是 -10+90=80天。过期30天将失去账号访问权限，过期50天后删除E5账号。

即，如果你在1月1日过期，将在2月1日失去权限，将在2月20日删除账号。

续期邮件：

![](../images/blog/523cc419-4809-41c5-885f-ac2214f3cb13.jpg)

更多问题请访问[https://www.gladtbam.top/posts/36944/](https://www.gladtbam.top/posts/36944/)

参考：[https://blog.csdn.net/qq_33212020/article/details/114482595?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522166942570616782429731893%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=166942570616782429731893&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_ecpm_v1~rank_v31_ecpm-6-114482595-null-null.nonecase&utm_term=Microsoft365%20E5&spm=1018.2226.3001.4450](https://blog.csdn.net/qq_33212020/article/details/114482595?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522166942570616782429731893%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=166942570616782429731893&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_ecpm_v1~rank_v31_ecpm-6-114482595-null-null.nonecase&utm_term=Microsoft365%20E5&spm=1018.2226.3001.4450)

注意：请勿使用E5账户进行非法活动，建议定期登录E5管理员账号保持使用活跃，并定期更改账号密码，切勿做甩手掌柜，也建议定期更换E5程序来调用API，不要照着一个E5应用程序死磕到底。

附：据最新不可靠消息称，微软扩大了本次的封杀范围，对使用过Mover.IO的Microsoft 365账户实施无地区差别的封禁此次微软所封禁的Microsoft 365账户类型不限于A1、A1P、E3（MSDN）、E5（Dev）等，且无地区差异，从子账户到全局管理员账户无一幸免！

这些被封禁账户的共同特征是使用了Mover.IO工具，建议大家近期不要再使用此工具迁移文件，管经使用过该工具且有重要数据存储在OD的用户请及时转移数据！
