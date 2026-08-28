---
title: "Resource.Save"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Save di Resource. Salva la risorsa nello stream fornito."
type: docs
weight: 70
url: /it/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Salva la risorsa nello stream fornito.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream in cui la risorsa verrà salvata. |
| contesto | ResourceHandlingContext | Contesto di gestione della risorsa. |

### Valore di ritorno

Questa risorsa per consentire la concatenazione delle chiamate.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Generato se [`OutputUrl`](../outputurl/) è `null`. [`OutputUrl`](../outputurl/) dovrebbe essere specificato prima di salvare la risorsa perché altrimenti è impossibile specificare il riferimento corretto nelle risorse che fanno riferimento a questa. |

### Vedi anche

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
