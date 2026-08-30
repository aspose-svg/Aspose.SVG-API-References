---
title: "IParentNode-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.IParentNode-gränssnitt. Definierar IParentNode-gränssnittet som implementeras av alla möjliga föräldrar"
type: docs
weight: 3080
url: /sv/net/aspose.svg.dom/iparentnode/
---
## IParentNode interface

Definierar `IParentNode`-gränssnittet som implementeras av alla möjliga föräldrar.

```csharp
public interface IParentNode : IElementTraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ChildElementCount](../../aspose.svg.dom/iparentnode/childelementcount/) { get; } | Attributet childElementCount måste returnera antalet barn till kontextobjektet som är element. |
| [Children](../../aspose.svg.dom/iparentnode/children/) { get; } | Returnerar barn‑elementen. |
| [FirstElementChild](../../aspose.svg.dom/iparentnode/firstelementchild/) { get; } | Returnerar det första barnet som är ett element, annars null. |
| [LastElementChild](../../aspose.svg.dom/iparentnode/lastelementchild/) { get; } | Returnerar det sista barnet som är ett element, annars null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [QuerySelector](../../aspose.svg.dom/iparentnode/queryselector/)(*string*) | Returnerar det första elementet som är en ättling till noden som matchar selektorer. |
| [QuerySelectorAll](../../aspose.svg.dom/iparentnode/queryselectorall/)(*string*) | Returnerar alla elementättlingar till noden som matchar selektorer. |

### Se även

* interface [IElementTraversal](../../aspose.svg.dom.traversal/ielementtraversal/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
