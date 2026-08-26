---
title: "Event.InitEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Event InitEvent Methode. Die InitEvent-Methode wird verwendet, um den Wert eines über die IDocumentEvent-Schnittstelle erstellten Ereignisses zu initialisieren."
type: docs
weight: 110
url: /de/net/aspose.svg.dom.events/event/initevent/
---
## Event.InitEvent method

Die `InitEvent`-Methode wird verwendet, um den Wert eines [`Event`](../) zu initialisieren, das über die [`IDocumentEvent`](../../idocumentevent/) Schnittstelle erstellt wurde.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp. |
| bubbles | Boolean | wenn auf `true` gesetzt [bubbles]. |
| cancelable | Boolean | wenn auf `true` gesetzt [cancelable]. |

## Hinweise

Diese Methode darf nur aufgerufen werden, bevor das Event über die [`DispatchEvent`](../../ieventtarget/dispatchevent/)‑Methode ausgelöst wurde, obwohl sie bei Bedarf während dieser Phase mehrfach aufgerufen werden kann. Bei mehrfachen Aufrufen hat der letzte Aufruf Vorrang. Wird sie von einer Unterklasse der Event‑Schnittstelle aufgerufen, werden nur die im initEvent‑Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
