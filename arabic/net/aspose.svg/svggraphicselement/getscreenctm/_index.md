---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGGraphicsElement GetScreenCTM. تُرجِع مصفوفة التحويل من وحدات المستخدم الحالية أي بعد تطبيق سمة transform إذا وجدت إلى ملاحظة وكيل المستخدم الأب للبكسل. بالنسبة لأجهزة العرض، تمثل عادةً بكسل شاشة مادي. بالنسبة للأجهزة أو البيئات الأخرى التي لا تُعرف فيها أحجام البكسل الفعلية، يمكن استخدام خوارزمية مشابهة لتعريف بكسل CSS2 بدلاً من ذلك. لاحظ أن القيمة null تُرجَع إذا لم يكن هذا العنصر مرتبطًا بشجرة المستند. كان من الممكن تسمية هذه الطريقة بشكل أكثر دقة كـ getClientCTM لكن تم الإبقاء على الاسم getScreenCTM لأسباب تاريخية."
type: docs
weight: 90
url: /ar/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

يرجع مصفوفة التحويل من وحدات المستخدم الحالية (أي بعد تطبيق سمة ‘transform’، إن وجدت) إلى ملاحظة الوكيل الأب للمستخدم للـ "pixel". بالنسبة لأجهزة العرض، يمثل ذلك عادةً بكسل الشاشة الفعلي. بالنسبة للأجهزة أو البيئات الأخرى التي لا تُعرف فيها أحجام البكسل الفعلية، يمكن استخدام خوارزمية مشابهة لتعريف CSS2 للـ "pixel". لاحظ أن null يُعاد إذا لم يكن هذا العنصر مرتبطًا بشجرة المستند. كان من الممكن تسمية هذه الطريقة بشكل أكثر دقة getClientCTM، لكن اسم getScreenCTM يُحافظ عليه لأسباب تاريخية.

```csharp
public SVGMatrix GetScreenCTM()
```

### قيمة الإرجاع

كائن SVGMatrix يحدد مصفوفة التحويل المعطاة.

### انظر أيضًا

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
