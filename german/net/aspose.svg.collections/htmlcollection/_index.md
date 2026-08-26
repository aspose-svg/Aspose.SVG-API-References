---
title: "HTMLCollection Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Collections.HTMLCollection Klasse. Die HTMLCollection stellt eine generische Sammlung von Element dar"
type: docs
weight: 2010
url: /de/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

Die `HTMLCollection` stellt eine generische Sammlung von [`Element`](../../aspose.svg.dom/element/) dar.

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | Gibt das Element an der Index‑Position in der Sammlung zurück. Wenn der Index größer oder gleich der Anzahl der Knoten in der Liste ist, wird null zurückgegeben. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | Die Anzahl der Knoten in der Liste. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | Liefert den Enumerator. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | Gibt das Element in der Sammlung zurück, das dem angegebenen Namen entspricht. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
