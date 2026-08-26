---
title: "IXPathNSResolver Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.XPath.IXPathNSResolver Schnittstelle. Die XPathNSResolver Schnittstelle erlaubt es, Präfixzeichenketten im Ausdruck korrekt an namespaceURI‑Zeichenketten zu binden. IXPathEvaluator kann eine Implementierung von IXPathNSResolver aus einem Knoten erstellen, oder die Schnittstelle kann von jeder Anwendung implementiert werden."
type: docs
weight: 3330
url: /de/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

Die `XPathNSResolver` Schnittstelle erlaubt `prefix`‑Zeichenketten im Ausdruck korrekt an `namespaceURI`‑Zeichenketten zu binden. [`IXPathEvaluator`](../ixpathevaluator/) kann eine Implementierung von `IXPathNSResolver` aus einem Knoten erstellen, oder die Schnittstelle kann von jeder Anwendung implementiert werden.

```csharp
public interface IXPathNSResolver
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | Sucht die dem angegebenen Namespace‑Präfix zugeordnete Namespace‑URI. Der XPath‑Evaluator darf dies niemals mit einem `null`‑ oder leeren Argument aufrufen, da das Ergebnis undefiniert ist. |

### Siehe auch

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
