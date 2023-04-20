---
title: SVGListBase1.ReplaceItem
second_title: Aspose.SVG for .NET API 参考
description: SVGListBase 方法. 用新项目替换列表中的现有项目
type: docs
weight: 110
url: /zh/net/aspose.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

用新项目替换列表中的现有项目。

```csharp
public T ReplaceItem(T newItem, ulong index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入到列表中的项目。 |
| index | UInt64 | 要替换的项目的索引。第一项是数字 0。 |

### 返回值

插入的项目。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). 无法修改列表时引发。 |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码[`INDEX_SIZE_ERR`](../../../aspose.svg.dom/domexception/index_size_err/). 如果索引号大于或等于 numberOfItems 则引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../)
* 命名空间 [Aspose.Svg.Collections](../../svglistbase-1/)
* 部件 [Aspose.SVG](../../../)


