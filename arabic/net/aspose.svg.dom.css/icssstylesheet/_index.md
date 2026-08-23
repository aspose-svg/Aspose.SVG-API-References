---
title: "واجهة ICSSStyleSheet"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet interface. واجهة CSSStyleSheet هي واجهة ملموسة تُستخدم لتمثيل ورقة أنماط CSS أي ورقة أنماط يكون نوع محتواها text/css"
type: docs
weight: 2660
url: /ar/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

واجهة CSSStyleSheet هي واجهة ملموسة تُستخدم لتمثيل ورقة أنماط CSS، أي ورقة أنماط يكون نوع محتواها "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | قائمة بجميع قواعد CSS الموجودة داخل ورقة الأنماط. تشمل هذه القائمة كل من مجموعات القواعد والقواعد الخاصة (at-rules). |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | إذا كانت ورقة الأنماط هذه ناتجة عن قاعدة @import، فستحتوي خاصية ownerRule على CSSImportRule. في هذه الحالة، ستكون خاصية ownerNode في واجهة StyleSheet ذات قيمة null. إذا كانت ورقة الأنماط ناتجة عن عنصر أو تعليمات معالجة، فستكون خاصية ownerRule ذات قيمة null وستحتوي خاصية ownerNode على Node. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | يُستخدم لحذف قاعدة من ورقة الأنماط. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | يُستخدم لإدراج قاعدة جديدة في ورقة الأنماط. تصبح القاعدة الجديدة الآن جزءًا من التسلسل الهرمي. |

### انظر أيضًا

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
