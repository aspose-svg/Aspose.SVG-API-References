---
title: "IMediaList-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.IMediaList interface. MediaList‑gränssnittet tillhandahåller en abstraktion av en ordnad samling av media utan att definiera eller begränsa hur denna samling implementeras. En tom lista är densamma som en lista som innehåller alla medium."
type: docs
weight: 2730
url: /sv/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

MediaList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur samlingen implementeras. En tom lista är densamma som en lista som innehåller mediet "all".

```csharp
public interface IMediaList : IEnumerable<string>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Returnerar elementet på det angivna indexet i listan. Om index är större än eller lika med antalet media i listan returneras null. Media‑indexet. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Antalet media i listan. Intervallet för giltiga media är 0 till längd‑1, inklusive. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | Den parsbara textrepresentationen av medialistan. Detta är en kommaseparerad lista med media. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | Lägger till mediet newMedium i slutet av listan. Om newMedium redan används tas det först bort. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | Tar bort mediet som anges av oldMedium från listan. |

### Se även

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
