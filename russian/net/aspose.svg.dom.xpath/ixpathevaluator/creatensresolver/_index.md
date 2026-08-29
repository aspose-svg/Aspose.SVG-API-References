---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод IXPathEvaluator CreateNSResolver. Приводит любой DOM‑узел к разрешению пространств имён, чтобы XPath‑выражение могло быть легко вычислено относительно контекста узла, в котором оно появилось в документе. Этот адаптер работает как метод DOM Level 3 lookupNamespaceURI у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узлов в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml."
type: docs
weight: 20
url: /ru/net/aspose.svg.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Адаптирует любой DOM‑узел для разрешения пространств имён, чтобы XPath‑выражение можно было легко вычислять относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, который будет использоваться в качестве контекста для разрешения пространств имён. |

### Возвращаемое значение

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### См. также

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.svg.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Svg.Dom.XPath](../../../aspose.svg.dom.xpath/)
* assembly [Aspose.SVG](../../../)
