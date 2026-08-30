---
title: "SVGBuilderExtensions.AddFeColorMatrix"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddFeColorMatrix. Añade una configuración del elemento feColorMatrix al constructor. Este elemento aplica una transformación matricial a los valores de color y alfa de cada píxel"
type: docs
weight: 140
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfecolormatrix/
---
## AddFeColorMatrix<TBuilder>(*this TBuilder, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix_1}

Agrega una configuración de elemento 'feColorMatrix' al creador. Este elemento aplica una transformación matricial a los valores de color y alfa de cada píxel.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, 
    Action<SVGFEColorMatrixElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feColorMatrix'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeColorMatrix<TBuilder>(*this TBuilder, [ColorMatrixOperation](../../colormatrixoperation/), double[], OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEColorMatrixElementBuilder&gt;*) {#addfecolormatrix}

Agrega un elemento 'feColorMatrix' al creador SVG, especificando el tipo de operación de la matriz de color y varias propiedades adicionales para el efecto del filtro.

```csharp
public static TBuilder AddFeColorMatrix<TBuilder>(this TBuilder builder, ColorMatrixOperation type, 
    double[] values = null, OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEColorMatrixElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feColorMatrix'. |
| type | El tipo de operación de matriz de color que se aplicará. |
| valores | Los valores para la operación de matriz de color. Parámetro opcional. |
| in | La entrada para el efecto de matriz de color. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFEColorMatrixElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEColorMatrixElementBuilder](../../svgfecolormatrixelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
