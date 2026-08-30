---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.SVG för .NET API-referens"
description: "IXPathEvaluator CreateExpression-metod. Skapar ett parsat XPath-uttryck med lösta namnrymder. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksträngen till en mer effektiv intern form och förhandslösa alla namnrymdsprefix som förekommer i uttrycket."
type: docs
weight: 10
url: /sv/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Skapar ett analyserat XPath-uttryck med upplösta namnrymder. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksträngen till en mer effektiv intern form och förupplösa alla namnrymdsprefix som förekommer i uttrycket.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttrycksträngen som ska parsas. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑namnrymdsprefixet, inom XPath-uttrycket till lämpliga namnrymd-URI:er. Om detta anges som `null` kommer vilket namnrymdsprefix som helst i uttrycket att resultera i att [`DOMException`](../../../aspose.svg.dom/domexception/) kastas med koden `NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath-uttrycket.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Kastas om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Kastas om uttrycket innehåller namnrymdsprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
