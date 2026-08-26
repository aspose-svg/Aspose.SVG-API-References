---
title: "IMediaList Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.IMediaList Schnittstelle. Die MediaList‑Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist dasselbe wie eine Liste, die das Medium all enthält."
type: docs
weight: 2730
url: /de/net/aspose.svg.dom.css/imedialist/
---
## IMediaList interface

Die MediaList-Schnittstelle bietet die Abstraktion einer geordneten Sammlung von Medien, ohne zu definieren oder einzuschränken, wie diese Sammlung implementiert wird. Eine leere Liste ist dasselbe wie eine Liste, die das Medium "all" enthält.

```csharp
public interface IMediaList : IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.svg.dom.css/imedialist/item/) { get; } | Gibt das Element mit dem angegebenen Index in der Liste zurück. Wenn index größer oder gleich der Anzahl der Medien in der Liste ist, wird null zurückgegeben. Der Medien‑Index. |
| [Length](../../aspose.svg.dom.css/imedialist/length/) { get; } | Die Anzahl der Medien in der Liste. Der gültige Bereich für Medien ist 0 bis Länge‑1 inklusive. |
| [MediaText](../../aspose.svg.dom.css/imedialist/mediatext/) { get; } | Die parsbare Textdarstellung der Medienliste. Dies ist eine kommagetrennte Liste von Medien. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendMedium](../../aspose.svg.dom.css/imedialist/appendmedium/)(*string*) | Fügt das Medium newMedium am Ende der Liste hinzu. Wenn newMedium bereits verwendet wird, wird es zuerst entfernt. |
| [DeleteMedium](../../aspose.svg.dom.css/imedialist/deletemedium/)(*string*) | Löscht das durch oldMedium angegebene Medium aus der Liste. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
