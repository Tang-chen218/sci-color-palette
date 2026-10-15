# Scientific figure colour palettes

47 colour schemes taken from published journal figures (Cell, Nature, Gut, JEM, STTT and others),
kept as a reference when choosing colours for a new figure.

Each palette is recorded as the hex values printed on its source card. **Values were copied from the
printed labels, not sampled from the image** — see *Known defects* below for why that distinction matters.

## Choosing a palette

Filter on the **colour count** column first; it maps to how many things the figure must distinguish:

| Need | Count |
|---|---|
| 2–5 groups (boxplot, Kaplan-Meier, forest) | 5–6 |
| 6–10 groups, or group x time | 8–10 |
| Many components in one schematic | 14–16 |

Then read the **use** column. Where a palette came from a schematic whose parts encode something
(healthy vs disease, cell type, time point), the note says what the colours are meant to carry.

## Known defects

Six source cards are imperfect. They are listed here rather than silently corrected:

| Cards | Problem |
|---|---|
| `08` `11` `12` `16` | the hex printed on the card disagrees with the RGB printed on the same swatch. The hex is used here. |
| `41` `44` | two visibly different swatches carry the same printed hex. Do not use these two without checking the original. |

Keeping the printed value — rather than sampling the swatch — is what surfaced these. Sampling would
have produced four plausible-looking colours and hidden the fact that the cards disagree with themselves.

## Index

| # | Colours | Journal | Use | Note |
|---|---|---|---|---|
| 01 | 6 | Gut | 多组件示意图；用色差大的颜色填充，区分度高 | — |
| 02 | 6 | JEM | 细胞互作图；浅色填充更柔和，相近色表示同组内不同组分 | — |
| 03 | 6 | Cell | 解剖结构分层图；色彩由浅到深表示层次 | — |
| 04 | 6 | Cell | 两类细胞互作 + 结构示意；颜色鲜明 | — |
| 05 | 6 | Cell | 单细胞测序 + 功能分群；对比强烈 | — |
| 06 | 6 | Cell | 环形/辐条式全景图；由内向外分层 | — |
| 07 | 6 | Nature | 明暗成对（暖橙-深红、灰蓝-深蓝）；适合两类对象对比，色相分离大 | — |
| 08 | 6 | STTT | 六色均衡；适合多分组 | check |
| 09 | 6 | Nature Reviews Neurology | 渐变系；适合同类对象的多亚型 | — |
| 10 | 6 | Cell | 器官 × 状态双维图；两侧配同色文字注释 | — |
| 11 | 6 | Cell | 多组学图谱；色彩丰富 | check |
| 12 | 6 | Cell | 宏观→微观的分层机制图 | check |
| 13 | 6 | Cell | 通路机制图；色彩丰富 | — |
| 14 | 6 | Cell | 上下分区背景色；适合区分早/晚两个时间层 | — |
| 15 | 6 | Cell | 多曲线/多轨迹图；每条曲线一个色 | — |
| 16 | 6 | Cell | 空间图谱；色彩丰富 | check |
| 17 | 6 | Cell | 多种细胞类型全景；用色多、区分靠色相 | — |
| 18 | 6 | Cell | 明暗成对；适合两类对象对比 | — |
| 19 | 6 | Cell | 明暗成对；适合两类对象对比 | — |
| 20 | 6 | Cell | 分子结构示意图；配色鲜明 | — |
| 21 | 6 | Cell | 分子结构示意图；配色鲜明 | — |
| 22 | 5 | — | — | — |
| 23 | 10 | — | — | — |
| 24 | 10 | — | — | — |
| 25 | 10 | — | — | — |
| 26 | 5 | — | — | — |
| 27 | 5 | — | — | — |
| 28 | 5 | — | — | — |
| 29 | 8 | — | — | — |
| 30 | 10 | — | — | — |
| 31 | 6 | — | — | — |
| 32 | 8 | — | — | — |
| 33 | 8 | — | — | — |
| 34 | 10 | — | — | — |
| 35 | 8 | — | — | — |
| 36 | 8 | — | — | — |
| 37 | 8 | — | — | — |
| 38 | 16 | — | — | — |
| 39 | 8 | — | — | — |
| 40 | 8 | — | — | — |
| 41 | 16 | — | — | check |
| 42 | 16 | — | — | — |
| 43 | 14 | — | — | — |
| 44 | 10 | — | — | check |
| 45 | 10 | — | — | — |
| 46 | 10 | — | — | — |
| 47 | 10 | — | — | — |

---

### 01 · Gut · 6 colours

`#f2df83` `#d3a73c` `#cc91a4` `#ffe8c6` `#a1b1e9` `#a9d0b3`

Use: 多组件示意图；用色差大的颜色填充，区分度高

### 02 · JEM · 6 colours

`#a8e4e8` `#20935f` `#94d1a5` `#ffd9b2` `#0dc9c8` `#ffba94`

Use: 细胞互作图；浅色填充更柔和，相近色表示同组内不同组分

### 03 · Cell · 6 colours

`#93779f` `#b6818b` `#eae3aa` `#dbeff4` `#a9ba9c` `#cdc2a5`

Use: 解剖结构分层图；色彩由浅到深表示层次

### 04 · Cell · 6 colours

`#72a895` `#97cd8f` `#8f8fca` `#dc6666` `#e83b38` `#e7a04e`

Use: 两类细胞互作 + 结构示意；颜色鲜明

### 05 · Cell · 6 colours

`#f26b4d` `#accd6f` `#f7b79e` `#0d539d` `#2ca361` `#891618`

Use: 单细胞测序 + 功能分群；对比强烈

### 06 · Cell · 6 colours

`#71add0` `#f6d89d` `#c0bfe0` `#dddff0` `#eaa5a5` `#2b8ac0`

Use: 环形/辐条式全景图；由内向外分层

### 07 · Nature · 6 colours

`#ee9276` `#cb3e37` `#6a8ab0` `#1d5490` `#86bd7c` `#c3619c`

Use: 明暗成对（暖橙-深红、灰蓝-深蓝）；适合两类对象对比，色相分离大

### 08 · STTT · 6 colours

`#d40d2b` `#de3c31` `#9d5b9d` `#671c65` `#e9ae6a` `#f6df41`

Use: 六色均衡；适合多分组

> **Note**: this card's printed hex and RGB disagree; the hex above is what is recorded.

### 09 · Nature Reviews Neurology · 6 colours

`#b6cb9a` `#97aeaa` `#acc8e5` `#f0a99b` `#97a4c9` `#d2b98f`

Use: 渐变系；适合同类对象的多亚型

### 10 · Cell · 6 colours

`#f7962d` `#3b89c1` `#215579` `#d45d99` `#8f9d5c` `#e15f4d`

Use: 器官 × 状态双维图；两侧配同色文字注释

### 11 · Cell · 6 colours

`#fccb79` `#85c334` `#e024e1` `#7dc6d4` `#204cfc` `#a0fa04`

Use: 多组学图谱；色彩丰富

> **Note**: this card's printed hex and RGB disagree; the hex above is what is recorded.

### 12 · Cell · 6 colours

`#36a1d1` `#96602e` `#ebac2c` `#f48cb5` `#e4308e` `#3fb64c`

Use: 宏观→微观的分层机制图

> **Note**: this card's printed hex and RGB disagree; the hex above is what is recorded.

### 13 · Cell · 6 colours

`#678948` `#e7d4c5` `#d5617b` `#2a8e9c` `#91799f` `#a37158`

Use: 通路机制图；色彩丰富

### 14 · Cell · 6 colours

`#eea7c0` `#ba6b97` `#7468a3` `#c3c3c3` `#5faaa4` `#a97d74`

Use: 上下分区背景色；适合区分早/晚两个时间层

### 15 · Cell · 6 colours

`#58b2e0` `#5cc6c0` `#a9c52e` `#f8cd29` `#ec454a` `#76459b`

Use: 多曲线/多轨迹图；每条曲线一个色

### 16 · Cell · 6 colours

`#8f3c73` `#753983` `#e6a397` `#6fb3a7` `#bbbbed` `#b1cfe9`

Use: 空间图谱；色彩丰富

> **Note**: this card's printed hex and RGB disagree; the hex above is what is recorded.

### 17 · Cell · 6 colours

`#9ec0db` `#d4c3d7` `#c34a55` `#f6c264` `#75bec6` `#d5c887`

Use: 多种细胞类型全景；用色多、区分靠色相

### 18 · Cell · 6 colours

`#68b9c2` `#d7c985` `#d94d39` `#5c9ccc` `#ebb3b3` `#c098c7`

Use: 明暗成对；适合两类对象对比

### 19 · Cell · 6 colours

`#cec3df` `#83ba8f` `#d9c8df` `#ffb084` `#bbd3f0` `#0067b8`

Use: 明暗成对；适合两类对象对比

### 20 · Cell · 6 colours

`#53b9e5` `#a83f53` `#9cb667` `#a3b5e1` `#d1d5db` `#9fcac5`

Use: 分子结构示意图；配色鲜明

### 21 · Cell · 6 colours

`#72ce80` `#ff8570` `#006ede` `#fff573` `#dd92cf` `#7eccc8`

Use: 分子结构示意图；配色鲜明

### 22 · — · 5 colours

`#c4afd1` `#f0e9f4` `#f0d4ca` `#e3a798` `#eee6c6`

### 23 · — · 10 colours

`#c8bbda` `#fbf8e5` `#bcb1ab` `#d4baf7` `#fad89f` `#fe96a1` `#bc6c6f` `#e4f7e4` `#f5f4e9` `#fff6e5`

### 24 · — · 10 colours

`#7ab393` `#fba799` `#e9eaf2` `#7fb558` `#fdf1a3` `#c3e4e2` `#feeaea` `#eddbea` `#c6c6c3` `#cdebde`

### 25 · — · 10 colours

`#b994b9` `#395b89` `#f0a586` `#4a9b2c` `#9ad464` `#fffbef` `#eff8e9` `#efefef` `#9b9fa2` `#686a69`

### 26 · — · 5 colours

`#dce8f1` `#f4e4be` `#a9abd2` `#d4eeed` `#e3bdce`

### 27 · — · 5 colours

`#eee6c6` `#eed2d0` `#f4d9ba` `#e993a9` `#f2e193`

### 28 · — · 5 colours

`#d7d7d7` `#c4c0db` `#81b3d4` `#b3df6a` `#fcb662`

### 29 · — · 8 colours

`#debdd8` `#d97072` `#cdf0fa` `#3f89be` `#cad1df` `#fee5e2` `#f1e8f1` `#ffeec0`

### 30 · — · 10 colours

`#92c08d` `#f8d9b3` `#fce094` `#ccd278` `#bde4f9` `#e2908d` `#599ac9` `#dd99b2` `#9687ba` `#bf9c42`

### 31 · — · 6 colours

`#f7c6c0` `#bee1f7` `#90d5d7` `#f8e7bc` `#a4a7ad` `#e5e6d1`

### 32 · — · 8 colours

`#d8e1b9` `#e7b479` `#dc6c60` `#6db3c8` `#64557a` `#354766` `#ede5c1` `#c8cac9`

### 33 · — · 8 colours

`#d2d0e3` `#da8d87` `#9dcbe3` `#81c5a1` `#bdc0cb` `#dbcc7a` `#9987be` `#e7e5cf`

### 34 · — · 10 colours

`#169e77` `#7373ac` `#da6206` `#f8c296` `#c0bece` `#53a68f` `#f3cc40` `#6d94c9` `#889094` `#cdab7d`

### 35 · — · 8 colours

`#a0be8c` `#987ac4` `#f9c397` `#3177bd` `#fa8202` `#66b8b6` `#a3318a` `#bebebe`

### 36 · — · 8 colours

`#830d79` `#3874d1` `#119491` `#2aa35f` `#eb7f30` `#6dc1dc` `#d63227` `#87592f`

### 37 · — · 8 colours

`#f18025` `#4c82c2` `#25908d` `#801f7d` `#9c9526` `#ceafde` `#a3a1a2` `#d6ece9`

### 38 · — · 16 colours

`#c53730` `#ec8969` `#f3bca3` `#dbd0cd` `#c4cfe6` `#579dc6` `#3b82b8` `#203b5b` `#f3f5f5` `#e5fffb` `#64cdcb` `#12b1c4` `#1190a5` `#0d6c8d` `#20607d` `#304c60`

### 39 · — · 8 colours

`#2c7ebb` `#db6403` `#944da3` `#46adac` `#90c448` `#fddc65` `#eb4e4a` `#9b9ddf`

### 40 · — · 8 colours

`#f4696a` `#faa124` `#28ac5b` `#3e67b6` `#884e9b` `#fee4bf` `#b8bcbf` `#acdad3`

### 41 · — · 16 colours

`#fef8f4` `#f8e3de` `#f0a8b5` `#e45297` `#c93189` `#9d1b7d` `#702574` `#341f48` `#b52d8f` `#842d91` `#842d91` `#e16c5a` `#ed824b` `#f4a33d` `#face27` `#f3e518`

> **Warning**: two swatches on this card carry the same printed hex but render as different colours. Verify against the original before use.

### 42 · — · 16 colours

`#232c6f` `#523996` `#7861a8` `#c7b7dd` `#f6ebe7` `#cf958b` `#a54835` `#8a1d1f` `#485283` `#6b6c9b` `#868bb0` `#d0cfe4` `#ffffd8` `#fdf4ac` `#ffee7c` `#f4e841`

### 43 · — · 14 colours

`#252968` `#64308b` `#862d91` `#b52f8e` `#cb417b` `#d75769` `#e16c5a` `#f8a23a` `#f28c47` `#ee844a` `#e16c5a` `#f5e31a` `#e9c540` `#eae92c`

### 44 · — · 10 colours

`#fefbe3` `#fefbe3` `#fcba76` `#fdf5ef` `#eec4c4` `#92c1f2` `#3d78b8` `#ded7d7` `#5f6163` `#705287`

> **Warning**: two swatches on this card carry the same printed hex but render as different colours. Verify against the original before use.

### 45 · — · 10 colours

`#fee3e1` `#ffedca` `#e8e2e8` `#c3e5f9` `#2aa3d8` `#fcb7ac` `#d76c6d` `#fd9cbd` `#8fb28b` `#84becf`

### 46 · — · 10 colours

`#d2e4ce` `#ccdaf1` `#fcdcd9` `#cbe0e0` `#ecf9ff` `#c1d790` `#486f9e` `#deadae` `#88c1c3` `#0167ab`

### 47 · — · 10 colours

`#fef5da` `#fec942` `#fca99b` `#f16156` `#b26a68` `#eef0fd` `#fbd9f5` `#7a7bae` `#04668b` `#0a95cf`
