# Mihon HarmonyOS 图源规则仓库

为鸿蒙版 [Mihon](https://github.com/Twfun/mihon) 提供 Kazumi 风格的声明式漫画图源规则仓库（`kazumi-comic-v1`）。

规则参考并转换自 [LittleSurvival/copymanga-copy20](https://github.com/LittleSurvival/copymanga-copy20)，仅使用纯声明式规则与原生确定性解码器，不执行任何远端 JavaScript 脚本。

## 订阅地址

在鸿蒙版 Mihon 的 **浏览 → 规则仓库 → 添加规则仓库** 中填入：

```text
https://raw.githubusercontent.com/Twfun/mihon-for-harmonyos-extebd/main/index.json
```

或精简版索引：

```text
https://raw.githubusercontent.com/Twfun/mihon-for-harmonyos-extebd/main/index.min.json
```

## 已收录图源

| 图源 ID | 名称 | 站点 | 状态 | 说明 |
| --- | --- | --- | --- | --- |
| `copymanga` | 拷贝漫画 | `https://api.2026copy.com` | 可用 | 官方 JSON API + `{{offset:20}}` 分页 + `@tmpl:` |
| `baozimanhua` | 包子漫画+ | `https://tw.webmota.com` | 可用 | SSR HTML + `allowedHosts` 跨镜像跳转 (`tw.twbzmg.com`) |
| `manwa2` | 漫蛙2+ | `https://manwadz.cc` | 可用 | `/api/search` + `/api/rank` + HTML 目录 + `manwa-public` 原生 AES-256-CBC 解密 |
| `hipmh` | 嬉皮漫畫 | `https://m.hipmh.com` | 可用 | `hipapi1.s3file.top` v1/v2 API + `hipmh-v2` 原生解码 |

## 未收录说明：`vomic漫+`

原仓库中的 `vomic漫+` 依赖后端硬编码 IP 接口 (`http://43.143.245.32/pics/...`) 及登录态 Bearer Token 鉴权；实测官网仅存展示页且后端接口已中断/拒连，为保证仓库中每条规则均真实可用，暂不发布不可用规则。
