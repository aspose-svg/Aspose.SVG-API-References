---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "ITreeWalker CurrentNode property. Noden där TreeWalker för närvarande är placerad. Ändringar i DOM-trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också explicit sättas till vilken nod som helst, oavsett om den ligger inom delträdet som specificerats av rot-noden eller skulle accepteras av filtret och whatToShow-flaggorna. Ytterligare traversering sker relativt till currentNode även om den inte är en del av den aktuella vyn genom att tillämpa filtren i den begärda riktningen; om ingen traversering är möjlig ändras inte currentNode."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Noden där TreeWalker för närvarande är placerad. Ändringar i DOM‑trädet kan göra att den aktuella noden inte längre accepteras av TreeWalkers associerade filter. currentNode kan också explicit sättas till vilken nod som helst, oavsett om den ligger inom underträdet som specificerats av rotnoden eller skulle accepteras av filtret och whatToShow‑flaggorna. Ytterligare traversering sker relativt till currentNode även om den inte är en del av den aktuella vyn, genom att tillämpa filtren i den begärda riktningen; om ingen traversering är möjlig ändras inte currentNode.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

Den aktuella noden.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om ett försök görs att sätta currentNode till null. |

### Se även

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
