---
title: "Resource Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Saving.Resource klasse. Deze klasse beschrijft een resource en biedt methoden voor de verwerking ervan"
type: docs
weight: 5710
url: /nl/net/aspose.svg.saving/resource/
---
## Resource class

Deze klasse beschrijft een bron en biedt methoden voor het verwerken ervan.

```csharp
public class Resource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Retourneert de !:Html.MimeType van deze resource. Kan `null` zijn als de resource niet werd gevonden. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Retourneert een string die de oorspronkelijke referentie naar deze bron bevat. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Retourneert een URL die aangeeft waar deze bron zich bevond. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Haalt op of stelt de URL in die aangeeft waar de bron zich na verwerking zal bevinden. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Retourneert de huidige status van de bron. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Integreert deze bron in zijn ouder door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Slaat de bron op in de opgegeven stream. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Specificeert de nieuwe URL die aangeeft waar de bron zich na verwerking zal bevinden. |

### Zie ook

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
