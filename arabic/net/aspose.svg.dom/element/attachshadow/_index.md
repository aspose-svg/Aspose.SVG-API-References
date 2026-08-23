---
title: "Element.AttachShadow"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Element AttachShadow. تنشئ جذر الظل وتربطه بالعنصر الحالي"
type: docs
weight: 220
url: /ar/net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

ينشئ shadow root ويُرفقه بالعنصر الحالي.

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mode | ShadowRootMode | الوضع الذي سيتم إنشاء جذر الظل فيه. |

### قيمة الإرجاع

تم الإنشاء [`ShadowRoot`](../../shadowroot/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| خطأ | NotSupportedError: العنصر لا يدعم شجرة الظل. |
| خطأ | InvalidStateError: العنصر يحتوي بالفعل على شجرة ظل. |

### انظر أيضًا

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
