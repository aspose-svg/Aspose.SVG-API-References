---
title: "Clase Resource"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Aspose.Svg.Saving.Resource class. Esta clase describe un recurso y proporciona métodos para procesarlo"
type: docs
weight: 5710
url: /es/net/aspose.svg.saving/resource/
---
## Resource class

Esta clase describe un recurso y proporciona métodos para procesarlo.

```csharp
public class Resource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Devuelve el !:Html.MimeType de este recurso. Puede ser `null` si no se encontró el recurso. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Devuelve una cadena que contiene la referencia original a este recurso. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Devuelve una URL que indica dónde se encontraba este recurso. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Obtiene o establece la URL que indica dónde se ubicará el recurso después del procesamiento. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Devuelve el estado actual del recurso. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Incrusta este recurso dentro de su padre codificándolo como Base64. El resultado de la codificación se escribirá en [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Guarda el recurso en el flujo proporcionado. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Especifica la nueva URL que indica dónde se ubicará el recurso después del procesamiento. |

### Ver también

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
