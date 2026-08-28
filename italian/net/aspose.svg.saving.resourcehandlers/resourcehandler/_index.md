---
title: "Classe ResourceHandler"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Classe Aspose.Svg.Saving.ResourceHandlers.ResourceHandler. Questa classe è responsabile della gestione delle risorse. Fornisce metodi che consentono di controllare cosa verrà fatto con la Resource così come quale riferimento verrà scritto nella Resource padre."
type: docs
weight: 5730
url: /it/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Questa classe è responsabile della gestione delle risorse. Fornisce metodi che consentono di controllare cosa verrà fatto con la [`Resource`](../../aspose.svg.saving/resource/), così come quale riferimento verrà scritto nella [`Resource`](../../aspose.svg.saving/resource/) padre.

```csharp
public abstract class ResourceHandler
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Questo metodo è responsabile della gestione della risorsa. In esso è possibile salvare la [`Resource`](../../aspose.svg.saving/resource/) nello stream o incorporarla nella risorsa padre. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Questo metodo è responsabile della gestione del riferimento alla risorsa. In questo metodo, è possibile impostare come apparirà il riferimento alla risorsa gestita. |

### Vedi anche

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
