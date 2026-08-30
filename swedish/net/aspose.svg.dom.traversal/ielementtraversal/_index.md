---
title: "IElementTraversal‑gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.IElementTraversal‑gränssnitt. ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konforme implementationer av Element Traversal måste alla objekt som implementerar Element också implementera ElementTraversal‑gränssnittet."
type: docs
weight: 3230
url: /sv/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

ElementTraversal‑gränssnittet är en uppsättning skrivskyddade attribut som låter en författare enkelt navigera mellan element i ett dokument. I konformande implementationer av Element Traversal måste alla objekt som implementerar Element även implementera ElementTraversal‑gränssnittet.

```csharp
public interface IElementTraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | Returnerar det aktuella antalet elementnoder som är barn till detta element. 0 om detta element inte har några barnnoder av nodtyp 1. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Returnerar den första barn‑elementnoden för detta element. Null om detta element inte har några barn‑element. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Returnerar det sista barn-elementnodet för detta element. null om detta element inte har några barn-element. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Returnerar nästa syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer efter detta i dokumentträdet. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Returnerar föregående syskon-elementnod för detta element. null om detta element inte har några element-syskon som kommer före detta i dokumentträdet. |

### Se även

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
