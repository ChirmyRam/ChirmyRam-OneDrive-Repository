<img align="right" width="240" src="https://gcore.jsdelivr.net/gh/ChirmyRam/ChirmyRam-OneDrive-Repository/odlogo.png">

# 🛖 七米蓝的仓库

> 食用方式：网页浏览下载、 WebDAV 挂载、 Rclone 批量搬运

> 联系方式：[【😸Github Issue】](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository/issues) <a href="mailto:office@chirmyram.top">【📧邮件】</a> [【👉永久链接】](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository) [![](https://img.shields.io/github/stars/ChirmyRam/ChirmyRam-OneDrive-Repository?style=social&label=star)](https://github.com/ChirmyRam/ChirmyRam-OneDrive-Repository)

不只分享资源，还分享经验。本站持续添加多账号负载均衡，且由于开放 WebDAV 而长期吸引海量访问量，服务器压力巨大，运营维护不易，特开启以下捐赠通道：

### 1. 微信赞赏码：

![微信赞赏码](https://gcore.jsdelivr.net/gh/ChirmyRam/ChirmyRam-OneDrive-Repository/WechatDonate.png)

### 2. USDT钱包地址：
- Polygon or BEP20 (Min > 0.5 USDT):<br/>
**0xefD714ffa7103E979A82f125dc76A5a9a3314Edf**

## 🎤 一、仓库介绍

- 各盘总文件近似大小（截止2023年6月）

|盘符|Rep|Ani|Mov|Doc|Tlv1|Tlv2|4K1|4K2|4K3|
|-|-|-|-|-|-|-|-|-|-|
|大小（TB）|3.5|24.8|19.5|7.3|21.1|13.1|20.1|20.3|20.7|

文件资源储存于国际版 OneDrive ，仅用于学习交流使用，搬运进度止步于当年，内容不会再更新。网站被频繁访问会触发 OneDrive 的 API 调用限制，即报错日志为 `activityLimitReached` 、`The request has been throttled`、`429 Too Many Requests` ，或者文件目录会出现空目录，请坐和放宽，尝试多次刷新或稍后再试。影视资源大多为内封字幕的 mkv 格式，为了方便浏览，以中文名称拼音首字母、常用英文名称首字母为顺序建立文件夹索引，并将内容联系程度紧密的作品归类在了一起，名称可能有多种翻译，无法找到需尝试换个名称。若下载太慢请使用高速的全局代理或多线程下载器。浏览器在电脑 UA 模式下可查看文件（夹）大小。为缩短本页版面，我对文字说明进行了折叠处理，点击每个标题下的 **▶【查看详情】** 展开完整内容。

## 📀 二、盘符介绍

<details>
  <summary>【查看详情】</summary>

不同的OneDrive目录程序所能挂载账户数量不尽相同，而我又不忍舍弃，所以部分网站同时挂载了九个盘，部分只挂载了一个盘。当然 **Root** 这个盘符是对网站整体九个盘抽象而言的，并不存在这样一个OneDrive账户。

- ![](https://img.shields.io/badge/Root-orange) 总盘 ：同时挂载以下九个盘。
- ![](https://img.shields.io/badge/Rep-orange) 仓库盘 ：存放杂七杂八的资源。
- ![](https://img.shields.io/badge/Ani-orange) 动画盘 ：存放动画。
- ![](https://img.shields.io/badge/Mov-orange) 电影盘 ：存放电影、纪录片。
- ![](https://img.shields.io/badge/Doc-orange) 图书盘 ：存放电子书。
- ![](https://img.shields.io/badge/Tlv1-orange) 剧集一盘 ：存放亚洲电视剧。
- ![](https://img.shields.io/badge/Tlv2-orange) 剧集二盘 ：存放欧美电视剧。
- ![](https://img.shields.io/badge/4K1-orange) 4K一盘 ：存放 4K iso 电影。
- ![](https://img.shields.io/badge/4K2-orange) 4K二盘 ：存放 4K iso 电影。
- ![](https://img.shields.io/badge/4K3-orange) 4K三盘 ：存放 4K iso 电影。

</details>

## 🦄 三、网络挂载

<details>
  <summary>【查看详情】</summary>

网页播放器无法识别内封字幕、不兼容 HEVC 视频编码，需使用挂载到本地播放器或下载后播放。PC 端播放器推荐 [Potplayer](https://potplayer.daum.net/?lang=zh_CN) ，安卓端多媒体播放器推荐 [Nplayer](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/nPlayer_1.7.7.7_191219.apk) ，可显示视频内封字幕、音乐内封歌词；安卓端音乐播放器推荐 [cloudbeats](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/CloudBeats_1.8.4.apk) ，可较快生成播放列表并串流播放，留下的缓存也极小；安卓端电子书阅读器推荐 [静读天下](https://al.chirmyram.com/rep/Android/%E8%B0%B7%E6%AD%8C%E5%95%86%E5%BA%97/Moon_Reader_Pro-v7.0_build_700005-M.apk) ，支持多种电子书格式。

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

注意：浏览器本身并不不支持 WebDAV 协议，除非相关程序适配 WebDAV 网页端，。

  </details>

## ⚙️ 四、程序鉴赏

<details>
  <summary>【查看详情】</summary>

挑选目录程序，我首先考虑能否在云托管平台一键部署，再考虑在 VPS 上部署，如果云平台无法部署、VPS 部署麻烦，就只能舍弃了，还考虑是否支持自动刷新 refresh token ，token 有效期三个月，毕竟重新获取一次还是挺麻烦的。我尤其偏爱利用 Golang 编写的程序，单个二进制文件直接执行、nginx 反代、supervisor 实现后台运行并守护进程，一条龙直接带走，也不需要考虑运行环境、依赖库、版本问题。

|程序|语言|运行环境|多账户|搜索范围|WebDAV|美化程度|
|-|-|-|-|-|-|-|
|[alist](https://github.com/Xhofe/alist)|Golang|直接运行|√|全盘|服务端（可改权限）、客户端|自定义|
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

> 可以将本站的 WebDAV 挂载至支持该功能的软件进行批量操作，不过更推荐 [Rclone](https://rclone.org/) 。

[Rclone](https://rclone.org/) 是一个支持多种云储存平台、国外云盘、储存协议的命令行工具。直接在 [Rclone](https://rclone.org/) 配置文件中填入下述配置，不能再逐步配置，再次配置会导致已被加密后的密码文本被再次加密造成失效， [Rclone](https://rclone.org/) 无法识别真实密码报错。配置名 `[root]` 即为盘符名，在 [Rclone](https://rclone.org/) 中称为 `remote` 。

[Rclone](https://rclone.org/) 还有相对简便易用的图形界面程序 [RcloneBrowser](https://github.com/kapitainsky/RcloneBrowser/releases) ，如果命令行用起来不太顺手可以试试。下载核心程序 [Rclone](https://rclone.org/downloads/) 解压，下载图形界面程序 [RcloneBrowser](https://github.com/kapitainsky/RcloneBrowser/releases)  安装。新建一个 `rclone.conf` 文本文件，将下述配置文件复制进去。在图形程序中，点击左上角 `file` → `preferences` ， `rclone location` 选择解压出的 rclone 核心主程序 `rclone.exe` ， `rclone.conf location` 选择新建的 `rclone.conf` 文件。回到图形程序界面点击左下角 `refresh` 刷新出配置，最后就可以浏览文件批量下载了，在顶部第二行 `Jobs` 中查看传输进度。

- [Rclone](https://rclone.org/) 配置文件

```
[root]
type = webdav
url = https://al.chirmyram.com/dav/
vendor = other
user = alist
pass = kCJQSyuVJDmwgI0BM60Mtum8VGnI
```

该 WebDAV 服务由本站 [alist](https://github.com/Xhofe/alist) 实现，不甚稳定。 [alist](https://github.com/Xhofe/alist) 挂载网盘后能将已挂载的网盘转化为 WebDAV 服务提供给第三方管理器来浏览文件，由 OneDrive 转化而来的 WebDAV 挂载到第三方后批量搬运不会消耗自建服务器的流量，且访客账号对文件为**只读**权限，即只能读取无法操作，实属理想的公共 WebDAV 服务。本站不提供 OneDrive WebDAV 挂载，若有需要自行参阅我的博客文章[让 OneDrive 实现 WebDAV 服务](https://www.chirmyram.top/archives/onedrivewebdav) 。 

</details>

## ✅ 六、状态检测

> 本站及各工具网站状态实时检测：[https://up.chirmyram.com/](https://up.chirmyram.com/)
