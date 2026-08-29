---
title: "IXPathEvaluator интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.XPath.IXPathEvaluator интерфейс. Оценка XPath‑выражений предоставляется IXPathEvaluator"
type: docs
weight: 3310
url: /ru/net/aspose.svg.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Оценка XPath‑выражений предоставляется `IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateExpression](../../aspose.svg.dom.xpath/ixpathevaluator/createexpression/)(*string, [IXPathNSResolver](../ixpathnsresolver/)*) | Создаёт разобранное XPath‑выражение с разрешёнными пространствами имён. Это полезно, когда выражение будет переиспользоваться в приложении, поскольку позволяет компилировать строку выражения в более эффективную внутреннюю форму и предварительно разрешать все префиксы пространств имён, встречающиеся в выражении. |
| [CreateNSResolver](../../aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | Адаптирует любой DOM‑узел для разрешения пространств имён, чтобы XPath‑выражение можно было легко вычислять относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml. |
| [Evaluate](../../aspose.svg.dom.xpath/ixpathevaluator/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../ixpathnsresolver/), [XPathResultType](../xpathresulttype/), object*) | Выполняет оценку строки XPath‑выражения и возвращает результат указанного типа, если это возможно. |

### См. также

* namespace [Aspose.Svg.Dom.XPath](../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../)
