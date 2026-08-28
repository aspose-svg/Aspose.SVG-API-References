---
title: "Resource.Embed"
second_title: "Riferimento API di Aspose.SVG per .NET"
description: "Metodo Embed di Resource. Incorpora questa risorsa nel suo genitore codificandola come Base64. Il risultato della codifica verrà scritto su OutputUrl."
type: docs
weight: 60
url: /it/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Incorpora questa risorsa nel suo genitore codificandola come Base64. Il risultato della codifica verrà scritto su [`OutputUrl`](../outputurl/).

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contesto | ResourceHandlingContext | Contesto di gestione della risorsa. |

### Valore di ritorno

Questa risorsa per consentire la concatenazione delle chiamate.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Generato se non esiste alcun [`ParentResource`](../../resourcehandlingcontext/parentresource/) perché non c'è un luogo dove incorporare il risultato. |

### Vedi anche

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
