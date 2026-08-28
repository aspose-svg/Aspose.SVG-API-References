---
title: "XPathResultType 列挙体"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.XPath.XPathResultType 列挙体。結果がどのタイプであるかを示す符号なし短整数です。特定のタイプが指定された場合、必要に応じて XPath の型変換を使用して、対応するタイプとして結果が返されます。"
type: docs
weight: 3360
url: /ja/net/aspose.svg.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

これは結果のタイプを示す符号なし短整数です。特定の `type` が指定された場合、必要に応じて XPath の型変換を使用し、対応する型として結果が返されます。

```csharp
public enum XPathResultType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Any | `0` | このコードは特定のタイプを表しません。XPath 式の評価でこのタイプが生成されることはありません。このタイプが要求された場合、評価は式の評価から自然に得られる任意のタイプを返します。`Any` タイプが要求されたときに自然な結果がノードセットである場合、常に `UnorderedNodeIterator` が結果のタイプになります。ノードセットの他の表現は明示的に要求する必要があります。 |
| Number | `1` | 結果は [XPath 1.0] で定義された数値です。ドキュメントの変更はその数値を無効にしませんが、再評価すると同じ数値が得られない可能性があります。 |
| String | `2` | The result is a string as defined by [XPath 1.0]. Document modification does not invalidate the string, but may mean that the string no longer corresponds to the current document. |
| Boolean | `3` | The result is a boolean as defined by [XPath 1.0]. Document modification does not invalidate the boolean, but may mean that reevaluation would not yield the same boolean. |
| UnorderedNodeIterator | `4` | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, which may not produce nodes in a particular order. Document modification invalidates the iteration. This is the default type returned if the result is a node set and `Any` type is requested. |
| OrderedNodeIterator | `5` | The result is a node set as defined by [XPath 1.0] that will be accessed iteratively, which will produce document-ordered nodes. Document modification invalidates the iteration. |
| UnorderedNodeSnapshot | `6` | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot list of nodes that may not be in a particular order. Document modification does not invalidate the snapshot but may mean that reevaluation would not yield the same snapshot and nodes in the snapshot may have been altered, moved, or removed from the document. |
| OrderedNodeSnapshot | `7` | The result is a node set as defined by [XPath 1.0] that will be accessed as a snapshot list of nodes that will be in original document order. Document modification does not invalidate the snapshot but may mean that reevaluation would not yield the same snapshot and nodes in the snapshot may have been altered, moved, or removed from the document. |
| AnyUnorderedNode | `8` | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, which may be `null` if the node set is empty. Document modification does not invalidate the node, but may mean that the result node no longer corresponds to the current document. This is a convenience that permits optimization since the implementation can stop once any node in the resulting set has been found. If there is more than one node in the actual result, the single node returned might not be the first in document order. |
| FirstOrderedNode | `9` | The result is a node set as defined by [XPath 1.0] and will be accessed as a single node, which may be `null` if the node set is empty. Document modification does not invalidate the node, but may mean that the result node no longer corresponds to the current document. This is a convenience that permits optimization since the implementation can stop once the first node in document order of the resulting set has been found. If there are more than one node in the actual result, the single node returned will be the first in document order. |

### 参照

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
