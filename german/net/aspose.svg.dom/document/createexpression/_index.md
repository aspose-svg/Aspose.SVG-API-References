---
title: "Document.CreateExpression"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document CreateExpression-Methode. Erstellt einen geparsten XPath-Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, den Ausdrucksstring in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace-Präfixe vorab aufzulösen."
type: docs
weight: 890
url: /de/net/aspose.svg.dom/document/createexpression/
---
## Document.CreateExpression method

Erstellt einen geparsten XPath‑Ausdruck mit aufgelösten Namespaces. Dies ist nützlich, wenn ein Ausdruck in einer Anwendung wiederverwendet wird, da es ermöglicht, die Ausdruckszeichenkette in eine effizientere interne Form zu kompilieren und alle im Ausdruck vorkommenden Namespace‑Präfixe vorab aufzulösen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Der XPath-Ausdruck-String, der geparst werden soll. |
| resolver | IXPathNSResolver | Der `resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich des `xml`-Namespace-Präfixes, innerhalb des XPath-Ausdrucks in geeignete Namespace-URIs. Wird er als `null` angegeben, führt jedes Namespace-Präfix im Ausdruck dazu, dass eine [`DOMException`](../../domexception/) mit dem Code `NAMESPACE_ERR` ausgelöst wird. |

### Rückgabewert

Die kompilierte Form des XPath-Ausdrucks.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des [`IXPathEvaluator`](../../../aspose.svg.dom.xpath/ixpathevaluator/) nicht zulässig ist. |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Namespace-Präfixe enthält, die vom angegebenen [`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) nicht aufgelöst werden können. |

### Siehe auch

* interface [IXPathExpression](../../../aspose.svg.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
