---
title: "SVGListBaseT-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Collections.SVGListBase1T-klass. Detta gränssnitt definierar en baskollektion av alla SVG-listor."
type: docs
weight: 2040
url: /sv/net/aspose.svg.collections/svglistbase-1/
---
## SVGListBase<T> class

Detta gränssnitt definierar en baskollektion av alla SVG‑listor.

```csharp
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt som lagras i listan. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.collections/svglistbase-1/item/) { get; set; } | Returnerar det index‑te objektet i listan. |
| [Length](../../aspose.svg.collections/svglistbase-1/length/) { get; } | Antalet objekt i listan. |
| [NumberOfItems](../../aspose.svg.collections/svglistbase-1/numberofitems/) { get; } | Antalet objekt i listan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendItem](../../aspose.svg.collections/svglistbase-1/appenditem/)(*T*) | Infogar ett nytt objekt i slutet av listan. |
| [Clear](../../aspose.svg.collections/svglistbase-1/clear/)() | Rensar alla befintliga aktuella objekt från listan, vilket resulterar i en tom lista. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Frigör ohanterade och - valfritt - hanterade resurser. |
| [GetEnumerator](../../aspose.svg.collections/svglistbase-1/getenumerator/)() | Hämtar enumeratorn. |
| [GetItem](../../aspose.svg.collections/svglistbase-1/getitem/)(*ulong*) | Returnerar det angivna objektet från listan. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [Initialize](../../aspose.svg.collections/svglistbase-1/initialize/)(*T*) | Rensar alla befintliga aktuella objekt från listan och initierar om listan för att hålla det enda objektet som anges av parametern. |
| [InsertItemBefore](../../aspose.svg.collections/svglistbase-1/insertitembefore/)(*T, ulong*) | Infogar ett nytt objekt i listan på den angivna positionen. Det första objektet har nummer 0. |
| [RemoveItem](../../aspose.svg.collections/svglistbase-1/removeitem/)(*ulong*) | Tar bort ett befintligt objekt från listan. |
| [ReplaceItem](../../aspose.svg.collections/svglistbase-1/replaceitem/)(*T, ulong*) | Ersätter ett befintligt objekt i listan med ett nytt objekt. |

### Se även

* class [SVGValueType](../../aspose.svg.datatypes/svgvaluetype/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
