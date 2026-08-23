---
title: "OneOf-3.Match"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة OneOf Match. تُنفّذ إحدى الدوال المقدمة بناءً على النوع الأساسي للقيمة"
type: docs
weight: 20
url: /ar/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

ينفذ أحد الدوال المقدمة بناءً على النوع الأساسي للقيمة.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| معامل | الوصف |
| --- | --- |
| TResult | نوع الإرجاع للدوال. |
| func1 | الدالة التي تُنفّذ إذا كانت القيمة من النوع T1. |
| func2 | الدالة التي تُنفّذ إذا كانت القيمة من النوع T2. |
| func3 | الدالة التي يتم تنفيذها إذا كانت القيمة من النوع T3. |

### قيمة الإرجاع

نتيجة الدالة المُنفّذة.

### انظر أيضًا

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
