---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG för .NET API-referens"
description: "IXPathEvaluator Evaluate-metod. Utvärderar en XPath-uttrycksträng och returnerar ett resultat av den angivna typen om möjligt."
type: docs
weight: 30
url: /sv/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Utvärderar en XPath-uttrycksträng och returnerar ett resultat av den angivna typen om möjligt.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttrycksträngen som ska parsas och utvärderas. |
| contextNode | Node | `context` är kontextnod för utvärderingen av detta XPath-uttryck. Om [`IXPathEvaluator`](../) erhölls genom att kasta [`Document`](../../../aspose.svg.dom/document/) måste detta ägas av samma dokument och måste vara ett [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/), eller XPathNamespace‑nod. Om kontextnoden är ett [`Text`](../../../aspose.svg.dom/text/) eller ett [`CDATASection`](../../../aspose.svg.dom/cdatasection/), tolkas kontexten som hela den logiska textnoden som XPath ser, såvida inte noden är tom, i så fall kan den inte användas som XPath‑kontext. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑namnrymdsprefixet, inom XPath-uttrycket till lämpliga namnrymd-URI:er. Om detta anges som `null` kommer vilket namnrymdsprefix som helst i uttrycket att resultera i att [`DOMException`](../../../aspose.svg.dom/domexception/) kastas med koden `NAMESPACE_ERR`. |
| type | XPathResultType | Om en specifik `type` anges, kommer resultatet att returneras som motsvarande typ. För XPath 1.0-resultat måste detta vara ett av värdena i enumen [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` specificerar ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. Om detta anges som `null` eller implementeringen inte återanvänder det angivna resultatet, kommer ett nytt resultatobjekt att konstrueras och returneras. För XPath 1.0‑resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath‑uttrycket. För XPath 1.0‑resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Kastas om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Uppstår om resultatet inte kan konverteras för att returnera den angivna typen. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Kastas om uttrycket innehåller namnrymdsprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden kommer från ett dokument som inte stöds av denna [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte av en typ som tillåts som XPath‑kontextnod eller så är den begärda typen inte tillåten av denna [`IXPathEvaluator`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
