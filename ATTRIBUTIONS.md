# 素材署名、来源与许可

初次整理：2026-11-24；2026-11-25 更新措辞与用途说明（未重新核对许可）。

本文件同时记录已知署名和待补资料，不能把所有条目都视作已获公开分发许可。项目作者为 duyn0112；自有代码及配套文档的 [MIT 许可证](LICENSE) 不覆盖第三方作品，也不替代其原有许可要求。具体见 [许可适用范围](LICENSE_SCOPE.md)。

主页面 `index.html` 的 `ASSETS` 中包含 78 个内嵌素材条目。下面的记录适用于 `assets/` 中的独立文件以及主页面中的内嵌版本；删除原始文件不会移除已经内嵌的作品。

## 用途声明

本项目为课程作业成果，仅用于课程评审、教学演示与个人学习，不用于商业用途。页面中的政区图、卫星影像、照片参考、商标及其他第三方作品归各自权利人所有；本文件如实记录已知来源与许可，尚未核清的条目仍需后续补齐。如权利人认为某项素材的使用方式不妥，可通过仓库 Issue 联系，核实后将替换或删除。

## 核对方式

- 下表四项 Commons 作品，以及平安金融中心、沈阳站两张参考照片的作者和许可，已于 2026-11-24 通过 Wikimedia Commons 文件元数据在线核对。
- 上海赛车场的作者和许可取自本地 SVG 的 RDF 元数据；其原始发布页面仍需补充。
- 其他记录来自项目已有的 [引用目录](assets/引用目录.txt)、尺寸说明及开发时保存的来源信息。只记有来源网址、用户提供或参考图，不等于已有再分发授权。
- 文件名不保证其内嵌格式：主页面部分 `.png` 键对应经过转码的 WebP 数据。独立文件、内嵌版本及原始作品尚未全部做逐字节比对，下面不声称它们完全相同。

## 已核对的 Commons 作品

| 项目文件或关联素材 | 原作品与作者 | 许可 | 本项目的使用与修改记录 |
| --- | --- | --- | --- |
| `assets/G15-shenhai-mainline.svg` 及内嵌版 | [G15 map.svg](https://commons.wikimedia.org/wiki/File:G15_map.svg)，Alan Fan Pei | 公有领域（Public domain），具体声明见原页面 | 原路线图作为参考；现有 SVG 提取红色 G15 干线并调整画布，保留来源记录。此图与 OSM XML 是不同来源。 |
| `assets/辽河.png` 及内嵌版；`assets/liao-river-sticker.svg` 及内嵌版 | [Liaorivermap.png](https://commons.wikimedia.org/wiki/File:Liaorivermap.png)，Kmusser；基于 Digital Chart of the World 和 GTOPO 数据制作 | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) | 原图用于参考图查看；SVG 根据水系走向重绘、突出干流并调整颜色与布局。重绘版本按原作品的相同方式共享要求处理，不纳入代码许可。 |
| `assets/新冠病毒.png` 及内嵌版 | [Coronavirus. SARS-CoV-2.png](https://commons.wikimedia.org/wiki/File:Coronavirus._SARS-CoV-2.png)，Alexey Solodovnikov（构思、制作、CG、编辑）、Valeria Arkhipova（科学顾问） | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) | 用于病毒结构示意并按选定直径缩放；主页面内嵌版本为 WebP。保留作者与许可，改编内容遵守相同方式共享要求。 |
| `assets/心脏_By Jerm.png` 及内嵌版 | [Heart anterior exterior view.png](https://commons.wikimedia.org/wiki/File:Heart_anterior_exterior_view.png)，Jerm；基于 Patrick J. Lynch 的 [原 JPG](https://commons.wikimedia.org/wiki/File:Heart_anterior_exterior_view.jpg) | [CC BY 2.5](https://creativecommons.org/licenses/by/2.5/) | 作为心脏插图按本项目尺寸基准缩放展示。保留 Jerm 与 Patrick J. Lynch 的作者链，不把文件名中的署名视作完整署名的替代。 |

新冠病毒作品页面另列科学顾问：Nikitin N.A.（莫斯科国立大学生物学院病毒学系）、Borisevich S.S.（俄罗斯科学院乌法化学研究所）、Arkhipova V.I.（俄罗斯科学院西伯利亚分院化学生物学与基础医学研究所）。完整身份和原作品说明以链接页面为准。

## 赛车场 SVG

| 文件 | 作品和作者 | 许可 | 尚需补充 |
| --- | --- | --- | --- |
| `assets/上海国际赛车场.svg` 及内嵌版 | Track map of Shanghai International Racing Circuit；Will Pittenger；元数据日期 September 23, 2009 | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) | 原始发布页面尚待补充。项目已移除原图标尺及其文字，保留赛道与弯道标记，并调整显示画布。当前文件保留了 Inkscape 和 RDF 版权元数据；后续压缩或重绘时须同时保留署名与许可。 |

## 照片参考与相关重绘

以下平安金融中心和沈阳站原照片的作者、许可已通过 Commons 元数据在线核对。重绘不自动消除原图权利；构成改编的内容应遵守原作品的许可。

| 项目关联文件 | 作者 / 原参考作品来源 | 已有许可记录与待办 |
| --- | --- | --- |
| `assets/pingan-finance-center-sticker.svg`；画廊中缺失的 `pingan-finance-center-photo.png` 引用 | Dinkun Chen；[PING AN FINANCE CENTER, SHENZHEN (2).jpg](https://commons.wikimedia.org/wiki/File:PING_AN_FINANCE_CENTER,_SHENZHEN_(2).jpg) | 原照片为 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。SVG 为贴纸化重绘。若后续补回画廊照片，需记录所用版本、裁剪和其他修改。 |
| `assets/shenyang-station-sticker.svg` | Liuxingy；[望向沈阳站东站房 01.jpg](https://commons.wikimedia.org/wiki/File:%E6%9C%9B%E5%90%91%E6%B2%88%E9%98%B3%E7%AB%99%E4%B8%9C%E7%AB%99%E6%88%BF_01.jpg) | 原照片为 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)。SVG 根据照片进行风格化重绘。 |
| `assets/asus-tuf-a16-sticker.svg` | ASUS；[TUF Gaming A16 (2025) 产品页](https://www.asus.com/laptops/for-gaming/tuf-gaming/asus-tuf-gaming-a16-2025/) | 根据产品图重绘。现有“个人学习/展示”描述不是权利人授权证明；重绘的使用范围需核对。 |
| `assets/corn-kernel-section-sticker.svg` | [素材页面](https://www.pngsucai.com/png/9318104.html)；原作者尚未记录 | 原始作者、许可证及网站是否有权授权尚待确认；SVG 保留剖面结构与中文标注并进行重绘。 |

## 政区 SVG 的图形来源

### DataV 图形（23 张）

来源记录：[阿里云 DataV 地理小工具](https://datav.aliyun.com/portal/school/atlas/area_selector)。项目尚未保存这批导出 SVG 对应的授权条款、版本及所需署名，许可状态待核；当前素材仅随课程作业仓库提供，用于教学展示，后续对外使用前仍需补齐。

对应 `assets/` 和主页面内嵌版本：

```text
中华人民共和国.svg
辽宁省.svg  北京市.svg  上海市.svg  四川省.svg
安徽省.svg  广东省.svg  新疆维吾尔自治区.svg  香港特别行政区.svg
沈阳市.svg  深圳市.svg
和平区.svg  沈河区.svg  大东区.svg  皇姑区.svg  铁西区.svg
苏家屯区.svg  浑南区.svg  于洪区.svg  辽中区.svg
新民市.svg  法库县.svg  康平县.svg
```

项目中对部分 SVG 根节点、命名空间、画布范围和显示布局做过调整。不能将调整后的文件表述为从未修改的官方原图。

### Vemaps 图形（4 张）

`俄罗斯.svg`、`日本.svg`、`美国.svg` 和 `巴西.svg` 的现有图形来源记录为 [Vemaps.com](https://vemaps.com/)。主页面相应对象的详情中已有 `© Vemaps.com`。

仍需补齐各图的下载页面、适用许可、是否允许修改及分发范围、署名位置要求。仅显示网站名称不证明已满足全部条款；SVG 已用于项目的裁切或布局适配与内嵌展示。相关许可状态待核，当前仅用于课程作业展示。

### 图形版权与尺寸数据来源不同

[政区图尺寸数据.md](政区图尺寸数据.md) 引用了 DataV GeoJSON、Natural Earth、dataofjapan/land 和 geo-countries 等数据，目的是计算地理范围与显示尺寸。它们不能替代上述实际 SVG 图形的来源和许可。

后续如果把这些边界数据文件或重绘结果直接加入仓库，还需核对并记录对应数据集的许可及版本。不能因为使用过 Natural Earth 数据计算尺寸，就把现有 Vemaps SVG 标为公有领域。

## Google Earth 卫星截图（8 张）

项目已有记录为“谷歌地球中截取”。以下文件在 `assets/` 和主页面内嵌素材中使用：

```text
浑南校区卫星图929m x1123m.png
南湖校区卫星图1154m x964m.png
沈阳方城1322m x 1353m.png
北京二环8803m x 9283m.png
鳌太线55.95km x 28.32km.png
青海湖115.7km x 88.06km.png
粤港澳大湾区238.77km x 196.25km.png
苏南地区+上海 355.27km x 177.80km.png
```

尚缺各张影像的截取时间、Google 及实际影像提供方署名、原截图中的版权信息和适用使用条款。请依据 [Google 地理内容使用指南](https://about.google/brand-resource-center/products-and-services/geo-guidelines/) 核对具体用途和当前要求，保留所需影像署名。相关许可状态待核，当前仅用于课程作业展示；不能一律写成“© Google”来代替实际提供方信息。

## OpenStreetMap 路线数据

`assets/沈海高速.xml` 来自 OpenStreetMap 路线关系 [16799228](https://www.openstreetmap.org/relation/16799228)。本地文件记载版本 189、时间戳 `2026-11-14T14:04:37Z`，属于固定版本快照；在线关系可能已更新。

- 署名：**© OpenStreetMap contributors**。
- 版权与许可入口：<https://www.openstreetmap.org/copyright>。
- 数据许可：[Open Data Commons Open Database License 1.0（ODbL）](https://opendatacommons.org/licenses/odbl/1-0/)。

本地 XML 保留了来源、许可和贡献记录。它只包含关系及成员引用，不含计算路线地理范围所需的完整节点和道路几何。此数据不等同于 Alan Fan Pei 的 G15 地图；两项来源应分别署名。分发或改编数据库时按 ODbL 的适用要求处理。

## 其他参考图、重绘和示意素材

以下条目用于完整列出尚未在前文覆盖的独立或内嵌素材。这里的“项目绘制”描述制作方式，不代表原始参考图、商标或人物等相关权利已全部核清。

| 素材或分组 | 已有记录 | 待补或使用说明 |
| --- | --- | --- |
| `assets/噬菌体.gif` 及内嵌版 | 尺寸根据图中标尺估算 | 缺原作者、原始作品网址、许可及修改记录。 |
| `milk-frog-photo.svg`、`milk-frog-laugh.svg` | 用户提供参考图，项目制作展示版本；前者 SVG 含位图数据 | 缺参考图作者、来源及授权。转成 SVG 或内嵌位图不改变该问题。 |
| `shenzhen-high-school-clock-tower.svg` | 用户提供照片和高度，项目重绘 | 照片摄影者、授权范围待确认；用户提供不等于用户拥有版权。 |
| `luckin-coffee-cup-sticker.svg` | 根据杯子和标志参考图重绘 | 缺参考图作者、来源及许可；品牌标志的相关权利仍属其权利人。 |
| `lautaro-martinez-sticker.svg` | 项目人物贴纸绘制 | 若参考特定照片或插画，需补原作者、来源和许可；不声称获得人物或相关品牌背书。 |
| `cctv-hq-sticker.svg`、`oriental-pearl-sticker.svg`、`jin-mao-tower-sticker.svg`、`shanghai-tower-sticker.svg`、`shanghai-world-financial-center-sticker.svg` | 对应央视、东方明珠、金茂、上海中心、上海环球金融中心参考图片进行风格化绘制 | 参考照片的具体作者和许可未完整记录，需补齐。 |
| `shengjing-grand-theatre-sticker.svg`、`liu-changchun-gymnasium-sticker.svg`、`dalian-suoyuwan-stadium-sticker.svg` | 对应盛京大剧院、刘长春体育馆、梭鱼湾球场参考图重绘 | 参考照片的原作者、来源和许可未完整记录，需补齐。 |
| `e-coli-structure-sticker.svg`、`hair-follicle-section-sticker.svg`、`human-ovum-sticker.svg` | 按参考图绘制结构、部分保留标注 | 原始结构图作者、作品网址、许可未完整记录，需补齐。 |
| `dna-double-helix-sticker.svg` | 项目双螺旋示意绘制，有 DNA 参考图 | 参考图来源与许可未记录，需确认是否实际用于改编。 |
| `earth-sticker.svg`、`moon-sticker.svg`、`asian-elephant-sticker.svg`、`chicken-sticker.svg`、`blue-whale-sticker.svg`、`mitochondrion-sticker.svg`、`red-blood-cell-sticker.svg`、`white-blood-cell-sticker.svg`、`platelet-sticker.svg`、`pm25-particle-sticker.svg`、`chip-3nm-sticker.svg`、`finfet-transistor-sticker.svg`、`rgb-screen-pixel-sticker.svg`、`mechanical-key-switch-sticker.svg`、`long-march-2f-sticker.svg` | 项目内绘制的风格化 SVG / 科学示意；尺寸参考见相关文档 | 不在本文件中擅自为全部图形指定统一许可。作者确认可授权范围后再单独声明；若使用过其他参考作品，还需补来源。 |

未写目录前缀的 SVG 均位于 `assets/`。画廊另有一处缺失的 `shanghai-lujiazui-trio-sticker.svg` 引用；该文件不在当前素材目录，不能据此声称提供了已授权的组合图。

## 尺寸与事实资料

- [物品尺寸与参考资料](sticker-objects-scale.md)
- [重绘图的比例尺与假设](redraw-scale.md)
- [地球与月球尺寸说明](earth-moon-scale.md)
- [政区图尺寸、数据来源与算法口径](政区图尺寸数据.md)

尺寸数据的引用与图像作品的版权分开处理；不能用建筑高度的资料来源代替建筑照片摄影者的署名。资料中的明确假设、近似值和不同测量口径应随数据保留。

## 分发时如何保留署名

1. 仓库中保留本文件和相关许可证链接；第三方文件自身已有的版权元数据也应保留。
2. 部署网页时提供清楚可见的“素材来源与许可”入口。当前主页面未单独设置该入口，署名与许可信息以本文件为准，随仓库一同提供。
3. 单独分发 `index.html` 时，附带本文件，或把必要的署名与许可直接放进页面；不要只发 HTML 而丢失素材说明。
4. 修改第三方作品时记录修改内容；涉及 CC BY-SA 的改编作品按相应版本的相同方式共享要求处理。这不表示整个 HTML 代码自动统一改用 CC BY-SA。
5. 后续替换素材或取得新授权时，更新文件名、作品页面、作者、许可版本、修改说明和核对日期。来源未确认的条目仍需解决，不能仅靠本声明取得授权。
