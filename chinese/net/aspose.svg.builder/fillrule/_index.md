---
title: "FillRule 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.FillRule 枚举。指定在 SVG 图形中确定形状内部或外部的规则。"
type: docs
weight: 270
url: /zh/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

指定在 SVG 图形中确定形状哪些部分在内部或外部的规则。

```csharp
public enum FillRule
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Nonzero | `0` | 非零环绕规则：通过从形状中的一点向任意方向射出一条射线并计数该射线穿过给定形状的路径段数量来确定该点的“内部性”。如果该数量为奇数，则点在内部；如果为偶数，则点在外部。 |
| Evenodd | `1` | 奇偶环绕规则：通过从形状中的一点向任意方向射出一条射线并计数该射线穿过给定形状的路径段数量来确定该点的“内部性”。如果该数量为偶数，则点在外部；如果为奇数，则点在内部。 |

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
