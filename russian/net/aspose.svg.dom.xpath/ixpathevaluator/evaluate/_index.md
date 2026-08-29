---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IXPathEvaluator Evaluate. Выполняет оценку строки XPath‑выражения и, если возможно, возвращает результат указанного типа."
type: docs
weight: 30
url: /ru/net/aspose.svg.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Выполняет оценку строки XPath‑выражения и возвращает результат указанного типа, если это возможно.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| expression | String | Строка XPath‑выражения, которую нужно разобрать и оценить. |
| contextNode | Node | Параметр `context` — это контекстный узел для оценки данного XPath‑выражения. Если [`IXPathEvaluator`](../) был получен путём приведения типа [`Document`](../../../aspose.svg.dom/document/), то этот узел должен принадлежать тому же документу и быть одним из следующих типов: [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) или узел XPathNamespace. Если контекстный узел является [`Text`](../../../aspose.svg.dom/text/) или [`CDATASection`](../../../aspose.svg.dom/cdatasection/), то контекст интерпретируется как весь логический текстовый узел, как видит его XPath, если только узел не пуст, в этом случае он не может служить контекстом XPath. |
| resolver | IXPathNSResolver | Параметр `resolver` позволяет переводить все префиксы, включая префикс пространства имён `xml`, внутри XPath‑выражения в соответствующие URI пространств имён. Если он указан как `null`, любой префикс пространства имён внутри выражения приведёт к выбросу [`DOMException`](../../../aspose.svg.dom/domexception/) с кодом `NAMESPACE_ERR`. |
| type | XPathResultType | Если указано конкретное `type`, результат будет возвращён в соответствующем типе. Для результатов XPath 1.0 это должно быть одно из значений перечисления [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. Если он указан как `null` или реализация не переиспользует указанный объект, будет создан и возвращён новый объект результата. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат вычисления XPath‑выражения. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | INVALID_EXPRESSION_ERR: вызывается, если выражение недопустимо согласно правилам [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Возникает, если результат нельзя преобразовать к указанному типу. |
| [DOMException](../../../aspose.svg.dom/domexception/) | NAMESPACE_ERR: вызывается, если выражение содержит префиксы пространств имён, которые не могут быть разрешены указанным [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Узел принадлежит документу, который не поддерживается этим [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Узел не является типом, допускаемым в качестве контекстного узла XPath, или запрашиваемый тип не поддерживается этим [`IXPathEvaluator`](../). |

### См. также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
