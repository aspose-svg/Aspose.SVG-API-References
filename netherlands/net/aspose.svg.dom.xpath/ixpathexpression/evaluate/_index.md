---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathExpression Evaluate methode. Evalueert deze XPath‑expressie en retourneert een resultaat"
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evalueert deze XPath-expressie en retourneert een resultaat.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contextNode | Node | De `context` is het contextknooppunt voor de evaluatie van deze XPath‑expressie. Als de [`IXPathEvaluator`](../../ixpathevaluator/) is verkregen door het casten van het [`Document`](../../../aspose.svg.dom/document/), dan moet dit eigendom zijn van hetzelfde document en moet het een [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) of XPathNamespace‑knooppunt zijn. Als het contextknooppunt een [`Text`](../../../aspose.svg.dom/text/) of een [`CDATASection`](../../../aspose.svg.dom/cdatasection/) is, dan wordt de context geïnterpreteerd als het volledige logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is, in welk geval het mogelijk niet als XPath‑context kan dienen. |
| type | XPathResultType | Als een specifiek `type` is opgegeven, dan wordt het resultaat omgezet om het opgegeven type te retourneren, gebruikmakend van XPath‑conversies, en zal falen als de gewenste omzetting niet mogelijk is. Dit moet een van de waarden van [`XPathResultType`](../../xpathresulttype/) zijn. |
| result | Object | De `result` geeft een specifiek resultaatobject aan dat door deze methode kan worden hergebruikt en geretourneerd. Als dit is opgegeven als `null` of de implementatie het opgegeven resultaat niet hergebruikt, wordt een nieuw resultaatobject gecreëerd en geretourneerd. Voor XPath 1.0‑resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath‑expressie. Voor XPath 1.0‑resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Opgeworpen als het resultaat niet kan worden geconverteerd naar het opgegeven type. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Het knooppunt komt uit een document dat niet wordt ondersteund door de [`IXPathEvaluator`](../../ixpathevaluator/) die deze [`IXPathExpression`](../) heeft gemaakt. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Het knooppunt is geen type dat is toegestaan als XPath‑contextknooppunt of het aangevraagde type is niet toegestaan door deze [`IXPathExpression`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
