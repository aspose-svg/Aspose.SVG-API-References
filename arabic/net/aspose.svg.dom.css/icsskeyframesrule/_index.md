---
title: "واجهة ICSSKeyframesRule"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule واجهة. تمثل واجهة CSSKeyframesRule مجموعة كاملة من الإطارات المفتاحية لتصميم واحد."
type: docs
weight: 2580
url: /ar/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

تمثل واجهة CSSKeyframesRule مجموعة كاملة من إطارات المفاتيح (keyframes) لتصميم واحد.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | هذه الخاصية توفر الوصول إلى الإطارات المفتاحية في القائمة. |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | هذه الخاصية هي اسم الإطارات المفتاحية، تُستخدم بواسطة خاصية ‘animation‑name’. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | طريقة appendRule تُضيف CSSKeyframeRule الممررة إلى القائمة عند المفتاح الممرر. |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | طريقة deleteRule تحذف CSSKeyframeRule بالمفتاح الممرر. إذا لم توجد قاعدة بهذا المفتاح، لا تفعل الطريقة شيئًا. |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | طريقة findRule تُعيد القاعدة التي مفتاحها يطابق المفتاح الممرر. إذا لم توجد مثل هذه القاعدة، تُعاد قيمة فارغة (null). |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
