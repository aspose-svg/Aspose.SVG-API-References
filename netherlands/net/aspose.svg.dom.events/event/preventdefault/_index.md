---
title: "Event.PreventDefault"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Event PreventDefault-methode. Als een gebeurtenis annuleerbaar is, wordt de PreventDefault-methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden."
type: docs
weight: 120
url: /nl/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Als een gebeurtenis annuleerbaar is, wordt de `PreventDefault`-methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden.

```csharp
public void PreventDefault()
```

## Opmerkingen

Als tijdens een willekeurige fase van de gebeurtenisstroom de `PreventDefault`-methode wordt aangeroepen, wordt de gebeurtenis geannuleerd. Elke standaardactie die aan de gebeurtenis is gekoppeld, zal niet plaatsvinden. Het aanroepen van deze methode voor een niet‑annuleerbare gebeurtenis heeft geen effect. Zodra `PreventDefault` is aangeroepen, blijft deze van kracht gedurende de rest van de voortplanting van de gebeurtenis. Deze methode kan tijdens elke fase van de gebeurtenisstroom worden gebruikt.

### Zie ook

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
