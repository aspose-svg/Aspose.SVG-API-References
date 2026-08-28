---
title: "SVGListBase-1.Item"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase Item プロパティ。リストのインデックス番目の項目を返します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.collections/svglistbase-1/item/
---
## SVGListBase<T> indexer

リスト内の index 番目の項目を返します。

```csharp
public T this[ulong index] { get; set; }
```

| パラメータ | 説明 |
| --- | --- |
| インデックス | リスト内のインデックスです。 |

### 戻り値

リストのインデックス番目の位置に格納されているオブジェクトです。

### Property Value

リストに格納されている項目の型です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
