---
title: "IBlob Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.IO.IBlob interface. Een Blob-object verwijst naar een byte‑reeks en heeft een size‑attribuut dat het totale aantal bytes in de byte‑reeks aangeeft, en een type‑attribuut dat een ASCII‑gecodeerde string in kleine letters is die het mediatype van de byte‑reeks weergeeft."
type: docs
weight: 4030
url: /nl/net/aspose.svg.io/iblob/
---
## IBlob interface

Een Blob‑object verwijst naar een byte‑reeks en heeft een size‑attribuut dat het totale aantal bytes in de reeks aangeeft, en een type‑attribuut, dat een ASCII‑gecodeerde tekenreeks in kleine letters is die het mediatype van de byte‑reeks weergeeft.

```csharp
public interface IBlob
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size/) { get; } | Retourneert de grootte van de byte‑reeks in aantal bytes. Bij ophalen moeten conforme gebruikersagenten het totale aantal bytes teruggeven dat gelezen kan worden door een FileReader‑ of FileReaderSync‑object, of 0 als de Blob geen bytes bevat om te lezen. |
| [Type](../../aspose.svg.io/iblob/type/) { get; } | De ASCII‑gecodeerde string in kleine letters die het mediatype van de Blob weergeeft. Bij ophalen moeten gebruikersagenten het type van een Blob retourneren als een ASCII‑gecodeerde string in kleine letters, zodanig dat wanneer deze wordt omgezet naar een byte‑reeks, het een parseerbaar MIME‑type is, of de lege string – 0 bytes – als het type niet kan worden bepaald. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice/)(*ulong, ulong, string*) | Retourneert een nieuw Blob-object met bytes die variëren van de optionele start‑parameter tot, maar exclusief, de optionele eind‑parameter, en met een type‑attribuut dat de waarde van de optionele contentType‑parameter is. |

### Zie ook

* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
