---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.SVG för .NET API-referens"
description: "INodeIterator PointerBeforeReferenceNode-egenskapen. Värdet på denna flagga bestämmer om barnen till entitetsreferensnoder är synliga för iteratorn. Om falskt kommer de och deras underordnade att avvisas. Observera att detta avslag har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt delträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entitetsreferenser är expanderade och där själva entitetsreferensnoden inte exponeras, använd whatToShow-flaggan för att dölja entitetsreferensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entitetsreferensnoder men ingen entitetsutvidgning, använd whatToShow-flaggan för att visa entitetsreferensnoden och sätt expandEntityReferences till false."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Värdet på denna flagga bestämmer om barnen till entitetsreferensnoder är synliga för iteratorn. Om falskt kommer de och deras underordnade att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entitetsreferenser är expanderade och där själva entitetsreferensnoden inte exponeras, använd whatToShow‑flaggorna för att dölja entitetsreferensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entitetsreferensnoder men ingen entitetsutvidgning, använd whatToShow‑flaggorna för att visa entitetsreferensnoden och sätt expandEntityReferences till false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` om [expand entity references]; annars, `false`.

### Se även

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
