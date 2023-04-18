---
title: SVGListBase1.RemoveItem
second_title: Aspose.SVG untuk Referensi .NET API
description: SVGListBase metode. Menghapus item yang ada dari daftar.
type: docs
weight: 100
url: /id/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Menghapus item yang ada dari daftar.

```csharp
public T RemoveItem(ulong index)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| index | UInt64 | Indeks item yang akan dihapus. Item pertama adalah nomor 0. |

### Nilai Pengembalian

Item yang dihapus.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kode[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Dimunculkan saat daftar tidak dapat diubah. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kode[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). Dimunculkan jika nomor indeks lebih besar atau sama dengan numberOfItems. |

### Lihat juga

* class [SVGListBase&lt;T&gt;](../)
* ruang nama [Aspose.Svg.Collections](../../svglistbase-1/)
* perakitan [Aspose.SVG](../../../)


