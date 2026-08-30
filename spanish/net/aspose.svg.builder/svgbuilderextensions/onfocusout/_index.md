---
title: "SVGBuilderExtensions.OnFocusOut"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método OnFocusOut de SVGBuilderExtensions. Establece el atributo de evento onfocusout para manejar eventos de pérdida de foco en el elemento"
type: docs
weight: 1460
url: /es/net/aspose.svg.builder/svgbuilderextensions/onfocusout/
---
## SVGBuilderExtensions.OnFocusOut<TBuilder> method

Establece el atributo de evento 'onfocusout' para manejar eventos de foco al salir del elemento.

```csharp
public static TBuilder OnFocusOut<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGraphicalEventAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La función o script JavaScript que se ejecuta cuando el elemento pierde el foco, típicamente antes del evento 'onblur'. |

### Valor de retorno

La instancia del constructor para encadenamiento.

## Observaciones

El evento 'onfocusout' se dispara cuando un elemento está a punto de perder el foco. Similar a 'onfocusin', este evento soporta bubbling y también puede usarse para detectar cambios de foco en elementos hijos.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGraphicalEventAttributeSetter](../../igraphicaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
