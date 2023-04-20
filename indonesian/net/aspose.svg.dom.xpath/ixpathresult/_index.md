---
title: Interface IXPathResult
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.Dom.XPath.IXPathResult antarmuka. ItuXPathResult antarmuka mewakili hasil evaluasi ekspresi XPath 1.0 dalam konteks node tertentu. Karena evaluasi dari ekspresi XPath dapat menghasilkan berbagai jenis hasil objek ini memungkinkan untuk menemukan dan memanipulasi jenis dan nilai hasil.
type: docs
weight: 1350
url: /id/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

Itu`XPathResult` antarmuka mewakili hasil evaluasi ekspresi XPath 1.0 dalam konteks node tertentu. Karena evaluasi dari ekspresi XPath dapat menghasilkan berbagai jenis hasil, objek ini memungkinkan untuk menemukan dan memanipulasi jenis dan nilai hasil.

```csharp
public interface IXPathResult
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | Nilai hasil boolean ini. |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Menandakan bahwa iterator menjadi tidak valid. Benar jika`jenishasil` adalah`UnorderedNodeIterator` ketik atau`OrderedNodeIterator` ketik dan dokumen telah dimodifikasi sejak hasil ini dikembalikan. |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | Nilai hasil bilangan ini. |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | Kode yang mewakili jenis hasil ini, seperti yang ditentukan oleh http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Nilai hasil simpul tunggal ini, yang mungkin`batal` . |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | Jumlah node dalam snapshot hasil. Nilai yang valid untuk indeks snapshotItem adalah`0` ke`snapshotLength-1` inklusif. |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | Nilai hasil string ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | Mengulangi dan mengembalikan node berikutnya dari set node atau`batal` jika tidak ada node lagi. |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(int) | Mengembalikan`indeks` item th dalam koleksi snapshot. Jika`indeks`lebih besar dari atau sama dengan jumlah node dalam daftar, metode ini kembali`batal` . Berbeda dengan hasil iterator , snapshot tidak menjadi tidak valid, tetapi mungkin tidak sesuai dengan dokumen saat ini jika dimutasikan. |

### Lihat juga

* ruang nama [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* perakitan [Aspose.SVG](../../)


