---
title: Class NodeFilter
second_title: Aspose.SVG untuk Referensi .NET API
description: Aspose.Svg.Dom.Traversal.Filters.NodeFilter kelas. Filter adalah objek yang mengetahui cara memfilter node.
type: docs
weight: 1210
url: /id/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter adalah objek yang mengetahui cara "memfilter" node.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metode

| Nama | Keterangan |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Uji apakah node tertentu terlihat dalam tampilan logis dari a TreeWalker atau NodeIterator. Fungsi ini akan dipanggil dengan implementasi TreeWalker dan NodeIterator; biasanya tidak dipanggil langsung from kode pengguna. (Meskipun Anda dapat melakukannya jika ingin menggunakan filter yang sama untuk memandu logika aplikasi Anda sendiri.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Metode ini digunakan untuk mengambil objek ECMAScriptType . |

## Bidang

| Nama | Keterangan |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Terima simpulnya. Metode navigasi yang ditentukan untuk NodeIterator atau TreeWalker akan mengembalikan node. ini |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Menolak node. Metode navigasi yang ditentukan untuk NodeIterator atau TreeWalker tidak akan mengembalikan node ini. Untuk TreeWalker, anak dari node ini juga akan ditolak. NodeIterator memperlakukan ini sebagai sinonim untuk FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Lewati simpul tunggal ini. Metode navigasi yang ditentukan untuk NodeIterator atau TreeWalker tidak akan mengembalikan node ini. Untuk NodeIterator dan TreeWalker, anak dari node ini masih akan dipertimbangkan . |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Tampilkan semua Node. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Tampilkan node Attr. Ini berarti hanya saat membuat iterator atau tree-walker dengan node atribut sebagai root ; dalam hal ini berarti node atribut akan muncul di posisi pertama iterasi atau traversal. Karena atribut tidak pernah menjadi anak dari node lain, mereka tidak muncul saat melintasi pohon dokumen. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Menampilkan node Bagian CDATA. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Tampilkan node Komentar. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Tampilkan simpul Dokumen. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Tampilkan node DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Tampilkan node DocumentType. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Tampilkan simpul Elemen. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Tampilkan node Entitas. Ini berarti hanya saat membuat iterator atau tree-walker dengan simpul Entitas sebagai akar ; dalam hal ini, berarti node Entity akan muncul di posisi pertama traversal. Karena entitas bukan bagian dari pohon dokumen, mereka tidak muncul saat melintasi pohon dokumen. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Tampilkan node Referensi Entitas. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Tampilkan simpul Notasi. Ini berarti hanya saat membuat iterator atau tree-walker dengan Node notasi sebagai root ; dalam hal ini, berarti simpul Notasi akan muncul di posisi pertama traversal . Karena notasi bukan bagian dari pohon dokumen, mereka tidak muncul saat menelusuri pohon dokumen. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Tampilkan node Instruksi Pemrosesan. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Tampilkan node Teks. |

### Lihat juga

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* ruang nama [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* perakitan [Aspose.SVG](../../)


