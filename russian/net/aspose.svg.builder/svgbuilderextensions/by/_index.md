---
title: "SVGBuilderExtensions.By"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions By. Устанавливает атрибут by, определяющий относительное значение смещения для анимации с указанным типом длины."
type: docs
weight: 620
url: /ru/net/aspose.svg.builder/svgbuilderextensions/by/
---
## SVGBuilderExtensions.By<TBuilder> method

Устанавливает атрибут 'by', определяя относительное значение смещения для анимации с указанным типом длины.

```csharp
public static TBuilder By<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Относительное значение смещения для анимации. |
| type | Тип длины для значения 'by'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
