---
title: "SVGBuilderExtensions.AddPolygon"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddPolygon de SVGBuilderExtensions. Añade una configuración de elemento polígono al constructor."
type: docs
weight: 420
url: /es/net/aspose.svg.builder/svgbuilderextensions/addpolygon/
---
## AddPolygon<TBuilder>(*this TBuilder, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon_1}

Agrega una configuración del elemento 'polygon' al generador.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, 
    Action<SVGPolygonElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'polygon'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddPolygon<TBuilder>(*this TBuilder, double[], OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGPolygonElementBuilder&gt;*) {#addpolygon}

Agrega un elemento 'polygon' al generador SVG, especificando sus vértices y estilos.

```csharp
public static TBuilder AddPolygon<TBuilder>(this TBuilder builder, double[] points, 
    OneOf<Color, Paint, string> fill = null, OneOf<Color, Paint, string> stroke = null, 
    string id = null, Action<SVGPolygonElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'polygon'. |
| points | Una matriz de doubles que representa los puntos del polígono (alternando coordenadas x e y). |
| relleno | El color de relleno o estilo de pintura para el polígono. Puede ser un valor de enumeración Color o Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color de trazo o estilo de pintura para el polígono. Puede ser un valor de enumeración Color o Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento polígono. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento polígono. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGPolygonElementBuilder](../../svgpolygonelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
