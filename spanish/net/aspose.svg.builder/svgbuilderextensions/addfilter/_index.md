---
title: "SVGBuilderExtensions.AddFilter"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddFilter de SVGBuilderExtensions. Añade una configuración de elemento filtro al constructor."
type: docs
weight: 300
url: /es/net/aspose.svg.builder/svgbuilderextensions/addfilter/
---
## AddFilter<TBuilder>(*this TBuilder, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter}

Agrega una configuración del elemento 'filter' al constructor.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    Action<SVGFilterElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'filter'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddFilter<TBuilder>(*this TBuilder, CoordinateUnits?, CoordinateUnits?, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;Color, Paint, string&gt;, OneOf&lt;Color, Paint, string&gt;, string, Action&lt;SVGFilterElementBuilder&gt;*) {#addfilter_1}

Agrega un elemento 'filter' al constructor SVG, definiendo un efecto de filtro que puede aplicarse a elementos SVG.

```csharp
public static TBuilder AddFilter<TBuilder>(this TBuilder builder, 
    CoordinateUnits? filterUnits = default, CoordinateUnits? primitiveUnits = default, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, OneOf<Color, Paint, string> fill = null, 
    OneOf<Color, Paint, string> stroke = null, string id = null, 
    Action<SVGFilterElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'filter'. |
| filterUnits | Especifica el sistema de coordenadas para los atributos x, y, width y height del filtro. Parámetro opcional. |
| primitiveUnits | Especifica el sistema de coordenadas para los atributos de los elementos hijos del filtro. Parámetro opcional. |
| x | La coordenada x de la región del filtro. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y de la región del filtro. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la región del filtro. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la región del filtro. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| relleno | El color de relleno o pintura para el elemento de filtro. Parámetro opcional. |
| trazo | El color del trazo o pintura para el elemento de filtro. Parámetro opcional. |
| id | El identificador único para el elemento de filtro. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGFilterElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* enum [CoordinateUnits](../../coordinateunits/)
* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [OneOf&lt;T1,T2,T3&gt;](../../oneof-3/)
* enum [Paint](../../paint/)
* class [SVGFilterElementBuilder](../../svgfilterelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveElementBuilder](../../ifilterprimitiveelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
