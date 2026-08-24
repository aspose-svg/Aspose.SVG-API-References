---
title: "NamedNodeMap 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Collections.NamedNodeMap 类。表示可以通过名称访问的属性集合。"
type: docs
weight: 2020
url: /zh/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

表示可通过名称访问的属性集合。

```csharp
public class NamedNodeMap : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | 返回映射中第 index 项。如果 index 大于或等于此映射中节点的数量，则返回 null。（2 个索引器） |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | 此映射中节点的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | 检索由名称指定的节点。 |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | 检索由本地名称和命名空间 URI 指定的节点。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | 移除由名称指定的节点。 |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | 移除由本地名称和命名空间 URI 指定的节点。 |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | 使用其 nodeName 属性添加节点。如果映射中已存在同名节点，则会被新节点替换。用自身替换节点没有任何效果。 |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | 使用其 namespaceURI 和 localName 添加节点。如果映射中已存在具有相同命名空间 URI 和本地名称的节点，则会被新节点替换。用自身替换节点没有任何效果。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
