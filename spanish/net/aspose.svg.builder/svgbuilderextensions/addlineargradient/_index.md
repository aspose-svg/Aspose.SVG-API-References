---
title: "SVGBuilderExtensions.AddLinearGradient"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddLinearGradient de SVGBuilderExtensions. Añade una configuración de elemento linearGradient al constructor"
type: docs
weight: 360
url: /es/net/aspose.svg.builder/svgbuilderextensions/addlineargradient/
---
## AddLinearGradient<TBuilder>(*this TBuilder, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient_1}

Agrega una configuración del elemento 'linearGradient' al generador.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    Action<SVGLinearGradientElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IPaintServerElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'linearGradient'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IPaintServerElementBuilder](../../ipaintserverelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLinearGradient<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, CoordinateUnits?, SpreadMethod?, string, string, Action&lt;SVGLinearGradientElementBuilder&gt;*) {#addlineargradient}

Agrega un elemento 'linearGradient' al generador SVG, especificando sus posiciones de inicio y fin, junto con otras propiedades del degradado.

```csharp
public static TBuilder AddLinearGradient<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1, OneOf<double, (double, LengthType)> y1, 
    OneOf<double, (double, LengthType)> x2, OneOf<double, (double, LengthType)> y2, 
    CoordinateUnits? gradientUnits, SpreadMethod? spreadMethod, string href = null, 
    string id = null, Action<SVGLinearGradientElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'linearGradient'. |
| x1 | La coordenada x inicial del gradiente. Puede ser un double o un ValueTuple con LengthType. |
| y1 | La coordenada y inicial del gradiente. Puede ser un double o un ValueTuple con LengthType. |
| x2 | La coordenada x final del gradiente. Puede ser un double o un ValueTuple con LengthType. |
| y2 | La coordenada y final del gradiente. Puede ser un double o un ValueTuple con LengthType. |
| gradientUnits | Especifica el sistema de coordenadas para el degradado. Parámetro opcional. |
| spreadMethod | Define cómo se extiende el degradado más allá de sus puntos de inicio y fin. Parámetro opcional. |
| href | La referencia a otro gradiente, si corresponde. Parámetro opcional. |
| id | El identificador único para el elemento gradiente. Parámetro opcional. |
| extender | Una acción opcional para configurar aún más el constructor del elemento de gradiente lineal. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* enum [CoordinateUnits](../../coordinateunits/)
* enum [SpreadMethod](../../spreadmethod/)
* class [SVGLinearGradientElementBuilder](../../svglineargradientelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
