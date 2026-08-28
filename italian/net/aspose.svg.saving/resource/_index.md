---
title: "Classe Resource"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Saving.Resource. Questa classe descrive una risorsa e fornisce metodi per elaborarla"
type: docs
weight: 5710
url: /it/net/aspose.svg.saving/resource/
---
## Resource class

Questa classe descrive una risorsa e fornisce metodi per elaborarla.

```csharp
public class Resource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | Restituisce il !:Html.MimeType di questa risorsa. Può essere `null` se la risorsa non è stata trovata. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | Restituisce una stringa contenente il riferimento originale a questa risorsa. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | Restituisce un URL che indica dove si trovava questa risorsa. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | Ottiene o imposta l'URL che indica dove la risorsa sarà posizionata dopo l'elaborazione. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | Restituisce lo stato corrente della risorsa. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | Incorpora questa risorsa nel suo genitore codificandola in Base64. Il risultato della codifica verrà scritto in [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | Salva la risorsa nello stream fornito. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | Specifica il nuovo URL che indica dove la risorsa sarà posizionata dopo l'elaborazione. |

### Vedi anche

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
