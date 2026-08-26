---
title: "Aspose.Svg.Dom.Traversal"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "The Aspose.Svg.Dom.Traversal namespace contains methods that create iterators and tree-walkers to navigate between elements and traverse a node and its children in document order"
type: docs
weight: 120
url: /de/net/aspose.svg.dom.traversal/
---
Der **Aspose.Svg.Dom.Traversal** Namensraum enthält Methoden, die Iteratoren und Baum‑Walker erzeugen, um zwischen Elementen zu navigieren und einen Knoten sowie dessen Kinder in Dokumentreihenfolge zu durchlaufen.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contains methods that create iterators and tree-walkers to traverse a node and its children in document order (depth first, pre-order traversal, which is equivalent to the order in which the start tags occur in the text representation of the document). In DOMs which support the Traversal feature, DocumentTraversal will be implemented by the same objects that implement the Document interface. |
| [IElementTraversal](./ielementtraversal/) | The ElementTraversal interface is a set of read-only attributes which allow an author to easily navigate between elements in a document. In conforming implementations of Element Traversal, all objects that implement Element must also implement the ElementTraversal interface. |
| [INodeFilter](./inodefilter/) | Filter sind Objekte, die wissen, wie man Knoten "filtert". Wenn einem NodeIterator oder TreeWalker ein NodeFilter übergeben wird, wendet er den Filter an, bevor er den nächsten Knoten zurückgibt. Wenn der Filter den Knoten akzeptiert, gibt die Traversal-Logik ihn zurück; andernfalls sucht die Traversal-Logik nach dem nächsten Knoten und tut so, als wäre der abgelehnte Knoten nicht vorhanden. |
| [INodeIterator](./inodeiterator/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Menge von Knoten. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die dokumentreihenfolge Traversierung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden erstellt, indem DocumentTraversal .createNodeIterator() aufgerufen wird. |
| [ITraversal](./itraversal/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Menge von Knoten. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die dokumentreihenfolge Traversierung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden erstellt, indem DocumentTraversal .createNodeIterator() aufgerufen wird. |
| [ITreeWalker](./itreewalker/) | TreeWalker-Objekte werden verwendet, um einen Dokumentbaum oder Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und Filter (falls vorhanden) definiert ist. Jede Funktion, die die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede durch einen TreeWalker definierte Ansicht. |
