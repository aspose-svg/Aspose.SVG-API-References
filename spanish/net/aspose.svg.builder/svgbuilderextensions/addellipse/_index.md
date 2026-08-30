---
title: "SVGBuilderExtensions.AddEllipse"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddEllipse de SVGBuilderExtensions. Añade una configuración de elemento elipse al constructor"
type: docs
weight: 120
url: /es/net/aspose.svg.builder/svgbuilderextensions/addellipse/
---
## AddEllipse<TBuilder>(*this TBuilder, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse_1}

Agrega una configuración de elemento 'ellipse' al creador.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    Action<SVGEllipseElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'ellipse'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddEllipse<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGEllipseElementBuilder&gt;*) {#addellipse}

Agrega un elemento 'ellipse' al creador SVG, especificando su centro, radios y estilos.

```csharp
public static TBuilder AddEllipse<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> rx = null, OneOf<double, (double, LengthType)> ry = null, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGEllipseElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'ellipse'. |
| cx | La coordenada x del centro de la elipse. Puede ser un valor double o una tupla de double y LengthType. |
| cy | La coordenada y del centro de la elipse. Puede ser un valor double o una tupla de double y LengthType. |
| rx | El radio x de la elipse. Puede ser un valor double o una tupla de double y LengthType. |
| ry | El radio y de la elipse. Puede ser un valor double o una tupla de double y LengthType. |
| relleno | El color de relleno o estilo de pintura para la elipse. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color de trazo o estilo de pintura para la elipse. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento elipse. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento elipse. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGEllipseElementBuilder](../../svgellipseelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
