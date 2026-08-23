---
title: "فئة TypeInfo"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.TypeInfo. تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr المحددة في المخططات المرتبطة بالمستند"
type: docs
weight: 3280
url: /ar/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr، محددًا في المخططات المرتبطة بالمستند.

```csharp
public class TypeInfo : DOMObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | اسم النوع المُعلن للعنصر أو السمة المرتبطة، أو null إذا كان غير معروف. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | يحصل على مساحة اسم النوع. مساحة اسم النوع المُعلن للعنصر أو السمة المرتبطة أو null إذا لم يكن للعنصر إعلان أو إذا لم تتوفر معلومات عن مساحة الاسم. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | تعيد هذه الطريقة ما إذا كان هناك اشتقاق بين تعريف النوع المرجعي، أي TypeInfo التي تُستدعى عليها الطريقة، وتعريف النوع الآخر، أي الذي يُمرَّر كمعامل. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | إذا كان مخطط المستند هو مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاشتقاق عن طريق التوسيع. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | إذا كان مخطط المستند هو مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل القائمة. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | إذا كان مخطط المستند هو مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاشتقاق عن طريق التقييد إذا كانت الأنواع المركبة متضمنة، أو تقييدًا إذا كانت الأنواع البسيطة متضمنة. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | إذا كان مخطط المستند هو مخطط XML [XML Schema Part 1]، فإن هذا الثابت يمثل الاتحاد إذا كانت الأنواع البسيطة متضمنة. |

### انظر أيضًا

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
