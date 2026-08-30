---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG för .NET API-referens"
description: "CustomEvent InitCustomEvent‑metod. /// InitEvent‑metoden används för att initiera värdet på ett Event som skapats via IDocumentEvent‑gränssnittet"
type: docs
weight: 30
url: /sv/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Metoden [`InitEvent`](../../event/initevent/) används för att initiera värdet på ett [`Event`](../../event/) som skapats via [`IDocumentEvent`](../../idocumentevent/)-gränssnittet.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | String | Händelsetypen. |
| bubbles | Boolean | om den är satt till `true` [bubbles]. |
| cancelable | Boolean | om den är satt till `true` [cancelable]. |
| detail | Objekt | Den anpassade datan. |

## Anmärkningar

Denna metod får endast anropas innan Event har dispatchats via metoden [`DispatchEvent`](../../ieventtarget/dispatchevent/), men den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har det sista anropet företräde. Om den anropas från en subklass av Event‑gränssnittet modifieras endast de värden som anges i initEvent‑metoden, alla andra attribut lämnas oförändrade.

### Se även

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
