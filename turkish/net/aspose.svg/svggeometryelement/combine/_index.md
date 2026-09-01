---
title: "SVGGeometryElement.Combine"
second_title: "Aspose.SVG for .NET API Reference"
description: "SVGGeometryElement Combine yöntemi. Bu geometriyi başka bir SVG geometrisiyle bir boolean işlem kullanarak birleştirir ve sonucu içeren yeni bir yol öğesi döndürür."
type: docs
weight: 20
url: /tr/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Bu geometriyi başka bir SVG geometrisiyle bir boolean işlem kullanarak birleştirir ve sonucu içeren yeni bir `<path>` öğesi döndürür.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | Birleştirilecek diğer geometri. Aynı belgede olmalıdır. |
| op | BooleanPathOp | Uygulanacak boolean operatör: Birleşim (A UNION B), Fark (A - B), Kesişim (A INTERSECT B) veya Dışlama (XOR). |

### Dönüş Değeri

Sonucu kök `<svg>` kullanıcı uzayında (CSS px) kodlayan `d` özniteliğine sahip yeni bir [`SVGPathElement`](../../svgpathelement/). Öğeye DOM'a eklenmez.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *geometryElement* null ise atılır. |
| InvalidOperationException | Bu öğenin sahibi belge yoksa atılır. |
| NotSupportedException | Boolean yol işlemleri kullanılamadığında atılır; bu özellik SkiaSharp arka ucunu gerektirir (Aspose.SVG.Drawing.SkiaSharp paketini yükleyin). |

### Ayrıca Bakınız

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
