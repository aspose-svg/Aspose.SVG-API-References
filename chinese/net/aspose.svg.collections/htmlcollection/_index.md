---
title: "HTMLCollection 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Collections.HTMLCollection 类。HTMLCollection 表示 Element 的通用集合。"
type: docs
weight: 2010
url: /zh/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

该 `HTMLCollection` 表示一个通用的 [`Element`](../../aspose.svg.dom/element/) 集合。

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | 返回集合中第 index 项。如果 index 大于或等于列表中节点的数量，则返回 null。 |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | 该列表中节点的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | 获取枚举器。 |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | 返回集合中匹配指定名称的项。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
