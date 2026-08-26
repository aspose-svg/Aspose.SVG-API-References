---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathEvaluator CreateExpression-Methode. Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet werden soll, da er es ermöglicht, den Ausdrucks‑String in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace‑Präfixe vorab aufzulösen."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace‑Präfixe vorab aufzulösen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Der XPath-Ausdruck-String, der geparst werden soll. |
| resolver | IXPathNSResolver | Der `resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich des `xml`-Namespace‑Präfixes, innerhalb des XPath-Ausdrucks in geeignete Namespace-URIs. Wird er als `null` angegeben, führt jedes Namespace‑Präfix im Ausdruck dazu, dass [`DOMException`](../../../aspose.svg.dom/domexception/) mit dem Code `NAMESPACE_ERR` ausgelöst wird. |

### Rückgabewert

Die kompilierte Form des XPath-Ausdrucks.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des [`IXPathEvaluator`](../) nicht zulässig ist. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Namespace‑Präfixe enthält, die vom angegebenen [`IXPathNSResolver`](../../ixpathnsresolver/) nicht aufgelöst werden können. |

### Siehe auch

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
