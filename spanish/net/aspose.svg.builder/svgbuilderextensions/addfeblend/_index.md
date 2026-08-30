---
title: "SVGBuilderExtensions.AddFeBlend"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddFeBlend. Añade una configuración de elemento feBlend al constructor. Este elemento define un efecto de mezcla entre dos gráficos"
type: docs
weight: 130
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfeblend/
---
## AddFeBlend<TBuilder>(*this TBuilder, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend}

Agrega una configuración de elemento 'feBlend' al creador. Este elemento define un efecto de mezcla entre dos gráficos.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, 
    Action<SVGFEBlendElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feBlend'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeBlend<TBuilder>(*this TBuilder, BlendMode?, OneOf&lt;string, FilterInput&gt;, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFEBlendElementBuilder&gt;*) {#addfeblend_1}

Agrega un elemento 'feBlend' al creador SVG, especificando el modo de mezcla y varias propiedades adicionales para el efecto del filtro.

```csharp
public static TBuilder AddFeBlend<TBuilder>(this TBuilder builder, BlendMode? mode = default, 
    OneOf<string, FilterInput> @in = null, OneOf<string, FilterInput> in2 = null, 
    string result = null, OneOf<double, (double, LengthType)> x = null, 
    OneOf<double, (double, LengthType)> y = null, OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFEBlendElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feBlend'. |
| modo | El modo de mezcla a utilizar. Parámetro opcional. |
| in | La primera entrada para el efecto de mezcla. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| in2 | La segunda entrada para el efecto de mezcla. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFEBlendElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* enum [BlendMode](../../blendmode/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFEBlendElementBuilder](../../svgfeblendelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
