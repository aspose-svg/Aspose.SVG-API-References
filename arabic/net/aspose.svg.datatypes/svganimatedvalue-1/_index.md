---
title: "SVGAnimatedValueT فئة"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "Aspose.Svg.DataTypes.SVGAnimatedValue1T فئة. تُستخدم للسمات من الأنواع التي يمكن تحريكها"
type: docs
weight: 2200
url: /ar/net/aspose.svg.datatypes/svganimatedvalue-1/
---
## SVGAnimatedValue<T> class

تُستخدم لسمات من الأنواع التي يمكن تحريكها.

```csharp
public abstract class SVGAnimatedValue<T> : SVGValueType
```

| معامل | الوصف |
| --- | --- |
| T | كائن قيمة SVG. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AnimVal](../../aspose.svg.datatypes/svganimatedvalue-1/animval/) { get; } | إذا كانت السمة أو الخاصية المحددة قيد التحريك، فإنها تحتوي على القيمة المتحركة الحالية للسمة أو الخاصية. إذا لم تكن السمة أو الخاصية المحددة قيد التحريك حالياً، فإنها تحتوي على نفس القيمة كما في baseVal. |
| [BaseVal](../../aspose.svg.datatypes/svganimatedvalue-1/baseval/) { get; set; } | القيمة الأساسية للسمة المحددة قبل تطبيق أي تحريكات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | يطلق الموارد غير المُدارة و- اختياريًا - المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |

### انظر أيضًا

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
