---
title: "Document.Evaluate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document Evaluate‑methode. Evalueert een XPath‑expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk."
type: docs
weight: 950
url: /nl/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Evalueert een XPath-expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De XPath‑expressiestring die geparseerd en geëvalueerd moet worden. |
| contextNode | Node | De context is de contextknoop voor de evaluatie van deze XPath-expressie. |
| resolver | IXPathNSResolver | De resolver staat vertaling van alle prefixes toe, inclusief de xml-namespaceprefix, binnen de XPath-expressie naar de juiste namespace-URI's. |
| type | XPathResultType | Als een specifiek type is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. |
| result | Object | Het resultaat specificeert een specifiek resultaatobject dat door deze methode kan worden hergebruikt en geretourneerd. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath-expressie.

### Zie ook

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
