---
title: "SVGListBase-1.Initialize"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGListBase Initialize 方法。清除列表中所有现有的当前项，并重新初始化列表以容纳参数指定的单个项。"
type: docs
weight: 80
url: /zh/net/aspose.svg.collections/svglistbase-1/initialize/
---
## SVGListBase<T>.Initialize method

清除列表中所有现有的当前项，并重新初始化列表以容纳参数指定的单个项。

```csharp
public T Initialize(T newItem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 该项应成为列表中唯一的成员。 |

### 返回值

正在插入列表的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出此错误。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
