---
title: "NodeFilter-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter-Klasse. Filter sind Objekte, die wissen, wie Knoten herausgefiltert werden können"
type: docs
weight: 3210
url: /de/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Filter sind Objekte, die wissen, wie man Knoten \"herausfiltert\".

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | Prüfen, ob ein bestimmter Knoten in der logischen Ansicht eines TreeWalker oder NodeIterator sichtbar ist. Diese Funktion wird von der Implementierung von TreeWalker und NodeIterator aufgerufen; sie wird normalerweise nicht direkt aus Benutzercode aufgerufen. (Obwohl Sie dies tun könnten, wenn Sie denselben Filter verwenden möchten, um Ihre Anwendungslogik zu steuern.) |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | Den Knoten akzeptieren. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten zurück. |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | Den Knoten ablehnen. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten nicht zurück. Für TreeWalker werden auch die Kinder dieses Knotens abgelehnt. NodeIterators behandeln dies als Synonym für FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | Überspringen Sie diesen einzelnen Knoten. Navigationsmethoden, die für NodeIterator oder TreeWalker definiert sind, geben diesen Knoten nicht zurück. Für sowohl NodeIterator als auch TreeWalker werden die Kinder dieses Knotens weiterhin berücksichtigt. |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | Alle Knoten anzeigen. |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | Attr-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Attributknoten als Wurzel erstellt wird; in diesem Fall bedeutet es, dass der Attributknoten an erster Stelle der Iteration oder Traversierung erscheint. Da Attribute niemals Kinder anderer Knoten sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection-Knoten anzeigen. |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | Kommentar-Knoten anzeigen. |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Dokument-Knoten anzeigen. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment-Knoten anzeigen. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType-Knoten anzeigen. |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Element-Knoten anzeigen. |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | Entity-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Entity-Knoten als Wurzel erstellt wird; in diesem Fall bedeutet es, dass der Entity-Knoten an erster Stelle der Traversierung erscheint. Da Entitäten nicht Teil des Dokumentbaums sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference-Knoten anzeigen. |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Notation-Knoten anzeigen. Dies ist nur sinnvoll, wenn ein Iterator oder Tree-Walker mit einem Notation-Knoten als Wurzel erstellt wird; in diesem Fall bedeutet es, dass der Notation-Knoten an erster Stelle der Traversierung erscheint. Da Notationen nicht Teil des Dokumentbaums sind, erscheinen sie nicht beim Durchlaufen des Dokumentbaums. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction-Knoten anzeigen. |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | Text-Knoten anzeigen. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
