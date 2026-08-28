---
title: "SVGListBase-1.GetItem"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase GetItem メソッド。リストから指定された項目を返します。"
type: docs
weight: 70
url: /ja/net/aspose.svg.collections/svglistbase-1/getitem/
---
## SVGListBase<T>.GetItem method

リストから指定された項目を返します。

```csharp
public T GetItem(ulong index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| インデックス | UInt64 | 返されるリスト内の項目のインデックスです。最初の項目は番号0です。 |

### 戻り値

選択された項目です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/)。インデックス番号が numberOfItems 以上の場合に発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
