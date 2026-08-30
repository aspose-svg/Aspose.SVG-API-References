---
title: "Document.GetElementById"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document GetElementById‑metoden. Denna metod returnerar ett Element‑objekt som representerar det element vars id‑egenskap matchar den angivna strängen. Eftersom element‑ID:n måste vara unika om de anges är de ett användbart sätt att snabbt få åtkomst till ett specifikt element."
type: docs
weight: 960
url: /sv/net/aspose.svg.dom/document/getelementbyid/
---
## Document.GetElementById method

Denna metod returnerar ett [`Element`](../../element/)‑objekt som representerar det element vars id‑egenskap matchar den angivna strängen. Eftersom element‑ID:n måste vara unika om de anges är de ett användbart sätt att snabbt få åtkomst till ett specifikt element.

Om du behöver komma åt ett element som inte har ett ID kan du använda [`QuerySelector`](../queryselector/) för att hitta elementet med valfri selector.

```csharp
public Element GetElementById(string elementId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| elementId | String | ID:t för elementet som ska lokaliseras. ID:t är en skiftlägeskänslig sträng som är unik inom dokumentet; endast ett element kan ha ett givet ID. |

### Returvärde

Ett [`Element`](../../element/)‑objekt som beskriver DOM‑elementet som matchar det angivna ID:t, eller null om inget matchande element hittades i dokumentet.

## Anmärkningar

Se den officiella [spec](https://dom.spec.whatwg.org/#dom-nonelementparentnode-getelementbyid).

### Se även

* class [Element](../../element/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
