---
title: "IXPathResult.SnapshotItem"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathResult SnapshotItem メソッド。スナップショットコレクションの index 番目の項目を返します。index がリスト内のノード数以上の場合、このメソッドは null を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。"
type: docs
weight: 90
url: /ja/net/aspose.svg.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

スナップショットコレクションの `index` 番目の項目を返します。`index` がリスト内のノード数以上の場合、このメソッドは `null` を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。

```csharp
public Node SnapshotItem(int index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| インデックス | Int32 | スナップショットコレクションへのインデックス。 |

### 戻り値

`NodeList` の `index` 番目の位置にあるノード、または有効なインデックスでない場合は `null`。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: `resultType` が `UnorderedNodeSnapshot` 型でも `OrderedNodeSnapshot` 型でもない場合に発生します。 |

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
