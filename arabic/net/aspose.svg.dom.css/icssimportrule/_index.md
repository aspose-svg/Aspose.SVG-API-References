---
title: "واجهة ICSSImportRule"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Css.ICSSImportRule واجهة. تمثل واجهة CSSImportRule قاعدة استيراد داخل ورقة أنماط CSS. تُستخدم قاعدة الاستيراد لاستيراد قواعد الأنماط من أوراق أنماط أخرى."
type: docs
weight: 2560
url: /ar/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

تمثل واجهة CSSImportRule قاعدة @import داخل ورقة أنماط CSS. تُستخدم قاعدة @import لاستيراد قواعد الأنماط من أوراق أنماط أخرى.

```csharp
public interface ICSSImportRule : ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | موقع ورقة الأنماط التي سيتم استيرادها. لن تحتوي السمة على المحدد "url(...)" حول الـ URI. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | قائمة بأنواع الوسائط التي يمكن استخدام ورقة الأنماط هذه معها. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | ورقة الأنماط المشار إليها بهذه القاعدة، إذا تم تحميلها. تكون قيمة هذه الخاصية null إذا لم يتم تحميل ورقة الأنماط بعد أو إذا لن يتم تحميلها (مثلاً إذا كانت ورقة الأنماط لنوع وسائط غير مدعوم من قبل وكيل المستخدم). |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
