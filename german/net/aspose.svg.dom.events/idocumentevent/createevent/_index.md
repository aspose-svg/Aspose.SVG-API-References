---
title: IDocumentEvent.CreateEvent
second_title: Aspose.SVG für .NET-API-Referenz
description: IDocumentEvent methode. Erstellt eineEvent eines Typs der von der Implementierung unterstützt wird.
type: docs
weight: 10
url: /de/net/aspose.svg.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Erstellt eine[`Event`](../../event/) eines Typs, der von der Implementierung unterstützt wird.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der eventType-Parameter gibt den Typ von an[`Event`](../../event/) zu erstellende Schnittstelle.  Wenn die[`Event`](../../event/)Die angegebene Schnittstelle wird von der Implementierung unterstützt. Diese Methode gibt ein new zurück.[`Event`](../../event/) des angeforderten Schnittstellentyps. Wenn die[`Event`](../../event/)soll per versendet werden[`DispatchEvent`](../../../aspose.svg.dom/eventtarget/dispatchevent/) Methode die entsprechende [`InitEvent`](../../event/initevent/) -Methode muss nach der Erstellung aufgerufen werden, um die zu initialisieren[`Event`](../../event/) s-Werte. |

### Rückgabewert

Die neu erstellte[`Event`](../../event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den Typ von nicht unterstützt[`Event`](../../event/) Schnittstelle angefordert |

### Siehe auch

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namensraum [Aspose.Svg.Dom.Events](../../idocumentevent/)
* Montage [Aspose.SVG](../../../)


