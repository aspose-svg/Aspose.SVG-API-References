---
title: "ResourceHandler.HandleResourceReference"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo ResourceHandler HandleResourceReference. Questo metodo è responsabile della gestione del riferimento alla Resource. In questo metodo è possibile impostare come apparirà il riferimento alla Resource gestita."
type: docs
weight: 20
url: /it/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Questo metodo è responsabile della gestione del riferimento alla risorsa. In questo metodo, è possibile impostare come apparirà il riferimento alla risorsa gestita.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resource | Resource | Il [`Resource`](../../../aspose.svg.saving/resource/) che sarà gestito. |
| contesto | ResourceHandlingContext | Contesto di gestione della risorsa. |

### Valore di ritorno

Una stringa che verrà scritta nella Resource padre e che rappresenta un riferimento alla Resource attualmente gestita.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Generato se [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) è `null` e [`Status`](../../../aspose.svg.saving/resource/status/) è Saved. [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/) dovrebbe essere specificato per la Resource salvata perché altrimenti è impossibile specificare il riferimento corretto nelle risorse che fanno riferimento a questa. |

### Vedi anche

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
