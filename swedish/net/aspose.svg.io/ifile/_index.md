---
title: "IFile gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.IO.IFile gränssnitt. Ett File-objekt är ett Blob-objekt med ett namn-attribut som är en sträng; det kan skapas i webbapplikationen via en konstruktor eller är en referens till en byte-sekvens från en fil i det underliggande OS-filsystemet"
type: docs
weight: 4050
url: /sv/net/aspose.svg.io/ifile/
---
## IFile interface

Ett File‑objekt är ett Blob‑objekt med ett name‑attribut, som är en sträng; det kan skapas i webbapplikationen via en konstruktor, eller så är det en referens till en byte‑sekvens från en fil i det underliggande (OS)‑filsystemet.

```csharp
public interface IFile : IBlob
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [LastModified](../../aspose.svg.io/ifile/lastmodified/) { get; } | Det senaste ändringsdatumet för filen. Vid hämtning, om användaragenter kan göra denna information tillgänglig, måste den returnera ett long long‑värde som är tiden då filen senast ändrades i antal millisekunder sedan Unix-epoken. |
| [Name](../../aspose.svg.io/ifile/name/) { get; } | Filens namn. Vid hämtning måste detta returnera filens namn som en sträng. |

### Se även

* interface [IBlob](../iblob/)
* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
