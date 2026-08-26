---
title: "IFile Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.IO.IFile Schnittstelle. Ein File-Objekt ist ein Blob-Objekt mit einem Namensattribut, das ein String ist; es kann innerhalb der Webanwendung über einen Konstruktor erstellt werden oder ist ein Verweis auf eine Byte‑Sequenz aus einer Datei des zugrunde liegenden Betriebssystem‑Dateisystems."
type: docs
weight: 4050
url: /de/net/aspose.svg.io/ifile/
---
## IFile interface

Ein File-Objekt ist ein Blob-Objekt mit einem Attribut name, das eine Zeichenkette ist; es kann innerhalb der Webanwendung über einen Konstruktor erstellt werden oder ist ein Verweis auf eine Byte-Sequenz aus einer Datei des zugrunde liegenden (OS-)Dateisystems.

```csharp
public interface IFile : IBlob
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [LastModified](../../aspose.svg.io/ifile/lastmodified/) { get; } | Das zuletzt geänderte Datum der Datei. Beim Abrufen, falls Benutzeragenten diese Information bereitstellen können, muss ein long long zurückgegeben werden, das auf die Zeit gesetzt ist, zu der die Datei zuletzt geändert wurde, angegeben in Millisekunden seit dem Unix‑Epoch. |
| [Name](../../aspose.svg.io/ifile/name/) { get; } | Der Name der Datei. Beim Abrufen muss der Name der Datei als String zurückgegeben werden. |

### Siehe auch

* interface [IBlob](../iblob/)
* namespace [Aspose.Svg.IO](../../aspose.svg.io/)
* assembly [Aspose.SVG](../../)
