---
title: "NodeFilter-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter-klass. Filter är objekt som vet hur man filtrerar bort noder"
type: docs
weight: 3210
url: /sv/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter är objekt som vet hur man "filtrerar bort" noder.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Testa om en specificerad nod är synlig i den logiska vyn av en TreeWalker eller NodeIterator. Denna funktion kommer att anropas av implementeringen av TreeWalker och NodeIterator; den anropas normalt inte direkt från användarkod. (Även om du kan göra det om du vill använda samma filter för att styra din egen programlogik.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Acceptera noden. Navigationsmetoder definierade för NodeIterator eller TreeWalker kommer att returnera denna nod. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Avvisa noden. Navigationsmetoder definierade för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För TreeWalker kommer även barnen till denna nod att avvisas. NodeIterators behandlar detta som en synonym för FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Hoppa över denna enskilda nod. Navigationsmetoder definierade för NodeIterator eller TreeWalker kommer inte att returnera denna nod. För både NodeIterator och TreeWalker kommer barnen till denna nod fortfarande att beaktas. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Visa alla noder. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Visa Attr-noder. Detta är meningsfullt endast när man skapar en iterator eller tree-walker med en attributnod som rot; i så fall betyder det att attributnoden kommer att visas i den första positionen av iterationen eller traverseringen. Eftersom attribut aldrig är barn till andra noder visas de inte vid traversering av dokumentträdet. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | Visa CDATASection-noder. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Visa Comment-noder. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Visa Document-noder. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | Visa DocumentFragment-noder. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | Visa DocumentType-noder. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Visa Element-noder. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Visa Entity-noder. Detta är meningsfullt endast när man skapar en iterator eller träd‑vandrare med en Entity-nod som rot; i detta fall betyder det att Entity-noden kommer att visas i den första positionen av traverseringen. Eftersom Entity-noder inte är en del av dokumentträdet visas de inte när man traverserar dokumentträdet. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | Visa EntityReference-noder. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Visa Notation-noder. Detta är meningsfullt endast när man skapar en iterator eller träd‑vandrare med en Notation-nod som rot; i detta fall betyder det att Notation-noden kommer att visas i den första positionen av traverseringen. Eftersom Notation-noder inte är en del av dokumentträdet visas de inte när man traverserar dokumentträdet. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | Visa ProcessingInstruction-noder. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Visa Text-noder. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
