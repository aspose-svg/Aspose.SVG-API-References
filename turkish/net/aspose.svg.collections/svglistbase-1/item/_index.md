---
title: SVGListBase1.Item
second_title: Aspose.SVG for .NET API Referansı
description: SVGListBase mülk. Listedeki dizinci öğeyi döndürür.
type: docs
weight: 10
url: /tr/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Listedeki dizinci öğeyi döndürür.

```csharp
public T this[ulong index] { get; set; }
```

| Parametre | Tanım |
| --- | --- |
| index | Listedeki dizin. |

### Geri dönüş değeri

Listedeki indeksinci pozisyonda saklanan nesne.

### Mülk değeri

list. içinde depolanan öğenin türü

### istisnalar

| istisna | şart |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | kod[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Liste değiştirilemediğinde tetiklenir. |
| [DOMException](../../../aspose.svg.dom/domexception/) | kod[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). İndeks numarası, itemOfItems'den büyük veya ona eşitse yükseltilir. |

### Ayrıca bakınız

* class [SVGListBase&lt;T&gt;](../)
* ad alanı [Aspose.Svg.Collections](../../svglistbase-1/)
* toplantı [Aspose.SVG](../../../)


