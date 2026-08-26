---
title: "ResourceHandler‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler‑Klasse. Diese Klasse ist für die Verarbeitung von Ressourcen verantwortlich. Sie bietet Methoden, mit denen Sie steuern können, was mit der Resource gemacht wird und welche Referenz in die übergeordnete Resource geschrieben wird."
type: docs
weight: 5730
url: /de/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

Diese Klasse ist für die Handhabung von Ressourcen verantwortlich. Sie stellt Methoden bereit, die es Ihnen ermöglichen zu steuern, was mit dem [`Resource`](../../aspose.svg.saving/resource/) geschieht, sowie welche Referenz zum übergeordneten [`Resource`](../../aspose.svg.saving/resource/) geschrieben wird.

```csharp
public abstract class ResourceHandler
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Diese Methode ist für die Verarbeitung der Ressource verantwortlich. In ihr können Sie die [`Resource`](../../aspose.svg.saving/resource/) in den Stream speichern oder sie in die übergeordnete Ressource einbetten. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | Diese Methode ist für die Verarbeitung der Ressourcenreferenz verantwortlich. In dieser Methode können Sie festlegen, wie die Referenz auf die zu verarbeitende Ressource aussehen soll. |

### Siehe auch

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
