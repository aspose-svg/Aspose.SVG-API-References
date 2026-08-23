---
title: "واجهة IStyleSheet"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Css.IStyleSheet. واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. تمثل ورقة نمط واحدة مرتبطة بمستند منظم"
type: docs
weight: 2740
url: /ar/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. تمثل ورقة نمط واحدة مرتبطة بمستند منظم.

```csharp
public interface IStyleSheet
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false إذا تم تطبيق ورقة النمط على المستند. true إذا لم يتم ذلك. قد يؤدي تعديل هذه الخاصية إلى حل جديد للنمط للمستند. تُطبق ورقة النمط فقط إذا كان تعريف الوسيط المناسب موجودًا وكانت خاصية disabled تساوي false. لذا، إذا لم يكن الوسيط مناسبًا للوكيل المستخدم الحالي، يتم تجاهل خاصية disabled. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | إذا كانت ورقة الأنماط ورقة أنماط مرتبطة، فإن قيمة سمةها هي موقعها. بالنسبة لأوراق الأنماط المضمنة، تكون قيمة هذه السمة فارغة (null). |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | وسائط الوجهة المقصودة لمعلومات الأنماط. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | العقدة التي تربط ورقة الأنماط هذه بالمستند. بالنسبة إلى HTML، قد تكون العنصر LINK أو STYLE المقابل. بالنسبة إلى XML، قد تكون تعليمات المعالجة للربط. بالنسبة لأوراق الأنماط التي تُدرج بواسطة أوراق أنماط أخرى، تكون قيمة هذه السمة فارغة (null). |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | بالنسبة للغات أوراق الأنماط التي تدعم مفهوم تضمين أوراق الأنماط، تمثل هذه السمة ورقة الأنماط المضمنة، إذا وجدت. إذا كانت ورقة الأنماط ورقة أنماط من المستوى الأعلى، أو إذا كانت لغة ورقة الأنماط لا تدعم التضمين، تكون قيمة هذه السمة فارغة (null). |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | العنوان الاستشاري. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | هذا يحدد لغة ورقة الأنماط لهذه الورقة. تُحدد لغة ورقة الأنماط كنوع محتوى (مثال: "text/css"). |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
