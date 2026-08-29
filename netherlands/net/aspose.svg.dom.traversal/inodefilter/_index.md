---
title: "INodeFilter Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.INodeFilter interface. Filters zijn objecten die weten hoe knooppunten gefilterd moeten worden. Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij de filter toe voordat hij het volgende knooppunt retourneert. Als de filter aangeeft het knooppunt te accepteren, retourneert de traversallogica het; anders zoekt de traversie naar het volgende knooppunt en doet alsof het afgewezen knooppunt er niet was."
type: docs
weight: 3240
url: /nl/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters zijn objecten die weten hoe ze knopen moeten \"filteren\". Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij de volgende knoop retourneert. Als het filter aangeeft de knoop te accepteren, retourneert de traversielogica deze; anders zoekt de traversie naar de volgende knoop en doet alsof de afgewezen knoop niet bestond.

De DOM biedt geen filters. NodeFilter is slechts een interface die gebruikers kunnen implementeren om hun eigen filters te leveren.

NodeFilters hoeven niet te weten hoe ze van node naar node moeten traversen, noch hoeven ze iets te weten over de datastructuur die wordt doorlopen. Dit maakt het zeer eenvoudig om filters te schrijven, aangezien het enige wat ze moeten weten hoe ze moeten doen, is het evalueren van een enkele node. Eén filter kan worden gebruikt met een aantal verschillende soorten doorlopen, wat codehergebruik stimuleert.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeFilter
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dat wel kunt doen als je dezelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.) |

### Zie ook

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
