---
title: "SVGBuilderExtensions.AddCircle"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions AddCircle. Añade una configuración de elemento círculo al constructor"
type: docs
weight: 70
url: /es/net/aspose.svg.builder/svgbuilderextensions/addcircle/
---
## AddCircle<TBuilder>(*this TBuilder, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle_1}

Agrega una configuración de elemento 'circle' al creador.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    Action<SVGCircleElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'circle'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddCircle<TBuilder>(*this TBuilder, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGCircleElementBuilder&gt;*) {#addcircle}

Agrega un elemento 'circle' con centro, radio y estilos especificados al creador SVG.

```csharp
public static TBuilder AddCircle<TBuilder>(this TBuilder builder, 
    OneOf<double, (double, LengthType)> cx = null, OneOf<double, (double, LengthType)> cy = null, 
    OneOf<double, (double, LengthType)> r = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGCircleElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IShapeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'circle'. |
| cx | La coordenada x del centro del círculo. Puede ser un valor double o una tupla de double y LengthType. |
| cy | La coordenada y del centro del círculo. Puede ser un valor double o una tupla de double y LengthType. |
| r | El radio del círculo. Puede ser un valor double o una tupla de double y LengthType. |
| relleno | El color de relleno o estilo de pintura para el círculo. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| trazo | El color del trazo o estilo de pintura para el contorno del círculo. Puede ser un Color o un valor enum Paint o un ID de servidor de pintura. Parámetro opcional. |
| id | El identificador único para el elemento círculo. Parámetro opcional. |
| extender | Una acción opcional para configurar más el constructor del elemento círculo. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGCircleElementBuilder](../../svgcircleelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IShapeElementBuilder](../../ishapeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
