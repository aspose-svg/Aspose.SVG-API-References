---
title: "فئة SVGException"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.SVGException. يتم رفع هذا الاستثناء عندما يكون من المستحيل تنفيذ عملية SVG محددة"
type: docs
weight: 5300
url: /ar/net/aspose.svg/svgexception/
---
## SVGException class

يتم رفع هذا الاستثناء عندما يكون تنفيذ عملية SVG معينة مستحيلًا.

```csharp
public class SVGException : PlatformException
```

## البناؤات

| الاسم | الوصف |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | يُنشئ مثيلًا جديدًا من الفئة `SVGException`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | رمز يحدد السبب الذي لم تُنفّذ العملية المطلوبة. ستكون قيمة هذا العضو واحدة من الثوابت في مجموعة رموز SVGException. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | يُرفع عندما يتم تمرير قيمة غير صالحة إلى عملية أو تعيينها إلى سمة. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | يُرفع عندما يُجرى محاولة لعكس مصفوفة غير قابلة للعكس. |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | يُرفع عندما يُمرّر كائن من نوع غير صحيح إلى عملية. |

### انظر أيضًا

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
