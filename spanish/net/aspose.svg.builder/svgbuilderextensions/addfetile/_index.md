---
title: "SVGBuilderExtensions.AddFeTile"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddFeTile de SVGBuilderExtensions. Añade una configuración de elemento feTile al constructor. Este elemento rellena un rectángulo con el patrón de mosaico repetido de una imagen de entrada."
type: docs
weight: 280
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfetile/
---
## AddFeTile<TBuilder>(*this TBuilder, Action&lt;SVGFETileElementBuilder&gt;*) {#addfetile_1}

Agrega una configuración del elemento 'feTile' al constructor. Este elemento llena un rectángulo con el patrón repetido y en mosaico de una imagen de entrada.

```csharp
public static TBuilder AddFeTile<TBuilder>(this TBuilder builder, 
    Action<SVGFETileElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'feTile'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFETileElementBuilder](../../svgfetileelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFeTile<TBuilder>(*this TBuilder, OneOf&lt;string, FilterInput&gt;, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFETileElementBuilder&gt;*) {#addfetile}

Agrega un elemento 'feTile' al constructor SVG, creando un patrón de mosaicos replicando la imagen de entrada.

```csharp
public static TBuilder AddFeTile<TBuilder>(this TBuilder builder, 
    OneOf<string, FilterInput> @in = null, string result = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFETileElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'feTile'. |
| in | La imagen de entrada que se replicará en mosaicos. Puede ser una cadena o un FilterInput. Parámetro opcional. |
| result | El identificador de resultado para este filtro primitivo. Parámetro opcional. |
| x | La coordenada x de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la subregión del filtro primitivo. Puede ser un double o una ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la subregión del filtro primitivo. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| trazo | El color del trazo, pintura o ID del servidor de pintura para el elemento. Parámetro opcional. |
| id | El identificador único para el elemento de filtro primitivo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFETileElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [FilterInput](../../filterinput/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFETileElementBuilder](../../svgfetileelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
