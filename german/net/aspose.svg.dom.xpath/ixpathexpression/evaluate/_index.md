---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "IXPathExpression‑Evaluate‑Methode. Bewertet diesen XPath-Ausdruck und gibt ein Ergebnis zurück."
type: docs
weight: 10
url: /de/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evaluiert diesen XPath-Ausdruck und gibt ein Ergebnis zurück.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contextNode | Node | Der `context` ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. Wenn der [`IXPathEvaluator`](../../ixpathevaluator/) durch Casten des [`Document`](../../../aspose.svg.dom/document/) erhalten wurde, muss er dem selben Dokument gehören und muss ein [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) oder XPathNamespace‑Knoten sein. Wenn der Kontextknoten ein [`Text`](../../../aspose.svg.dom/text/) oder ein [`CDATASection`](../../../aspose.svg.dom/cdatasection/) ist, wird der Kontext als der gesamte logische Textknoten interpretiert, wie von XPath gesehen, es sei denn, der Knoten ist leer, dann kann er nicht als XPath‑Kontext dienen. |
| type | XPathResultType | Wenn ein bestimmter `type` angegeben ist, wird das Ergebnis so umgewandelt, dass es den angegebenen Typ zurückgibt, wobei XPath‑Konvertierungen verwendet werden, und schlägt fehl, wenn die gewünschte Umwandlung nicht möglich ist. Dies muss einer der Werte von [`XPathResultType`](../../xpathresulttype/) sein. |
| result | Object | Das `result` gibt ein bestimmtes Ergebnisobjekt an, das wiederverwendet und von dieser Methode zurückgegeben werden kann. Wenn dies als `null` angegeben wird oder die Implementierung das angegebene Ergebnis nicht wiederverwendet, wird ein neues Ergebnisobjekt erstellt und zurückgegeben. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath‑Ausdrucks. Für XPath‑1.0‑Ergebnisse wird dieses Objekt vom Typ [`IXPathResult`](../../ixpathresult/) sein.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Wird ausgelöst, wenn das Ergebnis nicht in den angegebenen Typ konvertiert werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Der Knoten stammt aus einem Dokument, das von dem [`IXPathEvaluator`](../../ixpathevaluator/) nicht unterstützt wird, der diesen [`IXPathExpression`](../) erstellt hat. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Der Knoten ist kein zulässiger Typ für einen XPath‑Kontextknoten oder der Anforderungstyp ist von diesem [`IXPathExpression`](../) nicht erlaubt. |

### Siehe auch

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
