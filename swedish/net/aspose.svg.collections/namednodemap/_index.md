---
title: "NamedNodeMap-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Collections.NamedNodeMap-klass. Representerar samlingar av attribut som kan nås via namn."
type: docs
weight: 2020
url: /sv/net/aspose.svg.collections/namednodemap/
---
## NamedNodeMap class

Representerar samlingar av attribut som kan nås via namn.

```csharp
public class NamedNodeMap : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.svg.collections/namednodemap/item/) { get; } | Returnerar det index‑te objektet i kartan. Om index är större än eller lika med antalet noder i denna karta, returneras null. (2 indexerare) |
| [Length](../../aspose.svg.collections/namednodemap/length/) { get; } | Antalet noder i denna karta. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetNamedItem](../../aspose.svg.collections/namednodemap/getnameditem/)(*string*) | Hämtar en nod som specificeras av namn. |
| [GetNamedItemNS](../../aspose.svg.collections/namednodemap/getnameditemns/)(*string, string*) | Hämtar en nod som specificeras av lokalt namn och namnrymds‑URI. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [RemoveNamedItem](../../aspose.svg.collections/namednodemap/removenameditem/)(*string*) | Tar bort en nod som specificeras av namn. |
| [RemoveNamedItemNS](../../aspose.svg.collections/namednodemap/removenameditemns/)(*string, string*) | Tar bort en nod som specificeras av lokalt namn och namnrymds‑URI. |
| [SetNamedItem](../../aspose.svg.collections/namednodemap/setnameditem/)(*[Attr](../../aspose.svg.dom/attr/)*) | Lägger till en nod med dess nodeName-attribut. Om en nod med det namnet redan finns i denna karta, ersätts den av den nya. Att ersätta en nod med sig själv har ingen effekt. |
| [SetNamedItemNS](../../aspose.svg.collections/namednodemap/setnameditemns/)(*[Attr](../../aspose.svg.dom/attr/)*) | Lägger till en nod med dess namespaceURI och localName. Om en nod med den namespaceURI:n och det lokala namnet redan finns i den här kartan, ersätts den med den nya. Att ersätta en nod med sig själv har ingen effekt. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Collections](../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../)
