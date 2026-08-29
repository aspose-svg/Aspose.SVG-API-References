---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions TextDecoration. Устанавливает атрибут text-decoration для SVG‑элемента, определяя украшения, добавляемые к тексту."
type: docs
weight: 2210
url: /ru/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Устанавливает атрибут 'text-decoration' для SVG‑элемента, определяя украшения, добавляемые к тексту.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| underline | Указывает, должен ли текст быть подчёркнутым. |
| overline | Указывает, должен ли текст иметь надчеркивание. |
| lineThrough | Указывает, должна ли у текста быть перечёркнутая линия. |
| мигание | Указывает, должно ли текст мигать (не рекомендуется к использованию). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
