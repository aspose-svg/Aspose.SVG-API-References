---
title: "SVGListBase-1.RemoveItem"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase RemoveItem メソッド。リストから既存の項目を削除します。"
type: docs
weight: 100
url: /ja/net/aspose.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase<T>.RemoveItem method

リストから既存の項目を削除します。

```csharp
public T RemoveItem(ulong index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| インデックス | UInt64 | 削除される項目のインデックスです。最初の項目は番号0です。 |

### 戻り値

削除された項目です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
