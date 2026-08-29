---
title: "Document.Evaluate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document Evaluate. Выполняет оценку строки XPath-выражения и возвращает результат указанного типа, если это возможно."
type: docs
weight: 950
url: /ru/net/aspose.svg.dom/document/evaluate/
---
## Document.Evaluate method

Выполняет оценку строки XPath‑выражения и возвращает результат указанного типа, если это возможно.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка XPath‑выражения, которую нужно разобрать и оценить. |
| contextNode | Node | Контекст — это узел контекста для оценки этого XPath‑выражения. |
| разрешитель | IXPathNSResolver | Разрешитель позволяет переводить все префиксы, включая префикс пространства имён xml, внутри XPath‑выражения в соответствующие URI пространств имён. |
| type | XPathResultType | Если указан конкретный тип, то результат будет возвращён в виде соответствующего типа. |
| result | Объект | Результат указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. |

### Возвращаемое значение

Результат оценки XPath‑выражения.

### См. также

* interface [IXPathResult](../../../aspose.svg.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.svg.dom.xpath/xpathresulttype/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
