---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathEvaluator CreateNSResolver-Methode. Passt jeden DOM‑Knoten an, um Namespaces aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode lookupNamespaceURI bei Knoten, indem er den namespaceURI aus einem gegebenen Präfix mithilfe der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knoten‑Hierarchie auflöst und zudem das implizite xml‑Präfix korrekt behandelt."
type: docs
weight: 20
url: /de/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Passt jeden DOM‑Knoten an, um Namespaces aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` bei Knoten, indem er den namespaceURI aus einem gegebenen Präfix anhand der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeResolver | Node | Der Knoten, der als Kontext für die Namespace‑Auflösung verwendet wird. |

### Rückgabewert

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Siehe auch

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
