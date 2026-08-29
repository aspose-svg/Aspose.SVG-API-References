---
title: "Document.CreateExpression"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document CreateExpression‑methode. Maakt een geparseerde XPath‑expressie met opgeloste namespaces. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen."
type: docs
weight: 890
url: /nl/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Maakt een geparseerde XPath-expressie met opgeloste namespaces. Dit is nuttig wanneer een expressie opnieuw zal worden gebruikt in een toepassing, omdat het mogelijk maakt de expressiestring te compileren naar een efficiëntere interne vorm en alle namespace‑prefixen die in de expressie voorkomen vooraf op te lossen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De XPath‑expressiestring die geparseerd moet worden. |
| resolver | IXPathNSResolver | De `resolver` staat vertaling van alle prefixen toe, inclusief de `xml`‑namespace‑prefix, binnen de XPath‑expressie naar de juiste namespace‑URI's. Als dit wordt opgegeven als `null`, zal elke namespace‑prefix binnen de expressie resulteren in een [`DOMException`](../../domexception/) met de code `NAMESPACE_ERR`. |

### Retourwaarde

De gecompileerde vorm van de XPath‑expressie.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Wordt opgegooid als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Wordt opgegooid als de expressie namespace‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
