<div align="center">

<a href="https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce"><img src="images/logo.jpg" alt="gpt-image-2-for-e-commerce logo"></a>

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)
[![Website](https://img.shields.io/badge/Website-Live-orange)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)
[![Docs](https://img.shields.io/badge/Docs-Read-blue)](https://docs.evolink.ai)
[![Model](https://img.shields.io/badge/Model-Explore-purple)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)

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

# How to Use GPT Image 2 for E-commerce

> A prompt cookbook for creating e-commerce images with **GPT Image 2** — listing photos, model try-on, product showcases, interaction scenes, and social commerce creatives.

## 🍌 Introduction

This repository shows you **how to use GPT Image 2 to create e-commerce images** — listing photos, multi-country main images, A+ detail visuals, model try-on, product showcases, interaction scenes, and social commerce creatives — at production scale.

**Every case below is a recipe:** an input product photo, the exact prompt to paste into GPT Image 2, and real output examples. Replace the `{placeholders}` with your product, language, country, and selling points.

Need to run hundreds of SKUs at once? Jump to [🚀 Batch Generation via Evolink API](#-batch-generation-via-evolink-api).

Try it on Evolink: [GPT Image 2 workflow](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce)

If you find it useful, please give us a Star ⭐

> [!NOTE]
> This repository focuses on reusable prompt templates for ecommerce creatives. Replace the placeholders inside curly braces before use, and adjust to fit your actual platform, market, language, product, material, model type, and selling points.

<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://docs.evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce'><img src='https://img.shields.io/badge/🤗 Dataset-Evolink-yellow' height="25"></a>

## ⚡ Quick Start

1. **Pick a case** below that matches your e-commerce goal (listing main image, model try-on, multi-angle product, A+ detail visuals, etc.).
2. **Upload your product photo** and **copy the prompt** from that case — replace `{placeholders}` with your product, language, country, platform, and selling points.
3. **Run it on GPT Image 2** — either through the [Evolink workflow UI](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=gpt-image-2-for-e-commerce) for one-off creatives, or via the [Evolink API](#-batch-generation-via-evolink-api) for bulk SKUs and multi-language rollouts.

## 📰 News

- **May 7, 2026:** Repositioned the prompt library around **GPT Image 2 for e-commerce**, with a Quick Start and a Batch Generation via Evolink API section.
- **May 5, 2026:** Expanded the listing image, model try-on, and product showcase categories to align with the full set of ecommerce agent prompt patterns.
- **April 30, 2026:** Added complete prompt categories for listing images, model editing, product showcases, interaction scenes, and social commerce creatives.
- **April 30, 2026:** First English-first repository scaffold for ecommerce image prompt workflows.

## 📑 Menu

- [🍌 Introduction](#-introduction)
- [⚡ Quick Start](#-quick-start)
- [📰 News](#-news)
- [📑 Menu](#-menu)
- [🖼️ Ecommerce Listing Image Prompts](#️-ecommerce-listing-image-prompts)
  - [Case 1: Marketplace Listing Image Set](#case-1-marketplace-listing-image-set)
  - [Case 2: Multi-Country Listing Image Set](#case-2-multi-country-listing-image-set)
  - [Case 3: A+ Product Detail Visuals](#case-3-a-product-detail-visuals)
  - [Case 4: Bulk Amazon Listing Generation](#case-4-bulk-amazon-listing-generation)
  - [Case 5: Bulk Product Main Image Replacement](#case-5-bulk-product-main-image-replacement)
  - [Case 6: Bulk Listing Translation](#case-6-bulk-listing-translation)
- [👗 Model Try-On and Apparel Prompts](#-model-try-on-and-apparel-prompts)
  - [Case 1: Apparel Try-On Image Set](#case-1-apparel-try-on-image-set)
  - [Case 2: Model and Pet Try-On](#case-2-model-and-pet-try-on)
  - [Case 3: Model Pose Expansion](#case-3-model-pose-expansion)
  - [Case 4: Model Swap with Appearance Control](#case-4-model-swap-with-appearance-control)
  - [Case 5: Reference-Based Model Replacement](#case-5-reference-based-model-replacement)
  - [Case 6: Background Concepts for Apparel Sales](#case-6-background-concepts-for-apparel-sales)
  - [Case 7: Accessory Try-On](#case-7-accessory-try-on)
  - [Case 8: Nail Application](#case-8-nail-application)
  - [Case 9: Model Shoe Try-On](#case-9-model-shoe-try-on)
- [📦 Product Showcase Prompts](#-product-showcase-prompts)
  - [Case 1: Clean White Background Product Retouch](#case-1-clean-white-background-product-retouch)
  - [Case 2: Multi-Angle Product Views](#case-2-multi-angle-product-views)
  - [Case 3: Material and Color Variants](#case-3-material-and-color-variants)
  - [Case 4: Smart Background Generation](#case-4-smart-background-generation)
  - [Case 5: Background Replacement with Custom Description](#case-5-background-replacement-with-custom-description)
  - [Case 6: Reference-Based Product Background](#case-6-reference-based-product-background)
- [🤝 Product Interaction Prompts](#-product-interaction-prompts)
  - [Case 1: Handheld Product Close-Up](#case-1-handheld-product-close-up)
  - [Case 2: Generated Human Interaction Scene](#case-2-generated-human-interaction-scene)
  - [Case 3: Reference Character Product Interaction](#case-3-reference-character-product-interaction)
  - [Case 4: Pet and Product Interaction](#case-4-pet-and-product-interaction)
- [🛍️ Social Commerce Prompts](#️-social-commerce-prompts)
  - [Case 1: Fashion Studio Sales Set](#case-1-fashion-studio-sales-set)
  - [Case 2: Mirror Outfit Sales Video](#case-2-mirror-outfit-sales-video)
  - [Case 3: Gift Box Styling for Apparel](#case-3-gift-box-styling-for-apparel)
  - [Case 4: Fresh Food Sales Scene Set](#case-4-fresh-food-sales-scene-set)
  - [Case 5: General Food Sales Creative Set](#case-5-general-food-sales-creative-set)
- [🚀 Batch Generation via Evolink API](#-batch-generation-via-evolink-api)
- [🙏 Acknowledge](#-acknowledge)

## 🖼️ Ecommerce Listing Image Prompts

### Case 1: Marketplace Listing Image Set

**Prompt:**

```
Generate a {platform} listing image set for {country} in {language}. The product is {product_name}, and the selling points are {selling_points}.
```

> [!NOTE]
> **Replace {platform}, {country}, {language}, {product_name}, and {selling_points} before use.** This template fits Amazon, eBay, AliExpress, TEMU, SHEIN, TikTok Shop, Shopee, Lazada, Mercado Libre, Walmart, Etsy, Rakuten, Coupang, Shopify, and similar marketplaces. The agent will plan platform-appropriate listing assets such as clean white-background images, size diagrams, multi-angle views, lifestyle scenes, selling-point images, and material details.

#### Example 1: Solid Wood Dining Chair

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="4">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/01/input.webp" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/01/output-01.png" width="150"><br><sub>Clean background main</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-02.png" width="150"><br><sub>Selling points</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-03.png" width="150"><br><sub>Size diagram</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-04.png" width="150"><br><sub>Multi-angle</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/01/output-05.png" width="150"><br><sub>Lifestyle scene</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-06.png" width="150"><br><sub>Usage scene</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-08.png" width="150"><br><sub>Material detail</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### Example 2: Sport Water Bottle

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/02/input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/02/output-01.png" width="150"><br><sub>Clean background main</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-02.png" width="150"><br><sub>Multi-angle</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-03.png" width="150"><br><sub>Selling points</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/02/output-04.png" width="150"><br><sub>Size diagram</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-05.png" width="150"><br><sub>Usage scene</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-06.png" width="150"><br><sub>Material detail</sub></td>
  </tr>
</table>

#### Example 3: Sport T-shirt

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="4">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/03/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/03/Output-01.png" width="150"><br><sub>Selling points</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-02.png" width="150"><br><sub>Product specs</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-03.png" width="150"><br><sub>Size chart</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-04.png" width="150"><br><sub>Multi-angle</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/03/Output-05.png" width="150"><br><sub>Usage scene</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-06.png" width="150"><br><sub>Material detail</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-07.png" width="150"><br><sub>Selling-point summary</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### Case 2: Multi-Country Listing Image Set

**Prompt:**

```
Generate a {platform} listing image set for {country} in {language}.
```

> [!NOTE]
> **Replace {platform}, {country}, and {language} before use.** Use this shorter pattern when you want the model to infer the best listing layout automatically.

#### Example 1: Purple Polka-Dot Dress

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/01/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ar.png" width="150"><br><sub>Arabic</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Cn.png" width="150"><br><sub>Chinese</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-En.png" width="150"><br><sub>English</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ja.png" width="150"><br><sub>Japanese</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Kr.png" width="150"><br><sub>Korean</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Pt.png" width="150"><br><sub>Portuguese</sub></td>
  </tr>
</table>

#### Example 2: Cordless Vacuum

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/02/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Bn.png" width="150"><br><sub>Bengali</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-De.png" width="150"><br><sub>German</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Es%20.png" width="150"><br><sub>Spanish</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/02/Output-Fr.png" width="150"><br><sub>French</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Hi.png" width="150"><br><sub>Hindi</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Ru.png" width="150"><br><sub>Russian</sub></td>
  </tr>
</table>

#### Example 3: Christmas-Theme Phone Case

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/03/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Id.png" width="150"><br><sub>Indonesian</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-It.png" width="150"><br><sub>Italian</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Nl.png" width="150"><br><sub>Dutch</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/03/Output-Th.png" width="150"><br><sub>Thai</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Tr.png" width="150"><br><sub>Turkish</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Vi.png" width="150"><br><sub>Vietnamese</sub></td>
  </tr>
</table>

### Case 3: A+ Product Detail Visuals

**Prompt:**

```
This is a {product_description}. Generate A+ detail visuals for {country} in {language}.
```

> [!NOTE]
> **Replace {product_description}, {country}, and {language} before use.** Example: "This is a box of coffee beans. Generate A+ detail visuals for the US in English." Useful for product storytelling, feature breakdowns, usage scenes, and premium detail-page layouts.

#### Example 1: Premium Tea Gift Box

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/01/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/01/Output-01.png" width="150"><br><sub>Hero (selling points)</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-02.png" width="150"><br><sub>Design & craft</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-03.png" width="150"><br><sub>Product line</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/01/Output-04.png" width="150"><br><sub>Usage guide</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-05.png" width="150"><br><sub>Gifting scene</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-06.png" width="150"><br><sub>Usage scene</sub></td>
  </tr>
</table>

#### Example 2: Natural Glue Stick

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/02/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/02/Output-01.png" width="150"><br><sub>A+ hero</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-02.png" width="150"><br><sub>A+ detail 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-03.png" width="150"><br><sub>A+ detail 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/02/Output-04.png" width="150"><br><sub>A+ detail 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-05.png" width="150"><br><sub>A+ detail 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-06.png" width="150"><br><sub>A+ summary</sub></td>
  </tr>
</table>

#### Example 3: Bubble Tea Drink

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/03/Input.png" width="160" alt="Original product"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/03/Output-01.png" width="150"><br><sub>A+ hero</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-02.png" width="150"><br><sub>A+ detail 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-03.png" width="150"><br><sub>A+ detail 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/03/Output-04.png" width="150"><br><sub>A+ detail 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-05.png" width="150"><br><sub>A+ detail 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-06.png" width="150"><br><sub>A+ summary</sub></td>
  </tr>
</table>

### Case 4: Bulk Amazon Listing Generation

> [!NOTE]
> Use this when you need to generate listings in bulk across multiple SKUs of the same category. Per-language batch runs are not yet supported.

### Case 5: Bulk Product Main Image Replacement

**Input:** Upload the source product image and the target listing image set.

**Prompt:**

```
Replace the product in image 1 across images 2–7. Only the swapped product changes; keep everything else identical.
```

> [!NOTE]
> One-shot recreation of a viral listing — swap the product without redesigning the layout. Useful when many SKUs reuse the same creative style.

#### Example 1: Globe Ambient Lamp (swapped into the mushroom-lamp viral set)

<table>
  <tr>
    <th width="14%">Source product</th>
    <th colspan="6">Viral listing set (to be replaced)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/01/Input-01.png" width="120"><br>
      <sub>Globe ambient lamp</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/01/Input-02.png" width="110"><br><sub>Original main 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-03.png" width="110"><br><sub>Original main 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-04.png" width="110"><br><sub>Original main 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-05.png" width="110"><br><sub>Original main 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-06.png" width="110"><br><sub>Original main 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-07.png" width="110"><br><sub>Original main 6</sub></td>
  </tr>
  <tr>
    <th colspan="6">Replaced listing set</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/01/Output-02.png" width="110"><br><sub>Replaced 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-03.png" width="110"><br><sub>Replaced 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-04.png" width="110"><br><sub>Replaced 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-05.png" width="110"><br><sub>Replaced 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-06.png" width="110"><br><sub>Replaced 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-07.png" width="110"><br><sub>Replaced 6</sub></td>
  </tr>
</table>

#### Example 2: Wooden Bedside Table (swapped into the red cabinet viral set)

<table>
  <tr>
    <th width="14%">Source product</th>
    <th colspan="4">Viral listing set (to be replaced)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/02/Input.png" width="120"><br>
      <sub>Wooden bedside table</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/02/Input-01.png" width="120"><br><sub>Original main 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-02.png" width="120"><br><sub>Original main 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-03.png" width="120"><br><sub>Original main 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-04.png" width="120"><br><sub>Original main 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Replaced listing set</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/02/Output-01.png" width="120"><br><sub>Replaced 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-02.png" width="120"><br><sub>Replaced 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-03.png" width="120"><br><sub>Replaced 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-04.png" width="120"><br><sub>Replaced 4</sub></td>
  </tr>
</table>

### Case 6: Bulk Listing Translation

**Input:** Upload all listing images that contain text.

**Prompt:**

```
Translate the text in all images into {target_language}.
```

> [!NOTE]
> **Replace {target_language} before use.** Example: "Translate the text in all images into English." Batch-translates listing copy across languages while preserving the original layout — perfect for one-click global rollout.

#### Example 1: Cabinet Listing (ZH → EN)

<table>
  <tr>
    <th colspan="4">Original</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Input-01.png" width="140"><br><sub>Original 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-02.png" width="140"><br><sub>Original 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-03.png" width="140"><br><sub>Original 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-04.png" width="140"><br><sub>Original 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Translated</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Output-01.png" width="140"><br><sub>Translated 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-02.png" width="140"><br><sub>Translated 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-03.png" width="140"><br><sub>Translated 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-04.png" width="140"><br><sub>Translated 4</sub></td>
  </tr>
</table>

#### Example 2: Cabinet Listing (multilingual batch translation)

<table>
  <tr>
    <th colspan="4">Original</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Input-01.png" width="140"><br><sub>Original 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-02.png" width="140"><br><sub>Original 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-03.png" width="140"><br><sub>Original 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-04.png" width="140"><br><sub>Original 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Translated</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Output-01.png" width="140"><br><sub>Translated 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-02.png" width="140"><br><sub>Translated 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-03.png" width="140"><br><sub>Translated 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-04.png" width="140"><br><sub>Translated 4</sub></td>
  </tr>
</table>

## 👗 Model Try-On and Apparel Prompts

### Case 1: Apparel Try-On Image Set

**Prompt:**

```
This is a {apparel_type}. Generate a try-on image set for {country}.
```

> [!NOTE]
> **Replace {apparel_type} and {country} before use.** Example: "This is a dress. Generate a try-on image set for the US." Works for dresses, tops, outerwear, kidswear, and any apparel category that needs commercial try-on display.

#### Example 1: Green Floral Dress

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/01/Input.png" width="160"><br>
      <sub>Clean background product</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/01/Output-1.png" width="150"><br><sub>Model front</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-2.png" width="150"><br><sub>Multi-angle</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-3.png" width="150"><br><sub>Detail close-up</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/01/Output-4.png" width="150"><br><sub>Full styling</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-5.png" width="150"><br><sub>Lifestyle scene</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-6.png" width="150"><br><sub>Alternate angle</sub></td>
  </tr>
</table>

#### Example 2: Indian Sari Traditional Dress

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/02/Input.png" width="160"><br>
      <sub>Clean background product</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/02/Output-01.png" width="150"><br><sub>Model front</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-02.png" width="150"><br><sub>Back / turn</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-03.png" width="150"><br><sub>Detail</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/02/Output-04.png" width="150"><br><sub>Full styling</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-05.png" width="150"><br><sub>Lifestyle scene</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-06.png" width="150"><br><sub>Alternate angle</sub></td>
  </tr>
</table>

### Case 2: Model and Pet Try-On

**Input:** Upload the apparel or accessory image.

**Prompt:**

```
Generate a model wearing this garment.
Generate a pet dog wearing this garment.
```

> [!NOTE]
> This template covers both human-model try-on and pet try-on, suitable for apparel, cosplay props, and pet fashion creatives that need to showcase the same garment on different subjects.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case8/01/Input.png" width="140"><br><sub>#LOVE printed tee</sub></td>
    <td align="center"><img src="e-commerce/Case8/01/Output-01.png" width="140"><br><sub>Male model wearing</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Input.jpg" width="140"><br><sub>Cycling tee</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Output-01.png" width="140"><br><sub>Male model wearing</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Input.webp" width="140"><br><sub>Half-zip knit</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Output-01.png" width="140"><br><sub>Female model wearing</sub></td>
  </tr>
</table>

### Case 3: Model Pose Expansion

**Input:** Upload the original model-with-apparel image.

**Prompt:**

```
Expand the model into more poses.
```

> [!NOTE]
> Generates side, 45° turn, walking, and other pose variations to enrich an apparel asset set without re-shooting.

#### Example 1: #LOVE Printed Tee

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="4">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/01/Input.png" width="160"><br>
      <sub>Original model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/01/Output-01.png" width="150"><br><sub>Front stance</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-02.png" width="150"><br><sub>Side</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-03.png" width="150"><br><sub>45° turn</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-04.png" width="150"><br><sub>Walking</sub></td>
  </tr>
</table>

#### Example 2: Grey Half-Zip Pullover

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="4">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/02/Input.png" width="160"><br>
      <sub>Original model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/02/Output-01.png" width="150"><br><sub>Front stance</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-02.png" width="150"><br><sub>Side</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-03.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-04.png" width="150"><br><sub>Walking</sub></td>
  </tr>
</table>

### Case 4: Model Swap with Appearance Control

**Input:** Upload the original model-with-apparel image.

**Prompt:**

```
Replace the model with a {ethnicity} model, {hair_description}, while keeping the outfit unchanged.
Replace the figure with a {ethnicity} model, {skin_tone} skin, {hair_color} hair, while keeping the outfit unchanged.
```

> [!NOTE]
> **Replace {ethnicity}, {hair_description}, {skin_tone}, and {hair_color} before use.** Example: "Replace the model with a Black model, dreadlocks hairstyle, while keeping the outfit unchanged" or "Replace the figure with a Caucasian female model, fair skin, blonde hair, while keeping the outfit unchanged." Helps you localize fashion creatives for different audiences without re-shooting.

#### Example 1: #LOVE Printed Tee

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/01/Input.png" width="160"><br>
      <sub>Original model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case10/01/Output-01.png" width="180"><br><sub>Swapped model v1</sub></td>
    <td align="center"><img src="e-commerce/Case10/01/Output-02.png" width="180"><br><sub>Swapped model v2</sub></td>
  </tr>
</table>

#### Example 2: Grey Half-Zip Pullover

<table>
  <tr>
    <th width="40%">Input</th>
    <th width="60%">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/02/Input.png" width="200"><br>
      <sub>Original model</sub>
    </td>
    <td align="center">
      <img src="e-commerce/Case10/02/Output-01.png" width="200"><br>
      <sub>Swapped model</sub>
    </td>
  </tr>
</table>

### Case 5: Reference-Based Model Replacement

**Input:** Upload the original model image and the reference model image.

**Prompt:**

```
Replace the model in image 1 with the model in image 2, keeping the same pose.
```

> [!NOTE]
> Use this when you want to lock a specific model identity across multiple creative assets while reusing the original outfit and pose.

#### Example 1: Female Model Swap

<table>
  <tr>
    <th>Original model</th>
    <th>Reference model</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/01/Input-01.jpg" width="180"><br><sub>Original model</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Input-02.png" width="180"><br><sub>Reference model</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Output.png" width="180"><br><sub>Swap result</sub></td>
  </tr>
</table>

#### Example 2: Male Model Swap

<table>
  <tr>
    <th>Original model</th>
    <th>Reference model</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/02/Input-01.jpeg" width="180"><br><sub>Original model</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Input-02.jpeg" width="180"><br><sub>Reference model</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Output.png" width="180"><br><sub>Swap result</sub></td>
  </tr>
</table>

### Case 6: Background Concepts for Apparel Sales

**Prompt:**

```
Generate suitable background images for {apparel_type} sales display. Provide several indoor and outdoor options to choose from.
```

> [!NOTE]
> **Replace {apparel_type} before use.** Example: "Generate suitable background images for kidswear sales display. Provide several indoor and outdoor options to choose from." Useful when you separate scene ideation from model generation in your workflow.

#### Example 1: Beige Knit Pullover

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/01/Input.jpeg" width="160"><br>
      <sub>Original model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/01/Output-01.png" width="150"><br><sub>Indoor minimal</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-02.png" width="150"><br><sub>Outdoor natural 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-03.png" width="150"><br><sub>Outdoor natural 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/01/Output-04.png" width="150"><br><sub>City street</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-05.png" width="150"><br><sub>At-home scene</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-06.png" width="150"><br><sub>Casual scene</sub></td>
  </tr>
</table>

#### Example 2: Dark Blue Cable Knit

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/02/Input.jpg" width="160"><br>
      <sub>Original model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/02/Output-01.png" width="150"><br><sub>Indoor scene 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-02.png" width="150"><br><sub>Outdoor scene 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-03.png" width="150"><br><sub>Outdoor scene 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/02/Output-04.png" width="150"><br><sub>City street</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-05.png" width="150"><br><sub>Home environment</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-06.png" width="150"><br><sub>Other scene</sub></td>
  </tr>
</table>

### Case 7: Accessory Try-On

**Input:** Upload the accessory product image.

**Prompt:**

```
A model wearing this {accessory_type}, {additional_requirements}.
```

> [!NOTE]
> **Replace {accessory_type} and {additional_requirements} before use.** Example: "A model wearing this necklace, face not shown" or "A model wearing these earrings." Works for necklaces, earrings, hats, scarves, and other wearable accessories.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case13/01/Input.png" width="180"><br><sub>Jade pendant necklace</sub></td>
    <td align="center"><img src="e-commerce/Case13/01/Output.png" width="180"><br><sub>Worn on model</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Input.jpg" width="180"><br><sub>Gold hoop earrings</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Output.png" width="180"><br><sub>Worn on model</sub></td>
  </tr>
</table>

### Case 8: Nail Application

**Input:** Upload the nail design reference image.

**Prompt:**

```
Apply these nails to hands.
```

> [!NOTE]
> Useful for press-on nails, gel-polish concepts, salon design previews, and nail product marketing creatives.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case14/01/Input.jpg" width="180"><br><sub>Pink nail samples</sub></td>
    <td align="center"><img src="e-commerce/Case14/01/Output-01.png" width="180"><br><sub>Applied to hand</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Input.jpg" width="180"><br><sub>Multi-color nail samples</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Output-01.png" width="180"><br><sub>Applied to hand</sub></td>
  </tr>
</table>

### Case 9: Model Shoe Try-On

**Input:** Upload the shoe product image.

**Prompt:**

```
A model wearing the shoes from the image, {styling_description}.
```

> [!NOTE]
> **Replace {styling_description} before use.** Example: "A model wearing the shoes from the image, with a brown short skirt." Works for sneakers, heels, boots, and seasonal footwear creatives.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case15/01/Input.jpg" width="180"><br><sub>Black leather shoes</sub></td>
    <td align="center"><img src="e-commerce/Case15/01/Output-01.png" width="180"><br><sub>Male styling</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Input.jpg" width="180"><br><sub>Black high heels</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Output-01.png" width="180"><br><sub>Female styling</sub></td>
  </tr>
</table>

## 📦 Product Showcase Prompts

### Case 1: Clean White Background Product Retouch

**Input:** Upload a high-quality product photo.

**Prompt:**

```
Generate a clean white-background retouched image.
```

> [!NOTE]
> The better the source quality, the more accurate the result. High-quality inputs typically yield more faithful product preservation and cleaner ecommerce-grade output.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case16/01/Input.png" width="180"><br><sub>In-scene product photo</sub></td>
    <td align="center"><img src="e-commerce/Case16/01/Output-01.png" width="180"><br><sub>White-background retouch</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/images.jpeg" width="180"><br><sub>Raw product photo</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/Output-01.png" width="180"><br><sub>White-background retouch</sub></td>
  </tr>
</table>

### Case 2: Multi-Angle Product Views

**Input:** Upload the product reference image.

**Prompt:**

```
Generate multi-angle product images.
```

> [!NOTE]
> Useful for product cards, carousels, feature breakdowns, and angle-specific detail pages.

#### Example 1: Tan Hiking Boots

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/01/Input.png" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/01/Output-01.png" width="150"><br><sub>Front</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-02.png" width="150"><br><sub>45° side</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-03.png" width="150"><br><sub>Back</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/01/Output-04.png" width="150"><br><sub>Sole</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-05.png" width="150"><br><sub>Top-down</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-06.png" width="150"><br><sub>Other angle</sub></td>
  </tr>
</table>

#### Example 2: Hiking Boots (alternate model)

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/02/Input.png" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/02/Output-01.png" width="150"><br><sub>Front</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-02.png" width="150"><br><sub>Side</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-03.png" width="150"><br><sub>Back</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/02/Output-04.png" width="150"><br><sub>Sole detail</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-05.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-06.png" width="150"><br><sub>Alt angle</sub></td>
  </tr>
</table>

### Case 3: Material and Color Variants

**Input:** Upload the product or apparel image to edit.

**Prompt:**

```
Modify the material. Change the figure's clothing into: {material1}, {material2}, and {material3}.
```

> [!NOTE]
> **Replace {material1}, {material2}, and {material3} before use.** Example: "Modify the material. Change the figure's clothing into: light grey suede, dark brown denim, and burgundy corduroy." Works for fabric replacement, material testing, seasonal recoloring, and concept exploration.

#### Example 1: Green Jacket Material Variants

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/01/Input.jpg" width="160"><br>
      <sub>Original male model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/01/Output-01.png" width="150"><br><sub>Variant 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-02.png" width="150"><br><sub>Variant 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-03.png" width="150"><br><sub>Variant 3</sub></td>
  </tr>
</table>

#### Example 2: Black Leather Jacket Material Variants

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/02/Input.avif" width="160"><br>
      <sub>Original male model</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/02/Output-01.png" width="150"><br><sub>Variant 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-02.png" width="150"><br><sub>Variant 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-03.png" width="150"><br><sub>Variant 3</sub></td>
  </tr>
</table>

### Case 4: Smart Background Generation

**Input:** Upload the product image.

**Prompt:**

```
Generate suitable product images.
```

> [!NOTE]
> Use this when you want the model to infer the most fitting commercial product backgrounds without detailed art direction.

#### Example 1: Snack Box

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/01/Input.webp" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/01/Output-01.png" width="200"><br><sub>Smart background 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-02.png" width="200"><br><sub>Smart background 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/01/Output-03.png" width="200"><br><sub>Smart background 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-04.png" width="200"><br><sub>Smart background 4</sub></td>
  </tr>
</table>

#### Example 2: Skincare Serum

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/02/Input.jpg" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/02/Output-01.png" width="200"><br><sub>Smart background 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-02.png" width="200"><br><sub>Smart background 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/02/Output-03.png" width="200"><br><sub>Smart background 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-04.png" width="200"><br><sub>Smart background 4</sub></td>
  </tr>
</table>

### Case 5: Background Replacement with Custom Description

**Input:** Upload the product image.

**Prompt:**

```
Replace the background of the product in the image: {background_description}.
```

> [!NOTE]
> **Replace {background_description} before use.** Example: "Replace the background of the product in the image: a close-up of the perfume bottle resting on a smooth white stone, surrounded by soft white and pale-blue flowers, with a calm blue lake and clear-sky mountains in the distance — fresh, airy, and slightly cool aesthetic." Useful when you want full art direction over the new scene.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case20/01/Input.png" width="180"><br><sub>Product photo</sub></td>
    <td align="center"><img src="e-commerce/Case20/01/Output-01.png" width="180"><br><sub>Custom-described background</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Input.jpg" width="180"><br><sub>Product photo</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Output-01.png" width="180"><br><sub>Custom-described background</sub></td>
  </tr>
</table>

### Case 6: Reference-Based Product Background

**Input:** Upload the product image and a reference background image.

**Prompt:**

```
Image 1 is my {product}. Generate the new scene using the background style from image 2.
```

> [!NOTE]
> **Replace {product} before use.** Example: "Image 1 is my ring. Generate the new scene using the background style from image 2." Useful for aesthetic matching, brand consistency, and category-specific visual references.

#### Example 1: Pink Retro Car

<table>
  <tr>
    <th>Product</th>
    <th>Reference background</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/01/Input-01.jpg" width="180"><br><sub>Pink retro car</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Input-02.jpg" width="180"><br><sub>Green forest reference</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Output.png" width="180"><br><sub>Forest tabletop comp</sub></td>
  </tr>
</table>

#### Example 2: Red Lipstick

<table>
  <tr>
    <th>Product</th>
    <th>Reference background</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/02/Input-01.jpg" width="180"><br><sub>Red lipstick</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Input-02.jpg" width="180"><br><sub>Black-gold marble reference</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Output.png" width="180"><br><sub>Marble tabletop comp</sub></td>
  </tr>
</table>

## 🤝 Product Interaction Prompts

### Case 1: Handheld Product Close-Up

**Input:** Upload the product image.

**Prompt:**

```
A hand is holding this product, {scene_description}, keep the product color unchanged.
{action_description}
```

> [!NOTE]
> **Replace {scene_description} and {action_description} before use.** Example: "A hand is holding this product, fashion editorial backdrop, keep the product color unchanged" or "Hand holding an electric drill, drilling into wood." Works for beauty, tools, gadgets, packaged goods, and tactile product demos.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case22/01/Input.jpg" width="180"><br><sub>Pink lip gloss</sub></td>
    <td align="center"><img src="e-commerce/Case22/01/Output.png" width="180"><br><sub>Hand-held lip gloss close-up</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Input.avif" width="180"><br><sub>Wooden-handle mop</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Output.png" width="180"><br><sub>Hand-held mop cleaning floor</sub></td>
  </tr>
</table>

### Case 2: Generated Human Interaction Scene

**Input:** Upload the product scene or product image.

**Prompt:**

```
Add a human model to this product scene. The model should be {person_description}, in a {pose}, performing {action}.
```

> [!NOTE]
> **Replace {person_description}, {pose}, and {action} before use.** Example: "Add a human model to this product scene. The model should be a young girl, standing pose, holding a doll" or "Add a human model to this product scene, holding a mop." Useful for showcasing scale, usage, emotion, and audience fit.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case23/01/Input.jpg" width="180"><br><sub>CNY red arch scene</sub></td>
    <td align="center"><img src="e-commerce/Case23/01/Output-01.png" width="180"><br><sub>Qipao model entering</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Input.webp" width="180"><br><sub>Red & silver headphones</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Output.png" width="180"><br><sub>Female model wearing headphones</sub></td>
  </tr>
</table>

### Case 3: Reference Character Product Interaction

**Input:** Upload the product scene image and a reference character image.

**Prompt:**

```
Add the human model from image 2 into the product scene from image 1, with this action: {action_description}.
```

> [!NOTE]
> **Replace {action_description} before use.** Example: "Add the human model from image 2 into the product scene from image 1, with this action: model lying on the bed." Useful when you need consistent character identity across multiple creative assets.

#### Example 1: Bedroom King-Size Scene + Male Model

<table>
  <tr>
    <th>Product scene</th>
    <th>Reference character</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/01/Input-01.webp" width="180"><br><sub>Bedroom king-size scene</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Input-02.jpg" width="180"><br><sub>Male model in white tee</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Output.png" width="180"><br><sub>Male model reclining on bed</sub></td>
  </tr>
</table>

#### Example 2: Home Rocking-Chair Scene + Male Model

<table>
  <tr>
    <th>Product scene</th>
    <th>Reference character</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/02/Input-01.jpg" width="180"><br><sub>Home rocking-chair scene</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Input-02.jpg" width="180"><br><sub>Male model in white shirt</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Output.png" width="180"><br><sub>Male model in rocking chair</sub></td>
  </tr>
</table>

### Case 4: Pet and Product Interaction

**Input:** Upload the product image.

**Prompt:**

```
Generate a {pet} interacting with the {product} from the image.
```

> [!NOTE]
> **Replace {pet} and {product} before use.** Example: "Generate a cat interacting with the toy from the image" or "Generate a puppy interacting with the toy from the image." Especially useful for toy, pet accessory, home, and playful lifestyle product creatives.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case25/01/Input.jpg" width="180"><br><sub>Orange dog chew ball</sub></td>
    <td align="center"><img src="e-commerce/Case25/01/Output.png" width="180"><br><sub>Puppy biting ball</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Input.jpg" width="180"><br><sub>Hamster wheel</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Output.png" width="180"><br><sub>Hamster in wheel</sub></td>
  </tr>
</table>

## 🛍️ Social Commerce Prompts

### Case 1: Fashion Studio Sales Set

**Prompt:**

```
Generate a model sales image set, background is a fashion studio.
```

> [!NOTE]
> Useful for showroom-style apparel marketing, boutique visual merchandising, and studio-shoot social content.

#### Example 1: Blue Hoodie

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/01/Input.png" width="160"><br>
      <sub>Clean background product</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/01/Output-01.png" width="200"><br><sub>Studio shoot 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-02.png" width="200"><br><sub>Studio shoot 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/01/Output-03.png" width="200"><br><sub>Studio shoot 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-04.png" width="200"><br><sub>Studio shoot 4</sub></td>
  </tr>
</table>

#### Example 2: Pink Floral Dress

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/02/Input.webp" width="160"><br>
      <sub>Clean background product</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/02/Output-01.png" width="200"><br><sub>Studio shoot 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-02.png" width="200"><br><sub>Studio shoot 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/02/Output-03.png" width="200"><br><sub>Studio shoot 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-04.png" width="200"><br><sub>Studio shoot 4</sub></td>
  </tr>
</table>

### Case 2: Mirror Outfit Sales Video

**Prompt:**

```
Generate a mirror outfit sales video.
```

> [!NOTE]
> This template is ideal for creator-style fashion content, UGC aesthetics, and casual social-commerce sales formats.

### Case 3: Gift Box Styling for Apparel

**Input:** Upload the apparel image.

**Prompt:**

```
Place the apparel into a gift box.
```

> [!NOTE]
> Useful for holiday gift marketing, premium packaging mockups, and seasonal-themed product creatives.

<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case33/01/Input.jpg" width="180"><br><sub>Color-splatter tee</sub></td>
    <td align="center"><img src="e-commerce/Case33/01/Output.png" width="180"><br><sub>Gift box result</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Input.jpg" width="180"><br><sub>Red kids' down jacket</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Output.png" width="180"><br><sub>Gift box result</sub></td>
  </tr>
</table>

### Case 4: Fresh Food Sales Scene Set

**Prompt:**

```
Generate a fresh-food scene set for {food_name}.
```

> [!NOTE]
> **Replace {food_name} before use.** Example: "Generate a fresh-food scene set for pomelo." Useful for fruits, agricultural produce, boxed foods, specialty ingredients, and premium fresh-food displays.

#### Example 1: Watermelon

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/01/Input.webp" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/01/Output-01.png" width="200"><br><sub>Fresh-food scene 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-02.png" width="200"><br><sub>Fresh-food scene 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/01/Output-03.png" width="200"><br><sub>Fresh-food scene 3</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-04.png" width="200"><br><sub>Fresh-food scene 4</sub></td>
  </tr>
</table>

#### Example 2: Grapes

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/02/Input.jpg" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/02/Output-01.png" width="150"><br><sub>Fresh-food scene 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-02.png" width="150"><br><sub>Fresh-food scene 2</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-03.png" width="150"><br><sub>Fresh-food scene 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/02/Output-04.png" width="150"><br><sub>Fresh-food scene 4</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-05.png" width="150"><br><sub>Fresh-food scene 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### Case 5: General Food Sales Creative Set

**Prompt:**

```
Generate a food sales image set.
```

> [!NOTE]
> A flexible base template for snack brands, packaged foods, fresh-food products, and general social-commerce food content.

#### Example 1: Popcorn

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="3">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/01/Input.jpg" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/01/Output-01.png" width="150"><br><sub>Sales image 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-02.png" width="150"><br><sub>Sales image 2</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-03.png" width="150"><br><sub>Sales image 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/01/Output-04.png" width="150"><br><sub>Sales image 4</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-05.png" width="150"><br><sub>Sales image 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### Example 2: Candied Fruit Skewers

<table>
  <tr>
    <th width="20%">Input</th>
    <th colspan="2">Output</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/02/Input.webp" width="160"><br>
      <sub>Product photo</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/02/Output-01.png" width="200"><br><sub>Sales image 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-02.png" width="200"><br><sub>Sales image 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/02/Output-03.png" width="200"><br><sub>Sales image 3</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-04.png" width="200"><br><sub>Sales image 4</sub></td>
  </tr>
</table>

## 🚀 Batch Generation via Evolink API

For production runs across hundreds of SKUs, multiple languages, or multiple marketplaces, call the **Evolink GPT Image 2 API** directly instead of running prompts one by one.

**Why batch via API:**

- Bulk listing image generation for an entire catalog
- Multilingual translation of all listing assets in a single job
- Programmatic model swap, background replacement, multi-angle output
- Webhook callbacks integrate with your PIM, ERP, or marketing automation

**Prerequisites:** [Get an API key](https://evolink.ai/dashboard/keys).

### Step 1: Submit a generation task

GPT Image 2 generation is **asynchronous** — the call returns a `task_id` that you poll for results.

```bash
curl -X POST https://api.evolink.ai/v1/images/generations \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gpt-image-2",
    "prompt": "Generate an Amazon listing image set for the US in English. The product is a solid wood dining chair, and the selling points are sturdy frame, ergonomic backrest, easy assembly.",
    "image_urls": ["https://your-cdn.example.com/products/chair.jpg"],
    "size": "1:1",
    "resolution": "2K",
    "quality": "high",
    "n": 4
  }'
```

| Field | Required | Notes |
| :--- | :--- | :--- |
| `model` | yes | Must be `"gpt-image-2"` |
| `prompt` | yes | Up to 32,000 characters — paste the prompt from any case in this repo |
| `image_urls` | optional | 1–16 input/reference images (jpeg/png/webp, ≤50 MB each) for image-to-image and editing tasks |
| `size` | optional | Aspect ratio (`1:1`, `2:3`, `16:9`, …) or pixel dimensions; defaults to `auto` |
| `resolution` | optional | `1K`, `2K`, or `4K` when `size` is a ratio |
| `quality` | optional | `low`, `medium`, `high` — affects cost; defaults to `medium` |
| `n` | optional | 1–10 images per call |
| `callback_url` | optional | HTTPS webhook to receive completion instead of polling |

### Step 2: Poll the task

```bash
curl https://api.evolink.ai/v1/tasks/{task_id} \
  -H "Authorization: Bearer YOUR_API_KEY"
```

When `status` becomes `"completed"`, the `results` array contains the generated image URLs. **Generated images are valid for 24 hours — download them promptly.**

### Optional: webhook callback

Pass `"callback_url": "https://your-server.example.com/webhook"` in the submission, and Evolink will POST the task result to your endpoint when the task completes — no polling required.

**Full API reference:** [docs.evolink.ai · GPT Image 2 image generation](https://docs.evolink.ai/en/api-manual/image-series/gpt-image-2/gpt-image-2-image-generation)

## 🙏 Acknowledge

This repository is inspired by excellent open-source prompt collections and community-shared ecommerce workflows.

Thanks to all creators and contributors who openly share their work and make these case studies possible.

- [@EvoLinkAI](https://github.com/EvoLinkAI)

*We cannot guarantee that every case is attributed to its original creator. Please contact us if any correction is needed and we will update promptly.*

If you have more interesting prompt cases to share, feel free to reach out and help us extend the Evolink prompt library.

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/gpt-image-2-for-e-commerce&type=Date)](https://www.star-history.com/#EvoLinkAI/gpt-image-2-for-e-commerce&Date)
