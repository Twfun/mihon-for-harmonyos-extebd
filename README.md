# Mihon 鸿蒙版图源规则仓库

为鸿蒙版 [Mihon](https://github.com/Twfun/mihon) 提供开箱即用的声明式漫画图源规则仓库（共收录 **43** 个英文、简体中文、繁体中文与综合中文漫画站点，所有规则仅执行声明式数据提取，不执行远端脚本）。

## 待验收试点

| 语种 | ID | 范围 |
| --- | --- | --- |
| `en` | `keiyoushi.en.xkcd` | 官方存档与静态漫画，交互章节、悬浮文字和年月分组待支持 |
| `en` | `keiyoushi.en.peppercarrot` | 官方英文主漫画，其他译本、迷你剧场和插画待移植 |

两条均在鸿蒙 API 26 模拟器通过安装、更新和卸载。Pepper&Carrot 英文主漫画通过浏览、详情、章节列表和首图显示。xkcd 已通过浏览和详情，加载长章节目录时退回系统界面，完整章节和阅读验收待完成。

## 订阅地址

在鸿蒙版 Mihon 的 **浏览 → 图源规则仓库 → 添加规则仓库** 中填入：

```text
https://raw.githubusercontent.com/Twfun/mihon-for-harmonyos-extebd/main/index.json
```

## 已收录图源（43 条）

| 语种 | ID | 名称 | 分级 | 站点 | 简介 |
| --- | --- | --- | --- | --- | --- |
| `en` | `keiyoushi.en.arcrelight` | Arc-Relight | `safe` | https://arc-relight.com | 英文独立汉化组站，专注高质量翻译与重制日漫 |
| `en` | `keiyoushi.en.assortedscans` | Assorted Scans | `safe` | https://assortedscans.com | 英文精选汉化站，聚合多组连载与完结日式漫画 |
| `en` | `keiyoushi.en.cinblue` | Cin.blue | `nsfw` | https://cin.blue | 英文同人本与成年向彩色短篇漫画库 |
| `en` | `keiyoushi.en.hentai1io` | Hentai1.io | `nsfw` | https://hentai1.io | 英文韩漫与同人成人向连载漫画站点 |
| `en` | `keiyoushi.en.hentaihand` | HentaiHand | `nsfw` | https://hentaihand.com | 英文高清同人志、单行本与全彩短篇资料库 |
| `en` | `keiyoushi.en.hentaixdickgirl` | HentaiXDickgirl | `nsfw` | https://hentaixdickgirl.com | 英文特定题材成年向韩漫与漫画站点 |
| `en` | `keiyoushi.en.mangaeclipse` | Manga Eclipse | `safe` | https://mangaeclipse.com | 英文综合漫画阅读站，收录日漫、韩漫与奇幻连载 |
| `en` | `keiyoushi.en.mangahot` | MangaHot | `nsfw` | https://mangahot.org | 英文全彩条漫与成年向韩漫更新站点 |
| `en` | `keiyoushi.en.mangamaniacs` | MangaManiacs | `nsfw` | https://mangamaniacs.org | 英文耽美向与成年向日韩漫画站点 |
| `en` | `keiyoushi.en.mangapill` | MangaPill | `mixed` | https://mangapill.com | 英文高清热门日漫、韩漫与经典完结漫画站 |
| `en` | `keiyoushi.en.mangareadorg` | MangaRead.org | `mixed` | https://www.mangaread.org | 英文综合韩漫与日漫连载站点，涵盖重生奇幻等题材 |
| `en` | `keiyoushi.en.manhuaplus` | Manhua Plus | `safe` | https://manhuaplus.com | 英文热门国漫、武侠仙侠与玄幻条漫站 |
| `en` | `keiyoushi.en.manhuahot` | ManhuaHot | `safe` | https://manhuahot.com | 英文热门国漫与韩漫每日更新站 |
| `en` | `keiyoushi.en.manhwahubto` | ManhwaHub.to | `nsfw` | https://manhwahub.to | 英文全彩成人向韩漫连载站点 |
| `en` | `keiyoushi.en.orchisasia` | Orchisasia | `nsfw` | https://www.orchisasia.org | 英文成年向韩漫与同人条漫站点 |
| `en` | `keiyoushi.en.paritehaber` | Paritehaber | `nsfw` | https://www.paritehaber.com | 英文全彩成人向韩漫资源站 |
| `en` | `keiyoushi.en.petrotechsociety` | Petrotechsociety | `nsfw` | https://www.petrotechsociety.org | 英文全彩成年向韩漫镜像阅读站 |
| `en` | `keiyoushi.en.pornhwaz` | Pornhwaz | `nsfw` | https://www.pornhwaz.com | 英文全彩韩漫与成年向条漫阅读站 |
| `en` | `keiyoushi.en.saycomic` | Say Comics | `mixed` | https://saycomic.com | 英文全彩韩漫阅读站（站点限制每 5 秒拉取章节） |
| `en` | `keiyoushi.en.saymanhwa` | SayManhwa | `mixed` | https://saymanhwa.net | 英文韩漫更新站（站点限制每 5 秒拉取章节） |
| `en` | `keiyoushi.en.toonspace` | ToonSpace | `nsfw` | https://toon.space | 英文成人向同人志与全彩插画漫画站 |
| `en` | `keiyoushi.en.webtoonscan` | WebtoonScan | `nsfw` | https://webtoonscan.org | 英文条漫与成年向全彩韩漫阅读站 |
| `en` | `keiyoushi.en.yakshacomics` | YakshaComics | `safe` | https://yakshacomics.com | 英文热血战斗、奇幻与仙侠汉化漫画站 |
| `en` | `keiyoushi.en.yaoihub` | Yaoihub | `nsfw` | https://yaoihub.org | 英文耽美与纯爱向漫画连载站点 |
| `zh` | `keiyoushi.zh.cinblue` | Cin.blue | `nsfw` | https://cin.blue | 中文同人本与成年向彩色短篇漫画库 |
| `zh` | `keiyoushi.zh.hentaihand` | HentaiHand | `nsfw` | https://hentaihand.com | 中文汉化同人志、单行本与全彩短篇资料库 |
| `zh` | `keiyoushi.zh.toonspace` | ToonSpace | `nsfw` | https://toon.space | 中文成年向同人志与全彩漫画资源站 |
| `zh` | `keiyoushi.zh.zerobyw` | zero搬运网 | `mixed` | http://www.zerobyw33.com | 中文综合漫展搬运站，收录海量连载与生肉汉化漫画 |
| `zh` | `baozimanhua` | 包子漫画+ | `safe` | https://tw.webmota.com | 中文全彩国漫、韩漫与日漫免费在线阅读平台 |
| `zh` | `hipmh` | 嬉皮漫畫 | `mixed` | https://m.hipmh.com | 繁体中文热门韩漫、少女与综合条漫阅读站 |
| `zh` | `copymanga` | 拷贝漫画 | `safe` | https://api.2026copy.com | 中文高清日漫、轻改与热门连载漫画平台 |
| `zh` | `keiyoushi.zh.ikanmh` | 漫小肆韓漫 | `nsfw` | https://ikanmh.xyz | 中文全彩韩漫在线阅读站，已合入同源镜像域名 |
| `zh` | `keiyoushi.zh.manhuashe` | 漫画社 | `mixed` | https://www.311s.com | 中文综合漫画站，收录热门国漫、韩漫与完结作品 |
| `zh` | `manwa2` | 漫蛙2+ | `mixed` | https://manwadz.cc | 中文高速全彩韩漫与热门条漫阅读站 |
| `zh` | `keiyoushi.zh.guazimanhua` | 瓜子漫画 | `safe` | https://www.guazimanhua.com | 中文国漫、日漫与全彩韩漫高清在线阅读站 |
| `zh` | `keiyoushi.zh.nnhanman` | 鸟鸟韩漫 | `nsfw` | https://nnhanman.xyz | 中文韩漫连载与完结作品在线阅读站 |
| `zh` | `keiyoushi.zh.longjinman` | 龙禁漫 | `nsfw` | https://long52.com | 中文全彩韩漫与成年向条漫直连阅读站 |
| `zh-Hans` | `keiyoushi.zh-hans.cartoon18` | Cartoon18 | `nsfw` | https://www.cartoon18.com | 简体中文韩漫与成年向漫画资源站 |
| `zh-Hans` | `keiyoushi.zh-hans.saycomic` | Say Comics | `mixed` | https://saycomic.com | 简体中文全彩韩漫阅读站（站点限制每 5 秒拉取章节） |
| `zh-Hans` | `keiyoushi.zh-hans.saymanhwa` | SayManhwa | `mixed` | https://saymanhwa.net | 简体中文韩漫更新站（站点限制每 5 秒拉取章节） |
| `zh-Hant` | `keiyoushi.zh-hant.cartoon18` | Cartoon18 | `nsfw` | https://www.cartoon18.com | 繁体中文韩漫与成年向漫画资源站 |
| `zh-Hant` | `keiyoushi.zh-hant.saycomic` | Say Comics | `mixed` | https://saycomic.com | 繁体中文全彩韩漫阅读站（站点限制每 5 秒拉取章节） |
| `zh-Hant` | `keiyoushi.zh-hant.saymanhwa` | SayManhwa | `mixed` | https://saymanhwa.net | 繁体中文韩漫更新站（站点限制每 5 秒拉取章节） |
