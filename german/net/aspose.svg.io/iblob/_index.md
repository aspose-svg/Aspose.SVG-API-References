---
title: "IBlob Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.IO.IBlob Schnittstelle. Ein Blob-Objekt bezieht sich auf eine Byte‑Sequenz und hat ein Größenattribut, das die Gesamtzahl der Bytes in der Byte‑Sequenz angibt, sowie ein Typ‑Attribut, das ein ASCII‑kodierter String in Kleinbuchstaben ist und den Medientyp der Byte‑Sequenz darstellt."
type: docs
weight: 4030
url: /de/net/aspose.svg.io/iblob/
---
## IBlob interface

Ein Blob-Objekt bezieht sich auf eine Byte-Sequenz und hat ein Attribut size, das die Gesamtzahl der Bytes in der Sequenz angibt, sowie ein Attribut type, das eine ASCII-kodierte Zeichenkette in Kleinbuchstaben darstellt, die den Medientyp der Byte‑Sequenz repräsentiert.

```csharp
public interface IBlob
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Size](../../aspose.svg.io/iblob/size/) { get; } | Gibt die Größe der Byte‑Sequenz in Bytes zurück. Beim Abrufen müssen konforme Benutzeragenten die Gesamtzahl der Bytes zurückgeben, die von einem FileReader‑ oder FileReaderSync‑Objekt gelesen werden können, oder 0, wenn der Blob keine zu lesenden Bytes enthält. |
| [Type](../../aspose.svg.io/iblob/type/) { get; } | Der ASCII‑kodierte String in Kleinbuchstaben, der den Medientyp des Blob darstellt. Beim Abrufen müssen Benutzeragenten den Typ eines Blob als ASCII‑kodierten String in Kleinbuchstaben zurückgeben, sodass er, wenn er in eine Byte‑Sequenz konvertiert wird, ein parsbarer MIME‑Typ ist, oder den leeren String – 0 Bytes – wenn der Typ nicht bestimmt werden kann. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Slice](../../aspose.svg.io/iblob/slice/)(*ulong, ulong, string*) | Gibt ein neues Blob‑Objekt zurück, dessen Bytes vom optionalen Start‑Parameter bis (aber nicht einschließlich) dem optionalen End‑Parameter reichen, und dessen Typ‑Attribut den Wert des optionalen contentType‑Parameters hat. |

### Siehe auch

* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
