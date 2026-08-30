---
title: "Resource.Save"
second_title: "Aspose.SVG för .NET API-referens"
description: "Resource Save-metoden. Sparar resursen till den angivna strömmen"
type: docs
weight: 70
url: /sv/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Sparar resursen till den angivna strömmen.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen där resursen kommer att sparas. |
| context | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

Denna resurs så att du kan kedja anrop.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Utlöst om [`OutputUrl`](../outputurl/) är `null`. [`OutputUrl`](../outputurl/) bör specificeras innan resursen sparas eftersom det annars är omöjligt att ange rätt referens i de resurser som refererar till denna. |

### Se även

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
