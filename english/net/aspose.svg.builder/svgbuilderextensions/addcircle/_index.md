---
title: SVGBuilderExtensions.AddCircle
second_title: Aspose.SVG for .NET API Reference
description: SVGBuilderExtensions method. Adds a circle element with specified center radius and styles to the SVG builder
type: docs
weight: 70
url: /net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle&lt;TBuilder&gt;(this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;) {#addcircle}

Adds a 'circle' element with specified center, radius, and styles to the SVG builder.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Description |
| --- | --- |
| TBuilder | The type of the SVG element builder, facilitating fluent API usage. |
| builder | The SVG builder instance to which the 'circle' element will be added. |
| cx | The x-coordinate of the circle's center. Can be a double value or a tuple of double and LengthType. |
| cy | The y-coordinate of the circle's center. Can be a double value or a tuple of double and LengthType. |
| r | The radius of the circle. Can be a double value or a tuple of double and LengthType. |
| fill | The fill color or paint style for the circle. Can be a Color or a Paint enum value or paint server ID. Optional parameter. |
| stroke | The stroke color or paint style for the circle's outline. Can be a Color or a Paint enum value or paint server ID. Optional parameter. |
| id | The unique identifier for the circle element. Optional parameter. |
| extend | An optional action to further configure the circle element builder. |

### Return Value

The builder instance, allowing for method chaining.

### See Also

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle&lt;TBuilder&gt;(this TBuilder, Action&lt;SVGCircleElementBuilder&gt;) {#addcircle_1}

Adds a 'circle' element configuration to the builder.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Description |
| --- | --- |
| TBuilder | The type of the SVG element builder. |
| builder | The builder instance. |
| configure | The configuration action for the 'circle' element. |

### Return Value

The builder instance for chaining.

### See Also

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
