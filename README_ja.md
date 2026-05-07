<div align="center">

<img src="images/logo.jpg" alt="awesome-ecommerce-image-prompts logo">

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](LICENSE)
[![Try it on Evolink](https://img.shields.io/badge/Try_it_on-Evolink-black)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)
[![Website](https://img.shields.io/badge/Website-Live-orange)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)
[![Docs](https://img.shields.io/badge/Docs-Read-blue)](https://docs.evolink.ai)
[![Model](https://img.shields.io/badge/Model-Explore-purple)](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)

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

# GPT Image 2でEコマース画像を作る方法

> **GPT Image 2** でEコマース画像を作るためのプロンプト・レシピ集——商品メイン画像、モデル試着、商品ショーケース、インタラクションシーン、ソーシャルコマース・クリエイティブを網羅。

## 🍌 はじめに

このリポジトリでは、**GPT Image 2 を使って Eコマース画像を作る方法** を実例で解説します——商品メイン画像、多国向けローカライズ、A+ 詳細ビジュアル、モデル試着、商品ショーケース、インタラクションシーン、ソーシャルコマース・クリエイティブまで本番運用レベルで対応。

**各ケースはレシピ形式です：** 入力する商品画像、GPT Image 2 にそのまま貼り付けるプロンプト、実際の出力例の3点セット。`{プレースホルダー}` を自分の商品・言語・国・セールスポイントに置き換えるだけ。

数百 SKU を一括処理したい方は [🚀 Evolink API による一括生成](#-evolink-api-による一括生成) へ。

Evolink で試す：[GPT Image 2 ワークフロー](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)

役に立ったら Star ⭐ をお願いします

> [!NOTE]
> このリポジトリは再利用可能な Eコマース用プロンプトテンプレート集です。使用前に中括弧内のプレースホルダーを置き換え、実際のプラットフォーム・市場・言語・商品・素材・モデルタイプ・セールスポイントに合わせて調整してください。

<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://docs.evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🤗 Dataset-Evolink-yellow' height="25"></a>

## ⚡ クイックスタート

1. **目的に合うケースを選ぶ**——下記から自分の Eコマース目的に合うケース（メイン画像、モデル試着、多角度商品、A+ 詳細ビジュアルなど）を選択。
2. **商品画像をアップロードし、プロンプトをコピー**——ケースのプロンプトをコピーして、`{プレースホルダー}` を自分の商品・言語・国・プラットフォーム・セールスポイントに置換。
3. **GPT Image 2 で実行**——単発出力は [Evolink ワークフロー UI](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts) を、複数 SKU・多言語の一括処理は [Evolink API](#-evolink-api-による一括生成) を利用。

## 📰 更新履歴

- **2026年5月7日：** リポジトリを **GPT Image 2 for E-commerce** をテーマに再構成し、「クイックスタート」と「Evolink API による一括生成」セクションを追加。
- **2026年5月5日：** 電商 Agent プロンプトパターン全体に合わせて、メイン画像・モデル試着・商品ショーケースの3カテゴリを拡充。
- **2026年4月30日：** メイン画像・モデル編集・商品ショーケース・インタラクションシーン・ソーシャルコマース・クリエイティブの完全プロンプト分類を追加。
- **2026年4月30日：** Eコマース画像プロンプトワークフロー向けの英語ファースト・リポジトリ枠組みを最初に構築。

## 📑 目次

- [🍌 はじめに](#-はじめに)
- [⚡ クイックスタート](#-クイックスタート)
- [📰 更新履歴](#-更新履歴)
- [📑 目次](#-目次)
- [🖼️ Eコマース・メイン画像プロンプト](#️-eコマースメイン画像プロンプト)
  - [ケース 1：マーケットプレイス用メイン画像セット](#ケース-1マーケットプレイス用メイン画像セット)
  - [ケース 2：多国向けメイン画像セット](#ケース-2多国向けメイン画像セット)
  - [ケース 3：A+ 商品詳細ビジュアル](#ケース-3a-商品詳細ビジュアル)
  - [ケース 4：Amazon リスティング一括生成](#ケース-4amazon-リスティング一括生成)
  - [ケース 5：商品メイン画像の一括差し替え](#ケース-5商品メイン画像の一括差し替え)
  - [ケース 6：リスティング一括翻訳](#ケース-6リスティング一括翻訳)
- [👗 モデル試着・アパレル・プロンプト](#-モデル試着アパレルプロンプト)
  - [ケース 1：アパレル試着画像セット](#ケース-1アパレル試着画像セット)
  - [ケース 2：モデル＆ペット試着](#ケース-2モデルペット試着)
  - [ケース 3：モデルポーズ拡張](#ケース-3モデルポーズ拡張)
  - [ケース 4：外見制御付きモデル差し替え](#ケース-4外見制御付きモデル差し替え)
  - [ケース 5：参照モデル指定置換](#ケース-5参照モデル指定置換)
  - [ケース 6：アパレル販売用背景コンセプト](#ケース-6アパレル販売用背景コンセプト)
  - [ケース 7：アクセサリー試着](#ケース-7アクセサリー試着)
  - [ケース 8：ネイル装着](#ケース-8ネイル装着)
  - [ケース 9：モデル靴試着](#ケース-9モデル靴試着)
- [📦 商品ショーケース・プロンプト](#-商品ショーケースプロンプト)
  - [ケース 1：白背景商品レタッチ](#ケース-1白背景商品レタッチ)
  - [ケース 2：多角度商品ビュー](#ケース-2多角度商品ビュー)
  - [ケース 3：素材・カラー・バリエーション](#ケース-3素材カラーバリエーション)
  - [ケース 4：スマート背景生成](#ケース-4スマート背景生成)
  - [ケース 5：カスタム指定での背景差し替え](#ケース-5カスタム指定での背景差し替え)
  - [ケース 6：参照画像で商品背景生成](#ケース-6参照画像で商品背景生成)
- [🤝 商品インタラクション・プロンプト](#-商品インタラクションプロンプト)
  - [ケース 1：手持ち商品クローズアップ](#ケース-1手持ち商品クローズアップ)
  - [ケース 2：人物インタラクションシーン生成](#ケース-2人物インタラクションシーン生成)
  - [ケース 3：参照人物の商品インタラクション](#ケース-3参照人物の商品インタラクション)
  - [ケース 4：ペットと商品のインタラクション](#ケース-4ペットと商品のインタラクション)
- [🛍️ ソーシャルコマース・プロンプト](#️-ソーシャルコマースプロンプト)
  - [ケース 1：ファッションスタジオ販売セット](#ケース-1ファッションスタジオ販売セット)
  - [ケース 2：鏡越しコーデ販売動画](#ケース-2鏡越しコーデ販売動画)
  - [ケース 3：アパレルのギフトボックス演出](#ケース-3アパレルのギフトボックス演出)
  - [ケース 4：生鮮食品販売シーンセット](#ケース-4生鮮食品販売シーンセット)
  - [ケース 5：汎用フード販売クリエイティブセット](#ケース-5汎用フード販売クリエイティブセット)
- [🚀 Evolink API による一括生成](#-evolink-api-による一括生成)
- [🙏 謝辞](#-謝辞)

## 🖼️ Eコマース・メイン画像プロンプト

### ケース 1：マーケットプレイス用メイン画像セット

**プロンプト：**

```
Generate a {platform} listing image set for {country} in {language}. The product is {product_name}, and the selling points are {selling_points}.
```

> [!NOTE]
> **使用前に {platform}、{country}、{language}、{product_name}、{selling_points} を置き換えてください。** このテンプレートは Amazon、eBay、AliExpress、TEMU、SHEIN、TikTok Shop、Shopee、Lazada、Mercado Libre、Walmart、Etsy、Rakuten、Coupang、Shopify など主要マーケットプレイスに対応。エージェントが商品とプラットフォームの特性に応じて、白背景画像、サイズ図、多角度ビュー、ライフスタイル・シーン、セールスポイント画像、素材ディテールなどを自動構成します。

#### 例 1：無垢材ダイニングチェア

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="4">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/01/input.webp" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/01/output-01.png" width="150"><br><sub>白背景メイン</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-02.png" width="150"><br><sub>セールスポイント</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-03.png" width="150"><br><sub>サイズ図</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-04.png" width="150"><br><sub>多角度</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/01/output-05.png" width="150"><br><sub>ライフスタイル</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-06.png" width="150"><br><sub>使用シーン</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-08.png" width="150"><br><sub>素材ディテール</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 例 2：スポーツウォーターボトル

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/02/input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/02/output-01.png" width="150"><br><sub>白背景メイン</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-02.png" width="150"><br><sub>多角度</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-03.png" width="150"><br><sub>セールスポイント</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/02/output-04.png" width="150"><br><sub>サイズ図</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-05.png" width="150"><br><sub>使用シーン</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-06.png" width="150"><br><sub>素材ディテール</sub></td>
  </tr>
</table>

#### 例 3：スポーツ T シャツ

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="4">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/03/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/03/Output-01.png" width="150"><br><sub>セールスポイント</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-02.png" width="150"><br><sub>スペック</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-03.png" width="150"><br><sub>サイズ表</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-04.png" width="150"><br><sub>多角度</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/03/Output-05.png" width="150"><br><sub>使用シーン</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-06.png" width="150"><br><sub>素材ディテール</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-07.png" width="150"><br><sub>セールスポイント総括</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### ケース 2：多国向けメイン画像セット

**プロンプト：**

```
Generate a {platform} listing image set for {country} in {language}.
```

> [!NOTE]
> **使用前に {platform}、{country}、{language} を置き換えてください。** モデルに最適なメイン画像レイアウトを自動推論させたい場合に便利な短縮テンプレート。

#### 例 1：紫水玉ワンピース

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/01/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ar.png" width="150"><br><sub>アラビア語</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Cn.png" width="150"><br><sub>中国語</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-En.png" width="150"><br><sub>英語</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ja.png" width="150"><br><sub>日本語</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Kr.png" width="150"><br><sub>韓国語</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Pt.png" width="150"><br><sub>ポルトガル語</sub></td>
  </tr>
</table>

#### 例 2：コードレス掃除機

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/02/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Bn.png" width="150"><br><sub>ベンガル語</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-De.png" width="150"><br><sub>ドイツ語</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Es%20.png" width="150"><br><sub>スペイン語</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/02/Output-Fr.png" width="150"><br><sub>フランス語</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Hi.png" width="150"><br><sub>ヒンディー語</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Ru.png" width="150"><br><sub>ロシア語</sub></td>
  </tr>
</table>

#### 例 3：クリスマス柄スマホケース

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/03/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Id.png" width="150"><br><sub>インドネシア語</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-It.png" width="150"><br><sub>イタリア語</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Nl.png" width="150"><br><sub>オランダ語</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/03/Output-Th.png" width="150"><br><sub>タイ語</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Tr.png" width="150"><br><sub>トルコ語</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Vi.png" width="150"><br><sub>ベトナム語</sub></td>
  </tr>
</table>

### ケース 3：A+ 商品詳細ビジュアル

**プロンプト：**

```
This is a {product_description}. Generate A+ detail visuals for {country} in {language}.
```

> [!NOTE]
> **使用前に {product_description}、{country}、{language} を置き換えてください。** 例：「これはコーヒー豆のボックスです。アメリカ向けの A+ 詳細ビジュアルを英語で生成してください。」商品ストーリー、機能解説、使用シーン、プレミアム詳細ページのレイアウトに最適。

#### 例 1：高級茶ギフトボックス

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/01/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/01/Output-01.png" width="150"><br><sub>ヒーロー（セールス）</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-02.png" width="150"><br><sub>デザインと工芸</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-03.png" width="150"><br><sub>商品ライン</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/01/Output-04.png" width="150"><br><sub>使い方</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-05.png" width="150"><br><sub>ギフトシーン</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-06.png" width="150"><br><sub>使用シーン</sub></td>
  </tr>
</table>

#### 例 2：ナチュラル糊スティック

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/02/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/02/Output-01.png" width="150"><br><sub>A+ ヒーロー</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-02.png" width="150"><br><sub>A+ 詳細 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-03.png" width="150"><br><sub>A+ 詳細 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/02/Output-04.png" width="150"><br><sub>A+ 詳細 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-05.png" width="150"><br><sub>A+ 詳細 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-06.png" width="150"><br><sub>A+ 総括</sub></td>
  </tr>
</table>

#### 例 3：バブルティー

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/03/Input.png" width="160" alt="元商品"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/03/Output-01.png" width="150"><br><sub>A+ ヒーロー</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-02.png" width="150"><br><sub>A+ 詳細 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-03.png" width="150"><br><sub>A+ 詳細 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/03/Output-04.png" width="150"><br><sub>A+ 詳細 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-05.png" width="150"><br><sub>A+ 詳細 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-06.png" width="150"><br><sub>A+ 総括</sub></td>
  </tr>
</table>

### ケース 4：Amazon リスティング一括生成

> [!NOTE]
> 同一カテゴリの複数 SKU を一括生成したい場合に使用。言語別の一括実行は現時点では未対応。

### ケース 5：商品メイン画像の一括差し替え

**入力：** 元商品画像とターゲット・メイン画像セットをアップロード。

**プロンプト：**

```
Replace the product in image 1 across images 2–7. Only the swapped product changes; keep everything else identical.
```

> [!NOTE]
> 売れ筋メイン画像のワンショット複製——レイアウトはそのまま、商品だけを差し替え。複数 SKU が同じクリエイティブを再利用する場面に有効。

#### 例 1：球形アンビエントランプ（キノコランプの売れ筋セットへ差し替え）

<table>
  <tr>
    <th width="14%">元商品</th>
    <th colspan="6">売れ筋セット（差し替え対象）</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/01/Input-01.png" width="120"><br>
      <sub>球形アンビエントランプ</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/01/Input-02.png" width="110"><br><sub>元メイン 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-03.png" width="110"><br><sub>元メイン 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-04.png" width="110"><br><sub>元メイン 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-05.png" width="110"><br><sub>元メイン 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-06.png" width="110"><br><sub>元メイン 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-07.png" width="110"><br><sub>元メイン 6</sub></td>
  </tr>
  <tr>
    <th colspan="6">差し替え後セット</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/01/Output-02.png" width="110"><br><sub>差替後 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-03.png" width="110"><br><sub>差替後 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-04.png" width="110"><br><sub>差替後 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-05.png" width="110"><br><sub>差替後 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-06.png" width="110"><br><sub>差替後 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-07.png" width="110"><br><sub>差替後 6</sub></td>
  </tr>
</table>

#### 例 2：木製ベッドサイドテーブル（赤キャビネット売れ筋セットへ差し替え）

<table>
  <tr>
    <th width="14%">元商品</th>
    <th colspan="4">売れ筋セット（差し替え対象）</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/02/Input.png" width="120"><br>
      <sub>木製ベッドサイドテーブル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/02/Input-01.png" width="120"><br><sub>元メイン 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-02.png" width="120"><br><sub>元メイン 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-03.png" width="120"><br><sub>元メイン 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-04.png" width="120"><br><sub>元メイン 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">差し替え後セット</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/02/Output-01.png" width="120"><br><sub>差替後 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-02.png" width="120"><br><sub>差替後 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-03.png" width="120"><br><sub>差替後 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-04.png" width="120"><br><sub>差替後 4</sub></td>
  </tr>
</table>

### ケース 6：リスティング一括翻訳

**入力：** テキストを含むメイン画像を全てアップロード。

**プロンプト：**

```
Translate the text in all images into {target_language}.
```

> [!NOTE]
> **使用前に {target_language} を置き換えてください。** 例：「すべての画像のテキストを英語に翻訳してください。」元レイアウトを保ったまま商品コピーを多言語へ一括翻訳——ワンクリックでのグローバル展開に最適。

#### 例 1：キャビネット・リスティング（中→英）

<table>
  <tr>
    <th colspan="4">原文</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Input-01.png" width="140"><br><sub>原文 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-02.png" width="140"><br><sub>原文 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-03.png" width="140"><br><sub>原文 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-04.png" width="140"><br><sub>原文 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">翻訳後</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Output-01.png" width="140"><br><sub>翻訳後 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-02.png" width="140"><br><sub>翻訳後 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-03.png" width="140"><br><sub>翻訳後 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-04.png" width="140"><br><sub>翻訳後 4</sub></td>
  </tr>
</table>

#### 例 2：キャビネット・リスティング（多言語一括翻訳）

<table>
  <tr>
    <th colspan="4">原文</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Input-01.png" width="140"><br><sub>原文 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-02.png" width="140"><br><sub>原文 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-03.png" width="140"><br><sub>原文 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-04.png" width="140"><br><sub>原文 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">翻訳後</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Output-01.png" width="140"><br><sub>翻訳後 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-02.png" width="140"><br><sub>翻訳後 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-03.png" width="140"><br><sub>翻訳後 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-04.png" width="140"><br><sub>翻訳後 4</sub></td>
  </tr>
</table>

## 👗 モデル試着・アパレル・プロンプト

### ケース 1：アパレル試着画像セット

**プロンプト：**

```
This is a {apparel_type}. Generate a try-on image set for {country}.
```

> [!NOTE]
> **使用前に {apparel_type} と {country} を置き換えてください。** 例：「これはワンピースです。アメリカ向けの試着画像セットを生成してください。」ワンピース、トップス、アウター、子供服など、商業的な試着展示が必要な全カテゴリに対応。

#### 例 1：グリーン花柄ワンピース

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/01/Input.png" width="160"><br>
      <sub>白背景商品</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/01/Output-1.png" width="150"><br><sub>モデル正面</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-2.png" width="150"><br><sub>多角度</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-3.png" width="150"><br><sub>クローズアップ</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/01/Output-4.png" width="150"><br><sub>全体コーデ</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-5.png" width="150"><br><sub>ライフスタイル</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-6.png" width="150"><br><sub>別角度</sub></td>
  </tr>
</table>

#### 例 2：インドのサリー伝統衣装

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/02/Input.png" width="160"><br>
      <sub>白背景商品</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/02/Output-01.png" width="150"><br><sub>モデル正面</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-02.png" width="150"><br><sub>背面・振り向き</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-03.png" width="150"><br><sub>ディテール</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/02/Output-04.png" width="150"><br><sub>全体コーデ</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-05.png" width="150"><br><sub>ライフスタイル</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-06.png" width="150"><br><sub>別角度</sub></td>
  </tr>
</table>

### ケース 2：モデル＆ペット試着

**入力：** アパレルまたはアクセサリー画像をアップロード。

**プロンプト：**

```
Generate a model wearing this garment.
Generate a pet dog wearing this garment.
```

> [!NOTE]
> 本テンプレートは人物モデル試着とペット試着の両方をカバー。アパレル、コスプレ小物、ペットファッションなど、同じ衣装を異なる被写体で見せたいクリエイティブに最適。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case8/01/Input.png" width="140"><br><sub>#LOVE プリント T</sub></td>
    <td align="center"><img src="e-commerce/Case8/01/Output-01.png" width="140"><br><sub>男性モデル着用</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Input.jpg" width="140"><br><sub>サイクリング T</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Output-01.png" width="140"><br><sub>男性モデル着用</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Input.webp" width="140"><br><sub>ハーフジップ・ニット</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Output-01.png" width="140"><br><sub>女性モデル着用</sub></td>
  </tr>
</table>

### ケース 3：モデルポーズ拡張

**入力：** 元のモデル着用画像をアップロード。

**プロンプト：**

```
Expand the model into more poses.
```

> [!NOTE]
> サイド、45°振り向き、歩行など複数のポーズバリエーションを生成。再撮影なしでアパレル素材を充実化できます。

#### 例 1：#LOVE プリント T シャツ

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="4">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/01/Input.png" width="160"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/01/Output-01.png" width="150"><br><sub>正面立ち</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-02.png" width="150"><br><sub>サイド</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-03.png" width="150"><br><sub>45°振り向き</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-04.png" width="150"><br><sub>歩き姿</sub></td>
  </tr>
</table>

#### 例 2：グレー・ハーフジップ・プルオーバー

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="4">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/02/Input.png" width="160"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/02/Output-01.png" width="150"><br><sub>正面立ち</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-02.png" width="150"><br><sub>サイド</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-03.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-04.png" width="150"><br><sub>歩き姿</sub></td>
  </tr>
</table>

### ケース 4：外見制御付きモデル差し替え

**入力：** 元のモデル着用画像をアップロード。

**プロンプト：**

```
Replace the model with a {ethnicity} model, {hair_description}, while keeping the outfit unchanged.
Replace the figure with a {ethnicity} model, {skin_tone} skin, {hair_color} hair, while keeping the outfit unchanged.
```

> [!NOTE]
> **使用前に {ethnicity}、{hair_description}、{skin_tone}、{hair_color} を置き換えてください。** 例：「服装はそのままに、モデルを黒人モデル・ドレッドヘアに差し替えてください」「服装はそのままに、人物を白人女性モデル・色白・金髪に差し替えてください」。再撮影なしで多様なオーディエンス向けにファッション素材をローカライズ可能。

#### 例 1：#LOVE プリント T シャツ

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/01/Input.png" width="160"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case10/01/Output-01.png" width="180"><br><sub>差替モデル v1</sub></td>
    <td align="center"><img src="e-commerce/Case10/01/Output-02.png" width="180"><br><sub>差替モデル v2</sub></td>
  </tr>
</table>

#### 例 2：グレー・ハーフジップ・プルオーバー

<table>
  <tr>
    <th width="40%">入力</th>
    <th width="60%">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/02/Input.png" width="200"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center">
      <img src="e-commerce/Case10/02/Output-01.png" width="200"><br>
      <sub>差替モデル</sub>
    </td>
  </tr>
</table>

### ケース 5：参照モデル指定置換

**入力：** 元のモデル画像と参照モデル画像をアップロード。

**プロンプト：**

```
Replace the model in image 1 with the model in image 2, keeping the same pose.
```

> [!NOTE]
> 複数の素材で特定のモデルアイデンティティを固定しつつ、元の衣装とポーズを再利用したい場合に使用。

#### 例 1：女性モデル差し替え

<table>
  <tr>
    <th>元モデル</th>
    <th>指定モデル</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/01/Input-01.jpg" width="180"><br><sub>元モデル</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Input-02.png" width="180"><br><sub>指定モデル</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Output.png" width="180"><br><sub>置換結果</sub></td>
  </tr>
</table>

#### 例 2：男性モデル差し替え

<table>
  <tr>
    <th>元モデル</th>
    <th>指定モデル</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/02/Input-01.jpeg" width="180"><br><sub>元モデル</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Input-02.jpeg" width="180"><br><sub>指定モデル</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Output.png" width="180"><br><sub>置換結果</sub></td>
  </tr>
</table>

### ケース 6：アパレル販売用背景コンセプト

**プロンプト：**

```
Generate suitable background images for {apparel_type} sales display. Provide several indoor and outdoor options to choose from.
```

> [!NOTE]
> **使用前に {apparel_type} を置き換えてください。** 例：「子供服販売用の背景画像を生成し、室内・屋外の選択肢を複数提示してください。」シーン構想とモデル生成を分離して進めるワークフローに有効。

#### 例 1：ベージュ・ニット・プルオーバー

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/01/Input.jpeg" width="160"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/01/Output-01.png" width="150"><br><sub>室内ミニマル</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-02.png" width="150"><br><sub>屋外ナチュラル 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-03.png" width="150"><br><sub>屋外ナチュラル 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/01/Output-04.png" width="150"><br><sub>街中</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-05.png" width="150"><br><sub>自宅シーン</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-06.png" width="150"><br><sub>カジュアル</sub></td>
  </tr>
</table>

#### 例 2：ダークブルー・ケーブルニット

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/02/Input.jpg" width="160"><br>
      <sub>元モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/02/Output-01.png" width="150"><br><sub>室内シーン 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-02.png" width="150"><br><sub>屋外シーン 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-03.png" width="150"><br><sub>屋外シーン 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/02/Output-04.png" width="150"><br><sub>街中</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-05.png" width="150"><br><sub>自宅環境</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-06.png" width="150"><br><sub>その他シーン</sub></td>
  </tr>
</table>

### ケース 7：アクセサリー試着

**入力：** アクセサリー商品画像をアップロード。

**プロンプト：**

```
A model wearing this {accessory_type}, {additional_requirements}.
```

> [!NOTE]
> **使用前に {accessory_type} と {additional_requirements} を置き換えてください。** 例：「モデルがこのネックレスを着用、顔は見えない構図」「モデルがこのピアスを着用」。ネックレス、ピアス、帽子、スカーフなどの着用アクセサリーに対応。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case13/01/Input.png" width="180"><br><sub>翡翠ペンダント・ネックレス</sub></td>
    <td align="center"><img src="e-commerce/Case13/01/Output.png" width="180"><br><sub>モデル装着</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Input.jpg" width="180"><br><sub>ゴールド・フープピアス</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Output.png" width="180"><br><sub>モデル装着</sub></td>
  </tr>
</table>

### ケース 8：ネイル装着

**入力：** ネイルデザインの参照画像をアップロード。

**プロンプト：**

```
Apply these nails to hands.
```

> [!NOTE]
> ネイルチップ、ジェルポリッシュのコンセプト、サロン向けデザインプレビュー、ネイル商品マーケティング素材に最適。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case14/01/Input.jpg" width="180"><br><sub>ピンクネイル見本</sub></td>
    <td align="center"><img src="e-commerce/Case14/01/Output-01.png" width="180"><br><sub>手に装着</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Input.jpg" width="180"><br><sub>マルチカラーネイル見本</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Output-01.png" width="180"><br><sub>手に装着</sub></td>
  </tr>
</table>

### ケース 9：モデル靴試着

**入力：** 靴の商品画像をアップロード。

**プロンプト：**

```
A model wearing the shoes from the image, {styling_description}.
```

> [!NOTE]
> **使用前に {styling_description} を置き換えてください。** 例：「画像の靴をモデルが着用、ブラウンのミニスカートとコーディネート。」スニーカー、ヒール、ブーツ、シーズン靴のクリエイティブに対応。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case15/01/Input.jpg" width="180"><br><sub>黒革靴</sub></td>
    <td align="center"><img src="e-commerce/Case15/01/Output-01.png" width="180"><br><sub>男性コーデ</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Input.jpg" width="180"><br><sub>黒ハイヒール</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Output-01.png" width="180"><br><sub>女性コーデ</sub></td>
  </tr>
</table>

## 📦 商品ショーケース・プロンプト

### ケース 1：白背景商品レタッチ

**入力：** 高品質な商品写真をアップロード。

**プロンプト：**

```
Generate a clean white-background retouched image.
```

> [!NOTE]
> 元画像の品質が高いほど精度の高い結果が得られます。高品質な入力は商品の忠実な再現とクリーンな Eコマース水準の出力につながります。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case16/01/Input.png" width="180"><br><sub>シーン内商品画像</sub></td>
    <td align="center"><img src="e-commerce/Case16/01/Output-01.png" width="180"><br><sub>白背景レタッチ</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/images.jpeg" width="180"><br><sub>元商品画像</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/Output-01.png" width="180"><br><sub>白背景レタッチ</sub></td>
  </tr>
</table>

### ケース 2：多角度商品ビュー

**入力：** 商品参照画像をアップロード。

**プロンプト：**

```
Generate multi-angle product images.
```

> [!NOTE]
> 商品カード、カルーセル、機能解説、特定角度の詳細ページに有効。

#### 例 1：タンカラー登山靴

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/01/Input.png" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/01/Output-01.png" width="150"><br><sub>正面</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-02.png" width="150"><br><sub>45° サイド</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-03.png" width="150"><br><sub>背面</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/01/Output-04.png" width="150"><br><sub>靴底</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-05.png" width="150"><br><sub>真上</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-06.png" width="150"><br><sub>その他角度</sub></td>
  </tr>
</table>

#### 例 2：登山靴（別モデル）

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/02/Input.png" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/02/Output-01.png" width="150"><br><sub>正面</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-02.png" width="150"><br><sub>サイド</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-03.png" width="150"><br><sub>背面</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/02/Output-04.png" width="150"><br><sub>靴底ディテール</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-05.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-06.png" width="150"><br><sub>別角度</sub></td>
  </tr>
</table>

### ケース 3：素材・カラー・バリエーション

**入力：** 編集する商品またはアパレル画像をアップロード。

**プロンプト：**

```
Modify the material. Change the figure's clothing into: {material1}, {material2}, and {material3}.
```

> [!NOTE]
> **使用前に {material1}、{material2}、{material3} を置き換えてください。** 例：「素材を変更してください。人物の服装を以下に変更：ライトグレーのスエード、ダークブラウンのデニム、ワインカラーのコーデュロイ。」素材差し替え、素材テスト、シーズン色替え、コンセプト探索に対応。

#### 例 1：グリーンジャケット素材バリエーション

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/01/Input.jpg" width="160"><br>
      <sub>元・男性モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/01/Output-01.png" width="150"><br><sub>バリエーション 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-02.png" width="150"><br><sub>バリエーション 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-03.png" width="150"><br><sub>バリエーション 3</sub></td>
  </tr>
</table>

#### 例 2：黒革ジャケット素材バリエーション

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/02/Input.avif" width="160"><br>
      <sub>元・男性モデル</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/02/Output-01.png" width="150"><br><sub>バリエーション 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-02.png" width="150"><br><sub>バリエーション 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-03.png" width="150"><br><sub>バリエーション 3</sub></td>
  </tr>
</table>

### ケース 4：スマート背景生成

**入力：** 商品画像をアップロード。

**プロンプト：**

```
Generate suitable product images.
```

> [!NOTE]
> 詳細なアートディレクションなしで、モデルに最適な商業向け商品背景を自動推論させたい場面に最適。

#### 例 1：スナックボックス

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/01/Input.webp" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/01/Output-01.png" width="200"><br><sub>スマート背景 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-02.png" width="200"><br><sub>スマート背景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/01/Output-03.png" width="200"><br><sub>スマート背景 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-04.png" width="200"><br><sub>スマート背景 4</sub></td>
  </tr>
</table>

#### 例 2：スキンケア美容液

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/02/Input.jpg" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/02/Output-01.png" width="200"><br><sub>スマート背景 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-02.png" width="200"><br><sub>スマート背景 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/02/Output-03.png" width="200"><br><sub>スマート背景 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-04.png" width="200"><br><sub>スマート背景 4</sub></td>
  </tr>
</table>

### ケース 5：カスタム指定での背景差し替え

**入力：** 商品画像をアップロード。

**プロンプト：**

```
Replace the background of the product in the image: {background_description}.
```

> [!NOTE]
> **使用前に {background_description} を置き換えてください。** 例：「画像の商品の背景を以下に置き換えてください：滑らかな白い石の上に置かれた香水瓶のクローズアップ、周囲には柔らかな白と淡青の花、遠くには穏やかな青い湖と晴天の山々——爽やかで軽やか、ややクールな美的世界観。」新シーンを完全にアートディレクションしたい場合に有効。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case20/01/Input.png" width="180"><br><sub>商品画像</sub></td>
    <td align="center"><img src="e-commerce/Case20/01/Output-01.png" width="180"><br><sub>カスタム指定背景</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Input.jpg" width="180"><br><sub>商品画像</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Output-01.png" width="180"><br><sub>カスタム指定背景</sub></td>
  </tr>
</table>

### ケース 6：参照画像で商品背景生成

**入力：** 商品画像と参照背景画像をアップロード。

**プロンプト：**

```
Image 1 is my {product}. Generate the new scene using the background style from image 2.
```

> [!NOTE]
> **使用前に {product} を置き換えてください。** 例：「画像 1 は私の指輪です。画像 2 の背景スタイルで新しいシーンを生成してください。」美学マッチング、ブランド一貫性、カテゴリ別ビジュアル参照に有効。

#### 例 1：ピンクのレトロカー

<table>
  <tr>
    <th>商品</th>
    <th>参照背景</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/01/Input-01.jpg" width="180"><br><sub>ピンクのレトロカー</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Input-02.jpg" width="180"><br><sub>緑の森・参照</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Output.png" width="180"><br><sub>森のテーブル合成</sub></td>
  </tr>
</table>

#### 例 2：赤リップ

<table>
  <tr>
    <th>商品</th>
    <th>参照背景</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/02/Input-01.jpg" width="180"><br><sub>赤リップ</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Input-02.jpg" width="180"><br><sub>黒金大理石・参照</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Output.png" width="180"><br><sub>大理石テーブル合成</sub></td>
  </tr>
</table>

## 🤝 商品インタラクション・プロンプト

### ケース 1：手持ち商品クローズアップ

**入力：** 商品画像をアップロード。

**プロンプト：**

```
A hand is holding this product, {scene_description}, keep the product color unchanged.
{action_description}
```

> [!NOTE]
> **使用前に {scene_description} と {action_description} を置き換えてください。** 例：「手がこの商品を持っている、ファッション・エディトリアル背景、商品色は変更しない」「手で電動ドリルを持ち、木材に穴を開ける動作」。コスメ、工具、ガジェット、パッケージ商品、触感を伝える商品デモに対応。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case22/01/Input.jpg" width="180"><br><sub>ピンクリップグロス</sub></td>
    <td align="center"><img src="e-commerce/Case22/01/Output.png" width="180"><br><sub>手持ちリップ・クローズアップ</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Input.avif" width="180"><br><sub>木柄モップ</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Output.png" width="180"><br><sub>モップで床掃除</sub></td>
  </tr>
</table>

### ケース 2：人物インタラクションシーン生成

**入力：** 商品シーン画像または商品画像をアップロード。

**プロンプト：**

```
Add a human model to this product scene. The model should be {person_description}, in a {pose}, performing {action}.
```

> [!NOTE]
> **使用前に {person_description}、{pose}、{action} を置き換えてください。** 例：「この商品シーンに人物モデルを追加。少女、立ちポーズ、人形を持つ」「この商品シーンに人物モデルを追加、モップを持つ」。スケール感、使用方法、感情表現、ターゲット層との適合を見せたい場面に有効。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case23/01/Input.jpg" width="180"><br><sub>春節・赤アーチ</sub></td>
    <td align="center"><img src="e-commerce/Case23/01/Output-01.png" width="180"><br><sub>チャイナドレス・モデル登場</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Input.webp" width="180"><br><sub>赤×シルバー・ヘッドホン</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Output.png" width="180"><br><sub>ヘッドホン装着・女性モデル</sub></td>
  </tr>
</table>

### ケース 3：参照人物の商品インタラクション

**入力：** 商品シーン画像と参照人物画像をアップロード。

**プロンプト：**

```
Add the human model from image 2 into the product scene from image 1, with this action: {action_description}.
```

> [!NOTE]
> **使用前に {action_description} を置き換えてください。** 例：「画像 2 の人物モデルを画像 1 の商品シーンへ追加、動作はベッドに横たわる。」複数の素材で人物アイデンティティを一貫させたい場合に有効。

#### 例 1：キングサイズベッドルーム + 男性モデル

<table>
  <tr>
    <th>商品シーン</th>
    <th>参照人物</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/01/Input-01.webp" width="180"><br><sub>キングベッド寝室</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Input-02.jpg" width="180"><br><sub>白 T 男性モデル</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Output.png" width="180"><br><sub>ベッドで寛ぐ男性モデル</sub></td>
  </tr>
</table>

#### 例 2：自宅ロッキングチェア + 男性モデル

<table>
  <tr>
    <th>商品シーン</th>
    <th>参照人物</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/02/Input-01.jpg" width="180"><br><sub>自宅ロッキングチェア</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Input-02.jpg" width="180"><br><sub>白シャツ男性モデル</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Output.png" width="180"><br><sub>ロッキングチェアの男性モデル</sub></td>
  </tr>
</table>

### ケース 4：ペットと商品のインタラクション

**入力：** 商品画像をアップロード。

**プロンプト：**

```
Generate a {pet} interacting with the {product} from the image.
```

> [!NOTE]
> **使用前に {pet} と {product} を置き換えてください。** 例：「画像のおもちゃと猫がインタラクションしている様子を生成」「画像のおもちゃと子犬がインタラクションしている様子を生成」。おもちゃ、ペット用品、ホーム、ライフスタイル系商品の遊び心あるクリエイティブに最適。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case25/01/Input.jpg" width="180"><br><sub>オレンジ・ドッグボール</sub></td>
    <td align="center"><img src="e-commerce/Case25/01/Output.png" width="180"><br><sub>ボールを噛む子犬</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Input.jpg" width="180"><br><sub>ハムスターホイール</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Output.png" width="180"><br><sub>ホイールのハムスター</sub></td>
  </tr>
</table>

## 🛍️ ソーシャルコマース・プロンプト

### ケース 1：ファッションスタジオ販売セット

**プロンプト：**

```
Generate a model sales image set, background is a fashion studio.
```

> [!NOTE]
> ショールーム風アパレルマーケティング、ブティックのビジュアル・マーチャンダイジング、スタジオ撮影風のソーシャル・コンテンツに最適。

#### 例 1：青パーカー

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/01/Input.png" width="160"><br>
      <sub>白背景商品</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/01/Output-01.png" width="200"><br><sub>スタジオ撮影 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-02.png" width="200"><br><sub>スタジオ撮影 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/01/Output-03.png" width="200"><br><sub>スタジオ撮影 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-04.png" width="200"><br><sub>スタジオ撮影 4</sub></td>
  </tr>
</table>

#### 例 2：ピンク花柄ワンピース

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/02/Input.webp" width="160"><br>
      <sub>白背景商品</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/02/Output-01.png" width="200"><br><sub>スタジオ撮影 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-02.png" width="200"><br><sub>スタジオ撮影 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/02/Output-03.png" width="200"><br><sub>スタジオ撮影 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-04.png" width="200"><br><sub>スタジオ撮影 4</sub></td>
  </tr>
</table>

### ケース 2：鏡越しコーデ販売動画

**プロンプト：**

```
Generate a mirror outfit sales video.
```

> [!NOTE]
> クリエイター風のファッション・コンテンツ、UGC 美学、カジュアルなソーシャルコマース販売フォーマットに最適。

### ケース 3：アパレルのギフトボックス演出

**入力：** アパレル画像をアップロード。

**プロンプト：**

```
Place the apparel into a gift box.
```

> [!NOTE]
> ホリデーギフト・マーケティング、プレミアムパッケージのモックアップ、シーズンテーマの商品クリエイティブに最適。

<table>
  <tr>
    <th>入力</th>
    <th>出力</th>
    <th>入力</th>
    <th>出力</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case33/01/Input.jpg" width="180"><br><sub>カラー・スプラッシュ T</sub></td>
    <td align="center"><img src="e-commerce/Case33/01/Output.png" width="180"><br><sub>ギフトボックス結果</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Input.jpg" width="180"><br><sub>赤・キッズダウン</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Output.png" width="180"><br><sub>ギフトボックス結果</sub></td>
  </tr>
</table>

### ケース 4：生鮮食品販売シーンセット

**プロンプト：**

```
Generate a fresh-food scene set for {food_name}.
```

> [!NOTE]
> **使用前に {food_name} を置き換えてください。** 例：「ザボン用の生鮮食品シーンセットを生成してください。」フルーツ、農産物、箱入り食品、特産食材、プレミアム生鮮陳列に対応。

#### 例 1：スイカ

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/01/Input.webp" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/01/Output-01.png" width="200"><br><sub>生鮮シーン 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-02.png" width="200"><br><sub>生鮮シーン 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/01/Output-03.png" width="200"><br><sub>生鮮シーン 3</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-04.png" width="200"><br><sub>生鮮シーン 4</sub></td>
  </tr>
</table>

#### 例 2：ブドウ

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/02/Input.jpg" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/02/Output-01.png" width="150"><br><sub>生鮮シーン 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-02.png" width="150"><br><sub>生鮮シーン 2</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-03.png" width="150"><br><sub>生鮮シーン 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/02/Output-04.png" width="150"><br><sub>生鮮シーン 4</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-05.png" width="150"><br><sub>生鮮シーン 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### ケース 5：汎用フード販売クリエイティブセット

**プロンプト：**

```
Generate a food sales image set.
```

> [!NOTE]
> スナックブランド、パッケージ食品、生鮮商品、一般的なソーシャルコマース食品コンテンツに使える柔軟な基本テンプレート。

#### 例 1：ポップコーン

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="3">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/01/Input.jpg" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/01/Output-01.png" width="150"><br><sub>販売画像 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-02.png" width="150"><br><sub>販売画像 2</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-03.png" width="150"><br><sub>販売画像 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/01/Output-04.png" width="150"><br><sub>販売画像 4</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-05.png" width="150"><br><sub>販売画像 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 例 2：糖葫芦（中華風フルーツ飴串）

<table>
  <tr>
    <th width="20%">入力</th>
    <th colspan="2">出力</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/02/Input.webp" width="160"><br>
      <sub>商品画像</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/02/Output-01.png" width="200"><br><sub>販売画像 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-02.png" width="200"><br><sub>販売画像 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/02/Output-03.png" width="200"><br><sub>販売画像 3</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-04.png" width="200"><br><sub>販売画像 4</sub></td>
  </tr>
</table>

## 🚀 Evolink API による一括生成

数百 SKU・多言語・複数マーケットプレイスにまたがる本番運用では、プロンプトを 1 件ずつ手動実行するのではなく、**Evolink GPT Image 2 API** を直接呼び出すのが効率的です。

**API による一括処理のメリット：**

- カタログ全体のメイン画像を一括生成
- 全リスティング素材の多言語翻訳を 1 ジョブで完了
- モデル差し替え・背景置換・多角度出力をプログラム制御
- Webhook コールバックで PIM、ERP、マーケティング自動化と直結

**事前準備：** [API キーを取得](https://evolink.ai/dashboard/keys)。

### ステップ 1：生成タスクを送信

GPT Image 2 の生成は **非同期** です——呼び出しは `task_id` を返し、結果はポーリングで取得します。

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

| フィールド | 必須 | 説明 |
| :--- | :--- | :--- |
| `model` | 必須 | `"gpt-image-2"` 固定 |
| `prompt` | 必須 | 最大 32,000 文字——本リポジトリの任意ケースのプロンプトをそのまま貼り付け可能 |
| `image_urls` | 任意 | 入力／参照画像 1〜16 枚（jpeg/png/webp、各 ≤50 MB）。img2img・編集系タスクで使用 |
| `size` | 任意 | アスペクト比（`1:1`、`2:3`、`16:9` …）またはピクセル指定。デフォルト `auto` |
| `resolution` | 任意 | `1K` / `2K` / `4K`（`size` が比率の場合に有効） |
| `quality` | 任意 | `low` / `medium` / `high`——コストに影響。デフォルト `medium` |
| `n` | 任意 | 1〜10 枚／回 |
| `callback_url` | 任意 | 完了通知を受け取る HTTPS Webhook（ポーリング不要） |

### ステップ 2：タスクをポーリング

```bash
curl https://api.evolink.ai/v1/tasks/{task_id} \
  -H "Authorization: Bearer YOUR_API_KEY"
```

`status` が `"completed"` になると、`results` 配列に生成画像 URL が格納されます。**生成画像は 24 時間のみ有効です——速やかにダウンロードしてください。**

### オプション：Webhook コールバック

送信時に `"callback_url": "https://your-server.example.com/webhook"` を含めると、タスク完了時に Evolink が結果をその URL に POST します——ポーリング不要。

**API 完全リファレンス：** [docs.evolink.ai · GPT Image 2 画像生成](https://docs.evolink.ai/en/api-manual/image-series/gpt-image-2/gpt-image-2-image-generation)

## 🙏 謝辞

本リポジトリは、優れたオープンソースのプロンプト集とコミュニティが共有する Eコマース・ワークフローに触発されて作られました。

作品を惜しみなく公開し、これらのケーススタディを可能にしてくださった全てのクリエイター・貢献者の皆様に感謝します。

- [@EvoLinkAI](https://github.com/EvoLinkAI)

*すべてのケースについて元のクリエイターへのクレジットを保証することはできません。修正が必要な場合はご連絡ください、迅速に更新いたします。*

面白いプロンプト事例をお持ちの方は、お気軽にお寄せください。Evolink プロンプトライブラリの拡充にご協力をお願いいたします。

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/awesome-ecommerce-image-prompts&type=Date)](https://www.star-history.com/#EvoLinkAI/awesome-ecommerce-image-prompts&Date)
