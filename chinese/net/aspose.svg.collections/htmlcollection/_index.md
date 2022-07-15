---
title: HTMLCollection
second_title: Aspose.SVG for .NET API 参考
description: HTMLCollection./htmlcollection表示Element../aspose.svg.dom/element的通用集合
type: docs
weight: 20
url: /zh/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

[`HTMLCollection`](../htmlcollection)表示[`Element`](../../aspose.svg.dom/element)的通用集合。

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item) { get; } | 返回集合中的第 index 个项目。如果 index 大于或等于列表中的节点数，则返回 null。 |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length) { get; } | 列表中的节点数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator)() | 获取枚举数。 |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype)() | 此方法用于检索 ECMAScript 对象Type。 |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem)(string) | 返回集合中匹配指定名称的项目。 |

### 也可以看看

* class [DOMObject](../../aspose.svg.dom/domobject)
* class [Element](../../aspose.svg.dom/element)
* 命名空间 [Aspose.Svg.Collections](../../aspose.svg.collections)
* 部件 [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->