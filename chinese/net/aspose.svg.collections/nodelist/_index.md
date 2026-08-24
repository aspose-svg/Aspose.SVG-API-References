---
title: "NodeList 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Collections.NodeList 类。NodeList 提供了有序节点集合的抽象，而不定义或限制该集合的实现方式。"
type: docs
weight: 2030
url: /zh/net/aspose.svg.collections/nodelist/
---
## NodeList class

NodeList 提供了有序节点集合的抽象，而不定义或限制该集合的实现方式。

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | 方法返回集合中第 index 项。如果 index 大于或等于列表中节点的数量，则返回 null。 |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | 该列表中节点的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
