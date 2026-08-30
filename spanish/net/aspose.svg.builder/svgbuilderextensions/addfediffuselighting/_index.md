---
title: "SVGBuilderExtensions.AddFeDiffuseLighting"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddFeDiffuseLighting. Añade una configuración de elemento feDiffuseLighting al constructor. Este elemento proporciona un efecto de iluminación en una imagen"
type: docs
weight: 180
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfediffuselighting/
---
## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting}

Agrega una configuración de elemento 'feDiffuseLighting' al creador. Este elemento proporciona un efecto de iluminación sobre una imagen.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDiffuseLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feDiffuseLighting'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_1}

Agrega un elemento 'feDiffuseLighting' al creador SVG, aplicando un efecto de iluminación difusa usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del builder SVG a la que se añadirá el elemento 'feDiffuseLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación difusa. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| diffuseConstant | La constante usada para determinar el efecto de iluminación. Parámetro opcional. |
| in | La entrada para el efecto de iluminación difusa. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar aún más el SVGFEDiffuseLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_2}

Agrega un elemento 'feDiffuseLighting' al creador SVG, aplicando un efecto de iluminación difusa usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del builder SVG a la que se añadirá el elemento 'feDiffuseLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación difusa. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| diffuseConstant | La constante usada para determinar el efecto de iluminación. Parámetro opcional. |
| in | La entrada para el efecto de iluminación difusa. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar aún más el SVGFEDiffuseLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeDiffuseLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEDiffuseLightingElementBuilder&gt;*) {#addfediffuselighting_3}

Agrega un elemento 'feDiffuseLighting' al creador SVG, aplicando un efecto de iluminación difusa usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeDiffuseLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? diffuseConstant = null, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEDiffuseLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del builder SVG a la que se añadirá el elemento 'feDiffuseLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación difusa. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| diffuseConstant | La constante usada para determinar el efecto de iluminación. Parámetro opcional. |
| in | La entrada para el efecto de iluminación difusa. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar aún más el SVGFEDiffuseLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEDiffuseLightingElementBuilder](../../svgfediffuselightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
