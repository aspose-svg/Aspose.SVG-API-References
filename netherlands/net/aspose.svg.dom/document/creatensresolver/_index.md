---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateNSResolver-methode. Past elke DOM-knoop aan om namespaces op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van de knoop waarin deze in het document voorkomt. Deze adapter werkt zoals de DOM Level 3-methode lookupNamespaceURI op knopen bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de knoophiërarchie op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook correct de impliciete xml-prefix op."
type: docs
weight: 910
url: /nl/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Past elke DOM‑knoop aan om namespaces op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van de knoop waarin deze in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knopen bij het oplossen van de namespaceURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van de knoop op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat gebruikt wordt als context voor namespace‑resolutie. |

### Retourwaarde

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### Zie ook

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
