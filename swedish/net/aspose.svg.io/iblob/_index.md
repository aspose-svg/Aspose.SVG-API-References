---
title: "IBlob gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.IO.IBlob gränssnitt. Ett Blob-objekt refererar till en byte-sekvens och har ett size‑attribut som är det totala antalet byte i sekvensen samt ett type‑attribut som är en ASCII‑kodad sträng i gemener som representerar mediatypen för byte‑sekvensen"
type: docs
weight: 4030
url: /sv/net/aspose.svg.io/iblob/
---
## IBlob interface

Ett Blob‑objekt refererar till en byte‑sekvens och har ett size‑attribut som är det totala antalet byte i sekvensen samt ett type‑attribut, som är en ASCII‑kodad sträng i gemener som representerar mediatypen för byte‑sekvensen.

```csharp
public interface IBlob
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size/) { get; } | Returnerar storleken på byte‑sekvensen i antal byte. Vid hämtning måste kompatibla användaragenter returnera det totala antalet byte som kan läsas av ett FileReader‑ eller FileReaderSync‑objekt, eller 0 om Blob‑objektet inte har några byte att läsa. |
| [Type](../../aspose.svg.io/iblob/type/) { get; } | Den ASCII‑kodade strängen i gemener som representerar Blob‑objektets mediatyp. Vid hämtning måste användaragenter returnera typen för en Blob som en ASCII‑kodad sträng i gemener, så att den vid konvertering till en byte‑sekvens blir en parsbar MIME‑typ, eller den tomma strängen – 0 byte – om typen inte kan bestämmas. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice/)(*ulong, ulong, string*) | Returnerar ett nytt Blob‑objekt med byte‑värden från den valfria start‑parametern upp till, men utan att inkludera, den valfria slut‑parametern, samt med ett type‑attribut som är värdet för den valfria contentType‑parametern. |

### Se även

* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
