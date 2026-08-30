---
title: "SVGBuilderExtensions.AddText"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddText de SVGBuilderExtensions. Añade una configuración de elemento de texto al constructor."
type: docs
weight: 530
url: /es/net/aspose.svg.builder/svgbuilderextensions/addtext/
---
## AddText<TBuilder>(*this TBuilder, Action&lt;SVGTextElementBuilder&gt;*) {#addtext}

Agrega una configuración del elemento 'text' al constructor.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, 
    Action<SVGTextElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'text'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGTextElementBuilder](../../svgtextelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddText<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, FontStyle?, string, FontWeight?, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGTextElementBuilder&gt;*) {#addtext_1}

Agrega un elemento 'text' con contenido y atributos especificados al constructor SVG.

```csharp
public static TBuilder AddText<TBuilder>(this TBuilder builder, string content, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> fontSize = null, FontStyle? fontStyle = default, 
    string fontFamily = null, FontWeight? fontWeight = default, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGTextElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que permite encadenamiento. |
| constructor | La instancia del constructor a la que se añadirá el elemento 'text'. |
| content | El contenido de texto que se mostrará dentro del elemento 'text'. |
| x | La coordenada x del elemento de texto. Puede ser un valor double o una tupla de double y LengthType. |
| y | La coordenada y del elemento de texto. Puede ser un valor double o una tupla de double y LengthType. |
| fontSize | El tamaño de fuente del texto. Puede ser un valor double o una tupla de double y LengthType. |
| fontStyle | El estilo de fuente del texto (p. ej., normal, italic, oblique). |
| fontFamily | La familia de fuentes del texto (p. ej., Arial, Verdana). |
| fontWeight | El grosor (peso) de la fuente (p. ej., normal, bold). |
| relleno | El color de relleno o estilo de pintura del texto. Puede ser un Color, un valor del enum Paint o un ID de servidor de pintura. |
| trazo | El color de trazo o estilo de pintura del texto. Puede ser un Color, un valor del enum Paint o un ID de servidor de pintura. |
| id | El identificador único del elemento de texto. |
| extender | Una acción opcional para configurar aún más el constructor del elemento de texto. |

### Valor de retorno

La instancia del constructor para encadenar adiciones o configuraciones adicionales.

### Ver también

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
