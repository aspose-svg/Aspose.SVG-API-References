---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "INodeIterator PointerBeforeReferenceNode-eigenschap. De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentienodes zichtbaar zijn voor de iterator. Als false worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft op whatToShow en de filter. Ook merk op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knooppunten over te slaan. Om een weergave van het document te produceren waarbij entiteitsreferenties zijn uitgebreid en de entiteitsreferentieknoop zelf niet wordt blootgesteld, gebruik de whatToShow‑vlaggen om de entiteitsreferentieknoop te verbergen en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteitsreferentieknooppunten maar zonder entiteitsexpansie, gebruik de whatToShow‑vlaggen om de entiteitsreferentieknoop te tonen en stel expandEntityReferences in op false."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentieknooppunten zichtbaar zijn voor de iterator. Als false, worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knooppunten over te slaan. Om een weergave van het document te produceren waarin entiteitsreferenties zijn uitgebreid en het entiteitsreferentieknooppunt zelf niet wordt blootgesteld, gebruik de whatToShow vlaggen om het entiteitsreferentieknooppunt te verbergen en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteitsreferentieknooppunten maar zonder entiteitsexpansie, gebruik de whatToShow vlaggen om het entiteitsreferentieknooppunt te tonen en stel expandEntityReferences in op false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` als [expand entity references]; anders, `false`.

### Zie ook

* interface [INodeIterator](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
