---
title: "واجهة ICSSStyleDeclaration"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Css.ICSSStyleDeclaration. تمثل واجهة CSSStyleDeclaration كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط الحالية في كتلة أو لتعيين خصائص النمط صراحةً داخل الكتلة."
type: docs
weight: 2640
url: /ar/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

واجهة CSSStyleDeclaration تمثل كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط الحالية في الكتلة أو لتعيين خصائص النمط صراحةً داخل الكتلة.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | التمثيل النصي القابل للتحليل لكتلة التصريح (باستثناء الأقواس المعقوفة المحيطة). ضبط هذه الخاصية سيؤدي إلى تحليل القيمة الجديدة وإعادة ضبط جميع الخصائص في كتلة التصريح بما في ذلك إزالة أو إضافة الخصائص. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | يُستخدم لاسترجاع الخصائص التي تم تعيينها صراحةً في هذه كتلة التصريح. ترتيب الخصائص المسترجعة باستخدام هذه الطريقة لا يجب أن يكون هو نفس ترتيب تعيينها. يمكن استخدام هذه الطريقة للتكرار على جميع الخصائص في هذه كتلة التصريح. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | عدد الخصائص التي تم تعيينها صراحةً في هذه كتلة التصريح. نطاق الفهارس الصالحة هو من 0 إلى الطول-1 شاملًا. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | قاعدة CSS التي تحتوي على هذه كتلة التصريح أو null إذا لم يتم إرفاق هذا CSSStyleDeclaration بقاعدة CSS. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | يُستخدم لاسترجاع تمثيل الكائن لقيمة خاصية CSS إذا تم تعيينها صراحةً داخل هذه كتلة التصريح. تُرجع هذه الطريقة null إذا كانت الخاصية خاصية مختصرة. لا يمكن الوصول إلى قيم الخصائص المختصرة وتعديلها إلا كسلاسل نصية، باستخدام طريقتي getPropertyValue و setProperty. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | يُستخدم لاسترجاع أولوية خاصية CSS (مثل محدد "important") إذا تم تعيين الخاصية صراحةً في هذه كتلة التصريح. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | يُستخدم لاسترجاع قيمة خاصية CSS إذا تم تعيينها صراحةً داخل هذه كتلة التصريح. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | يُستخدم لإزالة خاصية CSS إذا تم تعيينها صراحةً داخل هذه كتلة التصريح. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | يُستخدم لتعيين قيمة خاصية بأولوية افتراضية داخل هذه كتلة التصريح. الأولوية الافتراضية ليست "important" أي String.Empty. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | يُستخدم لتعيين قيمة خاصية وأولوية داخل هذه كتلة التصريح. |

### انظر أيضًا

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
