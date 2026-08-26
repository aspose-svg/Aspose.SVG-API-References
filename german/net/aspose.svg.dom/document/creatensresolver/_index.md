---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document CreateNSResolver-Methode. Passt jeden DOM-Knoten an, um Namespaces aufzulösen, sodass ein XPath-Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM Level‑3‑Methode lookupNamespaceURI bei Knoten, um den namespaceURI aus einem gegebenen Präfix zu ermitteln, wobei die zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie verwendet werden, und löst zudem korrekt das implizite xml‑Präfix auf."
type: docs
weight: 910
url: /de/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Passt jeden DOM‑Knoten an, um Namespaces aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` bei Knoten, indem er den namespaceURI aus einem gegebenen Präfix anhand der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeResolver | Node | Der Knoten, der als Kontext für die Namespace‑Auflösung verwendet wird. |

### Rückgabewert

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Siehe auch

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
