---
title: "ResourceHandler.HandleResourceReference"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة ResourceHandler HandleResourceReference. هذه الطريقة مسؤولة عن معالجة مرجع المورد. في هذه الطريقة يمكنك تحديد الشكل الذي سيظهر به المرجع إلى المورد الجاري معالجته."
type: docs
weight: 20
url: /ar/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

هذه الطريقة مسؤولة عن معالجة مرجع المورد. في هذه الطريقة، يمكنك تحديد الشكل الذي سيظهر به المرجع إلى المورد الذي يتم معالجته.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resource | Resource | الـ[`Resource`](../../../aspose.svg.saving/resource/) الذي سيتم معالجته. |
| context | ResourceHandlingContext | سياق معالجة المورد. |

### قيمة الإرجاع

سلسلة نصية ستُكتب إلى المورد الأب وتمثل مرجعاً إلى المورد الذي يتم معالجته حالياً.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يُرفع إذا كان [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) `null` وكان [`Status`](../../../aspose.svg.saving/resource/status/) هو Saved. يجب تحديد [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) للمورد المحفوظ لأنه وإلا سيكون من المستحيل تحديد المرجع الصحيح في الموارد التي تشير إلى هذا المورد. |

### انظر أيضًا

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
