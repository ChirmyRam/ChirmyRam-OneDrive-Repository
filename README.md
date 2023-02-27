<img align="right" width="240" src="https://gcore.jsdelivr.net/gh/ChirmyRam/ChirmyRam-OneDrive-Repository/odlogo.png">

# 🛖 七米蓝的仓库

> 不只分享资源，还分享经验。本站用作学习交流，不得推广盈利。[【👉永久链接】](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository) [![](https://img.shields.io/github/forks/ChirmyRam/ChirmyRam-OneDrive-Repository?style=social&label=star)](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository) 

> 食用方式：网页浏览下载、 WebDAV 浏览下载、 Rclone 批量搬运

> 联系方式：[【😸Github Issue】](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository/issues) [【📧邮件】](https://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&email=office@chirmyram.top)

## 🎤 一、仓库介绍

- 各盘总文件近似大小（截止2022年11月）

|盘符|Rep|Ani|Mov|Doc|Tlv1|Tlv2|4K1|4K2|4K3|
|-|-|-|-|-|-|-|-|-|-|
|大小（TB）|3.5|24.8|19.5|6.5|21.1|13.1|20.1|20.3|20.7|

出于由来已久的囤积癖、白嫖怪的素养、收集剪辑素材的需求，我收集了这些资源，哗啦啦搬来一堆东西十分满足，但整理起来也是真的费劲。本着开放与共享的精神，我创建了此仓库。文件储存于国际版 OneDrive ，订阅类型为 Office365 E5 Developer，分享文件的同时也在刷 API 实现玄学免费续订，刷上瘾了属于是。除了域名和服务器，其他没怎么花钱，老白嫖怪了，当然所花的精力没法估量。

影视资源大多为内封字幕的 mkv 格式，为了方便浏览，以中文名称拼音首字母、常用英文名称首字母为顺序建立文件夹索引，并将内容联系程度紧密的作品归类在了一起，当然可能有多种翻译，找不到时试试换个名称。网站被频繁访问会触发 OneDrive 的 API 调用限制，即报错日志为 `activityLimitReached` 、`The request has been throttled`、`429 Too Many Requests` ，需稍后再试。若下载太慢请使用高速的全局代理或多线程下载器。浏览器在电脑 UA 模式下可查看文件（夹）大小。

动画资源主要来自 [1ove 论坛](https://www.qian.blue/archives/1ove-club.html) ，电子书、电影、电视剧资源主要来自阿里云盘各种资源分享渠道，4K iso电影资源主要来自 GoogleDrive 分享渠道，同一盘有字幕特效不同的重复电影，不同盘有部分重复电影但我摆烂不想剔了~。批量搬运阿里云盘资源的教程请参阅 [自建阿里云盘 webdav 功能并搬运资源](https://www.chirmyram.top/archives/aliyunwebdav) 。为缩短本页版面，我对文字说明进行了折叠处理，点击每个标题下的 **▶【查看详情】** 展开完整内容。

## 🏷️ 二、标签介绍

<details>
  <summary>【查看详情】</summary>

### 1. 盘符介绍

不同的OneDrive目录程序所能挂载账户数量不尽相同，而我又不忍舍弃，所以部分网站同时挂载了九个盘，部分只挂载了一个盘。当然 **Root** 这个盘符是对网站整体九个盘抽象而言的，并不存在这样一个OneDrive账户。

- ![](https://img.shields.io/badge/Root-orange) 总盘 ：同时挂载以下就九个盘。
- ![](https://img.shields.io/badge/Rep-orange) 仓库盘 ：存放杂七杂八的资源。
- ![](https://img.shields.io/badge/Ani-orange) 动画盘 ：存放动画。
- ![](https://img.shields.io/badge/Mov-orange) 电影盘 ：存放电影、纪录片。
- ![](https://img.shields.io/badge/Doc-orange) 图书盘 ：存放电子书。
- ![](https://img.shields.io/badge/Tlv1-orange) 剧集一盘 ：存放亚洲电视剧。
- ![](https://img.shields.io/badge/Tlv2-orange) 剧集二盘 ：存放欧美电视剧。
- ![](https://img.shields.io/badge/4K1-orange) 4K一盘 ：存放 4K iso 电影。
- ![](https://img.shields.io/badge/4K2-orange) 4K二盘 ：存放 4K iso 电影。
- ![](https://img.shields.io/badge/4K3-orange) 4K三盘 ：存放 4K iso 电影。

### 2. 标签介绍

绿色标签为**部署平台**，黑色蓝色标签为部署所用的**程序工具**，橙色标签为**挂载盘符**。可点击标签直接访问相关官网，程序软件均有部署教程。

以 [![](https://img.shields.io/badge/CFW-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/qkqpttgf/OneManager-cfworkerskv?style=flat&label=star)](https://github.com/qkqpttgf/OneManager-cfworkerskv) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://com.chirmyram.com/) 为例，意为在 **CFW** 上使用 **OneManager** 挂载了**九个盘**。

</details>

## 🛫 三、平台评测

<details>
  <summary>【查看详情】</summary>

首先引入两个概念：SaaS ， PaaS。
SaaS ，Software-as-a-Service ，意为软件即服务。平台为用户提供软件部署、托管服务，用户不必自己配置。
PaaS ，Platform as a Service ，意为平台即服务。平台为用户提供软件开发、运行环境等整套服务，侧重于开发。

这是我的浅薄理解，当然在这里也不必深入理解、甚至还会混为一谈，介绍它俩是为了方便在谷歌搜索相关内容，同义搜索词还有 free cloud container 、free cloud hosting 等等。只需要知道这些平台都有一个共同的特点：用户可以将程序项目放到云服务平台持续运行，平台已经预先提供了相应的运行环境。

为了方便这里就简称云平台了，以此来看，如[腾讯云函数](https://cloud.tencent.com/product/scf/)之类的已经是为众多折腾玩家所周知。部署方式多为从 github 仓库拉取源码、使用CLI命令行工具从本地上传源码等，大多为 docker 容器服务构建，即源码等东西放进去就没法修改或取不出来，不同于 VPS 具有完整的 Linux 环境，这些云平台的环境都是指定的，选则后除非删除否则无法自由更改。这类云平台在国内较少，就那几大云服务商的云函数，限制比较多，国外倒是多如牛毛，这里有一个别人总结的、为开发者提供一定免费额度服务的平台 [free-for-dev](https://github.com/ripienaar/free-for-dev) ，点进每个平台应直奔 Price 页面看价格套餐。薅羊毛必备，我上穷碧落下黄泉尝试了好几家，实在折腾得够呛。

|平台|性质|免费额度|主要限制|部署方式|自定义域名|
|-|-|-|-|-|-|
|[vercel](https://vercel.com/)|静态网页服务|每月总计100G流量|每天部署100次；部署的网站被访问过多会发邮件警告封号|拉取 github 仓库； CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[glitch](https://glitch.com/)|静态网页服务|每月总计1000小时|超30分钟不活跃将休眠|拉取 github 仓库|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[netlify](https://www.netlify.com/)|静态网页服务|每月总计100G流量；每月总计构建300分钟；站点数量无限|只能同时构建1个实例|拉取 github 仓库；CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[okteto](https://okteto.com/)|虚拟化容器服务|最大部署10个实例|每日重置数据；容易封号|拉取 github 仓库；docker 命令；CLI 命令行工具|免费版不支持，自行反代|
|[railway](https://railway.app/)|虚拟化容器服务|每月5美刀|需要已注册90天的 github 账户来注册它、风控较严|拉取 github 仓库；CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书|
|[fly.io](https://fly.io/)|虚拟化容器服务|每月总计2340小时；160G流量|绑卡可得（绑卡无扣款）；各地区流量额度不同|CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书；不会重定向至 https|
|[render](https://render.com/)|虚拟化容器服务|静态网页每月100G流量； Web 服务每月总计750小时|绑卡可得（绑卡会扣款）； Web 服务超15分钟不活跃将休眠并重置数据； Web 服务随时重置并丢失数据|拉取 github 仓库|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[koyeb](https://www.koyeb.com/)|虚拟化容器服务|2个实例|注册需要等待审核；实例会重启丢失数据|拉取 github 仓库； docker 命令； CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书；不会重定向至 https|
|[replit](https://replit.com/)|IDE 服务|500M储存空间；500M RAM；0.2 - 0.5 vCPUs|IDE 终端无 root 权限；实例不活跃将休眠；强制公开实例文件|拉取 github 仓库； IDE 终端执行|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[northflank](https://northflank.com/)|虚拟化容器服务|2个实例|绑卡可得（绑卡无扣款）|拉取 github 仓库中 Dockerfile 或源码；拉取docker镜像； CLI 命令行工具|通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|
|[cloudflare](https://www.cloudflare.com/zh-cn/)|域名综合服务| CFW 请求10W次/天； CFP 请求10W次/天|自定义域名必须更改域名 NS 至 cloudflare|CFW 为手动填写代码或从 github 仓库拉取； CFP 为从 github 仓库拉取代码、上传本地文件、CLI 命令行工具|CFP 可反代CFW；通过 CNAME 解析自定义域名；自动生成 SSL 证书；自动重定向至 https|

解读：

- 简介：，否则再次唤醒丢失数据超级麻烦，一夜回到解放前。

- 虚拟化容器服务：会休眠的容器平台非常容易丢数据，即恢复到部署后的初始状态，期间的任何更改被还原，不适合拿来搭经常变动的东西，比如挂载 OneDrive 就需会经常刷新 refresh token ，使用免费的云数据库平台可以有效解决重置数据的问题，前提是这些项目支持使用数据库而且数据量不能太大，如 MySQL 云数据库 [db4free](https://db4free.net/) 、PostgreSQL 云数据库 [ElephantSQL](https://www.elephantsql.com/) 、MongoDB 云数据库 [MongoDB](https://www.mongodb.com/) 。除此之外也适合部署即搭即用的项目，比如代理节点、解析下载工具、静态网页服务等测试项目。

- [fly.io](https://fly.io/)  ：Dockerfile 兼容性较差，别家都能用的 Dockerfile 在它这里总是报错无法成功部署。搭建代理节点收费。

- 绑卡：部分平台需要绑定国外信用卡才能获得或提升额度。可用虚拟信用卡过审核，绑卡若有扣款会在几天后返还，若无扣款但会验证信用卡真实性，随机生成的信息无法过审。

- CFW 、 CFP ：即 Cloudflare Workers 、Cloudflare Pages，前者托管 JavaScript 网页，后者为托管静态网页。我很看重自定义域名、https ，如你所见我的所有分站都是自己的域名且自动重定向到了 https 。我更喜欢通过 CNAME 解析来自定义域名，否则就用 CFP 反代。

- TOS ：网站底部或文档中的 Terms of Service ，即服务条款，各平台都会封禁搭建离线下载、群发垃圾邮件、色情暴力等服务，均属滥用范畴违反服务条款，较多平台也会封禁代理服务。提前排个雷，我已被这俩平台封了大小号（很多平台我注册了多个号都没事）：
[okteto](https://okteto.com/)：大号搭建 qBittorrent 下 bt ，倒是不冤，以身试法。不过这家封号真的喜怒无常，不只我有这种情况，我自认为小号搭的东西没有违反 TOS 也给封了。
[railway](https://railway.app/)：被封原因为注册多个账户，这个就很冤了，我就因为梯子速度太慢换了个节点多刷新了几次就给 ban 了。索性当场注册个小号也还是没了。

- 安卓：个别分站有 [![](https://img.shields.io/badge/Android-brightgreen?&style=flat)](https://f-droid.org/packages/com.termux/) 标签，这是我将退役的华为畅享 6 折腾成为服务器后搭建的，物尽其用榨干最后一滴价值，就不再列入表中了。装上软件 [Termux](https://f-droid.org/packages/com.termux/) ，在 [Termux](https://f-droid.org/packages/com.termux/) 里面装上精简 [Centos8](https://f-droid.org/zh_Hans/packages/exa.lnx.a/) 子系统，连环套娃，然后使用内网穿透的方式搭建网站，所以失联是家常便饭，稳定性随缘。我部署了很多具有试玩性质的项目，更多部署经验参阅 [将手机内网穿透当作服务器并运行了几个项目](https://www.chirmyram.top/archives/phoneserver) 。

</details>

## 🔣 四、程序鉴赏

<details>
  <summary>【查看详情】</summary>

挑选目录程序，我首先考虑能否在云托管平台一键部署，再考虑在 VPS 上部署，如果云平台无法部署、VPS 部署麻烦，就只能舍弃了，还考虑是否支持自动刷新 refresh token ，token 有效期三个月，毕竟重新获取一次还是挺麻烦的。我尤其偏爱利用 Golang 编写的程序，单个二进制文件直接执行、nginx 反代、supervisor 实现后台运行并守护进程，一条龙直接带走，也不需要考虑运行环境、依赖库、版本问题。

|程序|语言|运行环境|多账户|搜索范围|WebDAV|美化程度|
|-|-|-|-|-|-|-|
|[alist](https://github.com/Xhofe/alist)|Golang|直接运行|√|×|服务端（可改权限）、客户端|自定义|
|OneManager（[PHP](https://github.com/qkqpttgf/OneManager-php)、[CFW](https://github.com/qkqpttgf/OneManager-cfworkerskv)）|PHP、JavaScript|PHP、CFW|√|×|×|多主题|
|[OneIndex](https://github.com/motao123/oneindex)|PHP|PHP（composer ）|×|×|×|多主题|
|[FODI](https://github.com/vcheckzen/FODI)|JavaScript，HTML|CFW，Web|×|×|×|简约|
|[onedrive-vercel-index](https://github.com/spencerwooo/onedrive-vercel-index)|TypeScript|Vercel|×|×|×|简约|
|[gonelist](https://github.com/gonelist/gonelist)|Golang|直接运行|×|全盘|服务端（尚不完善）|简约|
|[sharelist](https://github.com/reruin/sharelist/tree/0.1)|JavaScript|nodejs|√|×|服务端（只读）、客户端|简约|
|[zfile](https://github.com/zhaojun1998/zfile)|Java|Java|√|×|服务端（需捐赠）、客户端|简约|
|[OLAINDEX](https://github.com/WangNingkai/OLAINDEX)|PHP|PHP（composer ）|√|当前目录|×|多主题|
|[PanIndex](https://github.com/libsgh/PanIndex)|Golang|直接运行|√|全盘|服务端、客户端|多主题|
|[onepoint](https://github.com/ukuq/onepoint)|JavaScript|nodejs、CFW|√|×|×|简约|
|[YukiDrive](https://github.com/YukiCoco/YukiDrive)|C#|直接运行|√|×|×|简约|
|[PyOne](https://github.com/abbeyokgo/PyOne)|Python|Python3、Redis、MongoDb（Aria2）|√|×|×|简约|
|CuteOne（[Python](https://github.com/Hackxiaoya/CuteOne)、[PHP](https://github.com/Hackxiaoya/CuteOneP)）|Python、PHP|Python3, MySQL, MongoDb、PHP（composer ）|√|全盘|×|简约|
|[JustList](https://github.com/txperl/JustList)|Python|Python3|√|全盘|×|简约|
|[OneList](https://github.com/MoeClub/OneList)|Python、Golang|Python3、直接运行|√|×|×|简约|
|[nextlist](https://github.com/lixiaofei123/nextlist)|Golang|直接运行，MySQL|√|×|×|简约|

解读：

- 简介：此表根据我的偏好习惯总结而来，我体验过上面大部分程序，差不多摸清了性质。更多细节请仔细阅读程序作者的介绍。如部分程序支持多账户挂载，多账户不单指 OneDrive 账户，还有国内外其他网盘、对象储存空间、文件传输协议。美化程度中多主题指程序内置预设好的多个主题，其他选项意为无法切换主题或自己修改代码切换主题。

- 全盘搜索：OneDrive 本身提供的全盘搜索 API 极为拉跨，程序要实现全盘搜索，一般首先会检索 OneDrive 中所有文件，在搭建环境中生成索引数据库，少量文件体验当然极为顺畅，但对于储存了海量文件的 OneDrive 简直是灾难，检索一遍极其耗费时间、检索结果不全造成大量空目录、触发 OneDrive API 调用限制导致网站崩溃、文件更新后无法及时跟进。故弃用。而 [gonelist](https://github.com/gonelist/gonelist) 则搭在手机上试玩。

- 运行环境： CFW 指 cloudflare workers ，和运行环境 vercel 一样，都是专为这些云托管平台而设计，因此直接将平台当做运行环境。[PyOne](https://github.com/abbeyokgo/PyOne) 的运行环境中有 Aria2 ，是因为它支持离线下载到 OneDrive ，这是一个可选功能，按需安装。

- WebDAV ：表中所指的 WebDAV 有两种情况。服务端：本程序 → 第三方，被第三方程序挂载，在第三方程序操作本程序的文件；客户端：第三方 → 本程序，挂载第三方 WebDAV 服务到本程序，在本程序操作第三方的文件。

- [alist](https://github.com/Xhofe/alist) ：可以使用免费的远程云数据库将其部署至 [render](https://render.com/) 等PaaS平台，参照项目 [alist-render](https://github.com/alist-org/alist-render) ，在应用休眠后再次唤醒不会丢失数据。需要注意的是：在 [render](https://render.com/) 上部署后无法使用 WebDAV 功能。

- [OneIndex](https://github.com/motao123/oneindex) ：原仓库已被作者删除，我用的是众多魔改分支中的一个，看图模式来自[闲得没事做改了一下 oneindex 的看图模式](https://www.hostloc.com/thread-484078-1-1.html)，评论系统来自 [oneindex网盘添加gitalk评论系统](https://www.rin404.com/archives/gitalk-od.html) ，主题美化来自[自带主题 nexmoe 的美化修改](https://github.com/Zisbusy/OneIndex-theme)。除此之外还有其他较为有特色的魔改版：[oneindex-j](https://github.com/jialezi/oneindex-j) 支持挂载国际版 Sharepoint 、世纪互联 OneDrive 及 Sharepoint ， 但仍只支持挂载一个账户；[OneindexN](https://github.com/xieqifei/OneindexN) 支持全盘搜索、aria2 离线下载，全局搜索为onedrive官方返回的结果，搜索结果并不准确；[OneindexM](https://github.com/Mintimate/OneindexM) 在 [OneindexN](https://github.com/xieqifei/OneindexN) 的基础上进行了修复和优化。

- [FODI](https://github.com/vcheckzen/FODI) ：前后端分离，后端部署于 CFW ，前端部署于 CFP ，也可部署于其他静态网站云平台或 VPS 主机，初次加载较慢需要数秒，加载完毕后就像在本地浏览文件一样，体验相当丝滑。

- [sharelist](https://github.com/reruin/sharelist/tree/0.1) ：表中所列出的是0.1版本，非最新版，0.1存在较多致命 bug ，如挂载账户超过1个所有账户的路径都会指向同一个，使用 WebDAV 播放视频时间一长就会导致整个网站变为所播放视频视频的直链，相当令人头痛，曾尝试搭建分站来解决问题，同时运行多个 nodejs 进程也很不方便，迫于是当时发现唯一支持挂载网盘为 WebDAV 只读功能的程序，就一直用着，憋得慌。而新版目前仍在开发中，文档也不完善，而且新版的 bug 还是巨多。直到遇见 [alist](https://github.com/Xhofe/alist) ，完美的解决了问题，同时挂载多个盘也实现了 WebDAV 只读，立马弃用 [sharelist](https://github.com/reruin/sharelist/tree/0.1) 。

</details>

## 🚀 五、批量搬运

<details>
  <summary>【查看详情】</summary>

> 使用原始的批量下载工具进行下载也行，不过更推荐认识一下 [Rclone](https://rclone.org/) 。

[Rclone](https://rclone.org/) 是一个支持多种云储存平台、国外云盘、储存协议的命令行工具，兼容 OneDrive 独特的 WebDAV 功能，需要自行搜索挂载教程。分享资源时登录 OneDrive 网页端，管理资源文件夹的访问权限，赋予同域内空白账户（无任何订阅许可证）为**可查看**权限，即**只读权限**，使用 [Rclone](https://rclone.org/) 配置该空白账户及资源文件夹链接，自动加密空白账户密码，既可共享出来批量搬运资源，又能：限制文件操作权限、避免泄露密码、避免没有创建 API 权限的尴尬、不会出现 refresh token 过期。直接在 [Rclone](https://rclone.org/) 配置文件中填入下述配置，不能再逐步配置，再次配置会导致已被加密后的密码文本被再次加密， [Rclone](https://rclone.org/) 无法识别真实密码报错。配置名 `[rep]` 即为盘符名，在 [Rclone](https://rclone.org/) 中称为 `remote` 。

[Rclone](https://rclone.org/) 还有相对简便易用的图形界面程序 [RcloneBrowser](https://github.com/kapitainsky/RcloneBrowser/releases) ，如果命令行用起来不太顺手可以试试。下载核心程序 [Rclone](https://rclone.org/downloads/) 解压，下载图形界面程序 [RcloneBrowser](https://github.com/kapitainsky/RcloneBrowser/releases)  安装。新建一个 `rclone.conf` 文本文件，将下述配置文件复制进去。在图形程序中，点击左上角 `file` → `preferences` ， `rclone location` 选择解压出的 rclone 核心主程序 `rclone.exe` ， `rclone.conf location` 选择新建的 `rclone.conf` 文件。回到图形程序界面点击左下角 `refresh` 刷新出配置，最后就可以浏览文件批量下载了，在顶部第二行 `Jobs` 中查看传输进程。

- [Rclone](https://rclone.org/) 配置文件

**‼️前六个账号因即将过期暂停分享**

~~[rep]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/pub_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

~~[ani]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/ani_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

~~[mov]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/mov_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

~~[doc]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/doc_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

~~[tlv1]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/tlv_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

~~[tlv2]~~
~~type = webdav~~
~~url = https://chirmyram-my.sharepoint.com/personal/tlv2_chirmyram_top/Documents/~~
~~vendor = sharepoint~~
~~user = share@chirmyram.top~~
~~pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ~~

```
[4k1]
type = webdav
url = https://qimilan-my.sharepoint.com/personal/4k1_2_chirmyram_top/Documents/
vendor = sharepoint
user = share@2.chirmyram.top
pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ
```

```
[4k2]
type = webdav
url = https://qimilan-my.sharepoint.com/personal/4k2_2_chirmyram_top/Documents/
vendor = sharepoint
user = share@2.chirmyram.top
pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ
```

```
[4k3]
type = webdav
url = https://qimilan-my.sharepoint.com/personal/4k3_2_chirmyram_top/Documents/
vendor = sharepoint
user = share@2.chirmyram.top
pass = 25es9-8BHYf1mDzSSaqMPBDAj3JjGh-95bjeWQ
```

```
[root]
type = webdav
url = https://al.chirmyram.com/dav/
vendor = other
user = alist
pass = kCJQSyuVJDmwgI0BM60Mtum8VGnI
```

最后一个配置文件由我用 [alist](https://github.com/Xhofe/alist) 自建，其余为 OneDrive 官方，自建远不如微软官方的稳定。 [alist](https://github.com/Xhofe/alist) 挂载网盘后能将已挂载的网盘转化为 WebDAV 服务提供给第三方管理器来浏览文件，由 OneDrive 转化而来的 WebDAV 挂载到第三方后批量搬运不会消耗自建服务器的流量，且访客账号对文件为**只读**权限，即只能读取无法操作，实属理想的公共 WebDAV 服务。更多实现 OneDrive WebDAV 的方式请参考我的博客文章[让 OneDrive 实现 WebDAV 服务](https://www.chirmyram.top/archives/onedrivewebdav) 。 

OneDrive 商业版本身不支持目前通行的 WebDAV 协议，但它确实有比较特殊的 WebDAV 功能。以我的 E5 OneDrive 登录后首页根目录地址为例：
```
https://chirmyram-my.sharepoint.com/personal/pub_chirmyram_top/_layouts/15/onedrive.aspx
```
则其对应的 WebDAV 链接为：
```
https://chirmyram-my.sharepoint.com/personal/pub_chirmyram_top/Documents/
```
观察其特点可发现，将末尾的 `/_layouts/15/onedrive.aspx` 替换为 `/Documents/` 就可以了。末尾 /Documents/ 即为 OneDrive 根目录，也可在其后继续添加子目录。建议分批次少量搬运，否则我修改部分资源的时候会导致搬运任务出错，前功尽弃。两个网盘对拷不会占用本地储存空间，流量还是烧的自己的，而且是双倍流量，可能部分 VPS 商家不会计算进入VPS 的入网流量。

</details>

## 🌟 六、特别推荐

<details>
  <summary>【查看详情】</summary>

酒香还怕巷子深，有部分资源初具规模但体积不够大（同类资源未超过5T），没有独立存放到一个盘上，而是杂七杂八散落在了仓库盘，不方便查找，于是在这里特别推荐。若链接无法访问请在第七章分站中按相同路径查找。

1. [欧路词典库](https://al.chirmyram.com/rep/Doc/%E6%AC%A7%E8%B7%AF%E8%AF%8D%E5%85%B8%E5%BA%93)

共25本英语词典，含离线语音文件，排版精美，与纸质版一致。

2. [音乐](https://al.chirmyram.com/rep/Music)

周杰伦全套 、许嵩全套、部分ACG音乐及其他杂七杂八我喜欢听的歌，能下到无损的均为无损，内嵌专辑封面、歌词。

3. [软件合集](https://al.chirmyram.com/rep/PC/sof)

包含由 [@vposy](https://weibo.com/u/1112829033) 修改的 Adobe 全家桶、 [NextITellYou](https://next.itellyou.cn/) 整站 Windows 官方镜像文件（截止2021-12-21）、[软件安装管家](https://mp.weixin.qq.com/s/3uYhgpRpkfo2hBNhuW-zpw)微信公众号软件目录整套软件（截止21年12月Win版），当然第一部分装机必备里面烂大街的软件没有搬。

</details>

## 📂 七、分站一览

> **✅/🔴  各分站状态实时监控：[https://up.chirmyram.com/](https://up.chirmyram.com/)**

### 1.总盘

- ▶ 1.1 [https://al.chirmyram.com/](https://al.chirmyram.com/) [![](https://img.shields.io/badge/Replit-brightgreen?&style=flat)](https://replit.com/) [![](https://img.shields.io/github/stars/Xhofe/alist?style=flat&label=star)](https://github.com/Xhofe/alist) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://al.chirmyram.com/)

**特别提示：** 网页播放器无法识别内封字幕、不兼容 HEVC 视频编码，需使用挂载到本地播放器或下载后播放。PC 端播放器推荐 [Potplayer](https://potplayer.daum.net/?lang=zh_CN) ，安卓端多媒体播放器推荐 [Nplayer](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/nPlayer_1.7.7.7_191219.apk) ，可显示视频内封字幕、音乐内封歌词；安卓端音乐播放器推荐 [cloudbeats](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/CloudBeats_1.8.4.apk) ，可较快生成播放列表并串流播放，留下的缓存也极小；安卓端电子书阅读器推荐 [静读天下](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/Moon_Reader_Pro-v7.0_build_700005-M.apk) ，支持多种电子书格式。
- WebDAV 配置参数

|参数|值|
|-|-|
|链接 / URL|https://al.chirmyram.com/dav/|
|主机 / Host|al.chirmyram.com|
|路径 / Path|/dav/|
|协议 / HTTPS|SSL|
|端口 / Port|443|
|账号 / User|alist|
|密码 / Password|alist|

注意：除非相关项目适配浏览器网页端，否则浏览器本身是不支持 WebDAV 协议的。

- ▶ 1.2 [https://om.chirmyram.com/](https://om.chirmyram.com/) [![](https://img.shields.io/badge/Northflank-brightgreen?&style=flat)](https://northflank.com/) [![](https://img.shields.io/github/stars/qkqpttgf/OneManager-php?style=flat&label=star)](https://github.com/qkqpttgf/OneManager-php) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://om.chirmyram.com/)

- ▶ 1.3 [https://op.chirmyram.com/](https://op.chirmyram.com/) [![](https://img.shields.io/badge/Replit-brightgreen?&style=flat)](https://replit.com/)  [![](https://img.shields.io/github/stars/ukuq/onepoint?style=flat&label=star)](https://github.com/ukuq/onepoint) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://op.chirmyram.com/)

- ▶ 1.4 [https://zf.chirmyram.com/](https://zf.chirmyram.com/) [![](https://img.shields.io/badge/Northflank-brightgreen?&style=flat)](https://northflank.com/) [![](https://img.shields.io/github/stars/zhaojun1998/Zfile?style=flat&label=star)](https://github.com/zhaojun1998/Zfile) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://zf.chirmyram.com/)

- ▶ 1.5 [https://zf.chirmyram.top/](https://zf.chirmyram.top/) [![](https://img.shields.io/badge/Android-brightgreen?&style=flat)](https://f-droid.org/packages/com.termux/) [![](https://img.shields.io/github/stars/zhaojun1998/Zfile?style=flat&label=star)](https://github.com/zhaojun1998/Zfile) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://zf.chirmyram.top/)

- ▶ 1.6 [https://oli.chirmyram.top/](https://oli.chirmyram.top/) [![](https://img.shields.io/badge/Northflank-brightgreen?&style=flat)](https://northflank.com/) [![](https://img.shields.io/github/stars/WangNingkai/OLAINDEX?style=flat&label=star)](https://github.com/WangNingkai/OLAINDEX) [![](https://img.shields.io/badge/Root-orange?&style=flat)](https://oli.chirmyram.top/)

### 2. 仓库盘

- ▶ 2.1 [https://oi.chirmyram.com/](https://oi.chirmyram.com/) [![](https://img.shields.io/badge/Northflank-brightgreen?&style=flat)](https://northflank.com/) [![](https://img.shields.io/github/stars/motao123/oneindex?style=flat&label=star)](https://github.com/motao123/oneindex) [![](https://img.shields.io/badge/Rep-orange?&style=flat)](https://oi.chirmyram.com/)

- ▶ 2.2 [https://cfdrep.chirmyram.com/](https://cfdrep.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Rep-orange?&style=flat)](https://cfdrep.chirmyram.com/)

- ▶ 2.3 [https://vcrep.chirmyram.com/](https://vcrep.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Rep-orange?&style=flat)](https://vcrep.chirmyram.com/)

- ▶ 2.4 [https://gl.chirmyram.top/](https://gl.chirmyram.top/) [![](https://img.shields.io/badge/Android-brightgreen?&style=flat)](https://f-droid.org/packages/com.termux/) [![](https://img.shields.io/github/stars/gonelist/gonelist?style=flat&label=star)](https://github.com/gonelist/gonelist) [![](https://img.shields.io/badge/Rep-orange?&style=flat)](https://gl.chirmyram.top/)

- ▶ 2.5 [https://oi.chirmyram.top/](https://oi.chirmyram.top/) [![](https://img.shields.io/badge/Android-brightgreen?&style=flat)](https://f-droid.org/packages/com.termux/) [![](https://img.shields.io/github/stars/motao123/oneindex?style=flat&label=star)](https://github.com/motao123/oneindex) [![](https://img.shields.io/badge/Rep-orange?&style=flat)](https://oi.chirmyram.top/)

### 3. 动画盘

- ▶ 3.1 [https://cfdani.chirmyram.com/](https://cfdani.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Ani-orange?&style=flat)](https://cfdani.chirmyram.com/)

- ▶ 3.2 [https://vcani.chirmyram.com/](https://vcani.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Ani-orange?&style=flat)](https://vcani.chirmyram.com/)

### 4. 电影盘

- ▶ 4.1 [https://cfdmov.chirmyram.com/](https://cfdmov.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Mov-orange?&style=flat)](https://cfdmov.chirmyram.com/)

- ▶ 4.2 [https://vcmov.chirmyram.com/](https://vcmov.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Mov-orange?&style=flat)](https://vcmov.chirmyram.com/)

### 5. 图书盘

- ▶ 5.1 [https://cfddoc.chirmyram.com/](https://cfddoc.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Doc-orange?&style=flat)](https://cfddoc.chirmyram.com/)

- ▶ 5.2 [https://vcdoc.chirmyram.com/](https://vcdoc.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Doc-orange?&style=flat)](https://vcdoc.chirmyram.com/)

### 6. 剧集一盘

- ▶ 6.1 [https://cfdtlv.chirmyram.com/](https://cfdtlv.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Tlv-orange?&style=flat)](https://cfdtlv.chirmyram.com/)

- ▶ 6.2 [https://vctlv.chirmyram.com/](https://vctlv.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Tlv-orange?&style=flat)](https://vctlv.chirmyram.com/)

### 7. 剧集二盘

- ▶ 7.1 [https://cfdtlv2.chirmyram.com/](https://cfdtlv2.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/Tlv2-orange?&style=flat)](https://cfdtlv2.chirmyram.com/)

- ▶ 7.2 [https://vctlv2.chirmyram.com/](https://vctlv2.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/Tlv2-orange?&style=flat)](https://vctlv2.chirmyram.com/)

### 8. 4K一盘

- ▶ 8.1 [https://cfd4k1.chirmyram.com/](https://cfd4k1.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/4K1-orange?&style=flat)](https://cfdtlv2.chirmyram.com/)

- ▶ 8.2 [https://vc4k1.chirmyram.com/](https://vc4k1.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/4K1-orange?&style=flat)](https://vctlv2.chirmyram.com/)

### 9. 4K二盘

- ▶ 9.1 [https://cfd4k2.chirmyram.com/](https://cfd4k2.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/4K2-orange?&style=flat)](https://cfdtlv2.chirmyram.com/)

- ▶ 9.2 [https://vc4k2.chirmyram.com/](https://vc4k2.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/4K2-orange?&style=flat)](https://vctlv2.chirmyram.com/)

### 10. 4K三盘

- ▶ 10.1 [https://cfd4k3.chirmyram.com/](https://cfd4k3.chirmyram.com/) [![](https://img.shields.io/badge/CFW_CFP-brightgreen?&style=flat)](https://www.cloudflare.com/zh-cn/) [![](https://img.shields.io/github/stars/vcheckzen/FODI?style=flat&label=star)](https://logi.im/back-end/fodi-on-cloudflare.html) [![](https://img.shields.io/badge/4K3-orange?&style=flat)](https://cfdtlv2.chirmyram.com/)

- ▶ 10.2 [https://vc4k3.chirmyram.com/](https://vc4k3.chirmyram.com/) [![](https://img.shields.io/badge/Vercel-brightgreen?&style=flat)](https://vercel.com/) [![](https://img.shields.io/github/stars/spencerwooo/onedrive-vercel-index?style=flat&label=star)](https://github.com/spencerwooo/onedrive-vercel-index) [![](https://img.shields.io/badge/4K3-orange?&style=flat)](https://vctlv2.chirmyram.com/)
