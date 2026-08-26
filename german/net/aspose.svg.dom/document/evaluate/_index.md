---
title: "Document.Evaluate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document Evaluate Methode. Bewertet einen XPath-Ausdrucksstring und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück."
type: docs
weight: 950
url: /de/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Wertet eine XPath‑Ausdruckszeichenkette aus und gibt, falls möglich, ein Ergebnis des angegebenen Typs zurück.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expression | String | Der XPath-Ausdruck-String, der geparst und ausgewertet werden soll. |
| contextNode | Node | Der Kontext ist der Kontextknoten für die Auswertung dieses XPath-Ausdrucks. |
| resolver | IXPathNSResolver | Der Resolver ermöglicht die Übersetzung aller Präfixe, einschließlich des xml-Namespace-Präfixes, innerhalb des XPath-Ausdrucks in geeignete Namespace-URIs. |
| type | XPathResultType | Wenn ein bestimmter Typ angegeben ist, wird das Ergebnis als der entsprechende Typ zurückgegeben. |
| result | Objekt | Das Ergebnis gibt ein bestimmtes Ergebnisobjekt an, das von dieser Methode wiederverwendet und zurückgegeben werden kann. |

### Rückgabewert

Das Ergebnis der Auswertung des XPath-Ausdrucks.

### Siehe auch

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
