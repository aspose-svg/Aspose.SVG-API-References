---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "CustomEvent InitCustomEvent Methode. /// Die InitEvent‑Methode wird verwendet, um den Wert eines über die IDocumentEvent‑Schnittstelle erstellten Ereignisses zu initialisieren."
type: docs
weight: 30
url: /de/net/aspose.svg.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// Die [`InitEvent`](../../event/initevent/) Methode wird verwendet, um den Wert eines [`Event`](../../event/) zu initialisieren, das über die [`IDocumentEvent`](../../idocumentevent/) Schnittstelle erstellt wurde.

```csharp
public void InitCustomEvent(string type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | String | Der Ereignistyp. |
| bubbles | Boolean | wenn auf `true` gesetzt [bubbles]. |
| cancelable | Boolean | wenn auf `true` gesetzt [cancelable]. |
| detail | Objekt | Die benutzerdefinierten Daten. |

## Hinweise

Diese Methode darf nur aufgerufen werden, bevor das Event über die [`DispatchEvent`](../../ieventtarget/dispatchevent/)‑Methode ausgelöst wurde, obwohl sie bei Bedarf während dieser Phase mehrfach aufgerufen werden kann. Bei mehrfachen Aufrufen hat der letzte Aufruf Vorrang. Wird sie von einer Unterklasse der Event‑Schnittstelle aufgerufen, werden nur die im initEvent‑Methode angegebenen Werte geändert, alle anderen Attribute bleiben unverändert.

### Siehe auch

* class [CustomEvent](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
