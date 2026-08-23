---
title: "واجهة ICSSRule"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Dom.Css.ICSSRule. واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. تشمل ذلك مجموعات القواعد والقواعد الخاصة (at-rules). من المتوقع أن تحافظ أي تنفيذ على جميع القواعد المحددة في ورقة أنماط CSS حتى إذا لم يتم التعرف على القاعدة من قبل المحلل. القواعد غير المعروفة يتم تمثيلها باستخدام واجهة ICSSUnknownRule."
type: docs
weight: 2620
url: /ar/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. وهذا يشمل مجموعات القواعد وat-rules. من المتوقع أن تحتفظ أي تنفيذ بجميع القواعد المحددة في ورقة أنماط CSS، حتى إذا لم يتعرف المحلل على القاعدة. القواعد غير المعروفة يتم تمثيلها باستخدام واجهة ICSSUnknownRule.

```csharp
public interface ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | التمثيل النصي القابل للتحليل للقاعدة. يعكس هذا الحالة الحالية للقاعدة وليس قيمتها الأولية. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | إذا كانت هذه القاعدة موجودة داخل قاعدة أخرى (مثال: قاعدة نمط داخل كتلة @media)، فهذه هي القاعدة الحاوية. إذا لم تكن هذه القاعدة متداخلة داخل أي قواعد أخرى، فإنها تُعيد null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | ورقة الأنماط التي تحتوي على هذه القاعدة. |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | نوع القاعدة، كما هو معرف أعلاه. يُتوقع أن تُستخدم طرق التحويل الخاصة بالربط لتحويل كائن من واجهة CSSRule إلى الواجهة المشتقة المحددة بالنوع. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
