---
title: "ComponentTransferType 枚举"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Builder.ComponentTransferType 枚举。指定在 SVG 的 FeComponentTransfer 过滤原语中应用的组件传输函数类型。"
type: docs
weight: 170
url: /zh/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

指定在 SVG 的 FeComponentTransfer 滤镜原语中应用的组件传输函数类型。

```csharp
public enum ComponentTransferType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Identity | `0` | 表示输入图形没有变化。这是默认类型。 |
| Table | `1` | 使用查找表在过滤器中定义函数。 |
| Discrete | `2` | 使用一组离散值在过滤器中定义函数。 |
| Linear | `3` | 定义过滤器中组件的线性变换。 |
| Gamma | `4` | 在过滤器中定义伽马校正变换。 |

## 备注

FeComponentTransfer 过滤器原语允许使用不同类型的传输函数对图形元素的颜色分量（RGB 和 alpha）进行单独操作。每种类型定义了在过滤器内进行颜色分量转换的不同计算方法。

### 另请参阅

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
