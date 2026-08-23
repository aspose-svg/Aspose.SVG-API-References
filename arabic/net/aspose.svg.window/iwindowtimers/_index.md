---
title: "IWindowTimers واجهة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Window.IWindowTimers واجهة. تسمح للمؤلفين بجدولة الاستدعاءات القائمة على المؤقت"
type: docs
weight: 5940
url: /ar/net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

يسمح للمؤلفين بجدولة ردود نداء تعتمد على المؤقت.

```csharp
public interface IWindowTimers
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(*int*) | يلغي المهلة المحددة بـ setInterval() والمُعرف بواسطة handle |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(*int*) | يلغي المهلة المحددة بـ setTimeout() والمُعرف بواسطة handle. |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(*object, int, params object[]*) | يُجدول مهلة لتشغيل المعالج كل timeout مللي ثانية. يتم تمرير أي وسائط مباشرة إلى المعالج. |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(*object, int, params object[]*) | يُجدول مهلة لتشغيل المعالج بعد timeout مللي ثانية. يتم تمرير أي وسائط مباشرة إلى المعالج. |

### انظر أيضًا

* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
