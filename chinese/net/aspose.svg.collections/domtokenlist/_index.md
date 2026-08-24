---
title: "DOMTokenList 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Collections.DOMTokenList 类。DOMTokenList 类表示一组以空格分隔的标记。它的索引从 0 开始，类似于 JavaScript 数组对象。DOMTokenList 始终区分大小写。"
type: docs
weight: 2000
url: /zh/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

DOMTokenList 类表示一组以空格分隔的标记。它的索引从 0 开始，类似于 JavaScript Array 对象。DOMTokenList 始终区分大小写。

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | 根据索引返回列表中的项，如果索引大于或等于列表长度，则返回 null。 |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | 返回一个 ulong，表示此列表中存储的标记数量。 |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | 获取或设置相应属性的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | 将指定的标记添加到列表中。 |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | 如果列表包含给定的标记，则返回 true，否则返回 false。 |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | 从列表中移除指定的标记。 |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | 用新标记替换已有的标记。如果第一个标记不存在，则不执行任何操作。 |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | 如果给定的标记在关联属性的支持标记中，则返回 true。 |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | 如果标记已存在于列表中则将其移除，否则将标记添加到列表中。 |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | 如果标记已存在于列表中则将其移除，否则将标记添加到列表中。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
