---
title: "واجهة ITraversal"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Dom.Traversal.ITraversal interface. تُستخدم Iterators للانتقال عبر مجموعة من العقد مثل مجموعة العقد في NodeList، وشجرة المستند الفرعية التي يتحكم فيها Node معين، أو نتائج استعلام أو أي مجموعة أخرى من العقد. يتم تحديد مجموعة العقد التي سيتم تكرارها بواسطة تنفيذ NodeIterator. يحدد DOM Level 2 تنفيذًا واحدًا لـ NodeIterator لت traversals بترتيب المستند لشجرة فرعية من المستند. يتم إنشاء مثيلات هذه الـ iterators عن طريق استدعاء DocumentTraversal .createNodeIterator"
type: docs
weight: 3260
url: /ar/net/aspose.svg.dom.traversal/itraversal/
---
## ITraversal interface

تُستخدم المكررات للانتقال عبر مجموعة من العقد، مثل مجموعة العقد في NodeList، الشجرة الفرعية للمستند التي تحكمها عقدة معينة، نتائج استعلام، أو أي مجموعة أخرى من العقد. تُحدَّد مجموعة العقد التي ستُكرر بواسطة تنفيذ NodeIterator. يحدد DOM المستوى 2 تنفيذًا واحدًا لـ NodeIterator لتصفح شجرة المستند بترتيب المستند. تُنشأ مثيلات هذه المكررات عن طريق استدعاء DocumentTraversal .createNodeIterator().

انظر أيضًا إلى [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Filter](../../aspose.svg.dom.traversal/itraversal/filter/) { get; } | NodeFilter المستخدم لتصفية العقد. |
| [Root](../../aspose.svg.dom.traversal/itraversal/root/) { get; } | العقدة الجذرية لـ NodeIterator، كما تم تحديدها عند إنشائها. |
| [WhatToShow](../../aspose.svg.dom.traversal/itraversal/whattoshow/) { get; } | تحدد هذه الخاصية أي أنواع العقد التي يتم تقديمها عبر الـ iterator. مجموعة الثوابت المتاحة معرفة في واجهة NodeFilter. العقد التي لا يقبلها whatToShow سيتم تخطيها، لكن قد تُؤخذ أبناؤها في الاعتبار. لاحظ أن هذا التخطي له أولوية على الفلتر، إذا كان موجودًا. |

### انظر أيضًا

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
