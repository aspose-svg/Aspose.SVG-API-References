---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathEvaluator Evaluate-methode. Evalueert een XPath‑expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk."
type: docs
weight: 30
url: /nl/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evalueert een XPath-expressiestring en retourneert een resultaat van het opgegeven type indien mogelijk.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De XPath‑expressiestring die geparseerd en geëvalueerd moet worden. |
| contextNode | Node | De `context` is het contextknooppunt voor de evaluatie van deze XPath‑expressie. Als de [`IXPathEvaluator`](../) verkregen is door het casten van het [`Document`](../../../aspose.svg.dom/document/), dan moet dit eigendom zijn van hetzelfde document en moet het een [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) of XPathNamespace‑knooppunt zijn. Als het contextknooppunt een [`Text`](../../../aspose.svg.dom/text/) of een [`CDATASection`](../../../aspose.svg.dom/cdatasection/) is, dan wordt de context geïnterpreteerd als het volledige logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is, in welk geval het niet als XPath‑context kan dienen. |
| resolver | IXPathNSResolver | De `resolver` maakt vertaling van alle prefixen, inclusief de `xml`‑namespace‑prefix, binnen de XPath‑expressie naar de juiste namespace‑URI's mogelijk. Als dit wordt opgegeven als `null`, zal elke namespace‑prefix binnen de expressie resulteren in een [`DOMException`](../../../aspose.svg.dom/domexception/) met de code `NAMESPACE_ERR`. |
| type | XPathResultType | Als een specifiek `type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. Voor XPath 1.0‑resultaten moet dit een van de waarden van de [`XPathResultType`](../../xpathresulttype/) enum zijn. |
| result | Object | De `result` geeft een specifiek resultaatobject aan dat door deze methode kan worden hergebruikt en geretourneerd. Als dit is opgegeven als `null` of de implementatie het opgegeven resultaat niet hergebruikt, wordt een nieuw resultaatobject gecreëerd en geretourneerd. Voor XPath 1.0‑resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath‑expressie. Voor XPath 1.0‑resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Opgeworpen als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Opgeworpen als het resultaat niet kan worden geconverteerd naar het opgegeven type. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Opgeworpen als de expressie namespace‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Het knooppunt komt uit een document dat niet wordt ondersteund door deze [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Het knooppunt is geen type dat is toegestaan als XPath‑contextknooppunt of het aangevraagde type wordt niet ondersteund door deze [`IXPathEvaluator`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
