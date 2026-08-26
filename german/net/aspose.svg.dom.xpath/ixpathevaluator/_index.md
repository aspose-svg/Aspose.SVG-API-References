---
title: "IXPathEvaluator‑Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.XPath.IXPathEvaluator Schnittstelle. Die Auswertung von XPath‑Ausdrücken wird von IXPathEvaluator bereitgestellt."
type: docs
weight: 3310
url: /de/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Die Auswertung von XPath‑Ausdrücken wird von `IXPathEvaluator` bereitgestellt.

```csharp
public interface IXPathEvaluator
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace‑Präfixe vorab aufzulösen. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Passt jeden DOM‑Knoten an, um Namespaces aufzulösen, sodass ein XPath‑Ausdruck leicht relativ zum Kontext des Knotens, in dem er im Dokument erschien, ausgewertet werden kann. Dieser Adapter funktioniert wie die DOM‑Level‑3‑Methode `lookupNamespaceURI` bei Knoten, indem er den namespaceURI aus einem gegebenen Präfix anhand der zum Zeitpunkt des Aufrufs von lookupNamespaceURI verfügbaren Informationen in der Knotenhierarchie auflöst und dabei auch das implizite xml‑Präfix korrekt behandelt. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Wertet eine XPath‑Ausdruckszeichenkette aus und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück. |

### Siehe auch

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
