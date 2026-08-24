---
title: "OneOf-3.Match"
second_title: "Aspose.SVG for .NET API 参考"
description: "OneOf Match 方法。根据值的底层类型执行提供的函数之一"
type: docs
weight: 20
url: /zh/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

根据值的底层类型执行提供的函数之一。

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| 参数 | 描述 |
| --- | --- |
| TResult | 函数的返回类型。 |
| func1 | 如果值的类型为 T1 时要执行的函数。 |
| func2 | 如果值的类型为 T2 时要执行的函数。 |
| func3 | 如果值的类型为 T3 时要执行的函数。 |

### 返回值

已执行函数的结果。

### 另请参阅

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
