---
title: "TypeInfo.IsDerivedFrom"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة TypeInfo IsDerivedFrom. تُعيد هذه الطريقة ما إذا كان هناك اشتقاق بين تعريف النوع المرجعي أي TypeInfo الذي تُستدعى عليه الطريقة وتعريف النوع الآخر أي الذي يُمرَّر كمعامل"
type: docs
weight: 30
url: /ar/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

تعيد هذه الطريقة ما إذا كان هناك اشتقاق بين تعريف النوع المرجعي، أي TypeInfo التي تُستدعى عليها الطريقة، وتعريف النوع الآخر، أي الذي يُمرَّر كمعامل.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| typeNamespaceArg | String | مساحة اسم تعريف النوع الآخر |
| typeNameArg | String | اسم تعريف النوع الآخر. |
| derivationMethod | UInt64 | نوع الاشتقاق والشروط المطبقة بين نوعين، كما هو موضح في قائمة الثوابت المقدمة في هذه الواجهة. |

### قيمة الإرجاع

إذا كان مخطط المستند هو DTD أو لا يوجد مخطط مرتبط بالمستند، فإن هذه الطريقة ستعيد دائمًا false. إذا كان مخطط المستند هو مخطط XML، فإن الطريقة ستعيد true إذا كان تعريف نوع المرجع مشتقًا من تعريف النوع الآخر وفقًا لمعلمة الاشتقاق. إذا كانت قيمة المعلمة 0 (لم يتم تعيين أي بت إلى 1 لمعلمة derivationMethod)، فإن الطريقة ستعيد true إذا كان يمكن الوصول إلى تعريف النوع الآخر عن طريق تكرار أي تركيبة من {base type definition}، {item type definition}، أو {member type definitions} من تعريف نوع المرجع.

### انظر أيضًا

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
