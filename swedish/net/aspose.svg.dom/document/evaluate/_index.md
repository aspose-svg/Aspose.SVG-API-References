---
title: "Document.Evaluate"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document Evaluate‑metod. Utvärderar en XPath‑uttrycksträng och returnerar ett resultat av den angivna typen om möjligt"
type: docs
weight: 950
url: /sv/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Utvärderar en XPath-uttrycksträng och returnerar ett resultat av den angivna typen om möjligt.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttrycksträngen som ska parsas och utvärderas. |
| contextNode | Node | Kontexten är kontextnod för utvärderingen av detta XPath‑uttryck. |
| resolver | IXPathNSResolver | Resolvern tillåter översättning av alla prefix, inklusive xml‑namnrymdsprefixet, inom XPath‑uttrycket till lämpliga namnrymd‑URI:er. |
| type | XPathResultType | Om en specifik typ anges, kommer resultatet att returneras som motsvarande typ. |
| result | Objekt | Resultatet specificerar ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. |

### Returvärde

Resultatet av utvärderingen av XPath‑uttrycket.

### Se även

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
