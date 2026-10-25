# 墨伴字体仓库

供「墨伴」App 与 Web 阅读页使用的字体索引仓库，收录 18 款开源 / 免费商用中文字体。

> 一键导入：[在墨伴中打开字体仓库](https://jason-wam.github.io/ReadFonts/)（手机端点击后自动把本仓库索引载入 App）

## 目录

- [版权与授权](#版权与授权)
- [字体索引](#字体索引)
- [一键导入到 App](#一键导入到-app)
- [手动配置](#手动配置)
- [索引协议](#索引协议)
- [字体来源](#字体来源)
- [目录结构](#目录结构)

## 版权与授权

本仓库已移除全部商用字体（仓耳、方正、汉仪、微信读书 AI 楷），目前仅保留 **OFL 开源授权、公有领域、作者声明免费商用** 的字体。

- 各字体的具体授权见下方索引表「授权」列，以原作者的授权声明为准。
- 允许个人与商业项目免费使用；**禁止单独售卖字体文件，禁止传播修改版字形**。
- 如果你使用的是 2026-10 之前的旧版仓库，建议在 App「字体管理 → 字体仓库」中删除已下载的商用字体缓存。

## 字体索引

按字形风格分组，共 18 款。

### 宋体（4 款）

| # | 字体 | 格式 | 解压后大小 | 授权 | 预览 |
| --- | --- | --- | --- | --- | --- |
| 1 | 思源宋体 | otf | 10.8 MB | OFL | [查看](preview/icon_reader_siyuansongti.png) |
| 2 | 京华老宋体 | ttf | 35.0 MB | 免费商用（作者声明） | [查看](preview/icon_reader_jinghualaosongti.png) |
| 3 | 思源屏显臻宋 | ttf | 13.8 MB | OFL | [查看](preview/icon_free_sourcehanserifcnfordisplay.png) |
| 4 | 汇文明朝体 | ttf | 23.3 MB | 公有领域 | [查看](preview/icon_free_huiwen_mincho.png) |

### 仿宋（2 款）

| # | 字体 | 格式 | 解压后大小 | 授权 | 预览 |
| --- | --- | --- | --- | --- | --- |
| 5 | 朱雀仿宋 | ttf | 4.6 MB | OFL | [查看](preview/icon_free_zhuquefangsong_regular.png) |
| 6 | 寒蝉活仿宋 | ttf | 19.2 MB | OFL | [查看](preview/icon_reader_hanchanhuosongti.png) |

### 黑体（1 款）

| # | 字体 | 格式 | 解压后大小 | 授权 | 预览 |
| --- | --- | --- | --- | --- | --- |
| 7 | 思源黑体 | ttf | 14.5 MB | OFL | [查看](preview/icon_reader_siyuanheiti.png) |

### 楷体（10 款）

| # | 字体 | 格式 | 解压后大小 | 授权 | 预览 |
| --- | --- | --- | --- | --- | --- |
| 8 | 霞鹜文楷 GB 粗体 | ttf | 29.1 MB | OFL | [查看](preview/icon_reader_xiawuwenkai.png) |
| 9 | 霞鹜文楷 Bright | ttf | 12.9 MB | OFL | [查看](preview/icon_free_lxgw_bright_regular.png) |
| 10 | 霞鹜文楷 Bright 中黑 | ttf | 12.7 MB | OFL | [查看](preview/icon_free_lxgw_bright_medium.png) |
| 11 | 月星楷 | ttf | 16.2 MB | OFL | [查看](preview/icon_free_moonstarskai_regular.png) |
| 12 | 月星楷 粗体 | ttf | 16.2 MB | OFL | [查看](preview/icon_free_moonstarskai_bold.png) |
| 13 | 玄冬楷书 | otf | 7.8 MB | OFL | [查看](preview/icon_free_xuandongkaishu.png) |
| 14 | 悠哉字体 | ttf | 14.9 MB | OFL | [查看](preview/icon_free_yozai_regular.png) |
| 15 | 悠哉字体 中黑 | ttf | 14.5 MB | OFL | [查看](preview/icon_free_yozai_medium.png) |
| 16 | 寒蝉正楷体 | ttf | 33.4 MB | 政府开放资料授权 | [查看](preview/icon_reader_hanchanzhengkaiti.png) |
| 17 | 汇文正楷 | ttf | 13.8 MB | 免费商用（作者声明） | [查看](preview/icon_reader_huiwenzhengkai.png) |

### 手写（1 款）

| # | 字体 | 格式 | 解压后大小 | 授权 | 预览 |
| --- | --- | --- | --- | --- | --- |
| 18 | 小赖字体 | ttf | 20.8 MB | OFL | [查看](preview/icon_free_xiaolaisc.png) |

> 序号对应 `font_index.json` 中的 `index` 字段，完整元数据（PostScript 名、SHA256、大小、授权等）见该文件。

## 一键导入到 App

墨伴注册了自定义协议，点击链接即可把本仓库索引写入 App，并自动打开「字体管理」页：

```text
mobanreader://fontrepo?url=<URL 编码后的 font_index.json 地址>
```

本仓库的完整链接（可直接在手机浏览器地址栏打开，或从导入页点击按钮）：

```text
mobanreader://fontrepo?url=https%3A%2F%2Fraw.githubusercontent.com%2FJason-wam%2FReadFonts%2Fmaster%2Ffont_index.json
```

说明：

- GitHub 会过滤 README 中的自定义协议链接，因此请通过 [导入页](https://jason-wam.github.io/ReadFonts/) 点击「在墨伴中打开」。
- 导入页同时展示本仓库的字体索引，可直接预览全部字体。
- 协议仅接受 `http://` 或 `https://` 索引地址；命中后立即写入「字体仓库设置」并跳转字体管理页。
- 索引中的 GitHub 地址会自动走镜像加速，也可换成自建地址或 jsDelivr 地址。

## 手动配置

1. 打开「墨伴 → 我的 → 字体管理」。
2. 点击「字体仓库」右侧设置项，填写索引地址：

   ```text
   https://raw.githubusercontent.com/Jason-wam/ReadFonts/master/font_index.json
   ```

3. 返回列表即可看到「字体仓库」分组，按需下载使用。
4. 局域网 Web 阅读页（`/api/read/fonts`）会复用同一份配置，无需在网页端另设。

## 索引协议

`font_index.json` 为唯一入口，根对象含 `items` 数组，每项字段如下：

| 字段 | 说明 |
| --- | --- |
| `font` | 字体短标识 |
| `fontName` | 展示名称 |
| `index` | 序号，对应上表 # |
| `version` | 版本号 |
| `suffix` | 字体格式：`ttf` / `otf` / `ttc` |
| `zipSize` | zip 压缩包字节数 |
| `fileSize` | 解压后字体字节数 |
| `url` | 字体 zip 相对路径（如 `zip/Yozai-Regular.zip`），也可写绝对地址 |
| `previewImageUrl` | 预览图相对路径（App 端读取同名 `.svg`，网页端读取 `.png`） |
| `postScriptName` | PostScript 名，与 `suffix` 拼接作为字体唯一标识 |
| `Sha256` | 字体文件 SHA256 |
| `fontType` | 分类：宋体 / 仿宋 / 黑体 / 楷体 / 手写 |
| `fontTypeIndex` | 分类排序 |
| `singleTypeIndex` | 单屏排序 |
| `largeScreenIndex` | 大屏排序 |
| `largeScreenSingleTypeIndex` | 大屏单屏排序 |
| `hasTraditionalGlyphs` | 是否含繁体字形（1/0） |
| `license` | 授权说明（OFL / 公有领域 / 免费商用等） |

相对路径规则：`url`、`previewImageUrl` 均相对于 `font_index.json` 所在目录解析。

## 字体来源

新增字体取自 [中文网字计划（chinese-free-web-font-storage）](https://github.com/KonghaYao/chinese-free-web-font-storage)，该仓库只收录允许免费商用的字体。

- 霞鹜文楷系列：LXGW / 落霞孤鹜，SIL OFL
- 月星楷：Moon Stars Kai，SIL OFL
- 悠哉字体：Yozai，SIL OFL
- 朱雀仿宋：Zhuque Fangsong，SIL OFL
- 思源宋体 / 思源黑体 / 思源屏显臻宋：Adobe / Google，SIL OFL
- 汇文明朝体：公有领域
- 京华老宋体、汇文正楷：作者声明免费商用
- 寒蝉活仿宋、寒蝉正楷体：SIL OFL / 政府开放资料授权
- 小赖字体：SIL OFL

## 目录结构

```text
ReadFonts/
├─ font_index.json   # 字体索引（App / Web 读取）
├─ index.html        # 一键导入落地页（GitHub Pages）
├─ preview/          # 字体预览图（png / svg）
└─ zip/              # 字体压缩包（ttf / otf）
```
