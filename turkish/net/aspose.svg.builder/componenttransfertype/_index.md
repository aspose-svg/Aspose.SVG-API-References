---
title: "ComponentTransferType Enum"
second_title: "Aspose.SVG for .NET API Reference"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Bir SVG'nin FeComponentTransfer filtre ilkelinde uygulanacak bileşen aktarım fonksiyonunun tipini belirtir."
type: docs
weight: 170
url: /tr/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

SVG'nin FeComponentTransfer filtre ilkelinde uygulanacak bileşen aktarım işlevi türünü belirtir.

```csharp
public enum ComponentTransferType
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Identity | `0` | Girdi grafiğinde hiçbir değişiklik olmadığını temsil eder. Bu varsayılan tiptir. |
| Table | `1` | Filtre içinde fonksiyonu tanımlamak için bir arama tablosu kullanır. |
| Discrete | `2` | Filtre içinde fonksiyonu tanımlamak için ayrık değerler kümesi kullanır. |
| Linear | `3` | Filtre içinde bileşenin lineer dönüşümünü tanımlar. |
| Gamma | `4` | Filtre içinde gama düzeltme dönüşümünü tanımlar. |

## Açıklamalar

FeComponentTransfer filtre ilkel, grafik öğelerinin renk bileşenlerini (RGB ve alfa) farklı aktarım fonksiyonlarıyla bireysel olarak manipüle etmeye olanak tanır. Her tip, filtre içinde renk bileşeni dönüşümü için ayrı bir hesaplama yöntemi tanımlar.

### Ayrıca Bakınız

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
