---
title: "Event.PreventDefault"
second_title: "Aspose.SVG för .NET API-referens"
description: "Event PreventDefault-metod. Om en händelse kan avbrytas används PreventDefault-metoden för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske"
type: docs
weight: 120
url: /sv/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Om en händelse kan avbrytas används `PreventDefault`-metoden för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske.

```csharp
public void PreventDefault()
```

## Anmärkningar

Om `PreventDefault`-metoden anropas under någon fas av händelseflödet avbryts händelsen. Alla standardåtgärder som är kopplade till händelsen kommer inte att ske. Att anropa denna metod för en icke‑avbrytbar händelse har ingen effekt. När `PreventDefault` har anropats förblir den i kraft under resten av händelsens spridning. Denna metod kan användas under vilken fas som helst av händelseflödet.

### Se även

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
