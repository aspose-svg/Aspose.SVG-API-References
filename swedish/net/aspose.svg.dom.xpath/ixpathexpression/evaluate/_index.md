---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.SVG för .NET API-referens"
description: "IXPathExpression Evaluate-metod. Utvärderar detta XPath-uttryck och returnerar ett resultat."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Utvärderar detta XPath-uttryck och returnerar ett resultat.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contextNode | Node | `context` är kontextnod för utvärderingen av detta XPath‑uttryck. Om [`IXPathEvaluator`](../../ixpathevaluator/) erhölls genom att kasta [`Document`](../../../aspose.svg.dom/document/) måste den ägas av samma dokument och måste vara ett [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) eller XPathNamespace‑nod. Om kontextnoden är ett [`Text`](../../../aspose.svg.dom/text/) eller ett [`CDATASection`](../../../aspose.svg.dom/cdatasection/), tolkas kontexten som hela den logiska textnoden som ses av XPath, såvida inte noden är tom, i så fall får den inte användas som XPath‑kontext. |
| type | XPathResultType | Om en specifik `type` anges, kommer resultatet att tvingas konverteras till den angivna typen med hjälp av XPath‑omvandlingar och misslyckas om önskad omvandling inte är möjlig. Detta måste vara ett av värdena i [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` specificerar ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. Om detta anges som `null` eller implementeringen inte återanvänder det angivna resultatet, kommer ett nytt resultatobjekt att konstrueras och returneras. För XPath 1.0‑resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath‑uttrycket. För XPath 1.0‑resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Uppstår om resultatet inte kan konverteras för att returnera den angivna typen. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden kommer från ett dokument som inte stöds av [`IXPathEvaluator`](../../ixpathevaluator/) som skapade detta [`IXPathExpression`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte av en typ som tillåts som XPath‑kontextnod eller så är begäranstypen inte tillåten av detta [`IXPathExpression`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
