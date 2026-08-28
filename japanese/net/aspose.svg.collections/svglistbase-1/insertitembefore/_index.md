---
title: "SVGListBase-1.InsertItemBefore"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase InsertItemBefore メソッド。指定された位置に新しい項目をリストに挿入します。最初の項目は番号0です。"
type: docs
weight: 90
url: /ja/net/aspose.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase<T>.InsertItemBefore method

指定された位置に新しい項目をリストに挿入します。最初の項目は番号 0 です。

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入される項目。 |
| インデックス | UInt64 | 新しい項目を挿入する前の項目のインデックスです。最初の項目は番号0です。インデックスが0と等しい場合、新しい項目はリストの先頭に挿入されます。インデックスが numberOfItems 以上の場合、新しい項目はリストの末尾に追加されます。 |

### 戻り値

挿入された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
