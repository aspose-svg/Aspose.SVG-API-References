---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Evaluate класса IXPathExpression. Выполняет вычисление этого XPath‑выражения и возвращает результат."
type: docs
weight: 10
url: /ru/net/aspose.svg.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Выполняет оценку этого XPath-выражения и возвращает результат.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| contextNode | Node | `context` — узел контекста для вычисления этого XPath‑выражения. Если [`IXPathEvaluator`](../../ixpathevaluator/) был получен путём приведения [`Document`](../../../aspose.svg.dom/document/), то он должен принадлежать тому же документу и быть [`Document`](../../../aspose.svg.dom/document/), [`Element`](../../../aspose.svg.dom/element/), [`Attr`](../../../aspose.svg.dom/attr/), [`Text`](../../../aspose.svg.dom/text/), [`CDATASection`](../../../aspose.svg.dom/cdatasection/), [`Comment`](../../../aspose.svg.dom/comment/), [`ProcessingInstruction`](../../../aspose.svg.dom/processinginstruction/) или узлом XPathNamespace. Если узел контекста является [`Text`](../../../aspose.svg.dom/text/) или [`CDATASection`](../../../aspose.svg.dom/cdatasection/), то контекст интерпретируется как весь логический текстовый узел, как видит его XPath, если только узел не пуст, в этом случае он не может служить контекстом XPath. |
| type | XPathResultType | Если указано конкретное `type`, то результат будет приведён к указанному типу с использованием преобразований XPath и вызовет ошибку, если требуемое приведение невозможно. Значение должно быть одним из вариантов [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` указывает конкретный объект результата, который может быть переиспользован и возвращён этим методом. Если он указан как `null` или реализация не переиспользует указанный объект, будет создан и возвращён новый объект результата. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/). |

### Возвращаемое значение

Результат вычисления XPath‑выражения. Для результатов XPath 1.0 этот объект будет типа [`IXPathResult`](../../ixpathresult/).

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | TYPE_ERR: Возникает, если результат нельзя преобразовать к указанному типу. |
| [DOMException](../../../aspose.svg.dom/domexception/) | WRONG_DOCUMENT_ERR: Узел принадлежит документу, не поддерживаемому [`IXPathEvaluator`](../../ixpathevaluator/), создавшим этот [`IXPathExpression`](../). |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Узел не является типом, разрешённым в качестве контекстного узла XPath, или запрашиваемый тип не допускается этим [`IXPathExpression`](../). |

### См. также

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.svg.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
