---
title: "HTMLCollection-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Collections.HTMLCollection-klass. HTMLCollection representerar en generisk samling av Element"
type: docs
weight: 2010
url: /sv/net/aspose.svg.collections/htmlcollection/
---
## HTMLCollection class

`HTMLCollection` representerar en generisk samling av [`Element`](../../aspose.svg.dom/element/).

```csharp
public abstract class HTMLCollection : DOMObject, IEnumerable<Element>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| abstract [Item](../../aspose.svg.collections/htmlcollection/item/) { get; } | Returnerar det index‑te objektet i samlingen. Om index är större än eller lika med antalet noder i listan, returneras null. |
| abstract [Length](../../aspose.svg.collections/htmlcollection/length/) { get; } | Antalet noder i listan. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| abstract [GetEnumerator](../../aspose.svg.collections/htmlcollection/getenumerator/)() | Hämtar enumeratorn. |
| override [GetPlatformType](../../aspose.svg.collections/htmlcollection/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objekttyp. |
| [NamedItem](../../aspose.svg.collections/htmlcollection/nameditem/)(*string*) | Returnerar objektet i samlingen som matchar det angivna namnet. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* class [Element](../../aspose.svg.dom/element/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
