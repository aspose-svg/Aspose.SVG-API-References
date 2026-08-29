---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathEvaluator CreateNSResolver-methode. Past elk DOM‑knooppunt aan om namespaces op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waarin het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode lookupNamespaceURI op knooppunten bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van de knooppunten op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook correct de impliciete xml‑prefix op."
type: docs
weight: 20
url: /nl/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Past elke DOM‑knoop aan om namespaces op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van de knoop waarin deze in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knopen bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van de knoop op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat gebruikt wordt als context voor namespace‑resolutie. |

### Retourwaarde

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Zie ook

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
