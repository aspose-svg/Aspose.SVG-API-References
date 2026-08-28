---
title: "SVGListBase-1.ReplaceItem"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase ReplaceItem メソッド。リスト内の既存の項目を新しい項目に置き換えます。"
type: docs
weight: 110
url: /ja/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase<T>.ReplaceItem method

リスト内の既存の項目を新しい項目と置き換えます。

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newItem | T | リストに挿入される項目。 |
| インデックス | UInt64 | 置き換えられる項目のインデックス。最初の項目は番号 0 です。 |

### 戻り値

挿入された項目。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
