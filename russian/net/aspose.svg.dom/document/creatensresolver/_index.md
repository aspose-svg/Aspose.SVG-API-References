---
title: "Document.CreateNSResolver"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document CreateNSResolver. Приводит любой DOM‑узел к возможности разрешать пространства имён, чтобы выражение XPath можно было легко оценить относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 lookupNamespaceURI у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узлов в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml."
type: docs
weight: 910
url: /ru/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Адаптирует любой DOM‑узел для разрешения пространств имён, чтобы XPath‑выражение можно было легко вычислять относительно контекста узла, где оно появилось в документе. Этот адаптер работает как метод DOM Level 3 `lookupNamespaceURI` у узлов, разрешая namespaceURI из заданного префикса, используя текущую информацию, доступную в иерархии узла в момент вызова lookupNamespaceURI, а также корректно разрешая неявный префикс xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, который будет использоваться в качестве контекста для разрешения пространств имён. |

### Возвращаемое значение

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### См. также

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
