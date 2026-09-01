---
title: "BlendMode Enum"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.BlendMode enum. SVG'de görüntüleri veya öğeleri birleştirmek için kullanılabilir karıştırma modlarını belirtir"
type: docs
weight: 80
url: /tr/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

SVG'de görüntüleri veya öğeleri birleştirmek için mevcut karıştırma modlarını belirtir.

```csharp
public enum BlendMode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Normal | `0` | Kaynak görüntüyü olduğu gibi, hiçbir karıştırma olmadan gösterir. |
| Multiply | `1` | Kaynak görüntünün ve arka planın renklerini çarpar. Sonuç daha karanlık bir görüntüdür. |
| Screen | `2` | Kaynak görüntünün karanlık bölümlerini aydınlatır ve aydınlık bölümleri değişmeden bırakır. |
| Overlay | `3` | Kontrastı artırmak için Multiply ve Screen karıştırma modlarını birleştirir. |
| Darken | `4` | Arka planı, kaynak görüntünün renklerine göre karartır. |
| Lighten | `5` | Arka planı, kaynak görüntünün renklerine göre aydınlatır. |
| ColorDodge | `6` | Arka planı, kaynak görüntüyü yansıtacak şekilde aydınlatır. |
| ColorBurn | `7` | Arka planı, kaynak görüntüyü yansıtacak şekilde karartır. |
| HardLight | `8` | Kaynak görüntünün parlaklığına dayalı sert ışık etkisi oluşturur. |
| SoftLight | `9` | Kaynak görüntünün parlaklığına dayalı yumuşak ışık etkisi oluşturur. |
| Difference | `10` | Kaynak görüntü ile arka plan arasındaki farkları vurgular. |
| Exclusion | `11` | Fark (Difference) benzeri bir etki oluşturur, ancak daha düşük kontrastla. |
| Hue | `12` | Kaynak görüntünün tonunu, arka planın parlaklığı ve doygunluğu ile birleştirir. |
| Saturation | `13` | Kaynak görüntünün doygunluğunu, arka planın tonu ve parlaklığı ile birleştirir. |
| Color | `14` | Kaynak görüntünün tonu ve doygunluğunu, arka planın parlaklığı ile birleştirir. |
| Luminosity | `15` | Kaynak görüntünün parlaklığını, arka planın tonu ve doygunluğu ile birleştirir. |

## Açıklamalar

SVG'deki karıştırma modları, iki katmanın birbirine nasıl karıştırılacağını belirlemek için kullanılır. Bu enum, karıştırılan katmanların renklerinin nasıl karıştığını ve farklı görsel efektler ürettiğini kontrol eden çeşitli seçenekler sunar.

### Ayrıca Bakınız

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
