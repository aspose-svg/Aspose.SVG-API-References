---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "IXPathEvaluator CreateExpression-methode. Maakt een geparseerde XPath‑expressie met opgeloste namespaces. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Maakt een geparseerde XPath-expressie met opgeloste namespaces. Dit is nuttig wanneer een expressie opnieuw zal worden gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De XPath‑expressiestring die geparseerd moet worden. |
| resolver | IXPathNSResolver | De `resolver` maakt vertaling van alle prefixen, inclusief de `xml`‑namespace‑prefix, binnen de XPath‑expressie naar de juiste namespace‑URI's mogelijk. Als dit wordt opgegeven als `null`, zal elke namespace‑prefix binnen de expressie resulteren in een [`DOMException`](../../../aspose.svg.dom/domexception/) met de code `NAMESPACE_ERR`. |

### Retourwaarde

De gecompileerde vorm van de XPath‑expressie.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Opgeworpen als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Opgeworpen als de expressie namespace‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
