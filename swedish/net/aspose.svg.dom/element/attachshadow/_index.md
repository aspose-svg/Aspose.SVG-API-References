---
title: "Element.AttachShadow"
second_title: "Aspose.SVG för .NET API-referens"
description: "Element AttachShadow metod. Skapar en shadow root och fäster den till det aktuella elementet"
type: docs
weight: 220
url: /sv/net/aspose.svg.dom/element/attachshadow/
---
## Element.AttachShadow method

Skapar ett shadow root och fäster det på det aktuella elementet.

```csharp
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mode | ShadowRootMode | Läge i vilket shadow root kommer att skapas. |

### Returvärde

Skapad [`ShadowRoot`](../../shadowroot/).

### Undantag

| undantag | villkor |
| --- | --- |
| Fel | NotSupportedError: Element stöder inte shadow tree. |
| Fel | InvalidStateError: Element har redan en shadow tree. |

### Se även

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
