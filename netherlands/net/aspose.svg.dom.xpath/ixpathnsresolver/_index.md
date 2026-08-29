---
title: "IXPathNSResolver Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.XPath.IXPathNSResolver interface. De XPathNSResolver‑interface staat toe dat prefix‑strings in de expressie correct worden gekoppeld aan namespaceURI‑strings. IXPathEvaluator kan een implementatie van IXPathNSResolver construeren vanuit een knoop, of de interface kan door elke toepassing worden geïmplementeerd."
type: docs
weight: 3330
url: /nl/net/aspose.svg.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

De `XPathNSResolver`-interface staat toe dat `prefix`-strings in de expressie correct worden gekoppeld aan `namespaceURI`-strings. [`IXPathEvaluator`](../ixpathevaluator/) kan een implementatie van `IXPathNSResolver` construeren vanuit een knoop, of de interface kan door elke toepassing worden geïmplementeerd.

```csharp
public interface IXPathNSResolver
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [LookupNamespaceURI](../../aspose.svg.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(*string*) | Zoek de namespace‑URI die bij de opgegeven namespace‑prefix hoort. De XPath‑evaluator mag dit nooit aanroepen met een `null` of leeg argument, omdat het resultaat hiervan ongedefinieerd is. |

### Zie ook

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
