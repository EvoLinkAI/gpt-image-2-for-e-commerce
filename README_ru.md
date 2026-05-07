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

# Как использовать GPT Image 2 для e-commerce

> Сборник промптов-рецептов для создания e-commerce изображений с **GPT Image 2** — фотографии листингов, виртуальная примерка, презентация товаров, сцены взаимодействия и креативы для social commerce.

## 🍌 Введение

Этот репозиторий показывает, **как использовать GPT Image 2 для создания e-commerce изображений** — фотографий листингов, главных изображений для разных стран, A+ визуалов, виртуальной примерки, витрин товара, сцен взаимодействия и креативов social commerce — на промышленных объёмах.

**Каждый кейс — это рецепт:** входная фотография товара, точный промпт для вставки в GPT Image 2 и реальные примеры результатов. Замените `{placeholders}` на свой товар, язык, страну и преимущества.

Нужно обработать сотни SKU за раз? Перейдите к [🚀 Пакетной генерации через API Evolink](#-пакетная-генерация-через-api-evolink).

Попробуйте на Evolink: [Workflow GPT Image 2](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts)

Если репозиторий полезен — поставьте ⭐

> [!NOTE]
> Этот репозиторий сфокусирован на переиспользуемых шаблонах промптов для e-commerce креативов. Замените плейсхолдеры в фигурных скобках перед использованием и адаптируйте под вашу реальную платформу, рынок, язык, товар, материал, тип модели и преимущества.

<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🚀 Try%20it%20on-Evolink-black' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🌐 Website-Evolink-orange' height="25"></a>
<a href='https://docs.evolink.ai'><img src='https://img.shields.io/badge/📘 Docs-Evolink-blue' height="25"></a>
<a href='https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts'><img src='https://img.shields.io/badge/🤗 Dataset-Evolink-yellow' height="25"></a>

## ⚡ Быстрый старт

1. **Выберите кейс** ниже, соответствующий вашей e-commerce задаче (главное изображение листинга, примерка на модели, мультиракурсный товар, A+ визуалы и т. д.).
2. **Загрузите фото товара** и **скопируйте промпт** из кейса — замените `{placeholders}` на свой товар, язык, страну, платформу и преимущества.
3. **Запустите в GPT Image 2** — для одиночных креативов через [UI Evolink workflow](https://evolink.ai?utm_source=github&utm_medium=readme&utm_campaign=awesome-ecommerce-image-prompts, для массовых SKU и мультиязычных раскаток через [API Evolink](#-пакетная-генерация-через-api-evolink).

## 📰 Новости

- **7 мая 2026:** Перепозиционировали библиотеку промптов вокруг **GPT Image 2 для e-commerce**, добавили раздел Быстрого старта и Пакетной генерации через API Evolink.
- **5 мая 2026:** Расширили категории изображений листингов, примерки на модели и витрин товаров до полного набора паттернов промптов e-commerce агента.
- **30 апреля 2026:** Добавили полные категории промптов для изображений листингов, редактирования моделей, витрин товаров, сцен взаимодействия и креативов social commerce.
- **30 апреля 2026:** Первый каркас репозитория English-first для e-commerce image prompt workflows.

## 📑 Содержание

- [🍌 Введение](#-введение)
- [⚡ Быстрый старт](#-быстрый-старт)
- [📰 Новости](#-новости)
- [📑 Содержание](#-содержание)
- [🖼️ Промпты изображений листингов e-commerce](#️-промпты-изображений-листингов-e-commerce)
  - [Кейс 1: Набор изображений для маркетплейса](#кейс-1-набор-изображений-для-маркетплейса)
  - [Кейс 2: Набор изображений для разных стран](#кейс-2-набор-изображений-для-разных-стран)
  - [Кейс 3: A+ детальные визуалы товара](#кейс-3-a-детальные-визуалы-товара)
  - [Кейс 4: Массовая генерация листингов Amazon](#кейс-4-массовая-генерация-листингов-amazon)
  - [Кейс 5: Массовая замена главного изображения](#кейс-5-массовая-замена-главного-изображения)
  - [Кейс 6: Массовый перевод листингов](#кейс-6-массовый-перевод-листингов)
- [👗 Промпты примерки на модели и одежды](#-промпты-примерки-на-модели-и-одежды)
  - [Кейс 1: Набор изображений примерки одежды](#кейс-1-набор-изображений-примерки-одежды)
  - [Кейс 2: Примерка на модели и питомце](#кейс-2-примерка-на-модели-и-питомце)
  - [Кейс 3: Расширение поз модели](#кейс-3-расширение-поз-модели)
  - [Кейс 4: Замена модели с контролем внешности](#кейс-4-замена-модели-с-контролем-внешности)
  - [Кейс 5: Замена модели по референсу](#кейс-5-замена-модели-по-референсу)
  - [Кейс 6: Концепции фона для продажи одежды](#кейс-6-концепции-фона-для-продажи-одежды)
  - [Кейс 7: Примерка аксессуаров](#кейс-7-примерка-аксессуаров)
  - [Кейс 8: Нанесение ногтей](#кейс-8-нанесение-ногтей)
  - [Кейс 9: Примерка обуви на модели](#кейс-9-примерка-обуви-на-модели)
- [📦 Промпты витрины товара](#-промпты-витрины-товара)
  - [Кейс 1: Ретушь товара на чистом белом фоне](#кейс-1-ретушь-товара-на-чистом-белом-фоне)
  - [Кейс 2: Мультиракурсные виды товара](#кейс-2-мультиракурсные-виды-товара)
  - [Кейс 3: Варианты материала и цвета](#кейс-3-варианты-материала-и-цвета)
  - [Кейс 4: Умная генерация фона](#кейс-4-умная-генерация-фона)
  - [Кейс 5: Замена фона по пользовательскому описанию](#кейс-5-замена-фона-по-пользовательскому-описанию)
  - [Кейс 6: Фон товара по референсу](#кейс-6-фон-товара-по-референсу)
- [🤝 Промпты взаимодействия с товаром](#-промпты-взаимодействия-с-товаром)
  - [Кейс 1: Крупный план товара в руке](#кейс-1-крупный-план-товара-в-руке)
  - [Кейс 2: Сгенерированная сцена с человеком](#кейс-2-сгенерированная-сцена-с-человеком)
  - [Кейс 3: Взаимодействие с товаром через референсного персонажа](#кейс-3-взаимодействие-с-товаром-через-референсного-персонажа)
  - [Кейс 4: Взаимодействие питомца и товара](#кейс-4-взаимодействие-питомца-и-товара)
- [🛍️ Промпты Social Commerce](#️-промпты-social-commerce)
  - [Кейс 1: Набор продаж в фэшн-студии](#кейс-1-набор-продаж-в-фэшн-студии)
  - [Кейс 2: Видео продажи лука у зеркала](#кейс-2-видео-продажи-лука-у-зеркала)
  - [Кейс 3: Стайлинг подарочной коробки для одежды](#кейс-3-стайлинг-подарочной-коробки-для-одежды)
  - [Кейс 4: Набор сцен продажи свежих продуктов](#кейс-4-набор-сцен-продажи-свежих-продуктов)
  - [Кейс 5: Креативный набор продажи продуктов](#кейс-5-креативный-набор-продажи-продуктов)
- [🚀 Пакетная генерация через API Evolink](#-пакетная-генерация-через-api-evolink)
- [🙏 Благодарности](#-благодарности)

## 🖼️ Промпты изображений листингов e-commerce

### Кейс 1: Набор изображений для маркетплейса

**Промпт:**

```
Generate a {platform} listing image set for {country} in {language}. The product is {product_name}, and the selling points are {selling_points}.
```

> [!NOTE]
> **Перед использованием замените {platform}, {country}, {language}, {product_name} и {selling_points}.** Этот шаблон подходит для Amazon, eBay, AliExpress, TEMU, SHEIN, TikTok Shop, Shopee, Lazada, Mercado Libre, Walmart, Etsy, Rakuten, Coupang, Shopify и других маркетплейсов. Агент спланирует ассеты листинга под платформу: изображения на чистом белом фоне, схемы размеров, мультиракурсные виды, лайфстайл-сцены, изображения с преимуществами и детали материала.

#### Пример 1: Стул из массива дерева

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="4">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/01/input.webp" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/01/output-01.png" width="150"><br><sub>Главное чистый фон</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-02.png" width="150"><br><sub>Преимущества</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-03.png" width="150"><br><sub>Схема размеров</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-04.png" width="150"><br><sub>Мультиракурс</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/01/output-05.png" width="150"><br><sub>Лайфстайл-сцена</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-06.png" width="150"><br><sub>Сцена использования</sub></td>
    <td align="center"><img src="e-commerce/Case1/01/output-08.png" width="150"><br><sub>Деталь материала</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### Пример 2: Спортивная бутылка

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/02/input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/02/output-01.png" width="150"><br><sub>Главное чистый фон</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-02.png" width="150"><br><sub>Мультиракурс</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-03.png" width="150"><br><sub>Преимущества</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/02/output-04.png" width="150"><br><sub>Схема размеров</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-05.png" width="150"><br><sub>Сцена использования</sub></td>
    <td align="center"><img src="e-commerce/Case1/02/output-06.png" width="150"><br><sub>Деталь материала</sub></td>
  </tr>
</table>

#### Пример 3: Спортивная футболка

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="4">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case1/03/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case1/03/Output-01.png" width="150"><br><sub>Преимущества</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-02.png" width="150"><br><sub>Характеристики</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-03.png" width="150"><br><sub>Таблица размеров</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-04.png" width="150"><br><sub>Мультиракурс</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case1/03/Output-05.png" width="150"><br><sub>Сцена использования</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-06.png" width="150"><br><sub>Деталь материала</sub></td>
    <td align="center"><img src="e-commerce/Case1/03/Output-07.png" width="150"><br><sub>Сводка преимуществ</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### Кейс 2: Набор изображений для разных стран

**Промпт:**

```
Generate a {platform} listing image set for {country} in {language}.
```

> [!NOTE]
> **Перед использованием замените {platform}, {country} и {language}.** Используйте этот сокращённый шаблон, когда хотите, чтобы модель автоматически определила лучшую раскладку листинга.

#### Пример 1: Фиолетовое платье в горошек

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/01/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ar.png" width="150"><br><sub>Арабский</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Cn.png" width="150"><br><sub>Китайский</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-En.png" width="150"><br><sub>Английский</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/01/Output-Ja.png" width="150"><br><sub>Японский</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Kr.png" width="150"><br><sub>Корейский</sub></td>
    <td align="center"><img src="e-commerce/Case2/01/Output-Pt.png" width="150"><br><sub>Португальский</sub></td>
  </tr>
</table>

#### Пример 2: Беспроводной пылесос

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/02/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Bn.png" width="150"><br><sub>Бенгальский</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-De.png" width="150"><br><sub>Немецкий</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Es%20.png" width="150"><br><sub>Испанский</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/02/Output-Fr.png" width="150"><br><sub>Французский</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Hi.png" width="150"><br><sub>Хинди</sub></td>
    <td align="center"><img src="e-commerce/Case2/02/Output-Ru.png" width="150"><br><sub>Русский</sub></td>
  </tr>
</table>

#### Пример 3: Чехол на телефон с рождественским мотивом

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case2/03/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Id.png" width="150"><br><sub>Индонезийский</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-It.png" width="150"><br><sub>Итальянский</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Nl.png" width="150"><br><sub>Нидерландский</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case2/03/Output-Th.png" width="150"><br><sub>Тайский</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Tr.png" width="150"><br><sub>Турецкий</sub></td>
    <td align="center"><img src="e-commerce/Case2/03/Output-Vi.png" width="150"><br><sub>Вьетнамский</sub></td>
  </tr>
</table>

### Кейс 3: A+ детальные визуалы товара

**Промпт:**

```
This is a {product_description}. Generate A+ detail visuals for {country} in {language}.
```

> [!NOTE]
> **Перед использованием замените {product_description}, {country} и {language}.** Пример: «Это коробка кофейных зёрен. Сгенерируй A+ детальные визуалы для США на английском.» Полезно для сторителлинга, разбора функций, сцен использования и премиум-макетов страниц с деталями.

#### Пример 1: Премиальный подарочный набор чая

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/01/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/01/Output-01.png" width="150"><br><sub>Hero (преимущества)</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-02.png" width="150"><br><sub>Дизайн и ремесло</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-03.png" width="150"><br><sub>Линейка товаров</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/01/Output-04.png" width="150"><br><sub>Инструкция</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-05.png" width="150"><br><sub>Подарочная сцена</sub></td>
    <td align="center"><img src="e-commerce/Case3/01/Output-06.png" width="150"><br><sub>Сцена использования</sub></td>
  </tr>
</table>

#### Пример 2: Натуральный клей-карандаш

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/02/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/02/Output-01.png" width="150"><br><sub>A+ Hero</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-02.png" width="150"><br><sub>A+ Деталь 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-03.png" width="150"><br><sub>A+ Деталь 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/02/Output-04.png" width="150"><br><sub>A+ Деталь 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-05.png" width="150"><br><sub>A+ Деталь 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/02/Output-06.png" width="150"><br><sub>A+ Сводка</sub></td>
  </tr>
</table>

#### Пример 3: Бабл-ти

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case3/03/Input.png" width="160" alt="Оригинальный товар"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case3/03/Output-01.png" width="150"><br><sub>A+ Hero</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-02.png" width="150"><br><sub>A+ Деталь 1</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-03.png" width="150"><br><sub>A+ Деталь 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case3/03/Output-04.png" width="150"><br><sub>A+ Деталь 3</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-05.png" width="150"><br><sub>A+ Деталь 4</sub></td>
    <td align="center"><img src="e-commerce/Case3/03/Output-06.png" width="150"><br><sub>A+ Сводка</sub></td>
  </tr>
</table>

### Кейс 4: Массовая генерация листингов Amazon

> [!NOTE]
> Используйте, когда нужно массово генерировать листинги для нескольких SKU одной категории. Запуск пакетов по языкам пока не поддерживается.

### Кейс 5: Массовая замена главного изображения

**Вход:** Загрузите исходное изображение товара и целевой набор листинга.

**Промпт:**

```
Replace the product in image 1 across images 2–7. Only the swapped product changes; keep everything else identical.
```

> [!NOTE]
> Воссоздание вирусного листинга в одно нажатие — меняем товар, не перерисовывая макет. Полезно, когда много SKU используют один и тот же креатив.

#### Пример 1: Шарообразный ночник (заменён в вирусном наборе с грибной лампой)

<table>
  <tr>
    <th width="14%">Исходный товар</th>
    <th colspan="6">Вирусный набор (для замены)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/01/Input-01.png" width="120"><br>
      <sub>Шарообразный ночник</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/01/Input-02.png" width="110"><br><sub>Исходное главное 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-03.png" width="110"><br><sub>Исходное главное 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-04.png" width="110"><br><sub>Исходное главное 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-05.png" width="110"><br><sub>Исходное главное 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-06.png" width="110"><br><sub>Исходное главное 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Input-07.png" width="110"><br><sub>Исходное главное 6</sub></td>
  </tr>
  <tr>
    <th colspan="6">Заменённый набор</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/01/Output-02.png" width="110"><br><sub>Заменено 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-03.png" width="110"><br><sub>Заменено 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-04.png" width="110"><br><sub>Заменено 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-05.png" width="110"><br><sub>Заменено 4</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-06.png" width="110"><br><sub>Заменено 5</sub></td>
    <td align="center"><img src="e-commerce/Case5/01/Output-07.png" width="110"><br><sub>Заменено 6</sub></td>
  </tr>
</table>

#### Пример 2: Деревянная прикроватная тумба (заменена в вирусном наборе с красным шкафом)

<table>
  <tr>
    <th width="14%">Исходный товар</th>
    <th colspan="4">Вирусный набор (для замены)</th>
  </tr>
  <tr>
    <td rowspan="3" align="center">
      <img src="e-commerce/Case5/02/Input.png" width="120"><br>
      <sub>Деревянная тумба</sub>
    </td>
    <td align="center"><img src="e-commerce/Case5/02/Input-01.png" width="120"><br><sub>Исходное главное 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-02.png" width="120"><br><sub>Исходное главное 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-03.png" width="120"><br><sub>Исходное главное 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Input-04.png" width="120"><br><sub>Исходное главное 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Заменённый набор</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case5/02/Output-01.png" width="120"><br><sub>Заменено 1</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-02.png" width="120"><br><sub>Заменено 2</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-03.png" width="120"><br><sub>Заменено 3</sub></td>
    <td align="center"><img src="e-commerce/Case5/02/Output-04.png" width="120"><br><sub>Заменено 4</sub></td>
  </tr>
</table>

### Кейс 6: Массовый перевод листингов

**Вход:** Загрузите все изображения листинга, содержащие текст.

**Промпт:**

```
Translate the text in all images into {target_language}.
```

> [!NOTE]
> **Перед использованием замените {target_language}.** Пример: «Переведи текст на всех изображениях на английский.» Пакетно переводит тексты листингов между языками с сохранением исходного макета — идеально для глобальной раскатки в один клик.

#### Пример 1: Листинг шкафа (ZH → EN)

<table>
  <tr>
    <th colspan="4">Оригинал</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Input-01.png" width="140"><br><sub>Оригинал 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-02.png" width="140"><br><sub>Оригинал 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-03.png" width="140"><br><sub>Оригинал 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Input-04.png" width="140"><br><sub>Оригинал 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Перевод</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/01/Output-01.png" width="140"><br><sub>Перевод 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-02.png" width="140"><br><sub>Перевод 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-03.png" width="140"><br><sub>Перевод 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/01/Output-04.png" width="140"><br><sub>Перевод 4</sub></td>
  </tr>
</table>

#### Пример 2: Листинг шкафа (мультиязычный пакетный перевод)

<table>
  <tr>
    <th colspan="4">Оригинал</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Input-01.png" width="140"><br><sub>Оригинал 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-02.png" width="140"><br><sub>Оригинал 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-03.png" width="140"><br><sub>Оригинал 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Input-04.png" width="140"><br><sub>Оригинал 4</sub></td>
  </tr>
  <tr>
    <th colspan="4">Перевод</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case6/02/Output-01.png" width="140"><br><sub>Перевод 1</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-02.png" width="140"><br><sub>Перевод 2</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-03.png" width="140"><br><sub>Перевод 3</sub></td>
    <td align="center"><img src="e-commerce/Case6/02/Output-04.png" width="140"><br><sub>Перевод 4</sub></td>
  </tr>
</table>

## 👗 Промпты примерки на модели и одежды

### Кейс 1: Набор изображений примерки одежды

**Промпт:**

```
This is a {apparel_type}. Generate a try-on image set for {country}.
```

> [!NOTE]
> **Перед использованием замените {apparel_type} и {country}.** Пример: «Это платье. Сгенерируй набор изображений примерки для США.» Подходит для платьев, топов, верхней одежды, детской одежды и любой категории с коммерческой примеркой.

#### Пример 1: Зелёное платье с цветами

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/01/Input.png" width="160"><br>
      <sub>Товар чистый фон</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/01/Output-1.png" width="150"><br><sub>Модель спереди</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-2.png" width="150"><br><sub>Мультиракурс</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-3.png" width="150"><br><sub>Крупный план</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/01/Output-4.png" width="150"><br><sub>Полный лук</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-5.png" width="150"><br><sub>Лайфстайл-сцена</sub></td>
    <td align="center"><img src="e-commerce/Case7/01/Output-6.png" width="150"><br><sub>Другой ракурс</sub></td>
  </tr>
</table>

#### Пример 2: Традиционное индийское сари

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case7/02/Input.png" width="160"><br>
      <sub>Товар чистый фон</sub>
    </td>
    <td align="center"><img src="e-commerce/Case7/02/Output-01.png" width="150"><br><sub>Модель спереди</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-02.png" width="150"><br><sub>Спина / поворот</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-03.png" width="150"><br><sub>Деталь</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case7/02/Output-04.png" width="150"><br><sub>Полный лук</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-05.png" width="150"><br><sub>Лайфстайл-сцена</sub></td>
    <td align="center"><img src="e-commerce/Case7/02/Output-06.png" width="150"><br><sub>Другой ракурс</sub></td>
  </tr>
</table>

### Кейс 2: Примерка на модели и питомце

**Вход:** Загрузите изображение одежды или аксессуара.

**Промпт:**

```
Generate a model wearing this garment.
Generate a pet dog wearing this garment.
```

> [!NOTE]
> Этот шаблон покрывает примерку как на людях, так и на питомцах — подходит для одежды, реквизита косплея и креативов для пет-фэшн, где одну вещь нужно показать на разных субъектах.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case8/01/Input.png" width="140"><br><sub>Футболка #LOVE</sub></td>
    <td align="center"><img src="e-commerce/Case8/01/Output-01.png" width="140"><br><sub>Мужская модель</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Input.jpg" width="140"><br><sub>Велофутболка</sub></td>
    <td align="center"><img src="e-commerce/Case8/02/Output-01.png" width="140"><br><sub>Мужская модель</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Input.webp" width="140"><br><sub>Вязаный полузамок</sub></td>
    <td align="center"><img src="e-commerce/Case8/03/Output-01.png" width="140"><br><sub>Женская модель</sub></td>
  </tr>
</table>

### Кейс 3: Расширение поз модели

**Вход:** Загрузите оригинальное изображение модели в одежде.

**Промпт:**

```
Expand the model into more poses.
```

> [!NOTE]
> Генерирует варианты в профиль, поворот на 45°, в движении и другие позы — чтобы расширить набор ассетов без пересъёмки.

#### Пример 1: Футболка с принтом #LOVE

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="4">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/01/Input.png" width="160"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/01/Output-01.png" width="150"><br><sub>Поза анфас</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-02.png" width="150"><br><sub>Сбоку</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-03.png" width="150"><br><sub>Поворот 45°</sub></td>
    <td align="center"><img src="e-commerce/Case9/01/Output-04.png" width="150"><br><sub>Идёт</sub></td>
  </tr>
</table>

#### Пример 2: Серый пуловер с полузастёжкой

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="4">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case9/02/Input.png" width="160"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case9/02/Output-01.png" width="150"><br><sub>Поза анфас</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-02.png" width="150"><br><sub>Сбоку</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-03.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case9/02/Output-04.png" width="150"><br><sub>Идёт</sub></td>
  </tr>
</table>

### Кейс 4: Замена модели с контролем внешности

**Вход:** Загрузите оригинальное изображение модели в одежде.

**Промпт:**

```
Replace the model with a {ethnicity} model, {hair_description}, while keeping the outfit unchanged.
Replace the figure with a {ethnicity} model, {skin_tone} skin, {hair_color} hair, while keeping the outfit unchanged.
```

> [!NOTE]
> **Перед использованием замените {ethnicity}, {hair_description}, {skin_tone} и {hair_color}.** Пример: «Замени модель на чёрную модель с дредами, оставив одежду неизменной» или «Замени персонажа на белую женскую модель со светлой кожей и блондом, не меняя одежду.» Помогает локализовать фэшн-креативы под разные аудитории без пересъёмки.

#### Пример 1: Футболка с принтом #LOVE

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/01/Input.png" width="160"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case10/01/Output-01.png" width="180"><br><sub>Заменённая v1</sub></td>
    <td align="center"><img src="e-commerce/Case10/01/Output-02.png" width="180"><br><sub>Заменённая v2</sub></td>
  </tr>
</table>

#### Пример 2: Серый пуловер с полузастёжкой

<table>
  <tr>
    <th width="40%">Вход</th>
    <th width="60%">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case10/02/Input.png" width="200"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center">
      <img src="e-commerce/Case10/02/Output-01.png" width="200"><br>
      <sub>Заменённая модель</sub>
    </td>
  </tr>
</table>

### Кейс 5: Замена модели по референсу

**Вход:** Загрузите изображение оригинальной модели и референсной модели.

**Промпт:**

```
Replace the model in image 1 with the model in image 2, keeping the same pose.
```

> [!NOTE]
> Используйте, когда хотите зафиксировать конкретную модель в нескольких ассетах, переиспользуя исходный наряд и позу.

#### Пример 1: Замена женской модели

<table>
  <tr>
    <th>Оригинальная модель</th>
    <th>Референсная модель</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/01/Input-01.jpg" width="180"><br><sub>Оригинальная модель</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Input-02.png" width="180"><br><sub>Референсная модель</sub></td>
    <td align="center"><img src="e-commerce/Case11/01/Output.png" width="180"><br><sub>Результат замены</sub></td>
  </tr>
</table>

#### Пример 2: Замена мужской модели

<table>
  <tr>
    <th>Оригинальная модель</th>
    <th>Референсная модель</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case11/02/Input-01.jpeg" width="180"><br><sub>Оригинальная модель</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Input-02.jpeg" width="180"><br><sub>Референсная модель</sub></td>
    <td align="center"><img src="e-commerce/Case11/02/Output.png" width="180"><br><sub>Результат замены</sub></td>
  </tr>
</table>

### Кейс 6: Концепции фона для продажи одежды

**Промпт:**

```
Generate suitable background images for {apparel_type} sales display. Provide several indoor and outdoor options to choose from.
```

> [!NOTE]
> **Перед использованием замените {apparel_type}.** Пример: «Сгенерируй фоновые изображения для витрины детской одежды. Предложи несколько вариантов в помещении и на улице.» Полезно, когда вы разделяете создание сцен и генерацию моделей в своём workflow.

#### Пример 1: Бежевый вязаный пуловер

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/01/Input.jpeg" width="160"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/01/Output-01.png" width="150"><br><sub>Интерьер минимал</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-02.png" width="150"><br><sub>На природе 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-03.png" width="150"><br><sub>На природе 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/01/Output-04.png" width="150"><br><sub>Городская улица</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-05.png" width="150"><br><sub>Домашняя сцена</sub></td>
    <td align="center"><img src="e-commerce/Case12/01/Output-06.png" width="150"><br><sub>Кэжуал-сцена</sub></td>
  </tr>
</table>

#### Пример 2: Тёмно-синий вязаный свитер

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case12/02/Input.jpg" width="160"><br>
      <sub>Оригинальная модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case12/02/Output-01.png" width="150"><br><sub>В помещении 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-02.png" width="150"><br><sub>На улице 1</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-03.png" width="150"><br><sub>На улице 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case12/02/Output-04.png" width="150"><br><sub>Городская улица</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-05.png" width="150"><br><sub>Домашняя среда</sub></td>
    <td align="center"><img src="e-commerce/Case12/02/Output-06.png" width="150"><br><sub>Другая сцена</sub></td>
  </tr>
</table>

### Кейс 7: Примерка аксессуаров

**Вход:** Загрузите изображение товара-аксессуара.

**Промпт:**

```
A model wearing this {accessory_type}, {additional_requirements}.
```

> [!NOTE]
> **Перед использованием замените {accessory_type} и {additional_requirements}.** Пример: «Модель в этом ожерелье, лицо не показывать» или «Модель в этих серьгах.» Подходит для ожерелий, серёг, шляп, шарфов и других носимых аксессуаров.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case13/01/Input.png" width="180"><br><sub>Колье с нефритом</sub></td>
    <td align="center"><img src="e-commerce/Case13/01/Output.png" width="180"><br><sub>На модели</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Input.jpg" width="180"><br><sub>Золотые серьги-кольца</sub></td>
    <td align="center"><img src="e-commerce/Case13/02/Output.png" width="180"><br><sub>На модели</sub></td>
  </tr>
</table>

### Кейс 8: Нанесение ногтей

**Вход:** Загрузите референсное изображение дизайна ногтей.

**Промпт:**

```
Apply these nails to hands.
```

> [!NOTE]
> Полезно для накладных ногтей, концептов гель-лаков, салонных превью и маркетинговых креативов nail-продуктов.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case14/01/Input.jpg" width="180"><br><sub>Розовые образцы ногтей</sub></td>
    <td align="center"><img src="e-commerce/Case14/01/Output-01.png" width="180"><br><sub>На руке</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Input.jpg" width="180"><br><sub>Цветные образцы ногтей</sub></td>
    <td align="center"><img src="e-commerce/Case14/02/Output-01.png" width="180"><br><sub>На руке</sub></td>
  </tr>
</table>

### Кейс 9: Примерка обуви на модели

**Вход:** Загрузите изображение обуви.

**Промпт:**

```
A model wearing the shoes from the image, {styling_description}.
```

> [!NOTE]
> **Перед использованием замените {styling_description}.** Пример: «Модель в обуви из изображения с короткой коричневой юбкой.» Подходит для кроссовок, каблуков, ботинок и сезонных коллекций обуви.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case15/01/Input.jpg" width="180"><br><sub>Чёрные кожаные туфли</sub></td>
    <td align="center"><img src="e-commerce/Case15/01/Output-01.png" width="180"><br><sub>Мужской лук</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Input.jpg" width="180"><br><sub>Чёрные туфли на каблуке</sub></td>
    <td align="center"><img src="e-commerce/Case15/02/Output-01.png" width="180"><br><sub>Женский лук</sub></td>
  </tr>
</table>

## 📦 Промпты витрины товара

### Кейс 1: Ретушь товара на чистом белом фоне

**Вход:** Загрузите качественную фотографию товара.

**Промпт:**

```
Generate a clean white-background retouched image.
```

> [!NOTE]
> Чем выше качество исходника, тем точнее результат. Качественные входные данные обычно дают более точное сохранение товара и чистый e-commerce-вывод.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case16/01/Input.png" width="180"><br><sub>Товар в сцене</sub></td>
    <td align="center"><img src="e-commerce/Case16/01/Output-01.png" width="180"><br><sub>Ретушь на белом</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/images.jpeg" width="180"><br><sub>Сырое фото товара</sub></td>
    <td align="center"><img src="e-commerce/Case16/02/Output-01.png" width="180"><br><sub>Ретушь на белом</sub></td>
  </tr>
</table>

### Кейс 2: Мультиракурсные виды товара

**Вход:** Загрузите референсное изображение товара.

**Промпт:**

```
Generate multi-angle product images.
```

> [!NOTE]
> Полезно для карточек товара, каруселей, разбора функций и страниц с детализацией по ракурсам.

#### Пример 1: Светло-коричневые ботинки

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/01/Input.png" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/01/Output-01.png" width="150"><br><sub>Спереди</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-02.png" width="150"><br><sub>45° сбоку</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-03.png" width="150"><br><sub>Сзади</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/01/Output-04.png" width="150"><br><sub>Подошва</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-05.png" width="150"><br><sub>Сверху</sub></td>
    <td align="center"><img src="e-commerce/Case17/01/Output-06.png" width="150"><br><sub>Другой угол</sub></td>
  </tr>
</table>

#### Пример 2: Походные ботинки (другая модель)

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case17/02/Input.png" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case17/02/Output-01.png" width="150"><br><sub>Спереди</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-02.png" width="150"><br><sub>Сбоку</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-03.png" width="150"><br><sub>Сзади</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case17/02/Output-04.png" width="150"><br><sub>Деталь подошвы</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-05.png" width="150"><br><sub>45°</sub></td>
    <td align="center"><img src="e-commerce/Case17/02/Output-06.png" width="150"><br><sub>Альт. ракурс</sub></td>
  </tr>
</table>

### Кейс 3: Варианты материала и цвета

**Вход:** Загрузите изображение товара или одежды для редактирования.

**Промпт:**

```
Modify the material. Change the figure's clothing into: {material1}, {material2}, and {material3}.
```

> [!NOTE]
> **Перед использованием замените {material1}, {material2} и {material3}.** Пример: «Измени материал. Замени одежду на: светло-серая замша, тёмно-коричневый деним и бордовый вельвет.» Подходит для замены тканей, тестирования материалов, сезонной перекраски и поиска концепций.

#### Пример 1: Варианты материала зелёной куртки

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/01/Input.jpg" width="160"><br>
      <sub>Исх. муж. модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/01/Output-01.png" width="150"><br><sub>Вариант 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-02.png" width="150"><br><sub>Вариант 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/01/Output-03.png" width="150"><br><sub>Вариант 3</sub></td>
  </tr>
</table>

#### Пример 2: Варианты материала чёрной кожаной куртки

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td align="center">
      <img src="e-commerce/Case18/02/Input.avif" width="160"><br>
      <sub>Исх. муж. модель</sub>
    </td>
    <td align="center"><img src="e-commerce/Case18/02/Output-01.png" width="150"><br><sub>Вариант 1</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-02.png" width="150"><br><sub>Вариант 2</sub></td>
    <td align="center"><img src="e-commerce/Case18/02/Output-03.png" width="150"><br><sub>Вариант 3</sub></td>
  </tr>
</table>

### Кейс 4: Умная генерация фона

**Вход:** Загрузите изображение товара.

**Промпт:**

```
Generate suitable product images.
```

> [!NOTE]
> Используйте, когда хотите, чтобы модель сама подобрала наиболее подходящий коммерческий фон без детального арт-дирекшена.

#### Пример 1: Коробка снеков

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/01/Input.webp" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/01/Output-01.png" width="200"><br><sub>Умный фон 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-02.png" width="200"><br><sub>Умный фон 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/01/Output-03.png" width="200"><br><sub>Умный фон 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/01/Output-04.png" width="200"><br><sub>Умный фон 4</sub></td>
  </tr>
</table>

#### Пример 2: Сыворотка для лица

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case19/02/Input.jpg" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case19/02/Output-01.png" width="200"><br><sub>Умный фон 1</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-02.png" width="200"><br><sub>Умный фон 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case19/02/Output-03.png" width="200"><br><sub>Умный фон 3</sub></td>
    <td align="center"><img src="e-commerce/Case19/02/Output-04.png" width="200"><br><sub>Умный фон 4</sub></td>
  </tr>
</table>

### Кейс 5: Замена фона по пользовательскому описанию

**Вход:** Загрузите изображение товара.

**Промпт:**

```
Replace the background of the product in the image: {background_description}.
```

> [!NOTE]
> **Перед использованием замените {background_description}.** Пример: «Замени фон товара на следующее: крупный план флакона духов на гладком белом камне, окружённый мягкими белыми и бледно-голубыми цветами, вдали — спокойное синее озеро и горы под чистым небом — свежая, лёгкая и слегка прохладная эстетика.» Полезно, когда вы хотите полный арт-дирекшн над новой сценой.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case20/01/Input.png" width="180"><br><sub>Фото товара</sub></td>
    <td align="center"><img src="e-commerce/Case20/01/Output-01.png" width="180"><br><sub>Кастомный фон</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Input.jpg" width="180"><br><sub>Фото товара</sub></td>
    <td align="center"><img src="e-commerce/Case20/02/Output-01.png" width="180"><br><sub>Кастомный фон</sub></td>
  </tr>
</table>

### Кейс 6: Фон товара по референсу

**Вход:** Загрузите изображение товара и референсное изображение фона.

**Промпт:**

```
Image 1 is my {product}. Generate the new scene using the background style from image 2.
```

> [!NOTE]
> **Перед использованием замените {product}.** Пример: «Изображение 1 — моё кольцо. Создай новую сцену в стиле фона из изображения 2.» Полезно для эстетического матчинга, бренд-консистентности и категорийных визуальных референсов.

#### Пример 1: Розовый ретро-автомобиль

<table>
  <tr>
    <th>Товар</th>
    <th>Референсный фон</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/01/Input-01.jpg" width="180"><br><sub>Розовый ретро-авто</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Input-02.jpg" width="180"><br><sub>Зелёный лес реф.</sub></td>
    <td align="center"><img src="e-commerce/Case21/01/Output.png" width="180"><br><sub>Композиция в лесу</sub></td>
  </tr>
</table>

#### Пример 2: Красная помада

<table>
  <tr>
    <th>Товар</th>
    <th>Референсный фон</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case21/02/Input-01.jpg" width="180"><br><sub>Красная помада</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Input-02.jpg" width="180"><br><sub>Чёрно-золотой мрамор реф.</sub></td>
    <td align="center"><img src="e-commerce/Case21/02/Output.png" width="180"><br><sub>Композиция на мраморе</sub></td>
  </tr>
</table>

## 🤝 Промпты взаимодействия с товаром

### Кейс 1: Крупный план товара в руке

**Вход:** Загрузите изображение товара.

**Промпт:**

```
A hand is holding this product, {scene_description}, keep the product color unchanged.
{action_description}
```

> [!NOTE]
> **Перед использованием замените {scene_description} и {action_description}.** Пример: «Рука держит этот товар, фон в стиле fashion-съёмки, цвет товара не менять» или «Рука с электродрелью, сверление дерева.» Подходит для бьюти, инструментов, гаджетов, упакованных товаров и тактильных демо.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case22/01/Input.jpg" width="180"><br><sub>Розовый блеск</sub></td>
    <td align="center"><img src="e-commerce/Case22/01/Output.png" width="180"><br><sub>Блеск в руке</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Input.avif" width="180"><br><sub>Швабра с ручкой</sub></td>
    <td align="center"><img src="e-commerce/Case22/02/Output.png" width="180"><br><sub>Уборка шваброй</sub></td>
  </tr>
</table>

### Кейс 2: Сгенерированная сцена с человеком

**Вход:** Загрузите изображение сцены с товаром или фото товара.

**Промпт:**

```
Add a human model to this product scene. The model should be {person_description}, in a {pose}, performing {action}.
```

> [!NOTE]
> **Перед использованием замените {person_description}, {pose} и {action}.** Пример: «Добавь в эту сцену с товаром человеческую модель: маленькая девочка стоит и держит куклу» или «Добавь в эту сцену с товаром человеческую модель со шваброй.» Полезно для показа масштаба, использования, эмоции и совпадения с аудиторией.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case23/01/Input.jpg" width="180"><br><sub>Красная арка КНГ</sub></td>
    <td align="center"><img src="e-commerce/Case23/01/Output-01.png" width="180"><br><sub>Модель в ципао</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Input.webp" width="180"><br><sub>Красно-серебр. наушники</sub></td>
    <td align="center"><img src="e-commerce/Case23/02/Output.png" width="180"><br><sub>Модель в наушниках</sub></td>
  </tr>
</table>

### Кейс 3: Взаимодействие с товаром через референсного персонажа

**Вход:** Загрузите изображение сцены с товаром и референс персонажа.

**Промпт:**

```
Add the human model from image 2 into the product scene from image 1, with this action: {action_description}.
```

> [!NOTE]
> **Перед использованием замените {action_description}.** Пример: «Добавь модель из изображения 2 в сцену с товаром из изображения 1 с действием: модель лежит на кровати.» Полезно, когда нужна согласованная идентичность персонажа на нескольких креативах.

#### Пример 1: Спальня с кроватью king-size + мужская модель

<table>
  <tr>
    <th>Сцена товара</th>
    <th>Референсный персонаж</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/01/Input-01.webp" width="180"><br><sub>Спальня king-size</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Input-02.jpg" width="180"><br><sub>Модель в белой футболке</sub></td>
    <td align="center"><img src="e-commerce/Case24/01/Output.png" width="180"><br><sub>Модель на кровати</sub></td>
  </tr>
</table>

#### Пример 2: Сцена с креслом-качалкой + мужская модель

<table>
  <tr>
    <th>Сцена товара</th>
    <th>Референсный персонаж</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case24/02/Input-01.jpg" width="180"><br><sub>Кресло-качалка дома</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Input-02.jpg" width="180"><br><sub>Модель в белой рубашке</sub></td>
    <td align="center"><img src="e-commerce/Case24/02/Output.png" width="180"><br><sub>Модель в кресле-качалке</sub></td>
  </tr>
</table>

### Кейс 4: Взаимодействие питомца и товара

**Вход:** Загрузите изображение товара.

**Промпт:**

```
Generate a {pet} interacting with the {product} from the image.
```

> [!NOTE]
> **Перед использованием замените {pet} и {product}.** Пример: «Сгенерируй кошку, взаимодействующую с игрушкой из изображения» или «Сгенерируй щенка, взаимодействующего с игрушкой из изображения.» Особенно полезно для креативов игрушек, аксессуаров для питомцев, домашних и игровых лайфстайл-товаров.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case25/01/Input.jpg" width="180"><br><sub>Оранжевый мяч для собаки</sub></td>
    <td align="center"><img src="e-commerce/Case25/01/Output.png" width="180"><br><sub>Щенок с мячом</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Input.jpg" width="180"><br><sub>Колесо для хомяка</sub></td>
    <td align="center"><img src="e-commerce/Case25/02/Output.png" width="180"><br><sub>Хомяк в колесе</sub></td>
  </tr>
</table>

## 🛍️ Промпты Social Commerce

### Кейс 1: Набор продаж в фэшн-студии

**Промпт:**

```
Generate a model sales image set, background is a fashion studio.
```

> [!NOTE]
> Полезно для маркетинга одежды в стиле шоурума, визуального мерчандайзинга бутиков и социального контента в студийном стиле.

#### Пример 1: Синяя худи

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/01/Input.png" width="160"><br>
      <sub>Товар чистый фон</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/01/Output-01.png" width="200"><br><sub>Студийная съёмка 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-02.png" width="200"><br><sub>Студийная съёмка 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/01/Output-03.png" width="200"><br><sub>Студийная съёмка 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/01/Output-04.png" width="200"><br><sub>Студийная съёмка 4</sub></td>
  </tr>
</table>

#### Пример 2: Розовое цветочное платье

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case31/02/Input.webp" width="160"><br>
      <sub>Товар чистый фон</sub>
    </td>
    <td align="center"><img src="e-commerce/Case31/02/Output-01.png" width="200"><br><sub>Студийная съёмка 1</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-02.png" width="200"><br><sub>Студийная съёмка 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case31/02/Output-03.png" width="200"><br><sub>Студийная съёмка 3</sub></td>
    <td align="center"><img src="e-commerce/Case31/02/Output-04.png" width="200"><br><sub>Студийная съёмка 4</sub></td>
  </tr>
</table>

### Кейс 2: Видео продажи лука у зеркала

**Промпт:**

```
Generate a mirror outfit sales video.
```

> [!NOTE]
> Этот шаблон идеален для фэшн-контента в крейтор-стиле, UGC-эстетики и неформальных social-commerce форматов продаж.

### Кейс 3: Стайлинг подарочной коробки для одежды

**Вход:** Загрузите изображение одежды.

**Промпт:**

```
Place the apparel into a gift box.
```

> [!NOTE]
> Полезно для маркетинга подарков к праздникам, премиум-моков упаковки и сезонных товарных креативов.

<table>
  <tr>
    <th>Вход</th>
    <th>Выход</th>
    <th>Вход</th>
    <th>Выход</th>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case33/01/Input.jpg" width="180"><br><sub>Футболка с брызгами</sub></td>
    <td align="center"><img src="e-commerce/Case33/01/Output.png" width="180"><br><sub>Подарочная коробка</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Input.jpg" width="180"><br><sub>Красный детский пуховик</sub></td>
    <td align="center"><img src="e-commerce/Case33/02/Output.png" width="180"><br><sub>Подарочная коробка</sub></td>
  </tr>
</table>

### Кейс 4: Набор сцен продажи свежих продуктов

**Промпт:**

```
Generate a fresh-food scene set for {food_name}.
```

> [!NOTE]
> **Перед использованием замените {food_name}.** Пример: «Сгенерируй набор сцен со свежими продуктами для помело.» Полезно для фруктов, сельхозпродуктов, коробочных продуктов, специальных ингредиентов и премиум-витрин фреш-продукции.

#### Пример 1: Арбуз

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/01/Input.webp" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/01/Output-01.png" width="200"><br><sub>Свежие продукты 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-02.png" width="200"><br><sub>Свежие продукты 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/01/Output-03.png" width="200"><br><sub>Свежие продукты 3</sub></td>
    <td align="center"><img src="e-commerce/Case34/01/Output-04.png" width="200"><br><sub>Свежие продукты 4</sub></td>
  </tr>
</table>

#### Пример 2: Виноград

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case34/02/Input.jpg" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case34/02/Output-01.png" width="150"><br><sub>Свежие продукты 1</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-02.png" width="150"><br><sub>Свежие продукты 2</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-03.png" width="150"><br><sub>Свежие продукты 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case34/02/Output-04.png" width="150"><br><sub>Свежие продукты 4</sub></td>
    <td align="center"><img src="e-commerce/Case34/02/Output-05.png" width="150"><br><sub>Свежие продукты 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

### Кейс 5: Креативный набор продажи продуктов

**Промпт:**

```
Generate a food sales image set.
```

> [!NOTE]
> Гибкий базовый шаблон для снек-брендов, упакованной еды, свежих продуктов и общего food-контента social commerce.

#### Пример 1: Попкорн

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="3">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/01/Input.jpg" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/01/Output-01.png" width="150"><br><sub>Продажное фото 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-02.png" width="150"><br><sub>Продажное фото 2</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-03.png" width="150"><br><sub>Продажное фото 3</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/01/Output-04.png" width="150"><br><sub>Продажное фото 4</sub></td>
    <td align="center"><img src="e-commerce/Case35/01/Output-05.png" width="150"><br><sub>Продажное фото 5</sub></td>
    <td>&nbsp;</td>
  </tr>
</table>

#### Пример 2: Шпажки с засахаренными фруктами

<table>
  <tr>
    <th width="20%">Вход</th>
    <th colspan="2">Выход</th>
  </tr>
  <tr>
    <td rowspan="2" align="center">
      <img src="e-commerce/Case35/02/Input.webp" width="160"><br>
      <sub>Фото товара</sub>
    </td>
    <td align="center"><img src="e-commerce/Case35/02/Output-01.png" width="200"><br><sub>Продажное фото 1</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-02.png" width="200"><br><sub>Продажное фото 2</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="e-commerce/Case35/02/Output-03.png" width="200"><br><sub>Продажное фото 3</sub></td>
    <td align="center"><img src="e-commerce/Case35/02/Output-04.png" width="200"><br><sub>Продажное фото 4</sub></td>
  </tr>
</table>

## 🚀 Пакетная генерация через API Evolink

Для продакшен-запусков по сотням SKU, нескольким языкам или маркетплейсам вызывайте **API GPT Image 2 от Evolink** напрямую вместо ручного выполнения промптов один за другим.

**Зачем нужен batch через API:**

- Массовая генерация изображений листингов для всего каталога
- Мультиязычный перевод всех ассетов листинга в одном задании
- Программная замена модели, замена фона, мультиракурсный вывод
- Webhook-колбэки интегрируются с вашим PIM, ERP или маркетинговой автоматизацией

**Требования:** [Получите API-ключ](https://evolink.ai/dashboard/keys).

### Шаг 1: Отправка задания на генерацию

Генерация GPT Image 2 — **асинхронная**: вызов возвращает `task_id`, по которому вы получаете результат опросом.

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

| Поле | Обязательное | Примечания |
| :--- | :--- | :--- |
| `model` | да | Должно быть `"gpt-image-2"` |
| `prompt` | да | До 32 000 символов — вставьте промпт из любого кейса в этом репозитории |
| `image_urls` | необязательно | 1–16 входных/референсных изображений (jpeg/png/webp, ≤50 МБ каждое) для image-to-image и редактирования |
| `size` | необязательно | Соотношение сторон (`1:1`, `2:3`, `16:9`, …) или размер в пикселях; по умолчанию `auto` |
| `resolution` | необязательно | `1K`, `2K` или `4K` при использовании соотношения в `size` |
| `quality` | необязательно | `low`, `medium`, `high` — влияет на стоимость; по умолчанию `medium` |
| `n` | необязательно | 1–10 изображений за вызов |
| `callback_url` | необязательно | HTTPS-webhook для получения готового результата без поллинга |

### Шаг 2: Опрос задания

```bash
curl https://api.evolink.ai/v1/tasks/{task_id} \
  -H "Authorization: Bearer YOUR_API_KEY"
```

Когда `status` станет `"completed"`, массив `results` будет содержать URL сгенерированных изображений. **Сгенерированные изображения действительны 24 часа — скачайте их вовремя.**

### Опционально: webhook-колбэк

Передайте `"callback_url": "https://your-server.example.com/webhook"` при отправке, и Evolink отправит POST с результатом на ваш эндпоинт по завершении задания — поллинг не нужен.

**Полная документация API:** [docs.evolink.ai · GPT Image 2 генерация изображений](https://docs.evolink.ai/en/api-manual/image-series/gpt-image-2/gpt-image-2-image-generation)

## 🙏 Благодарности

Этот репозиторий вдохновлён отличными open-source коллекциями промптов и e-commerce workflow, которыми делится сообщество.

Благодарим всех авторов и контрибьюторов, открыто делящихся своей работой и делающих эти кейс-стади возможными.

- [@EvoLinkAI](https://github.com/EvoLinkAI)

*Мы не можем гарантировать, что каждый кейс приписан к оригинальному автору. Свяжитесь с нами, если нужны правки, — оперативно обновим.*

Если у вас есть интересные кейсы промптов, поделитесь с нами и помогите расширить библиотеку промптов Evolink.

[![Star History Chart](https://api.star-history.com/svg?repos=EvoLinkAI/awesome-ecommerce-image-prompts&type=Date)](https://www.star-history.com/#EvoLinkAI/awesome-ecommerce-image-prompts&Date)
