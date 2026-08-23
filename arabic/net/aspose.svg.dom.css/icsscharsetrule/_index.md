---
title: "واجهة ICSSCharsetRule"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule interface. تمثل واجهة CSSCharsetRule قاعدة مجموعة أحرف في ورقة أنماط CSS. لا تؤثر قيمة خاصية الترميز (encoding) على ترميز بيانات النص في كائنات DOM؛ هذا الترميز دائمًا UTF-16. بعد تحميل ورقة الأنماط تكون قيمة خاصية الترميز هي القيمة الموجودة في قاعدة مجموعة الأحرف. إذا لم يكن هناك مجموعة أحرف في المستند الأصلي فلن يتم إنشاء CSSCharsetRule. قد تُستخدم قيمة خاصية الترميز أيضًا كإشارة للترميز المستخدم عند تسلسل ورقة الأنماط."
type: docs
weight: 2530
url: /ar/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

تمثل واجهة CSSCharsetRule قاعدة @charset في ورقة أنماط CSS. لا يؤثر قيمة سمة الترميز على ترميز بيانات النص في كائنات DOM؛ هذا الترميز دائمًا UTF-16. بعد تحميل ورقة الأنماط، تكون قيمة سمة الترميز هي القيمة الموجودة في قاعدة @charset. إذا لم توجد قاعدة @charset في المستند الأصلي، فلن يتم إنشاء CSSCharsetRule. قد تُستخدم قيمة سمة الترميز أيضًا كإشارة للترميز المستخدم عند تسلسل ورقة الأنماط.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | معلومات الترميز المستخدمة في قاعدة @charset هذه. |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
