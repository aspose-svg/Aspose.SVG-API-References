---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathEvaluator Evaluate-Methode. Bewertet einen XPath-Ausdrucks-String und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück."
type: docs
weight: 30
url: /de/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Wertet eine XPath‑Ausdruckszeichenkette aus und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Der XPath-Ausdruck-String, der geparst und ausgewertet werden soll. |
| contextNode | Node | Der `context` ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn der [`IXPathEvaluator`](../) durch Casten des [`Document`](../../../aspose.svg.dom/document/) erhalten wurde, muss dieser dem selben Dokument gehören und ein [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) oder XPathNamespace‑Knoten sein. Ist der Kontextknoten ein [`Text`](../../../aspose.svg.dom/text/) oder ein [`CDATASection`](../../../aspose.svg.dom/cdatasection/), wird der Kontext als der gesamte logische Textknoten interpretiert, wie er von XPath gesehen wird, es sei denn, der Knoten ist leer, dann kann er nicht als XPath‑Kontext dienen. |
| resolver | IXPathNSResolver | Der `resolver` ermöglicht die Übersetzung aller Präfixe, einschließlich des `xml`-Namespace‑Präfixes, innerhalb des XPath-Ausdrucks in geeignete Namespace-URIs. Wird er als `null` angegeben, führt jedes Namespace‑Präfix im Ausdruck dazu, dass [`DOMException`](../../../aspose.svg.dom/domexception/) mit dem Code `NAMESPACE_ERR` ausgelöst wird. |
| type | XPathResultType | Wenn ein bestimmter `type` angegeben ist, wird das Ergebnis als der entsprechende Typ zurückgegeben. Für XPath‑1.0‑Ergebnisse muss dies einer der Werte des Enums [`XPathResultType`](../../xpathresulttype/) sein. |
| result | Object | Das `result` gibt ein bestimmtes Ergebnisobjekt an, das wiederverwendet und von dieser Methode zurückgegeben werden kann. Wenn dies als `null` angegeben wird oder die Implementierung das angegebene Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath‑Ausdrucks. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: Wird ausgelöst, wenn der Ausdruck gemäß den Regeln des [`IXPathEvaluator`](../) nicht zulässig ist. |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Wird ausgelöst, wenn das Ergebnis nicht in den angegebenen Typ konvertiert werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: Wird ausgelöst, wenn der Ausdruck Namespace‑Präfixe enthält, die vom angegebenen [`IXPathNSResolver`](../../ixpathnsresolver/) nicht aufgelöst werden können. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das von diesem [`IXPathEvaluator`](../) nicht unterstützt wird. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Der Knoten ist kein zulässiger Typ für einen XPath-Kontextknoten oder der Anforderungstyp wird von diesem [`IXPathEvaluator`](../) nicht unterstützt. |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
