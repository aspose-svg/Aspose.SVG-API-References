---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGFEColorMatrixElementBuilder TypeAndValues metodu. feColorMatrix öğesinin type ve values özniteliklerini ayarlar; renk matrisi işlemini ve parametrelerini belirtir."
type: docs
weight: 30
url: /tr/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

feColorMatrix öğesinin 'type' ve 'values' özniteliklerini ayarlar, renk matrisi işlemini ve parametrelerini belirtir.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tip | ColorMatrixOperation | ColorMatrixOperation enum değeri, renk matrisi işleminin türünü temsil eder. |
| values | Double[] | Renk matrisi işlemi için parametreler. |

### Dönüş Değeri

Mevcut oluşturucu örneği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentException | Belirtilen türün gereksinimlerine sağlanan değerler uymadığında fırlatılır. |
| NotSupportedException | Desteklenmeyen bir matris işlemi türü sağlandığında fırlatılır. |

### Ayrıca Bakınız

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
