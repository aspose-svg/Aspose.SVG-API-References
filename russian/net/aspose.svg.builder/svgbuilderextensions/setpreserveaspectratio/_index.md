---
title: "SVGBuilderExtensions.SetPreserveAspectRatio"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions SetPreserveAspectRatio. Устанавливает атрибут preserveAspectRatio для SVG‑элемента."
type: docs
weight: 2020
url: /ru/net/aspose.svg.builder/svgbuilderextensions/setpreserveaspectratio/
---
## SVGBuilderExtensions.SetPreserveAspectRatio<TBuilder> method

Устанавливает атрибут 'preserveAspectRatio' для SVG‑элемента.

```csharp
public static TBuilder SetPreserveAspectRatio<TBuilder>(this TBuilder builder, 
    AspectRatioAlign align, AspectRatioScaling meetOrSlice = AspectRatioScaling.Meet)
    where TBuilder : ISVGElementBuilder, IPreserveAspectRatioAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Экземпляр билдера. |
| align | Настройка выравнивания для соотношения сторон. |
| meetOrSlice | Указывает, как сохраняется соотношение сторон (по умолчанию 'Meet'). |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* enum [AspectRatioAlign](../../aspectratioalign/)
* enum [AspectRatioScaling](../../aspectratioscaling/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPreserveAspectRatioAttributeSetter](../../ipreserveaspectratioattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
