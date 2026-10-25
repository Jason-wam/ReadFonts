# 墨伴字体仓库

供「墨伴」App 与 Web 阅读页使用的字体索引仓库，收录 28 款中文阅读字体。

> 一键导入：[在墨伴中打开字体仓库](https://jason-wam.github.io/ReadFonts/)（手机端点击后自动把本仓库索引载入 App）

## 目录

- [版权声明](#版权声明)
- [字体索引](#字体索引)
- [一键导入到 App](#一键导入到-app)
- [手动配置](#手动配置)
- [索引协议](#索引协议)
- [目录结构](#目录结构)

## 版权声明

> ⚠️ **重要版权声明**

本仓库内所有字体文件、预览素材仅用于**个人技术学习**。

所有字体版权归【方正、仓耳】等原字体著作权方所有。
**严禁任何形式的商用、二次分发、打包售卖、嵌入商业App、付费服务、广告引流等行为。**
如果你需要使用这些字体进行商业开发，请自行联系字体版权方获取正式授权。

「墨伴」App 不内置任何字体文件，字体由用户自行配置本仓库后按需下载，仓库地址与字体文件均不随 App 分发。

## 字体索引

按字体家族分组，共 28 款。文件为 zip 压缩包，App 下载后自动解压取其中的 ttf/otf。

### 仓耳（12 款）

| # | 字体 | 格式 | 解压后大小 | 预览 |
| --- | --- | --- | --- | --- |
| 1 | 仓耳今楷 04 | ttf | 24.5 MB | [查看](preview/icon_reader_cangerjinkai04.png) |
| 2 | 仓耳华新 | ttf | 17.1 MB | [查看](preview/icon_reader_cangerhuaxin.png) |
| 4 | 仓耳今楷 05 | ttf | 18.4 MB | [查看](preview/icon_reader_cangerjinkai05.png) |
| 7 | 仓耳玄三 04 | ttf | 5.0 MB | [查看](preview/icon_reader_cangerxuansan04.png) |
| 10 | 仓耳玄三 05 | ttf | 28.1 MB | [查看](preview/icon_reader_cangerxuansan05.png) |
| 13 | 仓耳云黑 04 | ttf | 13.0 MB | [查看](preview/icon_reader_yunhei04.png) |
| 16 | 仓耳云黑 05 | ttf | 7.4 MB | [查看](preview/icon_reader_yunhei05.png) |
| 19 | 仓耳明楷 04 | ttf | 3.9 MB | [查看](preview/icon_reader_cangermingkai04.png) |
| 22 | 仓耳明楷 05 | ttf | 3.9 MB | [查看](preview/icon_reader_cangermingkai05.png) |
| 25 | 仓耳状元楷 | ttf | 7.1 MB | [查看](preview/icon_reader_cangerzhuangyuankai.png) |
| 26 | 仓耳玉楷 | ttf | 4.7 MB | [查看](preview/icon_reader_cangeryukai.png) |
| 28 | 仓耳兰楷 | ttf | 4.5 MB | [查看](preview/icon_reader_cangerlankai.png) |

### 方正（7 款）

| # | 字体 | 格式 | 解压后大小 | 预览 |
| --- | --- | --- | --- | --- |
| 9 | 方正宋三 | ttf | 24.4 MB | [查看](preview/icon_reader_fangzhengsongsan.png) |
| 12 | 方正悠宋 | ttf | 23.6 MB | [查看](preview/icon_reader_fangzhengyousong.png) |
| 15 | 方正兰亭黑 | ttf | 17.1 MB | [查看](preview/icon_reader_fangzhenglantinghei.png) |
| 18 | 方正兰亭圆 | ttf | 18.4 MB | [查看](preview/icon_reader_fangzhenglantingyuan.png) |
| 21 | 方正盛世楷书 | ttf | 27.8 MB | [查看](preview/icon_reader_fangzhengshengshikaishu.png) |
| 24 | 方正聚珍新仿 | ttf | 30.1 MB | [查看](preview/icon_reader_fangzhengjuzhenxinfang.png) |
| 27 | 方正欧蝶正楷 | ttf | 4.8 MB | [查看](preview/icon_reader_fangzhengoudiezhengkai.png) |

### 其他（9 款）

| # | 字体 | 格式 | 解压后大小 | 预览 |
| --- | --- | --- | --- | --- |
| 3 | 思源宋体 | ttf | 19.8 MB | [查看](preview/icon_reader_siyuansongti.png) |
| 5 | 京华老宋体 | ttf | 35.0 MB | [查看](preview/icon_reader_jinghualaosongti.png) |
| 6 | 思源黑体 | ttf | 14.5 MB | [查看](preview/icon_reader_siyuanheiti.png) |
| 8 | 寒蝉活仿宋 | otf | 32.2 MB | [查看](preview/icon_reader_hanchanhuosongti.png) |
| 11 | 汉仪空山楷 | ttf | 30.3 MB | [查看](preview/icon_reader_hanyikongshankai.png) |
| 14 | 汇文正楷 | ttf | 13.8 MB | [查看](preview/icon_reader_huiwenzhengkai.png) |
| 17 | 寒蝉正楷体 | ttf | 33.4 MB | [查看](preview/icon_reader_hanchanzhengkaiti.png) |
| 20 | 霞鹜文楷 | ttf | 29.1 MB | [查看](preview/icon_reader_xiawuwenkai.png) |
| 23 | AI楷 | ttf | 29.2 MB | [查看](preview/icon_reader_aikai.png) |

> 序号对应 `font_index.json` 中的 `index` 字段，完整元数据（PostScript 名、SHA256、大小等）见该文件。

## 一键导入到 App

墨伴注册了自定义协议，点击链接即可把本仓库索引写入 App，并自动打开「字体管理」页：

```text
mobanreader://fontrepo?url=<URL 编码后的 font_index.json 地址>
```

本仓库的完整链接（可直接在手机浏览器地址栏打开，或从下面的导入页点击按钮）：

```text
mobanreader://fontrepo?url=https%3A%2F%2Fraw.githubusercontent.com%2FJason-wam%2FReadFonts%2Fmaster%2Ffont_index.json
```

说明：

- GitHub 会过滤 README 中的自定义协议链接，因此请通过 [导入页](https://jason-wam.github.io/ReadFonts/) 点击「在墨伴中打开」。
- 导入页同时展示本仓库的字体索引，可直接预览全部字体。
- 协议仅接受 `http://` 或 `https://` 索引地址；命中后立即写入「字体仓库设置」并跳转字体管理页。
- 索引中的 GitHub 地址会自动走 `ghfast.top` 镜像加速，也可换成自建地址或 jsDelivr 地址。

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
| `font` | 字体短标识（文件名前缀） |
| `fontName` | 展示名称 |
| `index` | 序号，对应上表 # |
| `version` | 版本号 |
| `suffix` | 字体格式：`ttf` / `otf` / `ttc` |
| `zipSize` | zip 压缩包字节数 |
| `fileSize` | 解压后字体字节数 |
| `url` | 字体 zip 相对路径（如 `zip/cejk.zip`），也可写绝对地址 |
| `previewImageUrl` | 预览图相对路径 |
| `postScriptName` | PostScript 名，与 `suffix` 拼接作为字体唯一标识 |
| `Sha256` | 字体文件 SHA256（部分字体为空） |
| `fontType` | 家族分组：仓耳 / 方正 / 其他 |
| `fontTypeIndex` | 家族排序 |
| `singleTypeIndex` | 单屏排序 |
| `largeScreenIndex` | 大屏排序 |
| `largeScreenSingleTypeIndex` | 大屏单屏排序 |
| `hasTraditionalGlyphs` | 是否含繁体字形（1/0） |

相对路径规则：`url`、`previewImageUrl` 均相对于 `font_index.json` 所在目录解析。

## 目录结构

```text
ReadFonts/
├─ font_index.json   # 字体索引（App / Web 读取）
├─ index.html        # 一键导入落地页（GitHub Pages）
├─ preview/          # 字体预览图（png / svg）
└─ zip/              # 字体压缩包（ttf / otf）
```
