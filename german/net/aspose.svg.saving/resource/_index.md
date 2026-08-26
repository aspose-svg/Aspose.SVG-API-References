---
title: "Resource Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Saving.Resource Klasse. Diese Klasse beschreibt eine Ressource und stellt Methoden zu deren Verarbeitung bereit."
type: docs
weight: 5710
url: /de/net/aspose.svg.saving/resource/
---
## Resource class

Diese Klasse beschreibt eine Ressource und stellt Methoden zur Verarbeitung bereit.

```csharp
public class Resource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Gibt den !:Html.MimeType dieser Ressource zurück. Kann `null` sein, wenn die Ressource nicht gefunden wurde. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Gibt einen String zurück, der die ursprüngliche Referenz zu dieser Ressource enthält. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Gibt eine URL zurück, die angibt, wo sich diese Ressource befand. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Liest oder setzt die URL, die angibt, wo die Ressource nach der Verarbeitung abgelegt wird. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Gibt den aktuellen Status der Ressource zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Betettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in [`OutputUrl`](./outputurl/) geschrieben. |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Speichert die Ressource in den bereitgestellten Stream. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Gibt die neue URL an, die angibt, wo die Ressource nach der Verarbeitung abgelegt wird. |

### Siehe auch

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
