---
title: "Document.CreateExpression"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document CreateExpression‑metod. Skapar ett analyserat XPath‑uttryck med upplösta namnrymder. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla namnrymdsprefix som förekommer i uttrycket."
type: docs
weight: 890
url: /sv/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Skapar ett analyserat XPath-uttryck med upplösta namnrymder. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksträngen till en mer effektiv intern form och förupplösa alla namnrymdsprefix som förekommer i uttrycket.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttrycksträngen som ska parsas. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑namnrymdsprefixet, inom XPath‑uttrycket till lämpliga namnrymd‑URI:er. Om detta anges som `null` kommer vilket namnrymdsprefix som helst i uttrycket att resultera i att [`DOMException`](../../domexception/) kastas med koden `NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath-uttrycket.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Uppstår om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Uppstår om uttrycket innehåller namnrymdsprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
