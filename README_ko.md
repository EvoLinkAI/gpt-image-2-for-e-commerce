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

# 이커머스를 위한 GPT Image 2 사용법

> **GPT Image 2** 로 이커머스 이미지를 만드는 프롬프트 레시피 모음 — 리스팅 사진, 모델 가상 피팅, 제품 쇼케이스, 인터랙션 씬, 소셜 커머스 크리에이티브를 모두 다룹니다.

## 🍌 소개

이 저장소는 **GPT Image 2 를 활용해 이커머스 이미지를 만드는 방법**을 실전 사례로 보여줍니다 — 리스팅 사진, 다국가 메인 이미지, A+ 상세 비주얼, 모델 가상 피팅, 제품 쇼케이스, 인터랙션 씬, 소셜 커머스 크리에이티브를 프로덕션 레벨로 다룹니다.

**모든 케이스는 레시피 형식입니다:** 입력 제품 사진, GPT Image 2 에 그대로 붙여 넣을 프롬프트, 실제 출력 예시. `{placeholders}` 부분을 본인의 제품·언어·국가·셀링 포인트로 바꾸기만 하면 됩니다.

수백 개 SKU 를 한 번에 처리하려면 [🚀 Evolink API 로 일괄 생성](#-evolink-api-로-일괄-생성) 으로 이동하세요.

Evolink 에서 사용해 보기: [GPT Image 2 워크플로우](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)

도움이 되었다면 Star ⭐ 부탁드립니다

> [!NOTE]
> 이 저장소는 이커머스 크리에이티브용 재사용 가능한 프롬프트 템플릿에 집중합니다. 사용 전에 중괄호 안의 자리표시자를 교체하고, 실제 플랫폼·시장·언어·제품·소재·모델 유형·셀링 포인트에 맞게 조정해 주세요.

<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://docs.evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🤗 Dataset-Evolink-yellow' height="25"></a>

## ⚡ 빠른 시작

1. **케이스 선택** — 본인의 이커머스 목표(리스팅 메인 이미지, 모델 가상 피팅, 다각도 제품, A+ 상세 비주얼 등)에 맞는 케이스를 고르세요.
2. **제품 사진 업로드 + 프롬프트 복사** — 해당 케이스의 프롬프트를 복사하고 `{placeholders}` 를 본인의 제품·언어·국가·플랫폼·셀링 포인트로 교체하세요.
3. **GPT Image 2 로 실행** — 단발 크리에이티브는 [Evolink 워크플로우 UI](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts) 로, 대량 SKU 와 다국어 롤아웃은 [Evolink API](#-evolink-api-로-일괄-생성) 로 처리하세요.

## 📰 업데이트

- **2026년 5월 7일:** 프롬프트 라이브러리를 **이커머스용 GPT Image 2** 중심으로 재포지셔닝하고, 빠른 시작 및 Evolink API 일괄 생성 섹션을 추가했습니다.
- **2026년 5월 5일:** 이커머스 에이전트 프롬프트 패턴 전체와 정렬되도록 리스팅 이미지·모델 피팅·제품 쇼케이스 카테고리를 확장했습니다.
- **2026년 4월 30일:** 리스팅 이미지·모델 편집·제품 쇼케이스·인터랙션 씬·소셜 커머스 크리에이티브의 전체 프롬프트 카테고리를 추가했습니다.
- **2026년 4월 30일:** 이커머스 이미지 프롬프트 워크플로우용 English-first 저장소 골격을 최초 구축했습니다.

## 📑 목차

- [🍌 소개](#-소개)
- [⚡ 빠른 시작](#-빠른-시작)
- [📰 업데이트](#-업데이트)
- [📑 목차](#-목차)
- [🖼️ 이커머스 리스팅 이미지 프롬프트](#️-이커머스-리스팅-이미지-프롬프트)
  - [케이스 1: 마켓플레이스 리스팅 이미지 세트](#케이스-1-마켓플레이스-리스팅-이미지-세트)
  - [케이스 2: 다국가 리스팅 이미지 세트](#케이스-2-다국가-리스팅-이미지-세트)
  - [케이스 3: A+ 제품 상세 비주얼](#케이스-3-a-제품-상세-비주얼)
  - [케이스 4: 아마존 리스팅 일괄 생성](#케이스-4-아마존-리스팅-일괄-생성)
  - [케이스 5: 메인 이미지 일괄 교체](#케이스-5-메인-이미지-일괄-교체)
  - [케이스 6: 리스팅 일괄 번역](#케이스-6-리스팅-일괄-번역)
- [👗 모델 가상 피팅·의류 프롬프트](#-모델-가상-피팅의류-프롬프트)
  - [케이스 1: 의류 피팅 이미지 세트](#케이스-1-의류-피팅-이미지-세트)
  - [케이스 2: 모델·반려동물 피팅](#케이스-2-모델반려동물-피팅)
  - [케이스 3: 모델 포즈 확장](#케이스-3-모델-포즈-확장)
  - [케이스 4: 외형 제어 모델 교체](#케이스-4-외형-제어-모델-교체)
  - [케이스 5: 참조 기반 모델 교체](#케이스-5-참조-기반-모델-교체)
  - [케이스 6: 의류 판매용 배경 컨셉](#케이스-6-의류-판매용-배경-컨셉)
  - [케이스 7: 액세서리 착용](#케이스-7-액세서리-착용)
  - [케이스 8: 네일 어플리케이션](#케이스-8-네일-어플리케이션)
  - [케이스 9: 모델 슈즈 피팅](#케이스-9-모델-슈즈-피팅)
- [📦 제품 쇼케이스 프롬프트](#-제품-쇼케이스-프롬프트)
  - [케이스 1: 화이트 배경 제품 리터치](#케이스-1-화이트-배경-제품-리터치)
  - [케이스 2: 다각도 제품 뷰](#케이스-2-다각도-제품-뷰)
  - [케이스 3: 소재·컬러 베리에이션](#케이스-3-소재컬러-베리에이션)
  - [케이스 4: 스마트 배경 생성](#케이스-4-스마트-배경-생성)
  - [케이스 5: 커스텀 설명 기반 배경 교체](#케이스-5-커스텀-설명-기반-배경-교체)
  - [케이스 6: 참조 기반 제품 배경](#케이스-6-참조-기반-제품-배경)
- [🤝 제품 인터랙션 프롬프트](#-제품-인터랙션-프롬프트)
  - [케이스 1: 핸드헬드 제품 클로즈업](#케이스-1-핸드헬드-제품-클로즈업)
  - [케이스 2: 인물 인터랙션 씬 생성](#케이스-2-인물-인터랙션-씬-생성)
  - [케이스 3: 참조 인물의 제품 인터랙션](#케이스-3-참조-인물의-제품-인터랙션)
  - [케이스 4: 반려동물·제품 인터랙션](#케이스-4-반려동물제품-인터랙션)
- [🛍️ 소셜 커머스 프롬프트](#️-소셜-커머스-프롬프트)
  - [케이스 1: 패션 스튜디오 판매 세트](#케이스-1-패션-스튜디오-판매-세트)
  - [케이스 2: 거울 코디 판매 영상](#케이스-2-거울-코디-판매-영상)
  - [케이스 3: 의류 기프트 박스 스타일링](#케이스-3-의류-기프트-박스-스타일링)
  - [케이스 4: 신선 식품 판매 씬 세트](#케이스-4-신선-식품-판매-씬-세트)
  - [케이스 5: 일반 식품 판매 크리에이티브 세트](#케이스-5-일반-식품-판매-크리에이티브-세트)
- [🚀 Evolink API 로 일괄 생성](#-evolink-api-로-일괄-생성)
- [🙏 감사의 글](#-감사의-글)

## 🖼️ 이커머스 리스팅 이미지 프롬프트

### 케이스 1: 마켓플레이스 리스팅 이미지 세트

**프롬프트:**

```
Generate a {platform} listing image set for {country} in {language}. The product is {product_name}, and the selling points are {selling_points}.
```

> [!NOTE]
> **사용 전 {platform}, {country}, {language}, {product_name}, {selling_points} 를 교체하세요.** 이 템플릿은 Amazon, eBay, AliExpress, TEMU, SHEIN, TikTok Shop, Shopee, Lazada, Mercado Libre, Walmart, Etsy, Rakuten, Coupang, Shopify 등 주요 마켓플레이스에 대응합니다. 에이전트가 플랫폼 특성에 맞춰 화이트 배경 이미지, 사이즈 도면, 다각도 뷰, 라이프스타일 씬, 셀링 포인트 이미지, 소재 디테일 등을 자동 구성합니다.

#### 예시 1: 원목 식탁 의자

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="4">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/01/input.webp" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/01/output-01.png" width="150"><br><sub>화이트 메인</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-02.png" width="150"><br><sub>셀링 포인트</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-03.png" width="150"><br><sub>사이즈 도면</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-04.png" width="150"><br><sub>다각도</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/01/output-05.png" width="150"><br><sub>라이프스타일 씬</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-06.png" width="150"><br><sub>사용 씬</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-08.png" width="150"><br><sub>소재 디테일</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 예시 2: 스포츠 물병

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/02/input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/02/output-01.png" width="150"><br><sub>화이트 메인</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-02.png" width="150"><br><sub>다각도</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-03.png" width="150"><br><sub>셀링 포인트</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/02/output-04.png" width="150"><br><sub>사이즈 도면</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-05.png" width="150"><br><sub>사용 씬</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-06.png" width="150"><br><sub>소재 디테일</sub></td>
  </tr>
</table>

#### 예시 3: 스포츠 티셔츠

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="4">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/03/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/03/Output-01.png" width="150"><br><sub>셀링 포인트</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-02.png" width="150"><br><sub>스펙</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-03.png" width="150"><br><sub>사이즈 차트</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-04.png" width="150"><br><sub>다각도</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/03/Output-05.png" width="150"><br><sub>사용 씬</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-06.png" width="150"><br><sub>소재 디테일</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-07.png" width="150"><br><sub>셀링 포인트 요약</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### 케이스 2: 다국가 리스팅 이미지 세트

**프롬프트:**

```
Generate a {platform} listing image set for {country} in {language}.
```

> [!NOTE]
> **사용 전 {platform}, {country}, {language} 를 교체하세요.** 모델이 최적의 리스팅 레이아웃을 자동 추론하길 원할 때 사용하는 단축 템플릿.

#### 예시 1: 보라색 도트 원피스

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/01/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ar.png" width="150"><br><sub>아랍어</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Cn.png" width="150"><br><sub>중국어</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-En.png" width="150"><br><sub>영어</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ja.png" width="150"><br><sub>일본어</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Kr.png" width="150"><br><sub>한국어</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Pt.png" width="150"><br><sub>포르투갈어</sub></td>
  </tr>
</table>

#### 예시 2: 무선 청소기

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/02/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Bn.png" width="150"><br><sub>벵골어</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-De.png" width="150"><br><sub>독일어</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Es%20.png" width="150"><br><sub>스페인어</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/02/Output-Fr.png" width="150"><br><sub>프랑스어</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Hi.png" width="150"><br><sub>힌디어</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Ru.png" width="150"><br><sub>러시아어</sub></td>
  </tr>
</table>

#### 예시 3: 크리스마스 테마 폰 케이스

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/03/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Id.png" width="150"><br><sub>인도네시아어</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-It.png" width="150"><br><sub>이탈리아어</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Nl.png" width="150"><br><sub>네덜란드어</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/03/Output-Th.png" width="150"><br><sub>태국어</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Tr.png" width="150"><br><sub>터키어</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Vi.png" width="150"><br><sub>베트남어</sub></td>
  </tr>
</table>

### 케이스 3: A+ 제품 상세 비주얼

**프롬프트:**

```
This is a {product_description}. Generate A+ detail visuals for {country} in {language}.
```

> [!NOTE]
> **사용 전 {product_description}, {country}, {language} 를 교체하세요.** 예시: "이것은 커피 원두 박스입니다. 미국용 A+ 상세 비주얼을 영어로 생성해 주세요." 제품 스토리텔링, 기능 분해, 사용 씬, 프리미엄 상세 페이지 레이아웃에 적합.

#### 예시 1: 프리미엄 차 선물세트

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/01/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/01/Output-01.png" width="150"><br><sub>히어로 (셀링)</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-02.png" width="150"><br><sub>디자인·공예</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-03.png" width="150"><br><sub>제품 라인</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/01/Output-04.png" width="150"><br><sub>사용 가이드</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-05.png" width="150"><br><sub>기프트 씬</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-06.png" width="150"><br><sub>사용 씬</sub></td>
  </tr>
</table>

#### 예시 2: 천연 풀 스틱

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/02/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/02/Output-01.png" width="150"><br><sub>A+ 히어로</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-02.png" width="150"><br><sub>A+ 디테일 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-03.png" width="150"><br><sub>A+ 디테일 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/02/Output-04.png" width="150"><br><sub>A+ 디테일 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-05.png" width="150"><br><sub>A+ 디테일 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-06.png" width="150"><br><sub>A+ 요약</sub></td>
  </tr>
</table>

#### 예시 3: 버블티 음료

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/03/Input.png" width="160" alt="원본 제품"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/03/Output-01.png" width="150"><br><sub>A+ 히어로</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-02.png" width="150"><br><sub>A+ 디테일 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-03.png" width="150"><br><sub>A+ 디테일 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/03/Output-04.png" width="150"><br><sub>A+ 디테일 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-05.png" width="150"><br><sub>A+ 디테일 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-06.png" width="150"><br><sub>A+ 요약</sub></td>
  </tr>
</table>

### 케이스 4: 아마존 리스팅 일괄 생성

> [!NOTE]
> 동일 카테고리의 여러 SKU 리스팅을 일괄 생성해야 할 때 사용. 언어별 일괄 실행은 아직 지원되지 않습니다.

### 케이스 5: 메인 이미지 일괄 교체

**입력:** 소스 제품 이미지와 타깃 리스팅 이미지 세트를 업로드하세요.

**프롬프트:**

```
Replace the product in image 1 across images 2–7. Only the swapped product changes; keep everything else identical.
```

> [!NOTE]
> 인기 리스팅을 원샷으로 재현 — 레이아웃은 그대로 두고 제품만 교체. 다수 SKU 가 동일 크리에이티브 스타일을 재사용할 때 유용.

#### 예시 1: 구체 무드등 (버섯 램프 인기 세트로 교체)

<table>
  <tr>
    <th width="14%">소스 제품</th>
    <th colspan="6">인기 세트 (교체 대상)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/01/Input-01.png" width="120"><br>
      <sub>구체 무드등</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/01/Input-02.png" width="110"><br><sub>원본 메인 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-03.png" width="110"><br><sub>원본 메인 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-04.png" width="110"><br><sub>원본 메인 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-05.png" width="110"><br><sub>원본 메인 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-06.png" width="110"><br><sub>원본 메인 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-07.png" width="110"><br><sub>원본 메인 6</sub></td>
  </tr>
  <tr>
    <th colspan="6">교체 후 세트</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/01/Output-02.png" width="110"><br><sub>교체 후 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-03.png" width="110"><br><sub>교체 후 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-04.png" width="110"><br><sub>교체 후 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-05.png" width="110"><br><sub>교체 후 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-06.png" width="110"><br><sub>교체 후 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-07.png" width="110"><br><sub>교체 후 6</sub></td>
  </tr>
</table>

#### 예시 2: 원목 협탁 (레드 캐비닛 인기 세트로 교체)

<table>
  <tr>
    <th width="14%">소스 제품</th>
    <th colspan="4">인기 세트 (교체 대상)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/02/Input.png" width="120"><br>
      <sub>원목 협탁</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/02/Input-01.png" width="120"><br><sub>원본 메인 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-02.png" width="120"><br><sub>원본 메인 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-03.png" width="120"><br><sub>원본 메인 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-04.png" width="120"><br><sub>원본 메인 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">교체 후 세트</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/02/Output-01.png" width="120"><br><sub>교체 후 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-02.png" width="120"><br><sub>교체 후 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-03.png" width="120"><br><sub>교체 후 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-04.png" width="120"><br><sub>교체 후 4</sub></td>
  </tr>
</table>

### 케이스 6: 리스팅 일괄 번역

**입력:** 텍스트가 포함된 모든 리스팅 이미지를 업로드하세요.

**프롬프트:**

```
Translate the text in all images into {target_language}.
```

> [!NOTE]
> **사용 전 {target_language} 를 교체하세요.** 예시: "모든 이미지의 텍스트를 영어로 번역하세요." 원본 레이아웃을 유지하면서 리스팅 텍스트를 다국어로 일괄 번역 — 원클릭 글로벌 롤아웃에 최적.

#### 예시 1: 캐비닛 리스팅 (ZH → EN)

<table>
  <tr>
    <th colspan="4">원본</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Input-01.png" width="140"><br><sub>원본 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-02.png" width="140"><br><sub>원본 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-03.png" width="140"><br><sub>원본 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-04.png" width="140"><br><sub>원본 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">번역</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Output-01.png" width="140"><br><sub>번역 후 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-02.png" width="140"><br><sub>번역 후 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-03.png" width="140"><br><sub>번역 후 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-04.png" width="140"><br><sub>번역 후 4</sub></td>
  </tr>
</table>

#### 예시 2: 캐비닛 리스팅 (다국어 일괄 번역)

<table>
  <tr>
    <th colspan="4">원본</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Input-01.png" width="140"><br><sub>원본 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-02.png" width="140"><br><sub>원본 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-03.png" width="140"><br><sub>원본 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-04.png" width="140"><br><sub>원본 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">번역</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Output-01.png" width="140"><br><sub>번역 후 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-02.png" width="140"><br><sub>번역 후 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-03.png" width="140"><br><sub>번역 후 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-04.png" width="140"><br><sub>번역 후 4</sub></td>
  </tr>
</table>

## 👗 모델 가상 피팅·의류 프롬프트

### 케이스 1: 의류 피팅 이미지 세트

**프롬프트:**

```
This is a {apparel_type}. Generate a try-on image set for {country}.
```

> [!NOTE]
> **사용 전 {apparel_type} 와 {country} 를 교체하세요.** 예시: "이것은 원피스입니다. 미국용 피팅 이미지 세트를 생성해 주세요." 원피스, 상의, 아우터, 아동복 등 상업용 피팅 디스플레이가 필요한 모든 카테고리에 대응.

#### 예시 1: 그린 플로럴 원피스

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/01/Input.png" width="160"><br>
      <sub>화이트 배경 제품</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/01/Output-1.png" width="150"><br><sub>모델 정면</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-2.png" width="150"><br><sub>다각도</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-3.png" width="150"><br><sub>디테일 클로즈업</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/01/Output-4.png" width="150"><br><sub>전체 스타일링</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-5.png" width="150"><br><sub>라이프스타일 씬</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-6.png" width="150"><br><sub>다른 각도</sub></td>
  </tr>
</table>

#### 예시 2: 인도 사리 전통 의상

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/02/Input.png" width="160"><br>
      <sub>화이트 배경 제품</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/02/Output-01.png" width="150"><br><sub>모델 정면</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-02.png" width="150"><br><sub>뒷모습 / 턴</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-03.png" width="150"><br><sub>디테일</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/02/Output-04.png" width="150"><br><sub>전체 스타일링</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-05.png" width="150"><br><sub>라이프스타일 씬</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-06.png" width="150"><br><sub>다른 각도</sub></td>
  </tr>
</table>

### 케이스 2: 모델·반려동물 피팅

**입력:** 의류 또는 액세서리 이미지를 업로드하세요.

**프롬프트:**

```
Generate a model wearing this garment.
Generate a pet dog wearing this garment.
```

> [!NOTE]
> 이 템플릿은 인물 모델 피팅과 반려동물 피팅을 모두 지원하며, 동일 의류를 서로 다른 피사체에 보여줘야 하는 의류·코스프레 소품·펫 패션 크리에이티브에 적합합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case8/01/Input.png" width="140"><br><sub>#LOVE 프린트 티</sub></td>
    <td align="center"><img src="e-commerce/Case8/01/Output-01.png" width="140"><br><sub>남성 모델 착용</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Input.jpg" width="140"><br><sub>사이클링 티</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Output-01.png" width="140"><br><sub>남성 모델 착용</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Input.webp" width="140"><br><sub>하프 집업 니트</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Output-01.png" width="140"><br><sub>여성 모델 착용</sub></td>
  </tr>
</table>

### 케이스 3: 모델 포즈 확장

**입력:** 의류 착용 모델의 원본 이미지를 업로드하세요.

**프롬프트:**

```
Expand the model into more poses.
```

> [!NOTE]
> 측면, 45° 턴, 워킹 등 다양한 포즈 베리에이션을 생성하여 재촬영 없이 의류 에셋을 풍부하게 합니다.

#### 예시 1: #LOVE 프린트 티셔츠

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="4">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/01/Input.png" width="160"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/01/Output-01.png" width="150"><br><sub>정면 자세</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-02.png" width="150"><br><sub>측면</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-03.png" width="150"><br><sub>45° 턴</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-04.png" width="150"><br><sub>워킹</sub></td>
  </tr>
</table>

#### 예시 2: 그레이 하프 집업 풀오버

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="4">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/02/Input.png" width="160"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/02/Output-01.png" width="150"><br><sub>정면 자세</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-02.png" width="150"><br><sub>측면</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-03.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-04.png" width="150"><br><sub>워킹</sub></td>
  </tr>
</table>

### 케이스 4: 외형 제어 모델 교체

**입력:** 의류 착용 모델의 원본 이미지를 업로드하세요.

**프롬프트:**

```
Replace the model with a {ethnicity} model, {hair_description}, while keeping the outfit unchanged.
Replace the figure with a {ethnicity} model, {skin_tone} skin, {hair_color} hair, while keeping the outfit unchanged.
```

> [!NOTE]
> **사용 전 {ethnicity}, {hair_description}, {skin_tone}, {hair_color} 를 교체하세요.** 예시: "의상은 그대로 두고 모델을 흑인 모델·드레드록 헤어로 교체해 주세요" 또는 "의상은 그대로 두고 인물을 백인 여성 모델·밝은 피부·금발로 교체해 주세요." 재촬영 없이 다양한 오디언스용으로 패션 크리에이티브를 로컬라이즈할 수 있습니다.

#### 예시 1: #LOVE 프린트 티셔츠

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/01/Input.png" width="160"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case10/01/Output-01.png" width="180"><br><sub>교체 모델 v1</sub></td>
    <td align="center"><img src="e-commerce/Case10/01/Output-02.png" width="180"><br><sub>교체 모델 v2</sub></td>
  </tr>
</table>

#### 예시 2: 그레이 하프 집업 풀오버

<table>
  <tr>
    <th width="40%">입력</th>
    <th width="60%">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/02/Input.png" width="200"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center">
      <img src="e-commerce/Case10/02/Output-01.png" width="200"><br>
      <sub>교체 모델</sub>
    </td>
  </tr>
</table>

### 케이스 5: 참조 기반 모델 교체

**입력:** 원본 모델 이미지와 참조 모델 이미지를 업로드하세요.

**프롬프트:**

```
Replace the model in image 1 with the model in image 2, keeping the same pose.
```

> [!NOTE]
> 여러 크리에이티브 에셋에서 특정 모델 아이덴티티를 고정하면서 원본 의상·포즈를 재사용하고 싶을 때 사용합니다.

#### 예시 1: 여성 모델 교체

<table>
  <tr>
    <th>원본 모델</th>
    <th>참조 모델</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/01/Input-01.jpg" width="180"><br><sub>원본 모델</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Input-02.png" width="180"><br><sub>참조 모델</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Output.png" width="180"><br><sub>교체 결과</sub></td>
  </tr>
</table>

#### 예시 2: 남성 모델 교체

<table>
  <tr>
    <th>원본 모델</th>
    <th>참조 모델</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/02/Input-01.jpeg" width="180"><br><sub>원본 모델</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Input-02.jpeg" width="180"><br><sub>참조 모델</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Output.png" width="180"><br><sub>교체 결과</sub></td>
  </tr>
</table>

### 케이스 6: 의류 판매용 배경 컨셉

**프롬프트:**

```
Generate suitable background images for {apparel_type} sales display. Provide several indoor and outdoor options to choose from.
```

> [!NOTE]
> **사용 전 {apparel_type} 를 교체하세요.** 예시: "아동복 판매 디스플레이용 배경 이미지를 생성하고, 실내·야외 옵션을 여러 개 제시해 주세요." 워크플로우에서 씬 아이데이션과 모델 생성을 분리할 때 유용합니다.

#### 예시 1: 베이지 니트 풀오버

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/01/Input.jpeg" width="160"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/01/Output-01.png" width="150"><br><sub>실내 미니멀</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-02.png" width="150"><br><sub>야외 자연 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-03.png" width="150"><br><sub>야외 자연 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/01/Output-04.png" width="150"><br><sub>도시 거리</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-05.png" width="150"><br><sub>홈 씬</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-06.png" width="150"><br><sub>캐주얼 씬</sub></td>
  </tr>
</table>

#### 예시 2: 다크블루 케이블 니트

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/02/Input.jpg" width="160"><br>
      <sub>원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/02/Output-01.png" width="150"><br><sub>실내 씬 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-02.png" width="150"><br><sub>야외 씬 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-03.png" width="150"><br><sub>야외 씬 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/02/Output-04.png" width="150"><br><sub>도시 거리</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-05.png" width="150"><br><sub>홈 환경</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-06.png" width="150"><br><sub>기타 씬</sub></td>
  </tr>
</table>

### 케이스 7: 액세서리 착용

**입력:** 액세서리 제품 이미지를 업로드하세요.

**프롬프트:**

```
A model wearing this {accessory_type}, {additional_requirements}.
```

> [!NOTE]
> **사용 전 {accessory_type} 와 {additional_requirements} 를 교체하세요.** 예시: "모델이 이 목걸이를 착용, 얼굴은 보이지 않게" 또는 "모델이 이 귀걸이를 착용." 목걸이, 귀걸이, 모자, 스카프 등 착용 액세서리에 대응합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case13/01/Input.png" width="180"><br><sub>옥 펜던트 목걸이</sub></td>
    <td align="center"><img src="e-commerce/Case13/01/Output.png" width="180"><br><sub>모델 착용</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Input.jpg" width="180"><br><sub>골드 후프 귀걸이</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Output.png" width="180"><br><sub>모델 착용</sub></td>
  </tr>
</table>

### 케이스 8: 네일 어플리케이션

**입력:** 네일 디자인 참조 이미지를 업로드하세요.

**프롬프트:**

```
Apply these nails to hands.
```

> [!NOTE]
> 붙이는 네일, 젤 폴리시 컨셉, 살롱 디자인 프리뷰, 네일 제품 마케팅 크리에이티브에 적합합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case14/01/Input.jpg" width="180"><br><sub>핑크 네일 샘플</sub></td>
    <td align="center"><img src="e-commerce/Case14/01/Output-01.png" width="180"><br><sub>손에 적용</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Input.jpg" width="180"><br><sub>멀티 컬러 네일</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Output-01.png" width="180"><br><sub>손에 적용</sub></td>
  </tr>
</table>

### 케이스 9: 모델 슈즈 피팅

**입력:** 신발 제품 이미지를 업로드하세요.

**프롬프트:**

```
A model wearing the shoes from the image, {styling_description}.
```

> [!NOTE]
> **사용 전 {styling_description} 를 교체하세요.** 예시: "이미지의 신발을 착용한 모델, 갈색 짧은 치마와 코디." 스니커즈, 힐, 부츠, 시즌 슈즈 크리에이티브에 대응합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case15/01/Input.jpg" width="180"><br><sub>블랙 가죽 구두</sub></td>
    <td align="center"><img src="e-commerce/Case15/01/Output-01.png" width="180"><br><sub>남성 스타일링</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Input.jpg" width="180"><br><sub>블랙 하이힐</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Output-01.png" width="180"><br><sub>여성 스타일링</sub></td>
  </tr>
</table>

## 📦 제품 쇼케이스 프롬프트

### 케이스 1: 화이트 배경 제품 리터치

**입력:** 고화질 제품 사진을 업로드하세요.

**프롬프트:**

```
Generate a clean white-background retouched image.
```

> [!NOTE]
> 원본 품질이 높을수록 결과가 정확해집니다. 고품질 입력은 보통 더 충실한 제품 보존과 더 깔끔한 이커머스급 출력을 만들어냅니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case16/01/Input.png" width="180"><br><sub>씬 내 제품 사진</sub></td>
    <td align="center"><img src="e-commerce/Case16/01/Output-01.png" width="180"><br><sub>화이트 리터치</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/images.jpeg" width="180"><br><sub>원본 제품 사진</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/Output-01.png" width="180"><br><sub>화이트 리터치</sub></td>
  </tr>
</table>

### 케이스 2: 다각도 제품 뷰

**입력:** 제품 참조 이미지를 업로드하세요.

**프롬프트:**

```
Generate multi-angle product images.
```

> [!NOTE]
> 제품 카드, 캐러셀, 기능 분해, 각도별 상세 페이지에 적합합니다.

#### 예시 1: 탄 컬러 등산화

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/01/Input.png" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/01/Output-01.png" width="150"><br><sub>정면</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-02.png" width="150"><br><sub>45° 측면</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-03.png" width="150"><br><sub>뒷면</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/01/Output-04.png" width="150"><br><sub>밑창</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-05.png" width="150"><br><sub>위에서</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-06.png" width="150"><br><sub>기타 각도</sub></td>
  </tr>
</table>

#### 예시 2: 등산화 (다른 모델)

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/02/Input.png" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/02/Output-01.png" width="150"><br><sub>정면</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-02.png" width="150"><br><sub>측면</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-03.png" width="150"><br><sub>뒷면</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/02/Output-04.png" width="150"><br><sub>밑창 디테일</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-05.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-06.png" width="150"><br><sub>대체 각도</sub></td>
  </tr>
</table>

### 케이스 3: 소재·컬러 베리에이션

**입력:** 편집할 제품 또는 의류 이미지를 업로드하세요.

**프롬프트:**

```
Modify the material. Change the figure's clothing into: {material1}, {material2}, and {material3}.
```

> [!NOTE]
> **사용 전 {material1}, {material2}, {material3} 을 교체하세요.** 예시: "소재를 변경하세요. 인물의 옷을 라이트 그레이 스웨이드, 다크 브라운 데님, 와인 코듀로이로 바꿔 주세요." 원단 교체, 소재 테스트, 시즌 컬러 변경, 컨셉 탐색에 대응합니다.

#### 예시 1: 그린 자켓 소재 베리에이션

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/01/Input.jpg" width="160"><br>
      <sub>남성 원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/01/Output-01.png" width="150"><br><sub>베리에이션 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-02.png" width="150"><br><sub>베리에이션 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-03.png" width="150"><br><sub>베리에이션 3</sub></td>
  </tr>
</table>

#### 예시 2: 블랙 레더 자켓 소재 베리에이션

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/02/Input.avif" width="160"><br>
      <sub>남성 원본 모델</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/02/Output-01.png" width="150"><br><sub>베리에이션 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-02.png" width="150"><br><sub>베리에이션 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-03.png" width="150"><br><sub>베리에이션 3</sub></td>
  </tr>
</table>

### 케이스 4: 스마트 배경 생성

**입력:** 제품 이미지를 업로드하세요.

**프롬프트:**

```
Generate suitable product images.
```

> [!NOTE]
> 상세한 아트 디렉션 없이 모델이 가장 적합한 상업용 제품 배경을 추론하길 원할 때 사용합니다.

#### 예시 1: 스낵 박스

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/01/Input.webp" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/01/Output-01.png" width="200"><br><sub>스마트 배경 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-02.png" width="200"><br><sub>스마트 배경 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/01/Output-03.png" width="200"><br><sub>스마트 배경 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-04.png" width="200"><br><sub>스마트 배경 4</sub></td>
  </tr>
</table>

#### 예시 2: 스킨케어 세럼

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/02/Input.jpg" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/02/Output-01.png" width="200"><br><sub>스마트 배경 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-02.png" width="200"><br><sub>스마트 배경 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/02/Output-03.png" width="200"><br><sub>스마트 배경 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-04.png" width="200"><br><sub>스마트 배경 4</sub></td>
  </tr>
</table>

### 케이스 5: 커스텀 설명 기반 배경 교체

**입력:** 제품 이미지를 업로드하세요.

**프롬프트:**

```
Replace the background of the product in the image: {background_description}.
```

> [!NOTE]
> **사용 전 {background_description} 를 교체하세요.** 예시: "이미지 속 제품의 배경을 다음과 같이 교체해 주세요: 매끄러운 흰 돌 위에 놓인 향수병의 클로즈업, 부드러운 화이트와 페일 블루 꽃들에 둘러싸여 있고, 멀리에는 잔잔한 푸른 호수와 맑은 하늘 아래 산이 보이는 — 상쾌하고 가볍고 약간 차가운 미감." 새 씬에 대한 완전한 아트 디렉션을 원할 때 유용합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case20/01/Input.png" width="180"><br><sub>제품 사진</sub></td>
    <td align="center"><img src="e-commerce/Case20/01/Output-01.png" width="180"><br><sub>커스텀 배경</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Input.jpg" width="180"><br><sub>제품 사진</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Output-01.png" width="180"><br><sub>커스텀 배경</sub></td>
  </tr>
</table>

### 케이스 6: 참조 기반 제품 배경

**입력:** 제품 이미지와 참조 배경 이미지를 업로드하세요.

**프롬프트:**

```
Image 1 is my {product}. Generate the new scene using the background style from image 2.
```

> [!NOTE]
> **사용 전 {product} 를 교체하세요.** 예시: "이미지 1은 제 반지입니다. 이미지 2의 배경 스타일을 사용해 새 씬을 생성해 주세요." 미감 매칭, 브랜드 일관성, 카테고리별 비주얼 레퍼런스에 적합합니다.

#### 예시 1: 핑크 레트로 자동차

<table>
  <tr>
    <th>제품</th>
    <th>참조 배경</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/01/Input-01.jpg" width="180"><br><sub>핑크 레트로 자동차</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Input-02.jpg" width="180"><br><sub>그린 포레스트 참조</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Output.png" width="180"><br><sub>포레스트 합성</sub></td>
  </tr>
</table>

#### 예시 2: 레드 립스틱

<table>
  <tr>
    <th>제품</th>
    <th>참조 배경</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/02/Input-01.jpg" width="180"><br><sub>레드 립스틱</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Input-02.jpg" width="180"><br><sub>블랙 골드 마블 참조</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Output.png" width="180"><br><sub>마블 합성</sub></td>
  </tr>
</table>

## 🤝 제품 인터랙션 프롬프트

### 케이스 1: 핸드헬드 제품 클로즈업

**입력:** 제품 이미지를 업로드하세요.

**프롬프트:**

```
A hand is holding this product, {scene_description}, keep the product color unchanged.
{action_description}
```

> [!NOTE]
> **사용 전 {scene_description} 와 {action_description} 를 교체하세요.** 예시: "손이 이 제품을 들고 있는 모습, 패션 에디토리얼 배경, 제품 색상은 그대로 유지" 또는 "손에 전동 드릴, 나무에 구멍 뚫는 동작." 뷰티, 공구, 가젯, 패키지 상품, 촉감 제품 데모에 적합합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case22/01/Input.jpg" width="180"><br><sub>핑크 립글로스</sub></td>
    <td align="center"><img src="e-commerce/Case22/01/Output.png" width="180"><br><sub>립글로스 핸드샷</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Input.avif" width="180"><br><sub>나무 손잡이 대걸레</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Output.png" width="180"><br><sub>대걸레로 바닥 청소</sub></td>
  </tr>
</table>

### 케이스 2: 인물 인터랙션 씬 생성

**입력:** 제품 씬 이미지 또는 제품 이미지를 업로드하세요.

**프롬프트:**

```
Add a human model to this product scene. The model should be {person_description}, in a {pose}, performing {action}.
```

> [!NOTE]
> **사용 전 {person_description}, {pose}, {action} 을 교체하세요.** 예시: "이 제품 씬에 인물 모델을 추가. 어린 소녀, 서 있는 자세, 인형을 들고 있음" 또는 "이 제품 씬에 인물 모델을 추가, 대걸레를 들고 있음." 스케일감, 사용 방식, 감정, 오디언스 적합성을 보여주고 싶을 때 유용합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case23/01/Input.jpg" width="180"><br><sub>설맞이 레드 아치 씬</sub></td>
    <td align="center"><img src="e-commerce/Case23/01/Output-01.png" width="180"><br><sub>치파오 모델 등장</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Input.webp" width="180"><br><sub>레드·실버 헤드폰</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Output.png" width="180"><br><sub>헤드폰 착용 모델</sub></td>
  </tr>
</table>

### 케이스 3: 참조 인물의 제품 인터랙션

**입력:** 제품 씬 이미지와 참조 인물 이미지를 업로드하세요.

**프롬프트:**

```
Add the human model from image 2 into the product scene from image 1, with this action: {action_description}.
```

> [!NOTE]
> **사용 전 {action_description} 를 교체하세요.** 예시: "이미지 2의 인물 모델을 이미지 1의 제품 씬에 추가, 액션: 모델이 침대에 누움." 여러 크리에이티브 에셋에서 인물 아이덴티티를 일관되게 유지하고 싶을 때 유용합니다.

#### 예시 1: 킹사이즈 침실 씬 + 남성 모델

<table>
  <tr>
    <th>제품 씬</th>
    <th>참조 인물</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/01/Input-01.webp" width="180"><br><sub>킹사이즈 침실</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Input-02.jpg" width="180"><br><sub>화이트 티 남성 모델</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Output.png" width="180"><br><sub>침대에 기댄 남성 모델</sub></td>
  </tr>
</table>

#### 예시 2: 홈 로킹체어 씬 + 남성 모델

<table>
  <tr>
    <th>제품 씬</th>
    <th>참조 인물</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/02/Input-01.jpg" width="180"><br><sub>홈 로킹체어</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Input-02.jpg" width="180"><br><sub>화이트 셔츠 남성 모델</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Output.png" width="180"><br><sub>로킹체어의 남성 모델</sub></td>
  </tr>
</table>

### 케이스 4: 반려동물·제품 인터랙션

**입력:** 제품 이미지를 업로드하세요.

**프롬프트:**

```
Generate a {pet} interacting with the {product} from the image.
```

> [!NOTE]
> **사용 전 {pet} 와 {product} 를 교체하세요.** 예시: "이미지의 장난감과 상호작용하는 고양이를 생성" 또는 "이미지의 장난감과 상호작용하는 강아지를 생성." 장난감·반려동물 액세서리·홈·플레이풀 라이프스타일 제품 크리에이티브에 특히 적합합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case25/01/Input.jpg" width="180"><br><sub>오렌지 강아지 공</sub></td>
    <td align="center"><img src="e-commerce/Case25/01/Output.png" width="180"><br><sub>공 무는 강아지</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Input.jpg" width="180"><br><sub>햄스터 휠</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Output.png" width="180"><br><sub>휠 위 햄스터</sub></td>
  </tr>
</table>

## 🛍️ 소셜 커머스 프롬프트

### 케이스 1: 패션 스튜디오 판매 세트

**프롬프트:**

```
Generate a model sales image set, background is a fashion studio.
```

> [!NOTE]
> 쇼룸 스타일 의류 마케팅, 부티크 비주얼 머천다이징, 스튜디오 촬영 소셜 콘텐츠에 적합합니다.

#### 예시 1: 블루 후드

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/01/Input.png" width="160"><br>
      <sub>화이트 배경 제품</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/01/Output-01.png" width="200"><br><sub>스튜디오 촬영 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-02.png" width="200"><br><sub>스튜디오 촬영 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/01/Output-03.png" width="200"><br><sub>스튜디오 촬영 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-04.png" width="200"><br><sub>스튜디오 촬영 4</sub></td>
  </tr>
</table>

#### 예시 2: 핑크 플로럴 원피스

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/02/Input.webp" width="160"><br>
      <sub>화이트 배경 제품</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/02/Output-01.png" width="200"><br><sub>스튜디오 촬영 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-02.png" width="200"><br><sub>스튜디오 촬영 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/02/Output-03.png" width="200"><br><sub>스튜디오 촬영 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-04.png" width="200"><br><sub>스튜디오 촬영 4</sub></td>
  </tr>
</table>

### 케이스 2: 거울 코디 판매 영상

**프롬프트:**

```
Generate a mirror outfit sales video.
```

> [!NOTE]
> 이 템플릿은 크리에이터 스타일 패션 콘텐츠, UGC 미감, 캐주얼한 소셜 커머스 판매 포맷에 이상적입니다.

### 케이스 3: 의류 기프트 박스 스타일링

**입력:** 의류 이미지를 업로드하세요.

**프롬프트:**

```
Place the apparel into a gift box.
```

> [!NOTE]
> 홀리데이 기프트 마케팅, 프리미엄 패키지 목업, 시즌 테마 제품 크리에이티브에 적합합니다.

<table>
  <tr>
    <th>입력</th>
    <th>출력</th>
    <th>입력</th>
    <th>출력</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case33/01/Input.jpg" width="180"><br><sub>컬러 스플래터 티</sub></td>
    <td align="center"><img src="e-commerce/Case33/01/Output.png" width="180"><br><sub>기프트 박스 결과</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Input.jpg" width="180"><br><sub>레드 아동 다운자켓</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Output.png" width="180"><br><sub>기프트 박스 결과</sub></td>
  </tr>
</table>

### 케이스 4: 신선 식품 판매 씬 세트

**프롬프트:**

```
Generate a fresh-food scene set for {food_name}.
```

> [!NOTE]
> **사용 전 {food_name} 를 교체하세요.** 예시: "포멜로용 신선 식품 씬 세트를 생성하세요." 과일, 농산물, 박스 식품, 특화 식재료, 프리미엄 신선 진열에 적합합니다.

#### 예시 1: 수박

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/01/Input.webp" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/01/Output-01.png" width="200"><br><sub>신선 씬 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-02.png" width="200"><br><sub>신선 씬 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/01/Output-03.png" width="200"><br><sub>신선 씬 3</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-04.png" width="200"><br><sub>신선 씬 4</sub></td>
  </tr>
</table>

#### 예시 2: 포도

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/02/Input.jpg" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/02/Output-01.png" width="150"><br><sub>신선 씬 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-02.png" width="150"><br><sub>신선 씬 2</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-03.png" width="150"><br><sub>신선 씬 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/02/Output-04.png" width="150"><br><sub>신선 씬 4</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-05.png" width="150"><br><sub>신선 씬 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### 케이스 5: 일반 식품 판매 크리에이티브 세트

**프롬프트:**

```
Generate a food sales image set.
```

> [!NOTE]
> 스낵 브랜드, 패키지 식품, 신선 식품, 일반 소셜 커머스 식품 콘텐츠에 활용 가능한 유연한 베이스 템플릿입니다.

#### 예시 1: 팝콘

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="3">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/01/Input.jpg" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/01/Output-01.png" width="150"><br><sub>판매 이미지 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-02.png" width="150"><br><sub>판매 이미지 2</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-03.png" width="150"><br><sub>판매 이미지 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/01/Output-04.png" width="150"><br><sub>판매 이미지 4</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-05.png" width="150"><br><sub>판매 이미지 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### 예시 2: 탕후루 (과일 캔디 꼬치)

<table>
  <tr>
    <th width="20%">입력</th>
    <th colspan="2">출력</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/02/Input.webp" width="160"><br>
      <sub>제품 사진</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/02/Output-01.png" width="200"><br><sub>판매 이미지 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-02.png" width="200"><br><sub>판매 이미지 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/02/Output-03.png" width="200"><br><sub>판매 이미지 3</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-04.png" width="200"><br><sub>판매 이미지 4</sub></td>
  </tr>
</table>

## 🚀 Evolink API 로 일괄 생성

수백 개 SKU, 여러 언어, 여러 마켓플레이스에 걸친 프로덕션 런에서는 프롬프트를 하나씩 실행하는 대신 **Evolink GPT Image 2 API** 를 직접 호출하세요.

**API 일괄 처리의 장점:**

- 카탈로그 전체 리스팅 이미지 일괄 생성
- 모든 리스팅 자산의 다국어 번역을 단일 작업으로 처리
- 모델 교체·배경 교체·다각도 출력의 프로그래밍 자동화
- 웹훅 콜백으로 PIM·ERP·마케팅 자동화 시스템과 연동

**준비물:** [API 키 발급](https://evolink.ai/dashboard/keys).

### 1단계: 생성 작업 제출

GPT Image 2 생성은 **비동기** 입니다 — 호출은 `task_id` 를 반환하며, 이를 폴링하여 결과를 가져옵니다.

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

| 필드 | 필수 | 설명 |
| :--- | :--- | :--- |
| `model` | 필수 | `"gpt-image-2"` 고정 |
| `prompt` | 필수 | 최대 32,000 자 — 본 저장소의 어떤 케이스 프롬프트든 그대로 사용 가능 |
| `image_urls` | 선택 | 1–16 장의 입력·참조 이미지 (jpeg/png/webp, 각 ≤50 MB). image-to-image·편집 작업에 사용 |
| `size` | 선택 | 비율 (`1:1`, `2:3`, `16:9` …) 또는 픽셀 단위. 기본값 `auto` |
| `resolution` | 선택 | `1K` / `2K` / `4K` (size 가 비율일 때만 유효) |
| `quality` | 선택 | `low` / `medium` / `high` — 비용에 영향. 기본값 `medium` |
| `n` | 선택 | 호출당 1–10 장 |
| `callback_url` | 선택 | 폴링 대신 완료 알림을 받을 HTTPS 웹훅 |

### 2단계: 작업 상태 폴링

```bash
curl https://api.evolink.ai/v1/tasks/{task_id} \
  -H "Authorization: Bearer YOUR_API_KEY"
```

`status` 가 `"completed"` 가 되면 `results` 배열에 생성된 이미지 URL 이 담깁니다. **생성 이미지는 24시간만 유효하므로 신속히 다운로드하세요.**

### 옵션: 웹훅 콜백

제출 시 `"callback_url": "https://your-server.example.com/webhook"` 을 포함하면, 작업 완료 시 Evolink 가 결과를 해당 엔드포인트로 POST 합니다 — 폴링 불필요.

**전체 API 레퍼런스:** [docs.evolink.ai · GPT Image 2 이미지 생성](https://docs.evolink.ai/en/api-manual/image-series/gpt-image-2/gpt-image-2-image-generation)

## 🙏 감사의 글

이 저장소는 우수한 오픈소스 프롬프트 컬렉션과 커뮤니티가 공유한 이커머스 워크플로우에서 영감을 받았습니다.

작품을 공개하여 이 케이스 스터디를 가능하게 해주신 모든 크리에이터·기여자분들께 감사드립니다.

- [@EvoLinkAI](https://github.com/EvoLinkAI)

*모든 케이스에 대해 원작자 크레딧을 보장하기는 어렵습니다. 수정이 필요하면 연락 주세요. 즉시 업데이트하겠습니다.*

더 흥미로운 프롬프트 케이스를 공유하고 싶으시다면 언제든 연락 주세요. Evolink 프롬프트 라이브러리 확장에 함께해 주세요.

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/awesome-ecommerce-image-prompts&type=Date)](https://www.star-history.com/#EvoLinkAI/awesome-ecommerce-image-prompts&Date)
