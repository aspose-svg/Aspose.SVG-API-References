---
title: "DOMTokenList-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Collections.DOMTokenList-klass. DOMTokenList-klassen representerar en uppsättning blankstegsavgränsade token. Den indexeras med början på 0 som med JavaScript Array-objekt. DOMTokenList är alltid skiftlägeskänslig."
type: docs
weight: 2000
url: /sv/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

Klassen DOMTokenList representerar en uppsättning av mellanslagsseparerade token. Den indexeras med start från 0 som med JavaScript Array‑objekt. DOMTokenList är alltid skiftlägeskänslig.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | Returnerar objektet i listan efter dess index, eller null om index är större än eller lika med listans längd. |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | Returnerar en ulong som representerar antalet token som lagras i denna lista. |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | Hämtar eller anger värdet för ett motsvarande attribut. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | Lägger till de specificerade token(s) i listan. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | Returnerar true om listan innehåller den angivna token, annars false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | Tar bort de specificerade token(s) från listan. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | Ersätter en befintlig token med en ny token. Gör inget om den första token inte finns. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | Returnerar true om en given token finns bland de stödda token för det associerade attributet. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | Tar bort token från listan om den finns, eller lägger till token i listan om den inte finns. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | Tar bort token från listan om den finns, eller lägger till token i listan om den inte finns. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
