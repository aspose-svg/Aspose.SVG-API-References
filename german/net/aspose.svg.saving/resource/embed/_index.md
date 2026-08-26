---
title: "Resource.Embed"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Resource Embed Methode. Bettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in OutputUrl geschrieben."
type: docs
weight: 60
url: /de/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

Betettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in [`OutputUrl`](../outputurl/) geschrieben.

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| context | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Diese Ressource, damit Sie Aufrufe verketten können.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Ausgelöst, wenn kein [`ParentResource`](../../resourcehandlingcontext/parentresource/) vorhanden ist, weil es keinen Ort gibt, um das Ergebnis einzubetten. |

### Siehe auch

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
