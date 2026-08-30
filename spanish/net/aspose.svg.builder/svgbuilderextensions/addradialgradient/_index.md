---
title: "SVGBuilderExtensions.AddRadialGradient"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddRadialGradient. Añade una configuración de elemento radialGradient al generador."
type: docs
weight: 440
url: /es/net/aspose.svg.builder/svgbuilderextensions/addradialgradient/
---
## AddRadialGradient<TBuilder>(*this TBuilder, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient_1}

Agrega una configuración del elemento 'radialGradient' al generador.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    Action<SVGRadialGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'radialGradient'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRadialGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGRadialGradientElementBuilder&gt;*) {#addradialgradient}

Agrega un elemento 'radialGradient' al generador SVG, especificando su centro, radio y puntos focales, junto con otras propiedades del degradado.

```csharp
public static TBuilder AddRadialGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<double, (double, LengthType)> fx = null, 
    OneOf<double, (double, LengthType)> fy = null, CoordinateUnits? gradientUnits = default, 
    SpreadMethod? spreadMethod = default, string href = null, string id = null, 
    Action<SVGRadialGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del generador SVG a la que se añadirá el elemento 'radialGradient'. |
| cx | La coordenada x del centro del degradado. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| cy | La coordenada y del centro del degradado. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| r | El radio del degradado. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| fx | La coordenada x del punto focal del degradado. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| fy | La coordenada y del punto focal del degradado. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| gradientUnits | Especifica el sistema de coordenadas para el degradado. Parámetro opcional. |
| spreadMethod | Define cómo se extiende el degradado más allá de sus puntos de inicio y fin. Parámetro opcional. |
| href | La referencia a otro gradiente, si corresponde. Parámetro opcional. |
| id | El identificador único para el elemento gradiente. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento de gradiente radial. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGRadialGradientElementBuilder](../../svgradialgradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
