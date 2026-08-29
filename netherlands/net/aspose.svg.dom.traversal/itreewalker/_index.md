---
title: "ITreeWalker-interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.ITreeWalker interface. TreeWalker-objecten worden gebruikt om door een documentboom of subboom te navigeren met behulp van de weergave van het document die wordt gedefinieerd door hun whatToShow‑vlaggen en eventueel filter. Elke functie die navigatie uitvoert met een TreeWalker zal automatisch elke weergave ondersteunen die door een TreeWalker wordt gedefinieerd."
type: docs
weight: 3270
url: /nl/net/aspose.svg.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker‑objecten worden gebruikt om een documentboom of subboom te navigeren met behulp van de weergave van het document die wordt gedefinieerd door hun whatToShow‑vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met een TreeWalker ondersteunt automatisch elke weergave die door een TreeWalker is gedefinieerd.

Het weglaten van nodes uit de logische weergave van een subboom kan resulteren in een structuur die wezenlijk verschilt van dezelfde subboom in het volledige, ongefilterde document. Nodes die broers/zussen zijn in de TreeWalker-weergave kunnen kinderen zijn van verschillende, sterk gescheiden nodes in de oorspronkelijke weergave. Bijvoorbeeld, overweeg een NodeFilter die alle nodes overslaat behalve Text-nodes en de rootnode van een document. In de resulterende logische weergave zullen alle tekstnodes broers/zussen zijn en verschijnen als directe kinderen van de rootnode, ongeacht hoe diep genest de structuur van het oorspronkelijke document is.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CurrentNode](../../aspose.svg.dom.traversal/itreewalker/currentnode/) { get; set; } | De node waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen in de DOM-boom kunnen ertoe leiden dat de huidige node niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elke node, ongeacht of deze zich binnen de door de rootnode gespecificeerde subboom bevindt of al dan niet wordt geaccepteerd door het filter en de whatToShow‑vlaggen. Verdere traversals vinden plaats ten opzichte van currentNode, zelfs als deze niet deel uitmaakt van de huidige weergave, door de filters in de gevraagde richting toe te passen; als er geen traversals mogelijk zijn, wordt currentNode niet gewijzigd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [FirstChild](../../aspose.svg.dom.traversal/itreewalker/firstchild/)() | Verplaatst de TreeWalker naar het eerste zichtbare kind van de huidige node en retourneert de nieuwe node. Als de huidige node geen zichtbare kinderen heeft, wordt null geretourneerd en blijft de huidige node behouden. |
| [LastChild](../../aspose.svg.dom.traversal/itreewalker/lastchild/)() | Verplaatst de TreeWalker naar het laatste zichtbare kind van de huidige node en retourneert de nieuwe node. Als de huidige node geen zichtbare kinderen heeft, wordt null geretourneerd en blijft de huidige node behouden. |
| [NextNode](../../aspose.svg.dom.traversal/itreewalker/nextnode/)() | Verplaatst de TreeWalker naar de volgende zichtbare node in documentvolgorde ten opzichte van de huidige node en retourneert de nieuwe node. Als de huidige node geen volgende node heeft, of als de zoektocht naar nextNode probeert omhoog te gaan vanaf de rootnode van de TreeWalker, wordt null geretourneerd en blijft de huidige node behouden. |
| [NextSibling](../../aspose.svg.dom.traversal/itreewalker/nextsibling/)() | Verplaatst de TreeWalker naar de volgende sibling van de huidige node en retourneert de nieuwe node. Als de huidige node geen zichtbaar volgende sibling heeft, wordt null geretourneerd en blijft de huidige node behouden. |
| [ParentNode](../../aspose.svg.dom.traversal/itreewalker/parentnode/)() | Verplaatst zich naar en retourneert het dichtstbijzijnde zichtbare voorouderknooppunt van het huidige knooppunt. Als de zoekopdracht naar parentNode probeert omhoog te gaan vanaf de wortelknooppunt van de TreeWalker, of als het geen zichtbaar voorouderknooppunt kan vinden, behoudt deze methode de huidige positie en retourneert null. |
| [PreviousNode](../../aspose.svg.dom.traversal/itreewalker/previousnode/)() | Verplaatst de TreeWalker naar het vorige zichtbare knooppunt in documentvolgorde ten opzichte van het huidige knooppunt, en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen vorig knooppunt heeft, of als de zoekopdracht naar previousNode probeert omhoog te gaan vanaf de wortelknooppunt van de TreeWalker, retourneert null, en behoudt het huidige knooppunt. |
| [PreviousSibling](../../aspose.svg.dom.traversal/itreewalker/previoussibling/)() | Verplaatst de TreeWalker naar de vorige sibling van het huidige knooppunt, en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbare vorige sibling heeft, retourneert null, en behoudt het huidige knooppunt. |

### Zie ook

* interface [ITraversal](../itraversal/)
* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
