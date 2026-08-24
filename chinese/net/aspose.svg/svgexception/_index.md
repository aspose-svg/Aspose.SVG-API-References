---
title: "SVGException 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.SVGException 类。当特定 SVG 操作无法执行时会抛出此异常"
type: docs
weight: 5300
url: /zh/net/aspose.svg/svgexception/
---
## SVGException class

当特定的 SVG 操作无法执行时，会抛出此异常。

```csharp
public class SVGException : PlatformException
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | 初始化 `SVGException` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | 标识请求的操作无法执行的原因的代码。此成员的值将是 SVGException 代码组中的常量之一。 |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | 当向操作传递无效值或为属性赋值时抛出。 |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | 当尝试求逆一个不可逆的矩阵时抛出。 |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | 当向操作传递错误类型的对象时抛出。 |

### 另请参阅

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
