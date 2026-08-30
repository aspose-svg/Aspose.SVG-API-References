---
title: "SVGBuilderExtensions.AddRect"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "SVGBuilderExtensions AddRect method. Añade una configuración de elemento rect al constructor"
type: docs
weight: 450
url: /es/net/aspose.svg.builder/svgbuilderextensions/addrect/
---
## AddRect<TBuilder>(*this TBuilder, Action&lt;SVGRectElementBuilder&gt;*) {#addrect_1}

Agrega una configuración del elemento 'rect' al generador.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    Action<SVGRectElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'rect'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRect<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGRectElementBuilder&gt;*) {#addrect}

Agrega un elemento 'rect' (rectángulo) con dimensiones y estilos especificados al generador SVG.

```csharp
public static TBuilder AddRect<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGRectElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'rect'. |
| x | La coordenada x del punto de inicio del rectángulo. Puede ser un valor double o una tupla de double y LengthType. |
| y | La coordenada y del punto de inicio del rectángulo. Puede ser un valor double o una tupla de double y LengthType. |
| width | El ancho del rectángulo. Puede ser un valor double o una tupla de double y LengthType. |
| altura | La altura del rectángulo. Puede ser un valor double o una tupla de double y LengthType. |
| relleno | El color de relleno o estilo de pintura para el rectángulo. Puede ser un Color o un valor de enumeración Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color del trazo o estilo de pintura para el contorno del rectángulo. Puede ser un Color o un valor de enumeración Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento rectángulo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento rectángulo. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGRectElementBuilder](../../svgrectelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
