---
title: "SVGBuilderExtensions.AddFeSpecularLighting"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddFeSpecularLighting. Añade una configuración de elemento feSpecularLighting al generador. Este elemento aplica un efecto de iluminación a la imagen simulando una reflexión especular."
type: docs
weight: 270
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfespecularlighting/
---
## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_2}

Agrega una configuración del elemento 'feSpecularLighting' al constructor. Este elemento aplica un efecto de iluminación a la imagen, simulando una reflexión especular.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpecularLightingElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feSpecularLighting'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEDistantLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting}

Agrega un elemento 'feSpecularLighting' al constructor SVG, aplicando un efecto de iluminación especular usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEDistantLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feSpecularLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación especular. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| specularConstant | La constante utilizada para escalar el término especular. Parámetro opcional. |
| specularExponent | El exponente para el término especular, que controla el enfoque del resalte especular. Parámetro opcional. |
| kernelUnitLength | La longitud de unidad del kernel para el filtro de convolución. Puede ser un double o una ValueTuple de dos doubles. Parámetro opcional. |
| in | La imagen de entrada a la que se aplicará el efecto de iluminación especular. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFESpecularLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFEDistantLightElementBuilder](../../svgfedistantlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFEPointLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_1}

Agrega un elemento 'feSpecularLighting' al constructor SVG, aplicando un efecto de iluminación especular usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFEPointLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feSpecularLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación especular. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| specularConstant | La constante utilizada para escalar el término especular. Parámetro opcional. |
| specularExponent | El exponente para el término especular, que controla el enfoque del resalte especular. Parámetro opcional. |
| kernelUnitLength | La longitud de unidad del kernel para el filtro de convolución. Puede ser un double o una ValueTuple de dos doubles. Parámetro opcional. |
| in | La imagen de entrada a la que se aplicará el efecto de iluminación especular. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFESpecularLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFEPointLightElementBuilder](../../svgfepointlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeSpecularLighting<TBuilder>(*this TBuilder, Action&lt;SVGFESpotLightElementBuilder&gt;, Color?, double?, double?, double?, OneOf&lt;double, (double, double)&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFESpecularLightingElementBuilder&gt;*) {#addfespecularlighting_3}

Agrega un elemento 'feSpecularLighting' al constructor SVG, aplicando un efecto de iluminación especular usando una fuente de luz especificada.

```csharp
public static TBuilder AddFeSpecularLighting<TBuilder>(this TBuilder builder, 
    Action<SVGFESpotLightElementBuilder> lightSource, Color? lightingColor = default, 
    double? surfaceScale = null, double? specularConstant = null, double? specularExponent = null, 
    OneOf<double, (double, double)> kernelUnitLength = null, OneOf<string, FilterInput> @in = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFESpecularLightingElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feSpecularLighting'. |
| lightSource | Una acción para configurar la fuente de luz para el efecto de iluminación especular. |
| lightingColor | El color de la luz. Parámetro opcional. |
| surfaceScale | El factor de escala de superficie para el efecto de iluminación. Parámetro opcional. |
| specularConstant | La constante utilizada para escalar el término especular. Parámetro opcional. |
| specularExponent | El exponente para el término especular, que controla el enfoque del resalte especular. Parámetro opcional. |
| kernelUnitLength | La longitud de unidad del kernel para el filtro de convolución. Puede ser un double o una ValueTuple de dos doubles. Parámetro opcional. |
| in | La imagen de entrada a la que se aplicará el efecto de iluminación especular. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFESpecularLightingElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [SVGFESpotLightElementBuilder](../../svgfespotlightelementbuilder/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFESpecularLightingElementBuilder](../../svgfespecularlightingelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
