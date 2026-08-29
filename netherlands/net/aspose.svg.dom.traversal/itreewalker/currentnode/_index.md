---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "ITreeWalker CurrentNode-eigenschap. Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen in de DOM-boom kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt, ongeacht of het zich binnen de door het rootknooppunt gespecificeerde subboom bevindt of al dan niet wordt geaccepteerd door het filter en de whatToShow‑vlaggen. Verdere traversals vinden plaats ten opzichte van currentNode, zelfs als het niet deel uitmaakt van de huidige weergave, door de filters in de gevraagde richting toe te passen; als er geen traversals mogelijk zijn, wordt currentNode niet gewijzigd."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

De node waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen in de DOM-boom kunnen ertoe leiden dat de huidige node niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elke node, ongeacht of deze zich binnen de door de rootnode gespecificeerde subboom bevindt of al dan niet wordt geaccepteerd door het filter en de whatToShow‑vlaggen. Verdere traversals vinden plaats ten opzichte van currentNode, zelfs als deze niet deel uitmaakt van de huidige weergave, door de filters in de gevraagde richting toe te passen; als er geen traversals mogelijk zijn, wordt currentNode niet gewijzigd.

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

Het huidige knooppunt.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Opgetreden wanneer een poging wordt gedaan om currentNode op null in te stellen. |

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
