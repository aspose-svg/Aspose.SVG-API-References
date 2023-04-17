---
title: Class NodeList
second_title: Aspose.SVG for .NET API 参考
description: Aspose.Svg.Collections.NodeList 班级. NodeList 提供了节点有序集合的抽象但没有定义或约束该集合的实现方式
type: docs
weight: 40
url: /zh/net/aspose.svg.collections/nodelist/
---
## NodeList class

NodeList 提供了节点有序集合的抽象，但没有定义或约束该集合的实现方式。

```csharp
public abstract class NodeList : DOMObject, IEnumerable<Node>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/nodelist/item/) { get; } | 方法返回集合中的第 indexth 个项目。如果索引大于或等于列表中的节点数，则返回 null. |
| abstract [Length](../../aspose.svg.collections/nodelist/length/) { get; } | 列表中的节点数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/nodelist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| override [GetPlatformType](../../aspose.svg.collections/nodelist/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type . |

### 也可以看看

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Node](../../aspose.svg.dom/node/)
* 命名空间 [Aspose.Svg.Collections](../../aspose.svg.collections/)
* 部件 [Aspose.SVG](../../)


