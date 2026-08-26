---
title: "DOMTokenList-Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Collections.DOMTokenList-Klasse. Die DOMTokenList-Klasse repräsentiert eine Menge von durch Leerzeichen getrennten Tokens. Sie ist ab Index 0 indiziert, wie bei JavaScript-Array-Objekten. DOMTokenList ist stets groß-/kleinschreibungssensitiv"
type: docs
weight: 2000
url: /de/net/aspose.svg.collections/domtokenlist/
---
## DOMTokenList class

Die DOMTokenList-Klasse stellt eine Menge von durch Leerzeichen getrennten Tokens dar. Sie ist ab Index 0 indiziert, wie bei JavaScript-Array-Objekten. DOMTokenList ist stets groß-/kleinschreibungssensitiv.

```csharp
public class DOMTokenList : DOMObject, IEnumerable<string>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.svg.collections/domtokenlist/item/) { get; } | Gibt das Element in der Liste anhand seines Index zurück oder null, wenn der Index größer oder gleich der Länge der Liste ist. |
| [Length](../../aspose.svg.collections/domtokenlist/length/) { get; } | Gibt ein ulong zurück, das die Anzahl der in dieser Liste gespeicherten Tokens darstellt. |
| [Value](../../aspose.svg.collections/domtokenlist/value/) { get; set; } | Liest oder setzt den Wert eines entsprechenden Attributs. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.svg.collections/domtokenlist/add/)(*params string[]*) | Fügt das/die angegebene(n) Token zur Liste hinzu. |
| [Contains](../../aspose.svg.collections/domtokenlist/contains/)(*string*) | Gibt true zurück, wenn die Liste das angegebene Token enthält, sonst false. |
| [GetEnumerator](../../aspose.svg.collections/domtokenlist/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [Remove](../../aspose.svg.collections/domtokenlist/remove/)(*params string[]*) | Entfernt das/die angegebene(n) Token aus der Liste. |
| [Replace](../../aspose.svg.collections/domtokenlist/replace/)(*string, string*) | Ersetzt ein vorhandenes Token durch ein neues Token. Tut nichts, wenn das erste Token nicht existiert. |
| [Supports](../../aspose.svg.collections/domtokenlist/supports/)(*string*) | Gibt true zurück, wenn ein angegebenes Token zu den unterstützten Tokens des zugehörigen Attributs gehört. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle)(*string*) | Entfernt das Token aus der Liste, falls es existiert, oder fügt das Token zur Liste hinzu, falls es nicht existiert. |
| [Toggle](../../aspose.svg.collections/domtokenlist/toggle/#toggle_1)(*string, bool*) | Entfernt das Token aus der Liste, falls es existiert, oder fügt das Token zur Liste hinzu, falls es nicht existiert. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
