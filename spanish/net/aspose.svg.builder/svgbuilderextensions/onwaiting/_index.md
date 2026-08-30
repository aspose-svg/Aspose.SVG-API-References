---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método OnWaiting de SVGBuilderExtensions. Establece el atributo de evento onwaiting para manejar eventos cuando la reproducción de medios se retrasa debido al almacenamiento en búfer de datos"
type: docs
weight: 1850
url: /es/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Establece el atributo de evento 'onwaiting' para manejar eventos cuando la reproducción de medios se retrasa debido al almacenamiento en búfer de datos.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La función o script JavaScript a ejecutar cuando la reproducción de medios se retrasa por el almacenamiento en búfer. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
