---
title: "IXPathEvaluator Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.XPath.IXPathEvaluator interface. De evaluatie van XPath-expressies wordt geleverd door IXPathEvaluator"
type: docs
weight: 3310
url: /nl/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

De evaluatie van XPath-expressies wordt geleverd door `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Maakt een geparseerde XPath-expressie met opgeloste namespaces. Dit is nuttig wanneer een expressie opnieuw zal worden gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Past elke DOM‑knoop aan om namespaces op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van de knoop waarin deze in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knopen bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van de knoop op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Evalueert een XPath-expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk. |

### Zie ook

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
