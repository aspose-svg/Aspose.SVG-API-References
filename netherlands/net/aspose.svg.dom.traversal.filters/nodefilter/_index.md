---
title: "NodeFilter Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter class. Filters zijn objecten die weten hoe ze knooppunten moeten filteren."
type: docs
weight: 3210
url: /nl/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filters zijn objecten die weten hoe ze knooppunten moeten "filteren".

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dat wel kunt doen als je dezelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Accepteer het knooppunt. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt retourneren. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Wijs het knooppunt af. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor TreeWalker worden ook de kinderen van dit knooppunt afgewezen. NodeIterators beschouwen dit als een synoniem voor FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Sla dit enkele knooppunt over. Navigatiemethoden gedefinieerd voor NodeIterator of TreeWalker zullen dit knooppunt niet retourneren. Voor zowel NodeIterator als TreeWalker worden de kinderen van dit knooppunt nog steeds in overweging genomen. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Toon alle knooppunten. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Toon Attr‑knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een attribuutknooppunt als root; in dat geval betekent dit dat het attribuutknooppunt op de eerste positie van de iteratie of traversie verschijnt. Aangezien attributen nooit kinderen van andere knooppunten zijn, verschijnen ze niet bij het doorlopen van de documentboom. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Toon CDATASection‑knooppunten. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Toon commentaarknooppunten. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Toon documentknooppunten. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Toon DocumentFragment-knooppunten. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Toon DocumentType-knooppunten. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Toon Element-knooppunten. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Toon Entity-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een Entity-knooppunt als wortel; in dit geval betekent dit dat het Entity-knooppunt op de eerste positie van de traversatie verschijnt. Aangezien entiteiten geen deel uitmaken van de documentboom, verschijnen ze niet bij het doorlopen van de documentboom. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Toon EntityReference-knooppunten. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Toon Notation-knooppunten. Dit is alleen zinvol bij het maken van een iterator of tree-walker met een Notation-knooppunt als wortel; in dit geval betekent dit dat het Notation-knooppunt op de eerste positie van de traversatie verschijnt. Aangezien notaties geen deel uitmaken van de documentboom, verschijnen ze niet bij het doorlopen van de documentboom. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Toon ProcessingInstruction-knooppunten. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Toon Text-knooppunten. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
