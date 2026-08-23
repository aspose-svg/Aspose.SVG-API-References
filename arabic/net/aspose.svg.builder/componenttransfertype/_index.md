---
title: "تعداد ComponentTransferType"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Builder.ComponentTransferType تعداد. يحدد نوع دالة نقل المكوّن التي تُطبق في بديل مرشح FeComponentTransfer في SVG."
type: docs
weight: 170
url: /ar/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

يحدد نوع دالة نقل المكوّن التي سيتم تطبيقها في بدائية الفلتر FeComponentTransfer في SVG.

```csharp
public enum ComponentTransferType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Identity | `0` | يمثل عدم وجود تغيير في الرسوم المدخلة. هذا هو النوع الافتراضي. |
| Table | `1` | يستخدم جدول بحث لتحديد الدالة داخل الفلتر. |
| Discrete | `2` | يستخدم مجموعة من القيم المتقطعة لتحديد الدالة في الفلتر. |
| Linear | `3` | يحدد تحويلًا خطيًا للمكوّن داخل الفلتر. |
| Gamma | `4` | يحدد تحويل تصحيح غاما في الفلتر. |

## ملاحظات

يتيح عنصر الفلتر FeComponentTransfer إمكانية التلاعب الفردي بمكونات اللون (RGB و alpha) لعناصر الرسومات باستخدام أنواع مختلفة من وظائف النقل. كل نوع يحدد طريقة حساب متميزة لتحويل مكونات اللون داخل الفلتر.

### انظر أيضًا

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
