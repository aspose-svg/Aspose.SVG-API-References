---
title: "SVGBuilderExtensions.To"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions To. Устанавливает атрибут to, определяющий конечное значение анимации с указанным типом длины."
type: docs
weight: 2250
url: /ru/net/aspose.svg.builder/svgbuilderextensions/to/
---
## SVGBuilderExtensions.To<TBuilder> method

Устанавливает атрибут 'to', определяя конечное значение анимации с указанным типом длины.

```csharp
public static TBuilder To<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : ISVGElementBuilder, IAnimationValueAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | Конечное значение анимации. |
| type | Тип длины для значения 'to'. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [LengthType](../../lengthtype/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationValueAttributeSetter](../../ianimationvalueattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
