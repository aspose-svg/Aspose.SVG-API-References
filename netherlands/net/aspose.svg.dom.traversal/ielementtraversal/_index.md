---
title: "IElementTraversal Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.IElementTraversal interface. De ElementTraversal-interface is een verzameling alleen-lees attributen die een auteur in staat stellen gemakkelijk tussen elementen in een document te navigeren. In conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal-interface implementeren."
type: docs
weight: 3230
url: /nl/net/aspose.svg.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

De ElementTraversal‑interface is een set van alleen‑lees‑attributen die een auteur in staat stelt gemakkelijk tussen elementen in een document te navigeren. In conforme implementaties van Element Traversal moeten alle objecten die Element implementeren ook de ElementTraversal‑interface implementeren.

```csharp
public interface IElementTraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom.traversal/ielementtraversal/childelementcount/) { get; } | Geeft het huidige aantal elementknooppunten terug die kinderen zijn van dit element. 0 als dit element geen kindknooppunten heeft van nodeType 1. |
| [FirstElementChild](../../aspose.svg.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Geeft het eerste kind‑elementknooppunt van dit element terug. null als dit element geen kind‑elementen heeft. |
| [LastElementChild](../../aspose.svg.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Retourneert het laatste kind-elementknooppunt van dit element. null als dit element geen kindelementen heeft. |
| [NextElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Retourneert het volgende sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die na dit knooppunt in de documentboom komen. |
| [PreviousElementSibling](../../aspose.svg.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Retourneert het vorige sibling‑elementknooppunt van dit element. null als dit element geen element‑sibling‑knooppunten heeft die vóór dit knooppunt in de documentboom komen. |

### Zie ook

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
