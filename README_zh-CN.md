<div align="center">

<a href="https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce"><img src="images/logo.jpg" alt="gpt-image-2-for-e-commerce logo"></a>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)
[![Website](https://img.shields.io/badge/Website-Live-orange)](https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)
[![Docs](https://img.shields.io/badge/Docs-Read-blue)](https://docs.evolink.ai)
[![Model](https://img.shields.io/badge/Model-Explore-purple)](https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)

[![🇺🇸 English](https://img.shields.io/badge/🇺🇸_English-Default_Source-111111)](README.md)
[![🇪🇸 Español](https://img.shields.io/badge/🇪🇸_Español-Ver-ffb703)](README_es.md)
[![🇵🇹 Português](https://img.shields.io/badge/🇵🇹_Português-Ver-2a9d8f)](README_pt.md)
[![🇯🇵 日本語](https://img.shields.io/badge/🇯🇵_日本語-表示-52b788)](README_ja.md)
[![🇰🇷 한국어](https://img.shields.io/badge/🇰🇷_한국어-보기-4ea8de)](README_ko.md)
[![🇩🇪 Deutsch](https://img.shields.io/badge/🇩🇪_Deutsch-Ansehen-f4a261)](README_de.md)
[![🇫🇷 Français](https://img.shields.io/badge/🇫🇷_Français-Voir-e76f51)](README_fr.md)
[![🇹🇷 Türkçe](https://img.shields.io/badge/🇹🇷_Türkçe-Görüntüle-d62828)](README_tr.md)
[![🇹🇼 繁體中文](https://img.shields.io/badge/🇹🇼_繁體中文-查看-8338ec)](README_zh-TW.md)
[![🇨🇳 简体中文](https://img.shields.io/badge/🇨🇳_简体中文-查看-ef476f)](README_zh-CN.md)
[![🇷🇺 Русский](https://img.shields.io/badge/🇷🇺_Русский-Смотреть-577590)](README_ru.md)

</div>

# 如何使用 GPT Image 2 制作电商素材

> 一份面向 **GPT Image 2** 的电商素材制作提示词手册——涵盖主图套图、多国主图、模特试穿、产品展示、互动场景、社交电商等场景。

## 🍌 简介

本仓库教你**如何使用 GPT Image 2 制作电商素材**——电商主图、多国本地化套图、A+ 产品详情、模特试穿、产品多角度展示、互动场景、社交电商带货图——并支持规模化生产。

**每个案例都是一份配方：** 一张产品原图 + 直接复制即用的 GPT Image 2 提示词 + 真实输出示例。使用前把 `{占位符}` 替换为你自己的商品、语言、国家和卖点即可。

需要批量跑成百上千个 SKU？请直接跳到 [🚀 批量生成 · 调用 Evolink API](#-批量生成--调用-evolink-api)。

在 Evolink 上试用：[GPT Image 2 工作流](https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)

如果觉得有用，欢迎点个 Star ⭐

> [!NOTE]
> 本仓库专注于可复用的电商素材提示词模板。使用前请替换大括号中的占位符，并根据实际的平台、市场、语言、产品、材质、模特类型和卖点进行调整。

<a href='https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://docs.evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>
<a href='https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🤗 Dataset-Evolink-yellow' height="25"></a>

## ⚡ 快速开始

1. **挑一个案例**——找到与你目标最匹配的电商场景（主图、模特试穿、产品多角度、A+ 详情等）。
2. **上传产品原图、复制提示词**——把案例下方的提示词复制走，把 `{占位符}` 替换为你的商品、语言、国家、平台和卖点。
3. **在 GPT Image 2 上跑起来**——单图出货可走 [Evolink 工作流 UI](https://evolink.ai/gpt-image-2?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)；多 SKU、多语言批量生产请走 [Evolink API](#-批量生成--调用-evolink-api)。

## 📰 更新日志

- **2026年5月7日：** 仓库重新定位为面向 **GPT Image 2 的电商素材制作指南**，新增"快速开始"与"批量生成 · 调用 Evolink API"两个小节。
- **2026年5月5日：** 扩充电商主图、模特试穿与产品展示三大分类，使其与电商 Agent 提示词整理表完整对齐。
- **2026年4月30日：** 新增主图、模特编辑、产品展示、互动场景和社交电商素材的完整提示词分类。
- **2026年4月30日：** 首次搭建电商图片提示词工作流的英文优先仓库框架。

## 📑 目录

- [🍌 简介](#-简介)
- [⚡ 快速开始](#-快速开始)
- [📰 更新日志](#-更新日志)
- [📑 目录](#-目录)
- [🖼️ 电商主图提示词](#️-电商主图提示词)
  - [案例 1：电商平台主图套图](#案例-1电商平台主图套图)
  - [案例 2：多国主图套图](#案例-2多国主图套图)
  - [案例 3：A+ 产品详情视觉](#案例-3a-产品详情视觉)
  - [案例 4：批量生成亚马逊套图](#案例-4批量生成亚马逊套图)
  - [案例 5：批量替换产品主图](#案例-5批量替换产品主图)
  - [案例 6：批量主图翻译](#案例-6批量主图翻译)
- [👗 模特试穿与服装提示词](#-模特试穿与服装提示词)
  - [案例 1：服装试穿图套图](#案例-1服装试穿图套图)
  - [案例 2：模特与宠物试衣](#案例-2模特与宠物试衣)
  - [案例 3：模特姿势拓展](#案例-3模特姿势拓展)
  - [案例 4：模特替换与外观控制](#案例-4模特替换与外观控制)
  - [案例 5：指定模特替换](#案例-5指定模特替换)
  - [案例 6：服装销售背景概念](#案例-6服装销售背景概念)
  - [案例 7：配饰试戴](#案例-7配饰试戴)
  - [案例 8：美甲佩戴](#案例-8美甲佩戴)
  - [案例 9：模特试鞋](#案例-9模特试鞋)
- [📦 产品展示提示词](#-产品展示提示词)
  - [案例 1：纯白背景产品精修](#案例-1纯白背景产品精修)
  - [案例 2：多角度产品视图](#案例-2多角度产品视图)
  - [案例 3：材质与颜色变体](#案例-3材质与颜色变体)
  - [案例 4：智能背景生成](#案例-4智能背景生成)
  - [案例 5：自定义描述换背景](#案例-5自定义描述换背景)
  - [案例 6：参考图背景生成](#案例-6参考图背景生成)
- [🤝 产品互动提示词](#-产品互动提示词)
  - [案例 1：手持产品特写](#案例-1手持产品特写)
  - [案例 2：生成人物互动场景](#案例-2生成人物互动场景)
  - [案例 3：参考人物产品互动](#案例-3参考人物产品互动)
  - [案例 4：宠物与产品互动](#案例-4宠物与产品互动)
- [🛍️ 社交电商提示词](#️-社交电商提示词)
  - [案例 1：时尚棚拍销售套图](#案例-1时尚棚拍销售套图)
  - [案例 2：镜子穿搭销售视频](#案例-2镜子穿搭销售视频)
  - [案例 3：服装礼盒造型](#案例-3服装礼盒造型)
  - [案例 4：生鲜食品销售场景套图](#案例-4生鲜食品销售场景套图)
  - [案例 5：通用食品销售素材套图](#案例-5通用食品销售素材套图)
- [🚀 批量生成 · 调用 Evolink API](#-批量生成--调用-evolink-api)
- [🙏 致谢](#-致谢)

## 🖼️ 电商主图提示词

### 案例 1：电商平台主图套图

**提示词：**

```
帮我生成一组{平台名}套图，售卖到{国家}，{语言}，这款商品为{商品名}，卖点是{卖点描述}
```

> [!NOTE]
> **使用前请替换 {平台名}、{国家}、{语言}、{商品名} 和 {卖点描述}。** 此模板适用于 Amazon、eBay、AliExpress、TEMU、SHEIN、TikTok Shop、Shopee、Lazada、Mercado Libre、Walmart、Etsy、Rakuten、Coupang、Shopify 等电商平台。Agent 会自动规划商品适合的套图内容及平台特点，生成包括：白底图、尺寸图、多角度展示图、使用场景图、卖点图、材质细节图等。

#### 示例 1：实木餐椅

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="4">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/01/input.webp" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/01/output-01.png" width="150"><br><sub>白底主图</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-02.png" width="150"><br><sub>核心卖点图</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-03.png" width="150"><br><sub>尺寸图</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-04.png" width="150"><br><sub>多角度图</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/01/output-05.png" width="150"><br><sub>生活场景图</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-06.png" width="150"><br><sub>使用场景图</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-08.png" width="150"><br><sub>材质细节图</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 示例 2：运动水壶

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/02/input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/02/output-01.png" width="150"><br><sub>白底主图</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-02.png" width="150"><br><sub>多角度图</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-03.png" width="150"><br><sub>核心卖点图</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/02/output-04.png" width="150"><br><sub>尺寸图</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-05.png" width="150"><br><sub>使用场景图</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-06.png" width="150"><br><sub>材质细节图</sub></td>
  </tr>
</table>

#### 示例 3：运动 T 恤

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="4">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/03/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/03/Output-01.png" width="150"><br><sub>核心卖点图</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-02.png" width="150"><br><sub>产品参数图</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-03.png" width="150"><br><sub>尺码表</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-04.png" width="150"><br><sub>多角度图</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/03/Output-05.png" width="150"><br><sub>使用场景图</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-06.png" width="150"><br><sub>材质细节图</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-07.png" width="150"><br><sub>卖点总结图</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### 案例 2：多国主图套图

**提示词：**

```
帮我生成一组{平台}套图，售卖到{国家}，{语言}
```

> [!NOTE]
> **使用前请替换 {平台}、{国家} 和 {语言}。** 当你希望模型自动推断最佳主图结构时，可以使用这个更简短的模板。

#### 示例 1：紫色波点连衣裙

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/01/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ar.png" width="150"><br><sub>阿拉伯语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Cn.png" width="150"><br><sub>中文版</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-En.png" width="150"><br><sub>英文版</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ja.png" width="150"><br><sub>日文版</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Kr.png" width="150"><br><sub>韩文版</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Pt.png" width="150"><br><sub>葡萄牙语版</sub></td>
  </tr>
</table>

#### 示例 2：无线吸尘器

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/02/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Bn.png" width="150"><br><sub>孟加拉语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-De.png" width="150"><br><sub>德语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Es%20.png" width="150"><br><sub>西班牙语版</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/02/Output-Fr.png" width="150"><br><sub>法语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Hi.png" width="150"><br><sub>印地语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Ru.png" width="150"><br><sub>俄语版</sub></td>
  </tr>
</table>

#### 示例 3：圣诞主题手机壳

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/03/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Id.png" width="150"><br><sub>印尼语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-It.png" width="150"><br><sub>意大利语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Nl.png" width="150"><br><sub>荷兰语版</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/03/Output-Th.png" width="150"><br><sub>泰语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Tr.png" width="150"><br><sub>土耳其语版</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Vi.png" width="150"><br><sub>越南语版</sub></td>
  </tr>
</table>

### 案例 3：A+ 产品详情视觉

**提示词：**

```
这是一{商品描述}，帮我生成A+详情图，售卖到{国家}，{语言}
```

> [!NOTE]
> **使用前请替换 {商品描述}、{国家} 和 {语言}。** 示例：「这是一盒咖啡豆，帮我生成A+详情图，售卖到美国，英文」。适用于产品故事、功能拆解、使用场景和高端详情页布局。

#### 示例 1：高端茶叶礼盒

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/01/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/01/Output-01.png" width="150"><br><sub>头屏（卖点）</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-02.png" width="150"><br><sub>设计与工艺</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-03.png" width="150"><br><sub>产品系列</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/01/Output-04.png" width="150"><br><sub>易用说明</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-05.png" width="150"><br><sub>礼赠场景</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-06.png" width="150"><br><sub>使用场景</sub></td>
  </tr>
</table>

#### 示例 2：天然胶水棒

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/02/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/02/Output-01.png" width="150"><br><sub>A+ 头屏</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-02.png" width="150"><br><sub>A+ 详情屏 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-03.png" width="150"><br><sub>A+ 详情屏 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/02/Output-04.png" width="150"><br><sub>A+ 详情屏 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-05.png" width="150"><br><sub>A+ 详情屏 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-06.png" width="150"><br><sub>A+ 总结屏</sub></td>
  </tr>
</table>

#### 示例 3：奶茶饮品

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/03/Input.png" width="160" alt="商品原图"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/03/Output-01.png" width="150"><br><sub>A+ 头屏</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-02.png" width="150"><br><sub>A+ 详情屏 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-03.png" width="150"><br><sub>A+ 详情屏 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/03/Output-04.png" width="150"><br><sub>A+ 详情屏 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-05.png" width="150"><br><sub>A+ 详情屏 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-06.png" width="150"><br><sub>A+ 总结屏</sub></td>
  </tr>
</table>

### 案例 4：批量生成亚马逊套图

> [!NOTE]
> 适用场景：多 SKU、同品类商品需批量生图时，暂不支持分不同语言批跑。

### 案例 5：批量替换产品主图

**输入：** 上传源产品图片和目标主图套图。

**提示词：**

```
把图1商品将他替换到图2~7当中，除了替换的商品改变，保证其它内容不变
```

> [!NOTE]
> 爆款主图一键复刻，换品不换版。适用于多个 SKU 复用同一套素材风格。

#### 示例 1：球形氛围灯（替换为蘑菇灯爆款套图）

<table>
  <tr>
    <th width="14%">源商品</th>
    <th colspan="6">爆款套图（待替换）</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/01/Input-01.png" width="120"><br>
      <sub>球形氛围灯</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/01/Input-02.png" width="110"><br><sub>原主图 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-03.png" width="110"><br><sub>原主图 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-04.png" width="110"><br><sub>原主图 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-05.png" width="110"><br><sub>原主图 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-06.png" width="110"><br><sub>原主图 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-07.png" width="110"><br><sub>原主图 6</sub></td>
  </tr>
  <tr>
    <th colspan="6">替换后套图</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/01/Output-02.png" width="110"><br><sub>替换后 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-03.png" width="110"><br><sub>替换后 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-04.png" width="110"><br><sub>替换后 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-05.png" width="110"><br><sub>替换后 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-06.png" width="110"><br><sub>替换后 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-07.png" width="110"><br><sub>替换后 6</sub></td>
  </tr>
</table>

#### 示例 2：木质床头柜（替换为红色储物柜爆款套图）

<table>
  <tr>
    <th width="14%">源商品</th>
    <th colspan="4">爆款套图（待替换）</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/02/Input.png" width="120"><br>
      <sub>木质床头柜</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/02/Input-01.png" width="120"><br><sub>原主图 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-02.png" width="120"><br><sub>原主图 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-03.png" width="120"><br><sub>原主图 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-04.png" width="120"><br><sub>原主图 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">替换后套图</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/02/Output-01.png" width="120"><br><sub>替换后 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-02.png" width="120"><br><sub>替换后 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-03.png" width="120"><br><sub>替换后 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-04.png" width="120"><br><sub>替换后 4</sub></td>
  </tr>
</table>

### 案例 6：批量主图翻译

**输入：** 上传所有包含文字的主图。

**提示词：**

```
将所有图片的文字翻译成{目标语言}
```

> [!NOTE]
> **使用前请替换 {目标语言}。** 示例：「将所有图片的文字翻译成英文」。批量翻译商品图文，精准转换多语言，完美保留原有排版，助您一键铺货全球。

#### 示例 1：储物柜主图（中文 → 英文）

<table>
  <tr>
    <th colspan="4">原文版</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Input-01.png" width="140"><br><sub>原图 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-02.png" width="140"><br><sub>原图 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-03.png" width="140"><br><sub>原图 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-04.png" width="140"><br><sub>原图 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">翻译后</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Output-01.png" width="140"><br><sub>翻译后 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-02.png" width="140"><br><sub>翻译后 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-03.png" width="140"><br><sub>翻译后 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-04.png" width="140"><br><sub>翻译后 4</sub></td>
  </tr>
</table>

#### 示例 2：储物柜主图（多语言批量翻译）

<table>
  <tr>
    <th colspan="4">原文版</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Input-01.png" width="140"><br><sub>原图 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-02.png" width="140"><br><sub>原图 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-03.png" width="140"><br><sub>原图 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-04.png" width="140"><br><sub>原图 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">翻译后</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Output-01.png" width="140"><br><sub>翻译后 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-02.png" width="140"><br><sub>翻译后 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-03.png" width="140"><br><sub>翻译后 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-04.png" width="140"><br><sub>翻译后 4</sub></td>
  </tr>
</table>

## 👗 模特试穿与服装提示词

### 案例 1：服装试穿图套图

**提示词：**

```
这是一件{服装类型}，帮我生成一套试穿套图，售卖到{国家}
```

> [!NOTE]
> **使用前请替换 {服装类型} 和 {国家}。** 示例：「这是一件连衣裙，帮我生成一套试穿套图，售卖到美国」。适用于连衣裙、上衣、外套、童装或任何需要商业试穿展示的服装品类。

#### 示例 1：绿色碎花连衣裙

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/01/Input.png" width="160"><br>
      <sub>白底产品图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/01/Output-1.png" width="150"><br><sub>模特正面</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-2.png" width="150"><br><sub>多角度展示</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-3.png" width="150"><br><sub>细节特写</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/01/Output-4.png" width="150"><br><sub>整体搭配</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-5.png" width="150"><br><sub>生活场景</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-6.png" width="150"><br><sub>其他视角</sub></td>
  </tr>
</table>

#### 示例 2：印度莎丽传统服饰

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/02/Input.png" width="160"><br>
      <sub>白底产品图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/02/Output-01.png" width="150"><br><sub>模特正面</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-02.png" width="150"><br><sub>背面/转身</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-03.png" width="150"><br><sub>细节展示</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/02/Output-04.png" width="150"><br><sub>整体搭配</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-05.png" width="150"><br><sub>生活场景</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-06.png" width="150"><br><sub>其他角度</sub></td>
  </tr>
</table>

### 案例 2：模特与宠物试衣

**输入：** 上传服装或配饰图片。

**提示词：**

```
生成一个模特穿上这件衣服
生成宠物狗狗穿上这件衣服
```

> [!NOTE]
> 此模板同时覆盖人物模特试穿与宠物试穿场景，适合服装、Cosplay 道具以及宠物时尚等需要在不同主体上展示同一件衣服的素材。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case8/01/Input.png" width="140"><br><sub>LOVE 卡通 T 恤</sub></td>
    <td align="center"><img src="e-commerce/Case8/01/Output-01.png" width="140"><br><sub>男模特上身</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Input.jpg" width="140"><br><sub>骑行 T 恤</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Output-01.png" width="140"><br><sub>男模特上身</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Input.webp" width="140"><br><sub>半拉链针织衫</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Output-01.png" width="140"><br><sub>女模特上身</sub></td>
  </tr>
</table>

### 案例 3：模特姿势拓展

**输入：** 上传原始的模特服装图片。

**提示词：**

```
给模特拓展姿势
```

> [!NOTE]
> 可生成侧身、45 度侧身、正面行走等多种姿势，无需重新拍摄即可丰富一组服装素材。

#### 示例 1：LOVE 卡通 T 恤

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="4">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/01/Input.png" width="160"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/01/Output-01.png" width="150"><br><sub>正面站姿</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-02.png" width="150"><br><sub>侧身</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-03.png" width="150"><br><sub>45 度转身</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-04.png" width="150"><br><sub>行走</sub></td>
  </tr>
</table>

#### 示例 2：灰色半拉链卫衣

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="4">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/02/Input.png" width="160"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/02/Output-01.png" width="150"><br><sub>正面站姿</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-02.png" width="150"><br><sub>侧身</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-03.png" width="150"><br><sub>45 度</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-04.png" width="150"><br><sub>行走</sub></td>
  </tr>
</table>

### 案例 4：模特替换与外观控制

**输入：** 上传原始模特穿搭图。

**提示词：**

```
帮我分别把图片的模特换成{人种}模特，{发型描述}，保持衣服不变
帮我把人物换成一个{人种}模特，{肤色}，{发色}，服装不变
```

> [!NOTE]
> **使用前请替换 {人种}、{发型描述}、{肤色} 和 {发色}。** 示例：「帮我分别把图片的模特换成黑人模特，脏辫发型，保持衣服不变」「帮我把人物换成一个欧美女模特，白皮肤，金发，服装不变」。此模板帮助你在不重新拍摄的情况下，为不同受众本地化时尚素材。

#### 示例 1：LOVE 卡通 T 恤

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/01/Input.png" width="160"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center"><img src="e-commerce/Case10/01/Output-01.png" width="180"><br><sub>替换模特版本 1</sub></td>
    <td align="center"><img src="e-commerce/Case10/01/Output-02.png" width="180"><br><sub>替换模特版本 2</sub></td>
  </tr>
</table>

#### 示例 2：灰色半拉链卫衣

<table>
  <tr>
    <th width="40%">输入</th>
    <th width="60%">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/02/Input.png" width="200"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center">
      <img src="e-commerce/Case10/02/Output-01.png" width="200"><br>
      <sub>替换后模特</sub>
    </td>
  </tr>
</table>

### 案例 5：指定模特替换

**输入：** 上传原始模特图和参考模特图。

**提示词：**

```
把图一的模特换成图二的模特，保持姿势不变
```

> [!NOTE]
> 当你希望在多组素材中锁定特定模特形象，又要复用原有的服装与姿势时使用。

#### 示例 1：女模特换装

<table>
  <tr>
    <th>原始模特</th>
    <th>参考模特</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/01/Input-01.jpg" width="180"><br><sub>原始模特</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Input-02.png" width="180"><br><sub>指定模特</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Output.png" width="180"><br><sub>替换后效果</sub></td>
  </tr>
</table>

#### 示例 2：男模特换装

<table>
  <tr>
    <th>原始模特</th>
    <th>参考模特</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/02/Input-01.jpeg" width="180"><br><sub>原始模特</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Input-02.jpeg" width="180"><br><sub>指定模特</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Output.png" width="180"><br><sub>替换后效果</sub></td>
  </tr>
</table>

### 案例 6：服装销售背景概念

**提示词：**

```
生成合适的背景图，用于{服装类型}的售卖展示，给我设计几个室内的和户外的背景让我选择
```

> [!NOTE]
> **使用前请替换 {服装类型}。** 示例：「生成合适的背景图，用于童装的售卖展示，给我设计几个室内的和户外的背景让我选择」。适用于将场景构思与模特生成分开处理的工作流。

#### 示例 1：米色针织卫衣

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/01/Input.jpeg" width="160"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/01/Output-01.png" width="150"><br><sub>室内简约</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-02.png" width="150"><br><sub>户外自然 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-03.png" width="150"><br><sub>户外自然 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/01/Output-04.png" width="150"><br><sub>城市街景</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-05.png" width="150"><br><sub>居家场景</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-06.png" width="150"><br><sub>休闲场景</sub></td>
  </tr>
</table>

#### 示例 2：深蓝针织毛衣

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/02/Input.jpg" width="160"><br>
      <sub>原始模特</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/02/Output-01.png" width="150"><br><sub>室内场景 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-02.png" width="150"><br><sub>户外场景 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-03.png" width="150"><br><sub>户外场景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/02/Output-04.png" width="150"><br><sub>城市街景</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-05.png" width="150"><br><sub>居家环境</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-06.png" width="150"><br><sub>其他场景</sub></td>
  </tr>
</table>

### 案例 7：配饰试戴

**输入：** 上传配饰产品图片。

**提示词：**

```
一个模特戴着这个{配饰类型}，{补充要求}
```

> [!NOTE]
> **使用前请替换 {配饰类型} 和 {补充要求}。** 示例：「一个模特戴着这个项链，模特不露脸」「一个模特戴着这个耳饰」。适用于项链、耳饰、帽子、围巾等可佩戴配饰。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case13/01/Input.png" width="180"><br><sub>玉石项链</sub></td>
    <td align="center"><img src="e-commerce/Case13/01/Output.png" width="180"><br><sub>佩戴效果</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Input.jpg" width="180"><br><sub>金色圆环耳环</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Output.png" width="180"><br><sub>佩戴效果</sub></td>
  </tr>
</table>

### 案例 8：美甲佩戴

**输入：** 上传美甲设计参考图。

**提示词：**

```
美甲应用上手
```

> [!NOTE]
> 适用于穿戴甲、甲油胶概念、美甲店设计预览以及美甲产品营销素材。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case14/01/Input.jpg" width="180"><br><sub>粉色美甲样品</sub></td>
    <td align="center"><img src="e-commerce/Case14/01/Output-01.png" width="180"><br><sub>上手效果</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Input.jpg" width="180"><br><sub>多色美甲样品</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Output-01.png" width="180"><br><sub>上手效果</sub></td>
  </tr>
</table>

### 案例 9：模特试鞋

**输入：** 上传鞋子产品图片。

**提示词：**

```
一个模特穿图中鞋子，{搭配描述}
```

> [!NOTE]
> **使用前请替换 {搭配描述}。** 示例：「一个模特穿图中鞋子，棕色短裙」。适用于运动鞋、高跟鞋、靴子和当季鞋款的素材。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case15/01/Input.jpg" width="180"><br><sub>黑色皮鞋</sub></td>
    <td align="center"><img src="e-commerce/Case15/01/Output-01.png" width="180"><br><sub>男模搭配</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Input.jpg" width="180"><br><sub>黑色高跟鞋</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Output-01.png" width="180"><br><sub>女模搭配</sub></td>
  </tr>
</table>

## 📦 产品展示提示词

### 案例 1：纯白背景产品精修

**输入：** 上传高质量产品照片。

**提示词：**

```
生成白底精修图
```

> [!NOTE]
> 原图质量越好，商品效果越精准。高质量的源图通常能带来更精准的产品保留和更干净的电商级输出。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case16/01/Input.png" width="180"><br><sub>居家场景产品图</sub></td>
    <td align="center"><img src="e-commerce/Case16/01/Output-01.png" width="180"><br><sub>白底精修图</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/images.jpeg" width="180"><br><sub>原始产品图</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/Output-01.png" width="180"><br><sub>白底精修图</sub></td>
  </tr>
</table>

### 案例 2：多角度产品视图

**输入：** 上传产品参考图。

**提示词：**

```
生成多角度的商品图
```

> [!NOTE]
> 适用于产品卡片、轮播图、功能拆解和特定角度的详情页。

#### 示例 1：黄棕色登山靴

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/01/Input.png" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/01/Output-01.png" width="150"><br><sub>正面</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-02.png" width="150"><br><sub>侧面 45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-03.png" width="150"><br><sub>背面</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/01/Output-04.png" width="150"><br><sub>靴底</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-05.png" width="150"><br><sub>俯视</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-06.png" width="150"><br><sub>其他角度</sub></td>
  </tr>
</table>

#### 示例 2：登山靴（其他款）

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/02/Input.png" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/02/Output-01.png" width="150"><br><sub>正面</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-02.png" width="150"><br><sub>侧面</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-03.png" width="150"><br><sub>背面</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/02/Output-04.png" width="150"><br><sub>靴底细节</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-05.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-06.png" width="150"><br><sub>其他视角</sub></td>
  </tr>
</table>

### 案例 3：材质与颜色变体

**输入：** 上传需要编辑的产品或服装图片。

**提示词：**

```
修改商品材质，人物衣服分别变成：{材质1}、{材质2}和{材质3}
```

> [!NOTE]
> **使用前请替换 {材质1}、{材质2} 和 {材质3}。** 示例：「修改商品材质，人物衣服分别变成：浅灰色麂皮材质、深棕色牛仔和酒红色灯芯绒材质」。适用于面料替换、材质测试、季节性换色和概念探索。

#### 示例 1：绿色夹克材质变体

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/01/Input.jpg" width="160"><br>
      <sub>男模特原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/01/Output-01.png" width="150"><br><sub>变体 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-02.png" width="150"><br><sub>变体 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-03.png" width="150"><br><sub>变体 3</sub></td>
  </tr>
</table>

#### 示例 2：黑色皮夹克材质变体

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/02/Input.avif" width="160"><br>
      <sub>男模特原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/02/Output-01.png" width="150"><br><sub>变体 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-02.png" width="150"><br><sub>变体 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-03.png" width="150"><br><sub>变体 3</sub></td>
  </tr>
</table>

### 案例 4：智能背景生成

**输入：** 上传产品图片。

**提示词：**

```
生成合适的商品图
```

> [!NOTE]
> 当你希望模型自动推断最合适的商业产品背景，而无需详细的美术指导时使用。

#### 示例 1：休闲零食

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/01/Input.webp" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/01/Output-01.png" width="200"><br><sub>智能背景 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-02.png" width="200"><br><sub>智能背景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/01/Output-03.png" width="200"><br><sub>智能背景 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-04.png" width="200"><br><sub>智能背景 4</sub></td>
  </tr>
</table>

#### 示例 2：护肤精华液

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/02/Input.jpg" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/02/Output-01.png" width="200"><br><sub>智能背景 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-02.png" width="200"><br><sub>智能背景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/02/Output-03.png" width="200"><br><sub>智能背景 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-04.png" width="200"><br><sub>智能背景 4</sub></td>
  </tr>
</table>

### 案例 5：自定义描述换背景

**输入：** 上传产品图片。

**提示词：**

```
帮我图中的商品换一个背景：{背景描述}
```

> [!NOTE]
> **使用前请替换 {背景描述}。** 示例：「帮我图中的商品换一个背景：香水瓶的特写，静置在一块光滑的白色石头上。背景是柔和的白色和淡蓝色花朵，更远处是平静的蓝色湖泊和晴空下的山脉。整个场景营造出清新、飘逸、略带清冷的唯美意境。」适用于希望对新背景有完整美术把控的场景。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case20/01/Input.png" width="180"><br><sub>商品原图</sub></td>
    <td align="center"><img src="e-commerce/Case20/01/Output-01.png" width="180"><br><sub>自定义描述背景</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Input.jpg" width="180"><br><sub>商品原图</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Output-01.png" width="180"><br><sub>自定义描述背景</sub></td>
  </tr>
</table>

### 案例 6：参考图背景生成

**输入：** 上传产品图片和参考背景图。

**提示词：**

```
图一是我的{商品}，参考图二背景生成
```

> [!NOTE]
> **使用前请替换 {商品}。** 示例：「图一是我的戒指，参考图二背景生成」。此模板适用于风格匹配、品牌一致性和品类专属视觉参考。

#### 示例 1：粉色复古小汽车

<table>
  <tr>
    <th>商品图</th>
    <th>参考背景</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/01/Input-01.jpg" width="180"><br><sub>粉色复古小汽车</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Input-02.jpg" width="180"><br><sub>绿色森林背景</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Output.png" width="180"><br><sub>森林桌面合成</sub></td>
  </tr>
</table>

#### 示例 2：红色口红

<table>
  <tr>
    <th>商品图</th>
    <th>参考背景</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/02/Input-01.jpg" width="180"><br><sub>红色口红</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Input-02.jpg" width="180"><br><sub>黑金大理石背景</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Output.png" width="180"><br><sub>大理石桌面合成</sub></td>
  </tr>
</table>

## 🤝 产品互动提示词

### 案例 1：手持产品特写

**输入：** 上传产品图片。

**提示词：**

```
一只手拿着这个商品，{场景描述}，商品颜色不变
{动作描述}
```

> [!NOTE]
> **使用前请替换 {场景描述} 和 {动作描述}。** 示例：「一只手拿着这个商品，时尚摄影大片背景，商品颜色不变」「手拿电钻，钻木头」。适用于美妆、工具、数码、包装商品和触感产品演示。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case22/01/Input.jpg" width="180"><br><sub>粉色唇蜜</sub></td>
    <td align="center"><img src="e-commerce/Case22/01/Output.png" width="180"><br><sub>手拿唇蜜特写</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Input.avif" width="180"><br><sub>木柄拖把</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Output.png" width="180"><br><sub>手拿拖把拖地</sub></td>
  </tr>
</table>

### 案例 2：生成人物互动场景

**输入：** 上传产品场景图或产品图。

**提示词：**

```
给这个商品场景添加人物模特，模特要求是：{人物描述}，{姿势}，{动作}
```

> [!NOTE]
> **使用前请替换 {人物描述}、{姿势} 和 {动作}。** 示例：「给这个商品场景添加人物模特，模特要求是：小女孩，站姿，手拿玩偶」「给这个商品场景添加人物模特，手拿着拖把」。适用于展示产品比例、使用方式、情感表达和受众匹配。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case23/01/Input.jpg" width="180"><br><sub>中国风红色拱门场景</sub></td>
    <td align="center"><img src="e-commerce/Case23/01/Output-01.png" width="180"><br><sub>旗袍模特入场</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Input.webp" width="180"><br><sub>红银头戴耳机</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Output.png" width="180"><br><sub>戴耳机女模特</sub></td>
  </tr>
</table>

### 案例 3：参考人物产品互动

**输入：** 上传产品场景图和参考人物图。

**提示词：**

```
给图一的商品场景添加图二人物模特，{动作描述}
```

> [!NOTE]
> **使用前请替换 {动作描述}。** 示例：「给图一的商品场景添加图二人物模特，模特躺在床上」。当你需要在多个素材中保持人物形象一致时使用。

#### 示例 1：卧室大床场景 + 男模特

<table>
  <tr>
    <th>商品场景</th>
    <th>参考人物</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/01/Input-01.webp" width="180"><br><sub>大床卧室场景</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Input-02.jpg" width="180"><br><sub>白T男模特</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Output.png" width="180"><br><sub>男模特斜倚床上</sub></td>
  </tr>
</table>

#### 示例 2：摇椅居家场景 + 男模特

<table>
  <tr>
    <th>商品场景</th>
    <th>参考人物</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/02/Input-01.jpg" width="180"><br><sub>摇椅居家场景</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Input-02.jpg" width="180"><br><sub>白衬衫男模特</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Output.png" width="180"><br><sub>男模特坐摇椅</sub></td>
  </tr>
</table>

### 案例 4：宠物与产品互动

**输入：** 上传产品图片。

**提示词：**

```
生成{宠物}和图中{商品}互动
```

> [!NOTE]
> **使用前请替换 {宠物} 和 {商品}。** 示例：「生成猫和图中玩具互动」「生成一只狗狗和图中玩具互动」。特别适用于玩具、宠物用品、家居和趣味生活方式产品素材。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case25/01/Input.jpg" width="180"><br><sub>橙色狗咬球</sub></td>
    <td align="center"><img src="e-commerce/Case25/01/Output.png" width="180"><br><sub>幼犬咬球</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Input.jpg" width="180"><br><sub>仓鼠跑轮</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Output.png" width="180"><br><sub>仓鼠在跑轮里</sub></td>
  </tr>
</table>

## 🛍️ 社交电商提示词

### 案例 1：时尚棚拍销售套图

**提示词：**

```
生成一套模特带货图,背景是服装工作室
```

> [!NOTE]
> 适用于展厅风格的服装推广、精品店视觉营销和棚拍风格的社交内容。

#### 示例 1：蓝色连帽卫衣

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/01/Input.png" width="160"><br>
      <sub>白底产品图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/01/Output-01.png" width="200"><br><sub>棚拍效果 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-02.png" width="200"><br><sub>棚拍效果 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/01/Output-03.png" width="200"><br><sub>棚拍效果 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-04.png" width="200"><br><sub>棚拍效果 4</sub></td>
  </tr>
</table>

#### 示例 2：粉色碎花连衣裙

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/02/Input.webp" width="160"><br>
      <sub>白底产品图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/02/Output-01.png" width="200"><br><sub>棚拍效果 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-02.png" width="200"><br><sub>棚拍效果 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/02/Output-03.png" width="200"><br><sub>棚拍效果 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-04.png" width="200"><br><sub>棚拍效果 4</sub></td>
  </tr>
</table>

### 案例 2：镜子穿搭销售视频

**提示词：**

```
生成对镜穿搭服装带货视频
```

> [!NOTE]
> 此模板非常适合达人风格的时尚内容、UGC 美学和休闲社交带货形式。

### 案例 3：服装礼盒造型

**输入：** 上传服装图片。

**提示词：**

```
将衣服放进礼盒
```

> [!NOTE]
> 适用于节日礼品营销、高端包装效果图和节日主题产品素材。

<table>
  <tr>
    <th>输入</th>
    <th>输出</th>
    <th>输入</th>
    <th>输出</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case33/01/Input.jpg" width="180"><br><sub>彩色泼墨 T 恤</sub></td>
    <td align="center"><img src="e-commerce/Case33/01/Output.png" width="180"><br><sub>礼盒效果</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Input.jpg" width="180"><br><sub>红色儿童羽绒服</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Output.png" width="180"><br><sub>礼盒效果</sub></td>
  </tr>
</table>

### 案例 4：生鲜食品销售场景套图

**提示词：**

```
生成一套{食品名}的生鲜场景图
```

> [!NOTE]
> **使用前请替换 {食品名}。** 示例：「生成一套柚子的生鲜场景图」。适用于水果、农产品、盒装食品、特色食材和高端生鲜陈列。

#### 示例 1：西瓜

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/01/Input.webp" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/01/Output-01.png" width="200"><br><sub>生鲜场景 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-02.png" width="200"><br><sub>生鲜场景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/01/Output-03.png" width="200"><br><sub>生鲜场景 3</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-04.png" width="200"><br><sub>生鲜场景 4</sub></td>
  </tr>
</table>

#### 示例 2：葡萄

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/02/Input.jpg" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/02/Output-01.png" width="150"><br><sub>生鲜场景 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-02.png" width="150"><br><sub>生鲜场景 2</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-03.png" width="150"><br><sub>生鲜场景 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/02/Output-04.png" width="150"><br><sub>生鲜场景 4</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-05.png" width="150"><br><sub>生鲜场景 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### 案例 5：通用食品销售素材套图

**提示词：**

```
生成一组食品带货图
```

> [!NOTE]
> 可作为零食品牌、包装食品、生鲜商品和通用社交电商食品内容的灵活基础模板。

#### 示例 1：爆米花

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="3">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/01/Input.jpg" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/01/Output-01.png" width="150"><br><sub>带货图 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-02.png" width="150"><br><sub>带货图 2</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-03.png" width="150"><br><sub>带货图 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/01/Output-04.png" width="150"><br><sub>带货图 4</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-05.png" width="150"><br><sub>带货图 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 示例 2：糖葫芦串

<table>
  <tr>
    <th width="20%">输入</th>
    <th colspan="2">输出</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/02/Input.webp" width="160"><br>
      <sub>商品原图</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/02/Output-01.png" width="200"><br><sub>带货图 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-02.png" width="200"><br><sub>带货图 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/02/Output-03.png" width="200"><br><sub>带货图 3</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-04.png" width="200"><br><sub>带货图 4</sub></td>
  </tr>
</table>

## 🚀 批量生成 · 调用 Evolink API

如果你需要在大量 SKU、多语言、多平台之间规模化生产电商素材，建议直接调用 **Evolink GPT Image 2 API**，而不是逐张手动生成。

**为什么用 API 跑批量：**

- 整盘 SKU 的电商主图一次性出图
- 一次任务搞定全部主图的多语言版本翻译
- 程序化模特替换、背景替换、多角度出图
- Webhook 回调可直接对接 PIM、ERP 或营销自动化系统

**前置条件：** [获取 API Key](https://evolink.ai/dashboard/keys)。

### 步骤 1：提交生成任务

GPT Image 2 是**异步任务**——接口返回 `task_id`，需要轮询任务详情拿到结果。

```bash
curl -X POST https://api.evolink.ai/v1/images/generations \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-image-2",
    "prompt": "帮我生成一组Amazon套图，售卖到美国，英文，这款商品为实木餐椅，卖点是稳固框架、人体工学椅背、易组装",
    "image_urls": ["https://your-cdn.example.com/products/chair.jpg"],
    "size": "1:1",
    "resolution": "2K",
    "quality": "high",
    "n": 4
  }'
```

| 字段 | 是否必填 | 说明 |
| :--- | :--- | :--- |
| `model` | 必填 | 固定为 `"gpt-image-2"` |
| `prompt` | 必填 | 最长 32,000 字符——直接复制本仓库任意 case 的提示词即可 |
| `image_urls` | 可选 | 1–16 张参考图（jpeg/png/webp，单张 ≤50 MB），用于图生图与编辑场景 |
| `size` | 可选 | 比例（`1:1`、`2:3`、`16:9` …）或像素尺寸；默认 `auto` |
| `resolution` | 可选 | `1K`、`2K`、`4K`，配合比例使用 |
| `quality` | 可选 | `low` / `medium` / `high`，影响计费；默认 `medium` |
| `n` | 可选 | 单次生成 1–10 张 |
| `callback_url` | 可选 | HTTPS Webhook 地址，任务完成后回调，无需轮询 |

### 步骤 2：轮询任务结果

```bash
curl https://api.evolink.ai/v1/tasks/{task_id} \
  -H "Authorization: Bearer YOUR_API_KEY"
```

当 `status` 变为 `"completed"` 时，`results` 数组里就是生成的图片 URL。**生成的图片仅 24 小时内有效，请尽快下载留存。**

### 可选：Webhook 回调

在提交任务时传入 `"callback_url": "https://your-server.example.com/webhook"`，Evolink 会在任务完成后 POST 结果到你指定的接口，无需轮询。

**完整 API 文档：** [docs.evolink.ai · GPT Image 2 image generation](https://docs.evolink.ai/en/api-manual/image-series/gpt-image-2/gpt-image-2-image-generation)

## 🙏 致谢

本仓库的灵感来源于优秀的开源提示词合集和社区分享的电商工作流。

感谢公开分享作品并促成这些案例研究的创作者和贡献者。

- [@EvoLinkAI](https://github.com/EvoLinkAI)

*我们无法保证每个案例都归属于原始创作者。如有需要更正之处，请联系我们，我们会及时更新。*

如果你有更多有趣的提示词案例想要分享，欢迎联系我们，帮助我们扩展 Evolink 提示词库。

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/gpt-image-2-for-e-commerce&type=Date)](https://www.star-history.com/#EvoLinkAI/gpt-image-2-for-e-commerce&Date)
