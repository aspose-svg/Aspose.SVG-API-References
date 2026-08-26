---
title: "ResourceHandlingOptions Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Saving.ResourceHandlingOptions Klasse. Stellt Optionen zur Ressourcenverwaltung dar."
type: docs
weight: 5760
url: /de/net/aspose.svg.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

Stellt Optionen zur Ressourcenverarbeitung dar.

```csharp
public class ResourceHandlingOptions
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Default](../../aspose.svg.saving/resourcehandlingoptions/default/) { get; set; } | Liest oder legt das Enum fest, das die standardmäßige Art der Ressourcenverwaltung darstellt. Derzeit werden die Werte Save, Ignore und Embed unterstützt. Standardwert ist Save. |
| [JavaScript](../../aspose.svg.saving/resourcehandlingoptions/javascript/) { get; set; } | Liest oder legt das Enum fest, das die Art der Skriptverarbeitung darstellt. Derzeit werden die Werte Save, Ignore, Discard und Embed unterstützt. Standardwert ist Save. |
| [MaxHandlingDepth](../../aspose.svg.saving/resourcehandlingoptions/maxhandlingdepth/) { get; set; } | Liest oder legt die maximale Tiefe der zu verarbeitenden Seiten fest. Eine Tiefe von 1 bedeutet, dass nur direkt aus dem gespeicherten Dokument referenzierte Seiten verarbeitet werden. Das Setzen dieser Eigenschaft auf -1 führt zur Verarbeitung aller Seiten. Standardwert ist 0. |
| [PageUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/pageurlrestriction/) { get; set; } | Ruft die Beschränkung ab oder legt sie fest, die auf URLs der behandelten Seiten angewendet wird. Standardwert ist RootAndSubFolders. |
| [ResourceUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/resourceurlrestriction/) { get; set; } | Ruft die Beschränkung ab oder legt sie fest, die auf URLs der behandelten Ressourcen wie CSS, JS, Bilder usw. angewendet wird. Standardwert ist SameHost. |

### Siehe auch

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
