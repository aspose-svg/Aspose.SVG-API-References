---
title: "واجهة ICSSRuleList"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الواجهة Aspose.Svg.Dom.Css.ICSSRuleList. توفر واجهة CSSRuleList تجريدًا لمجموعة مرتبة من قواعد CSS."
type: docs
weight: 2630
url: /ar/net/aspose.svg.dom.css/icssrulelist/
---
## ICSSRuleList interface

واجهة CSSRuleList توفر تجريد مجموعة مرتبة من قواعد CSS.

```csharp
public interface ICSSRuleList : IEnumerable<ICSSRule>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.svg.dom.css/icssrulelist/item/) { get; } | يُستخدم لاسترجاع قاعدة CSS عبر الطريقة item() (http://www.w3.org/TR/DOM-Level-2-Style/css.html#CSS-CSSRuleList). يمثل الترتيب في هذه المجموعة ترتيب القواعد في ورقة أنماط CSS. إذا كان الفهرس أكبر من أو يساوي عدد القواعد في القائمة، تُعيد هذه القيمة فارغة (null). |
| [Length](../../aspose.svg.dom.css/icssrulelist/length/) { get; } | عدد قواعد CSSRules في القائمة. نطاق مؤشرات القواعد الفرعية الصالحة هو من 0 إلى length-1 شاملًا. |

### انظر أيضًا

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
