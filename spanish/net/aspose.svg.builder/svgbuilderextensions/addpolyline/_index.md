---
title: "SVGBuilderExtensions.AddPolyline"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddPolyline de SVGBuilderExtensions. Añade una configuración de elemento polilínea al generador"
type: docs
weight: 430
url: /es/net/aspose.svg.builder/svgbuilderextensions/addpolyline/
---
## AddPolyline<TBuilder>(*this TBuilder, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline_1}

Agrega una configuración del elemento 'polyline' al generador.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, 
    Action<SVGPolylineElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'polyline'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolyline<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolylineElementBuilder&gt;*) {#addpolyline}

Agrega un elemento 'polyline' al generador SVG, especificando sus vértices y estilos.

```csharp
public static TBuilder AddPolyline<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolylineElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del generador SVG a la que se añadirá el elemento 'polyline'. |
| points | Una matriz de doubles que representa los puntos de la polilínea (alternando coordenadas x e y). |
| relleno | El color de relleno o estilo de pintura para la polilínea. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color del trazo o estilo de pintura para la polilínea. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento polilínea. Parámetro opcional. |
| extender | Una acción opcional para configurar más el generador de elementos polilínea. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolylineElementBuilder](../../svgpolylineelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
