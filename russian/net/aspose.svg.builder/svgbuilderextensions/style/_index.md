---
title: "SVGBuilderExtensions.Style"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions Style. Устанавливает атрибут style, используя построитель правил для определения CSS‑стилей."
type: docs
weight: 2160
url: /ru/net/aspose.svg.builder/svgbuilderextensions/style/
---
## Style<TBuilder>(*this TBuilder, Action&lt;RuleBuilder&gt;*) {#style}

Устанавливает атрибут 'style' с помощью построителя правил для определения CSS‑стилей.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, Action<RuleBuilder> configureRule)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| configureRule | Действие для настройки CSS‑правила. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* class [RuleBuilder](../../rulebuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Style<TBuilder>(*this TBuilder, string*) {#style_1}

Устанавливает атрибут 'style', определяя встроенные CSS‑стили для SVG‑элемента.

```csharp
public static TBuilder Style<TBuilder>(this TBuilder builder, string rules)
    where TBuilder : ISVGElementBuilder, ICoreAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| rules | CSS‑правила в виде строки. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICoreAttributeSetter](../../icoreattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
