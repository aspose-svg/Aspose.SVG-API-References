---
title: "SVGBuilderExtensions.OnFocusIn"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions OnFocusIn. Establece el atributo de evento onfocusin para manejar eventos de enfoque en el elemento."
type: docs
weight: 1450
url: /es/net/aspose.svg.builder/svgbuilderextensions/onfocusin/
---
## SVGBuilderExtensions.OnFocusIn<TBuilder> method

Establece el atributo de evento 'onfocusin' para manejar eventos de foco al entrar en el elemento.

```csharp
public static TBuilder OnFocusIn<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La función o script JavaScript que se ejecuta cuando el elemento recibe foco, típicamente antes del evento 'onfocus'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

El evento 'onfocusin' se dispara cuando un elemento está a punto de recibir foco. Este evento difiere de 'onfocus' en que soporta bubbling y puede usarse para detectar cambios de foco en elementos hijos también.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
