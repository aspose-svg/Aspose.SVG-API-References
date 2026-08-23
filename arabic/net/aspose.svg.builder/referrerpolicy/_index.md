---
title: "تعداد ReferrerPolicy"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "تعداد Aspose.Svg.Builder.ReferrerPolicy. يحدد سياسة المرجع التي سيتم استخدامها عند جلب الموارد"
type: docs
weight: 1020
url: /ar/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

يحدد سياسة المرجع التي تُستخدم عند جلب الموارد.

```csharp
public enum ReferrerPolicy
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | `0` | لم يتم تعيين سياسة مرجع. |
| NoReferrer | `1` | لن يتم إرسال رأس Referer. |
| NoReferrerWhenDowngrade | `2` | لن يتم إرسال رأس Referer إلى الأصول ذات الأمان الأقل (HTTPS → HTTP). |
| SameOrigin | `3` | سيتم إرسال رأس Referer لطلبات نفس الأصل فقط. |
| Origin | `4` | سيتم إرسال أصل المستند فقط كقيمة لرأس Referer. |
| StrictOrigin | `5` | سيتم إرسال أصل المستند فقط كقيمة لرأس Referer في السياقات الآمنة. |
| OriginWhenCrossOrigin | `6` | سيتم إرسال عنوان URL الكامل كقيمة لرأس Referer لطلبات نفس الأصل، ولكن سيتم إرسال الأصل فقط لطلبات عبر الأصل. |
| StrictOriginWhenCrossOrigin | `7` | سيتم إرسال أصل المستند فقط كقيمة لرأس Referer لطلبات نفس الأصل، ولكن لن يتم إرسال أي رأس لطلبات عبر الأصل في السياقات غير الآمنة. |
| UnsafeUrl | `8` | سيتم دائمًا إرسال عنوان URL الكامل، بما في ذلك المسار وسلسلة الاستعلام، كقيمة لرأس Referer. |

### انظر أيضًا

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
