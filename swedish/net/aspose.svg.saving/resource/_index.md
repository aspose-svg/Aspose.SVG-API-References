---
title: "Resource-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Saving.Resource-klass. Denna klass beskriver en resurs och tillhandahåller metoder för att bearbeta den"
type: docs
weight: 5710
url: /sv/net/aspose.svg.saving/resource/
---
## Resource class

Denna klass beskriver en resurs och tillhandahåller metoder för att bearbeta den.

```csharp
public class Resource
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Returnerar !:Html.MimeType för denna resurs. Kan vara `null` om resursen inte hittades. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Returnerar en sträng som innehåller den ursprungliga referensen till denna resurs. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Returnerar en URL som anger var denna resurs befann sig. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Hämtar eller anger URL:en som visar var resursen kommer att ligga efter bearbetning. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Returnerar den aktuella statusen för resursen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Bäddar in denna resurs i dess förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Sparar resursen till den angivna strömmen. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Anger den nya URL:en som visar var resursen kommer att ligga efter bearbetning. |

### Se även

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
