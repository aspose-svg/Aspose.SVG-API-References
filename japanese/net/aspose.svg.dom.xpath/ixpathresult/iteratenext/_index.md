---
title: "IXPathResult.IterateNext"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "IXPathResult IterateNext メソッド。ノードセットから次のノードを反復取得し、ノードがもう無い場合は null を返します。"
type: docs
weight: 80
url: /ja/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

ノードセットから次のノードを反復取得し、ノードがもうない場合は `null` を返します。

```csharp
public Node IterateNext()
```

### 戻り値

次のノードを返します。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: `resultType` が `UnorderedNodeIterator` 型でも `OrderedNodeIterator` 型でもない場合に発生します。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: 結果が返された後にドキュメントが変更されました。 |

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
