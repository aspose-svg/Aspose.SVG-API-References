---
title: "Resource.Save"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Resource Save-methode. Slaat de resource op naar de opgegeven stream."
type: docs
weight: 70
url: /nl/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Slaat de bron op in de opgegeven stream.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stream waarin de resource zal worden opgeslagen. |
| context | ResourceHandlingContext | Resource handling context. |

### Retourwaarde

Deze resource zodat u keten‑aanroepen kunt doen.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| InvalidOperationException | Wordt opgegooid als [`OutputUrl`](../outputurl/) `null` is. [`OutputUrl`](../outputurl/) moet worden opgegeven voordat de resource wordt opgeslagen, omdat het anders onmogelijk is de juiste referentie op te geven in de resources die naar deze verwijzen. |

### Zie ook

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
