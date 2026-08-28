---
title: "IXPathResult インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.XPath.IXPathResult インターフェイス。XPathResult インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。XPath 式の評価はさまざまな結果タイプになる可能性があるため、このオブジェクトは結果のタイプと値を検出および操作できるようにします。"
type: docs
weight: 3350
url: /ja/net/aspose.svg.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` インターフェイスは、特定のノードのコンテキスト内で XPath 1.0 式を評価した結果を表します。XPath 式の評価はさまざまな結果タイプになる可能性があるため、このオブジェクトは結果のタイプと値を検出および操作できるようにします。

```csharp
public interface IXPathResult
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BooleanValue](../../aspose.svg.dom.xpath/ixpathresult/booleanvalue/) { get; } | このブール結果の値。 |
| [InvalidIteratorState](../../aspose.svg.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | イテレータが無効になったことを示します。`resultType` が `UnorderedNodeIterator` タイプまたは `OrderedNodeIterator` タイプで、結果が返された後にドキュメントが変更されている場合は true です。 |
| [NumberValue](../../aspose.svg.dom.xpath/ixpathresult/numbervalue/) { get; } | この数値結果の値。 |
| [ResultType](../../aspose.svg.dom.xpath/ixpathresult/resulttype/) { get; } | この結果のタイプを表すコードで、http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult に定義された [`XPathResultType`](../xpathresulttype/) 列挙体によります。 |
| [SingleNodeValue](../../aspose.svg.dom.xpath/ixpathresult/singlenodevalue/) { get; } | この単一ノード結果の値で、`null` の可能性があります。 |
| [SnapshotLength](../../aspose.svg.dom.xpath/ixpathresult/snapshotlength/) { get; } | 結果スナップショット内のノード数。snapshotItem インデックスの有効な値は `0` から `snapshotLength-1` までです。 |
| [StringValue](../../aspose.svg.dom.xpath/ixpathresult/stringvalue/) { get; } | この文字列結果の値。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [IterateNext](../../aspose.svg.dom.xpath/ixpathresult/iteratenext/)() | ノードセットから次のノードを反復取得し、ノードがもうない場合は `null` を返します。 |
| [SnapshotItem](../../aspose.svg.dom.xpath/ixpathresult/snapshotitem/)(*int*) | スナップショットコレクションの `index` 番目の項目を返します。`index` がリスト内のノード数以上の場合、このメソッドは `null` を返します。イテレータ結果とは異なり、スナップショットは無効になりませんが、ドキュメントが変更された場合は現在のドキュメントと一致しない可能性があります。 |

### 参照

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
