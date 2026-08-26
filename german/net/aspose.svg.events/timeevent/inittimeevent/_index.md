---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "TimeEvent InitTimeEvent Methode. Die initTimeEvent‑Methode wird verwendet, um den Wert eines TimeEvent zu initialisieren, das über die DocumentEvent‑Schnittstelle erstellt wurde. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent‑Methode gesendet wurde, kann jedoch in dieser Phase bei Bedarf mehrfach aufgerufen werden. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang"
type: docs
weight: 30
url: /de/net/aspose.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

Die Methode initTimeEvent wird verwendet, um den Wert eines über die DocumentEvent‑Schnittstelle erstellten TimeEvent zu initialisieren. Diese Methode darf nur aufgerufen werden, bevor das TimeEvent über die dispatchEvent‑Methode gesendet wurde, kann jedoch bei Bedarf während dieser Phase mehrfach aufgerufen werden. Wird sie mehrfach aufgerufen, hat der letzte Aufruf Vorrang.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeArg | String | Gibt den Ereignistyp an. |
| viewArg | IAbstractView | Gibt die AbstractView des Ereignisses an. |
| detailArg | Int64 | Gibt das Detail des Ereignisses an. |

### Siehe auch

* interface [IAbstractView](../../../aspose.svg.dom.views/iabstractview/)
* class [TimeEvent](../)
* namespace [Aspose.Svg.Events](../../../aspose.svg.events/)
* assembly [Aspose.SVG](../../../)
