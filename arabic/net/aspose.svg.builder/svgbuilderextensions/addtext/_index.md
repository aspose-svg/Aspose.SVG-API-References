---
title: "SVGBuilderExtensions.AddText"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة SVGBuilderExtensions AddText. تُضيف تكوين عنصر نص إلى المُنشئ."
type: docs
weight: 530
url: /ar/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

يضيف تكوين عنصر 'text' إلى المُنشئ.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع مُنشئ عنصر SVG. |
| builder | كائن المُنشئ. |
| تكوين | إجراء التكوين لعنصر 'text'. |

### قيمة الإرجاع

كائن المُنشئ للتسلسل.

### انظر أيضًا

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

يضيف عنصر 'text' بمحتوى وسمات محددة إلى مُنشئ SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| معامل | الوصف |
| --- | --- |
| TBuilder | نوع منشئ عنصر SVG، مما يسمح بالسلسلة. |
| builder | مثيل المنشئ الذي سيُضاف إليه عنصر 'text'. |
| content | محتوى النص الذي سيُعرض داخل عنصر 'text'. |
| x | الإحداثي x لعنصر النص. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| y | الإحداثي y لعنصر النص. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| fontSize | حجم الخط للنص. يمكن أن يكون قيمة مزدوجة أو زوجًا من مزدوج وLengthType. |
| fontStyle | نمط الخط للنص (مثال: عادي، مائل، مائل مائل). |
| fontFamily | عائلة الخط للنص (مثال: Arial, Verdana). |
| fontWeight | الوزن (السُمك) للخط (مثال: normal, bold). |
| fill | لون التعبئة أو نمط الرسم للنص. يمكن أن يكون قيمة من نوع Color أو Paint enum أو معرف خادم الرسم. |
| stroke | لون الحد أو نمط الرسم للنص. يمكن أن يكون قيمة من نوع Color أو Paint enum أو معرف خادم الرسم. |
| معرّف | المعرّف الفريد لعنصر النص. |
| extend | إجراء اختياري لتكوين إضافي لمنشئ عنصر النص. |

### قيمة الإرجاع

مثيل المنشئ لسلسلة الإضافات أو التكوينات الإضافية.

### انظر أيضًا

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [FontStyle](../../fontstyle/)
* enum [FontWeight](../../fontweight/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
