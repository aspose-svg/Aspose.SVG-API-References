---
title: "SVGBuilderExtensions.AddImage"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método AddImage de SVGBuilderExtensions. Añade una configuración de elemento image al constructor"
type: docs
weight: 330
url: /es/net/aspose.svg.builder/svgbuilderextensions/addimage/
---
## AddImage<TBuilder>(*this TBuilder, Action&lt;SVGImageElementBuilder&gt;*) {#addimage}

Agrega una configuración del elemento 'image' al constructor.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, 
    Action<SVGImageElementBuilder> configure)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | La instancia del constructor. |
| configurar | La acción de configuración para el elemento 'image'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddImage<TBuilder>(*this TBuilder, string, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, OneOf&lt;double, (double, LengthType)&gt;, string, Action&lt;SVGImageElementBuilder&gt;*) {#addimage_1}

Agrega un elemento 'image' al constructor SVG, incrustando una imagen externa en el documento SVG.

```csharp
public static TBuilder AddImage<TBuilder>(this TBuilder builder, string href = null, 
    OneOf<double, (double, LengthType)> x = null, OneOf<double, (double, LengthType)> y = null, 
    OneOf<double, (double, LengthType)> width = null, 
    OneOf<double, (double, LengthType)> height = null, string id = null, 
    Action<SVGImageElementBuilder> extend = null)
    where TBuilder : ISVGElementBuilder, ICompositeElementBuilder
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG, que facilita el uso de una API fluida. |
| constructor | La instancia del constructor SVG a la que se añadirá el elemento 'image'. |
| href | La URL o referencia a la imagen externa. Parámetro opcional. |
| x | La coordenada x donde se coloca la imagen. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| y | La coordenada y donde se coloca la imagen. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| width | El ancho de la imagen. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| altura | La altura de la imagen. Puede ser un double o un ValueTuple con LengthType. Parámetro opcional. |
| id | El identificador único para el elemento image. Parámetro opcional. |
| extender | Una acción opcional para configurar más el SVGImageElementBuilder. |

### Valor de retorno

La instancia del constructor, que permite encadenar métodos.

### Ver también

* class [OneOf&lt;T1,T2&gt;](../../oneof-2/)
* enum [LengthType](../../lengthtype/)
* class [SVGImageElementBuilder](../../svgimageelementbuilder/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [ICompositeElementBuilder](../../icompositeelementbuilder/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
