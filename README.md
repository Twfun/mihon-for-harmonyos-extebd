# Mihon HarmonyOS 图源规则仓库

为鸿蒙版 [Mihon](https://github.com/Twfun/mihon) 提供 Kazumi 风格的声明式漫画图源规则仓库（`kazumi-comic-v1`）。

规则来源：
- [LittleSurvival/copymanga-copy20](https://github.com/LittleSurvival/copymanga-copy20)（基础 4 源）
- [Keiyoushi Extensions](https://keiyoushi.github.io/extensions/)（仅移植 `en`、`zh`、`zh-Hans`、`zh-Hant` 语种，共收录并完成端到端实测 **39** 个 Keiyoushi 独立图源，全仓合计 **43** 条规则）

所有规则均通过 `KazumiRuleCompiler` 校验，并完成列表浏览、搜索、详情、章节目录、页面提取与图片响应魔数实测；不执行任何远端 JavaScript 脚本。

## 订阅地址

在鸿蒙版 Mihon 的 **浏览 → 图源规则仓库 → 添加规则仓库** 中填入：

```text
https://raw.githubusercontent.com/Twfun/mihon-for-harmonyos-extebd/main/index.json
```

或精简版索引：

```text
https://raw.githubusercontent.com/Twfun/mihon-for-harmonyos-extebd/main/index.min.json
```

## 已收录图源（43 条）

| 语种 | ID | 名称 | 分级 | 站点 | 说明 |
| --- | --- | --- | --- | --- | --- |
| `en` | `keiyoushi.en.arcrelight` | Arc-Relight | `safe` | `https://arc-relight.com` | Ported from Keiyoushi en.arcrelight (MangAdventure API v2). |
| `en` | `keiyoushi.en.assortedscans` | Assorted Scans | `safe` | `https://assortedscans.com` | Ported from Keiyoushi en.assortedscans (MangAdventure API v2). |
| `en` | `keiyoushi.en.cinblue` | Cin.blue | `nsfw` | `https://cin.blue` | Ported from Keiyoushi all.cinblue (en). |
| `en` | `keiyoushi.en.hentai1io` | Hentai1.io | `nsfw` | `https://hentai1.io` | Ported from Keiyoushi en.hentai1io (WordPress Madara inline). |
| `en` | `keiyoushi.en.hentaihand` | HentaiHand | `nsfw` | `https://hentaihand.com` | Ported from Keiyoushi all.hentaihand (English). |
| `en` | `keiyoushi.en.hentaixdickgirl` | HentaiXDickgirl | `nsfw` | `https://hentaixdickgirl.com` | Ported from Keiyoushi en.hentaixdickgirl (WordPress Madara inline). |
| `en` | `keiyoushi.en.mangaeclipse` | Manga Eclipse | `safe` | `https://mangaeclipse.com` | Ported from Keiyoushi en.mangaeclipse (WordPress Madara inline). |
| `en` | `keiyoushi.en.mangahot` | MangaHot | `nsfw` | `https://mangahot.org` | Ported from Keiyoushi en.mangahot (WordPress Madara inline). |
| `en` | `keiyoushi.en.mangamaniacs` | MangaManiacs | `nsfw` | `https://mangamaniacs.org` | Ported from Keiyoushi en.mangamaniacs (WordPress Madara inline). |
| `en` | `keiyoushi.en.mangapill` | MangaPill | `mixed` | `https://mangapill.com` | Ported from Keiyoushi en.mangapill. |
| `en` | `keiyoushi.en.mangareadorg` | MangaRead.org | `mixed` | `https://www.mangaread.org` | Ported from Keiyoushi en.mangareadorg (WordPress Madara). |
| `en` | `keiyoushi.en.manhuaplus` | Manhua Plus | `safe` | `https://manhuaplus.com` | Ported from Keiyoushi en.manhuaplus (WordPress Madara inline). |
| `en` | `keiyoushi.en.manhuahot` | ManhuaHot | `safe` | `https://manhuahot.com` | Ported from Keiyoushi en.manhuahot (WordPress Madara inline). |
| `en` | `keiyoushi.en.manhwahubto` | ManhwaHub.to | `nsfw` | `https://manhwahub.to` | Ported from Keiyoushi en.manhwahubto (WordPress Madara inline). |
| `en` | `keiyoushi.en.orchisasia` | Orchisasia | `nsfw` | `https://www.orchisasia.org` | Ported from Keiyoushi en.orchisasia (WordPress Madara inline). |
| `en` | `keiyoushi.en.paritehaber` | Paritehaber | `nsfw` | `https://www.paritehaber.com` | Ported from Keiyoushi en.paritehaber (WordPress Madara inline). |
| `en` | `keiyoushi.en.petrotechsociety` | Petrotechsociety | `nsfw` | `https://www.petrotechsociety.org` | Ported from Keiyoushi en.petrotechsociety (WordPress Madara inline). |
| `en` | `keiyoushi.en.pornhwaz` | Pornhwaz | `nsfw` | `https://www.pornhwaz.com` | Ported from Keiyoushi en.pornhwaz (WordPress Madara inline). |
| `en` | `keiyoushi.en.saycomic` | Say Comics | `mixed` | `https://saycomic.com` | Ported from Keiyoushi all.saymanhwa (Say Comics, en). Note: source enforces 5s chapter rate limit. |
| `en` | `keiyoushi.en.saymanhwa` | SayManhwa | `mixed` | `https://saymanhwa.net` | Ported from Keiyoushi all.saymanhwa (SayManhwa, en). Note: source enforces 5s chapter rate limit. |
| `en` | `keiyoushi.en.toonspace` | ToonSpace | `nsfw` | `https://toon.space` | Ported from Keiyoushi all.toonspace (en). |
| `en` | `keiyoushi.en.webtoonscan` | WebtoonScan | `nsfw` | `https://webtoonscan.org` | Ported from Keiyoushi en.webtoonscan (WordPress Madara inline). |
| `en` | `keiyoushi.en.yakshacomics` | YakshaComics | `safe` | `https://yakshacomics.com` | Ported from Keiyoushi en.yakshacomics (WordPress Madara inline). |
| `en` | `keiyoushi.en.yaoihub` | Yaoihub | `nsfw` | `https://yaoihub.org` | Ported from Keiyoushi en.yaoihub (WordPress Madara inline). |
| `zh` | `keiyoushi.zh.cinblue` | Cin.blue | `nsfw` | `https://cin.blue` | Ported from Keiyoushi all.cinblue (zh). |
| `zh` | `keiyoushi.zh.hentaihand` | HentaiHand | `nsfw` | `https://hentaihand.com` | Ported from Keiyoushi all.hentaihand (Chinese). |
| `zh` | `keiyoushi.zh.toonspace` | ToonSpace | `nsfw` | `https://toon.space` | Ported from Keiyoushi all.toonspace (zh). |
| `zh` | `keiyoushi.zh.zerobyw` | zero搬运网 | `mixed` | `http://www.zerobyw33.com` | Ported from Keiyoushi zh.zerobyw. |
| `zh` | `baozimanhua` | 包子漫画+ | `safe` | `https://tw.webmota.com` | 包子漫画 SSR 声明式规则（改编自 copymanga-copy20） |
| `zh` | `hipmh` | 嬉皮漫畫 | `mixed` | `https://m.hipmh.com` | 嬉皮漫畫 SSR + hipmh-v2 声明式规则（改编自 copymanga-copy20） |
| `zh` | `copymanga` | 拷贝漫画 | `safe` | `https://api.2026copy.com` | 拷贝漫画官方 API 声明式规则（改编自 copymanga-copy20） |
| `zh` | `keiyoushi.zh.ikanmh` | 漫小肆韓漫 | `nsfw` | `https://ikanmh.xyz` | Keiyoushi 移植 · 漫小肆韓漫（同源镜像 jjmhw2.top 已合并去重） |
| `zh` | `keiyoushi.zh.manhuashe` | 漫画社 | `mixed` | `https://www.311s.com` | Keiyoushi 移植 · 漫画社 |
| `zh` | `manwa2` | 漫蛙2+ | `mixed` | `https://manwadz.cc` | 漫蛙2+ JSON/HTML 声明式规则，配合原生 AES-256-CBC manwa-public 解密（改编自 copymanga-copy20） |
| `zh` | `keiyoushi.zh.guazimanhua` | 瓜子漫画 | `safe` | `https://www.guazimanhua.com` | Keiyoushi 移植 · 瓜子漫画（国漫/日漫/全彩韩漫在线阅读） |
| `zh` | `keiyoushi.zh.nnhanman` | 鸟鸟韩漫 | `nsfw` | `https://nnhanman.xyz` | Keiyoushi 移植 · 鸟鸟韩漫 |
| `zh` | `keiyoushi.zh.longjinman` | 龙禁漫 | `nsfw` | `https://long52.com` | Keiyoushi 移植 · 龙禁漫（直连图源） |
| `zh-Hans` | `keiyoushi.zh-hans.cartoon18` | Cartoon18 | `nsfw` | `https://www.cartoon18.com` | Ported from Keiyoushi zh.cartoon18 (zh-Hans). |
| `zh-Hans` | `keiyoushi.zh-hans.saycomic` | Say Comics | `mixed` | `https://saycomic.com` | Ported from Keiyoushi all.saymanhwa (Say Comics, zh-Hans). Note: source enforces 5s chapter rate limit. |
| `zh-Hans` | `keiyoushi.zh-hans.saymanhwa` | SayManhwa | `mixed` | `https://saymanhwa.net` | Ported from Keiyoushi all.saymanhwa (SayManhwa, zh-Hans). Note: source enforces 5s chapter rate limit. |
| `zh-Hant` | `keiyoushi.zh-hant.cartoon18` | Cartoon18 | `nsfw` | `https://www.cartoon18.com` | Ported from Keiyoushi zh.cartoon18 (zh-Hant). |
| `zh-Hant` | `keiyoushi.zh-hant.saycomic` | Say Comics | `mixed` | `https://saycomic.com` | Ported from Keiyoushi all.saymanhwa (Say Comics, zh-Hant). Note: source enforces 5s chapter rate limit. |
| `zh-Hant` | `keiyoushi.zh-hant.saymanhwa` | SayManhwa | `mixed` | `https://saymanhwa.net` | Ported from Keiyoushi all.saymanhwa (SayManhwa, zh-Hant). Note: source enforces 5s chapter rate limit. |

## 去重与跳过说明

- **与现有规则重复跳过**：`zh.copymanga`（拷贝漫画）、`zh.baozimanhua`（包子漫画）、`zh.manwamanhua`（漫蛙）、`zh.xipimanhua`（嬉皮漫画）；另 `zh.mangaxiaosi`（漫画小站）与 `zh.ikanmh` 为同一站点镜像，已合入 `keiyoushi.zh.ikanmh` `allowedHosts`；`all.nhentaicom`（en/zh）与 `all.hentaihand` 数据库镜像完全一致，保留 `keiyoushi.*.hentaihand`。
- **受当前运行时/网络边界限制跳过**：
  - Cloudflare / 403 / 反爬盾：`allporncomic`、`madaradex`、`zinmanga`（图床 403/404）、`hentaiclub`、`mangadex`/`bato` 等需防护挑战或动态签名的站点。
  - 额外运行时能力缺失：`Keyoapp` 系列（QuickJS 执行）、`FlameComics`（Next.js 动态 `buildId`）、`Creativecomic`/`Rumanhua`/`SixMH`（AES+WebView `localStorage`）、`Roumanwu`/`BoyLove`（Canvas 图片解扰）、`Hanime1`/`Manga18`/`Wnacg`/`Manben`（JS 页面数组组装或后缀推算）、`Komiic`（登录 RefreshToken + GraphQL 配额鉴权）、`Guya`/`Cubari`（相对文件名动态拼接目录路径）。
