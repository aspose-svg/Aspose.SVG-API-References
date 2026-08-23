---
title: "واجهة ISVGAnimatedPathData"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData واجهة. تدعم واجهة SVGAnimatedPathData العناصر التي لديها سمة d التي تحتوي على بيانات مسار SVG وتدعم إمكانية تحريك تلك السمة"
type: docs
weight: 4550
url: /ar/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

واجهة SVGAnimatedPathData تدعم العناصر التي لديها سمة ‘d’ التي تحمل بيانات مسار SVG، وتدعم القدرة على تحريك تلك السمة.

```csharp
public interface ISVGAnimatedPathData
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | يوفر الوصول إلى المحتويات المتحركة الحالية لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. إذا كانت السمة أو الخاصية المعطاة قيد التحريك، فإنه يحتوي على القيمة المتحركة الحالية لتلك السمة أو الخاصية، وكلا من الكائن نفسه ومحتوياته للقراءة فقط. إذا لم تكن السمة أو الخاصية المعطاة قيد التحريك حاليًا، فإنه يحتوي على نفس القيمة مثل pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | يوفر الوصول إلى المحتويات الأساسية (أي الثابتة) لسمة ‘d’ في صيغة تتطابق واحدًا لواحد مع صياغة SVG. وبالتالي، إذا كانت سمة ‘d’ تحتوي على أمر \"moveto مطلق (M)\" وأمر \"arcto مطلق (A)\", فإن pathSegList سيحتوي على مدخلين: SVG_PATHSEG_MOVETO_ABS و SVG_PATHSEG_ARC_ABS. |

### انظر أيضًا

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
