---
title: "IXPathResult.IterateNext"
second_title: "Aspose.SVG för .NET API-referens"
description: "IXPathResult IterateNext‑metod. Itererar och returnerar nästa nod från nodmängden eller null om det inte finns fler noder"
type: docs
weight: 80
url: /sv/net/aspose.svg.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Itererar och returnerar nästa nod från nodmängden eller `null` om det inte finns fler noder.

```csharp
public Node IterateNext()
```

### Returvärde

Returnerar nästa nod.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: uppstår om `resultType` inte är av typen `UnorderedNodeIterator` eller `OrderedNodeIterator`. |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_STATE_ERR: Dokumentet har förändrats sedan resultatet returnerades. |

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathResult](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
