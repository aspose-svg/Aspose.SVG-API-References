---
title: "SVGBuilderExtensions.AddLine"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddLine. Añade una configuración de elemento línea al constructor"
type: docs
weight: 350
url: /es/net/aspose.svg.builder/svgbuilderextensions/addline/
---
## AddLine<TBuilder>(*this TBuilder, Action&lt;SVGLineElementBuilder&gt;*) {#addline_1}

Agrega una configuración del elemento 'line' al constructor.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    Action<SVGLineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'line'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddLine<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGLineElementBuilder&gt;*) {#addline}

Agrega un elemento 'line' con puntos de inicio y fin especificados, y estilos al constructor SVG.

```csharp
public static TBuilder AddLine<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x1 = null, OneOf<double, (double, LengthType)> y1 = null, 
    OneOf<double, (double, LengthType)> x2 = null, OneOf<double, (double, LengthType)> y2 = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGLineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del SVG builder a la que se añadirá el elemento 'line'. |
| x1 | La coordenada x del punto de inicio de la línea. Puede ser un valor double o una tupla de double y LengthType. |
| y1 | La coordenada y del punto de inicio de la línea. Puede ser un valor double o una tupla de double y LengthType. |
| x2 | La coordenada x del punto final de la línea. Puede ser un valor double o una tupla de double y LengthType. |
| y2 | La coordenada y del punto final de la línea. Puede ser un valor double o una tupla de double y LengthType. |
| relleno | El color de relleno o estilo de pintura para la línea. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color de trazo o estilo de pintura para la línea. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento línea. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento línea. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGLineElementBuilder](../../svglineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
