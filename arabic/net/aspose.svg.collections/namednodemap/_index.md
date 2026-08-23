---
title: "فئة NamedNodeMap"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Collections.NamedNodeMap. تمثل مجموعات من السمات التي يمكن الوصول إليها بالاسم."
type: docs
weight: 2020
url: /ar/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

يمثل مجموعات من السمات التي يمكن الوصول إليها بالاسم.

```csharp
public class NamedNodeMap : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | يرجع العنصر رقم الفهرس في الخريطة. إذا كان الفهرس أكبر من أو يساوي عدد العقد في هذه الخريطة، فإنها تُرجع null. (مؤشرين) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | عدد العقد في هذه الخريطة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | يسترجع عقدة محددة بالاسم. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | يسترجع عقدة محددة بالاسم المحلي وURI مساحة الاسم. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | يزيل عقدة محددة بالاسم. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | يزيل عقدة محددة بالاسم المحلي وURI مساحة الاسم. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | يضيف عقدة باستخدام خاصية nodeName الخاصة بها. إذا كانت هناك عقدة بهذا الاسم موجودة بالفعل في هذه الخريطة، يتم استبدالها بالعقدة الجديدة. استبدال عقدة بنفسها لا يؤثر. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | يضيف عقدة باستخدام خاصيتي namespaceURI و localName. إذا كانت هناك عقدة بهذا الـ namespace URI وهذا الاسم المحلي موجودة بالفعل في هذه الخريطة، يتم استبدالها بالعقدة الجديدة. استبدال عقدة بنفسها لا يؤثر. |

### انظر أيضًا

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
