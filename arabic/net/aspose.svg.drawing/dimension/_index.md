---
title: "فئة Dimension"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Drawing.Dimension. توفر الفئة الأساسية للأبعاد. المصطلح العام 'dimension' يشير إلى عدد مع وحدة مرفقة به ويتم الإشارة إليه بواسطة UnitType."
type: docs
weight: 3410
url: /ar/net/aspose.svg.drawing/dimension/
---
## Dimension class

توفر الفئة الأساسية للأبعاد. المصطلح العام 'dimension' يشير إلى عدد مع وحدة مرفقة به، ويتم الإشارة إليه بواسطة [`UnitType`](../unittype/).

```csharp
public abstract class Dimension : Numeric
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [UnitType](../../aspose.svg.drawing/unit/unittype/) { get; } | يحصل على نوع الوحدة لـ [`Unit`](../unit/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CompareTo](../../aspose.svg.drawing/numeric/compareto/)(*[Numeric](../numeric/)*) | يقارن النسخة الحالية مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كانت النسخة الحالية تسبق أو تتبع أو تقع في نفس الموضع في ترتيب الفرز مقارنةً بالكائن الآخر. |
| override [Equals](../../aspose.svg.drawing/unit/equals/)(*object*) | يحدد ما إذا كان الكائن المحدد مساويًا لهذه الحالة. |
| override [Equals](../../aspose.svg.drawing/numeric/equals/)(*[Unit](../unit/)*) | يحدد ما إذا كانت الـ [`Unit`](../unit/) المحددة مساوية لهذه النسخة. |
| override [GetHashCode](../../aspose.svg.drawing/numeric/gethashcode/)() | يرجع رمز تجزئة (hash code) لهذه الحالة. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)() | يحصل على قيمة الوحدة. |
| [GetValue](../../aspose.svg.drawing/numeric/getvalue/)(*[UnitType](../unittype/)*) | يحصل على القيمة محوّلة إلى الـ [`UnitType`](../unittype/) المحدد. |
| override [ToString](../../aspose.svg.drawing/dimension/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

### انظر أيضًا

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
