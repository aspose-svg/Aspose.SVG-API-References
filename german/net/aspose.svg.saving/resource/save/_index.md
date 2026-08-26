---
title: "Resource.Save"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Resource Save Methode. Speichert die Ressource im bereitgestellten Stream."
type: docs
weight: 70
url: /de/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

Speichert die Ressource in den bereitgestellten Stream.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Strom | Der Stream, in dem die Ressource gespeichert wird. |
| context | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Diese Ressource, damit Sie Aufrufe verketten können.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Ausgelöst, wenn [`OutputUrl`](../outputurl/) `null` ist. [`OutputUrl`](../outputurl/) sollte vor dem Speichern der Ressource angegeben werden, da sonst die korrekte Referenz in den Ressourcen, die diese referenzieren, nicht angegeben werden kann. |

### Siehe auch

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
