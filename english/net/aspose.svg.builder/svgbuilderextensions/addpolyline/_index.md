---
title: SVGBuilderExtensions.AddPolyline
second_title: Aspose.SVG for .NET API Reference
description: SVGBuilderExtensions method. Adds a polyline element to the SVG builder specifying its vertices and styles
type: docs
weight: 430
url: /net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline&lt;TBuilder&gt;(this TBuilder, double[], OneOf&lt;Color, Paint&gt;, OneOf&lt;Color, Paint&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;) {#addpolyline}

Adds a 'polyline' element to the SVG builder, specifying its vertices, and styles.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint> fill = null, OneOf<Color, Paint> stroke = null, string id = null, 
    Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Description |
| --- | --- |
| TBuilder | The type of the SVG element builder, facilitating fluent API usage. |
| builder | The SVG builder instance to which the 'polyline' element will be added. |
| points | An array of doubles representing the points of the polyline (alternating x and y coordinates). |
| fill | The fill color or paint style for the polyline. Can be a Color or a Paint enum value. Optional parameter. |
| stroke | The stroke color or paint style for the polyline. Can be a Color or a Paint enum value. Optional parameter. |
| id | The unique identifier for the polyline element. Optional parameter. |
| extend | An optional action to further configure the polyline element builder. |

### Return Value

The builder instance, allowing for method chaining.

### See Also

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline&lt;TBuilder&gt;(this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;) {#addpolyline_1}

Adds a 'polyline' element configuration to the builder.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parameter | Description |
| --- | --- |
| TBuilder | The type of the SVG element builder. |
| builder | The builder instance. |
| configure | The configuration action for the 'polyline' element. |

### Return Value

The builder instance for chaining.

### See Also

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
