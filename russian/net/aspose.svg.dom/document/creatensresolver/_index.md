---
title: CreateNSResolver
second_title: Справочник по Aspose.SVG для .NET API
description: Адаптирует любой узел DOM для разрешения пространств имен чтобы выражение XPath можно было легко вычислить относительно контекста узла в котором оно появилось в документе. Этот адаптер работает аналогично методу DOM уровня 3 lookupNamespaceURI на узлах при разрешении namespaceURI из заданного префикса используя текущую информацию доступную в узлах. иерархии во время вызова lookupNamespaceURI что также правильно разрешает неявный префикс xml.
type: docs
weight: 910
url: /ru/net/aspose.svg.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Адаптирует любой узел DOM для разрешения пространств имен, чтобы выражение XPath можно было легко вычислить относительно контекста узла, в котором оно появилось в документе. Этот адаптер работает аналогично методу DOM уровня 3` lookupNamespaceURI` на узлах при разрешении namespaceURI из заданного префикса, используя текущую информацию, доступную в узлах. иерархии во время вызова lookupNamespaceURI, что также правильно разрешает неявный префикс xml.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| nodeResolver | Node | Узел, который будет использоваться в качестве контекста для разрешения пространства имен. |

### Возвращаемое значение

[`IXPathNSResolver`](../../../aspose.svg.dom.xpath/ixpathnsresolver), который разрешает пространства имен относительно определений в области действия для указанного узла.

### Смотрите также

* interface [IXPathNSResolver](../../../aspose.svg.dom.xpath/ixpathnsresolver)
* class [Node](../../node)
* class [Document](../../document)
* пространство имен [Aspose.Svg.Dom](../../document)
* сборка [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->