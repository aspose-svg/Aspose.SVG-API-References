---
title: "ResourceHandlingOptions klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Saving.ResourceHandlingOptions klass. Representerar alternativ för resurshantering"
type: docs
weight: 5760
url: /sv/net/aspose.svg.saving/resourcehandlingoptions/
---
## ResourceHandlingOptions class

Representerar alternativ för resurshantering.

```csharp
public class ResourceHandlingOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Default](../../aspose.svg.saving/resourcehandlingoptions/default/) { get; set; } | Hämtar eller anger en enum som representerar standardmetoden för resurshantering. För närvarande stöds värdena Save, Ignore och Embed. Standardvärdet är Save. |
| [JavaScript](../../aspose.svg.saving/resourcehandlingoptions/javascript/) { get; set; } | Hämtar eller anger en enum som representerar hur skript hanteras. För närvarande stöds värdena Save, Ignore, Discard och Embed. Standardvärdet är Save. |
| [MaxHandlingDepth](../../aspose.svg.saving/resourcehandlingoptions/maxhandlingdepth/) { get; set; } | Hämtar eller anger maximal djup för sidor som ska hanteras. Djupet 1 betyder att endast sidor som direkt refereras från det sparade dokumentet kommer att hanteras. Att sätta denna egenskap till -1 innebär att alla sidor hanteras. Standardvärdet är 0. |
| [PageUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/pageurlrestriction/) { get; set; } | Hämtar eller anger begränsning som tillämpas på URL:er för hanterade sidor. Standardvärdet är RootAndSubFolders. |
| [ResourceUrlRestriction](../../aspose.svg.saving/resourcehandlingoptions/resourceurlrestriction/) { get; set; } | Hämtar eller anger begränsning som tillämpas på URL:er för hanterade resurser såsom css, js, bilder etc. Standardvärdet är SameHost. |

### Se även

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
