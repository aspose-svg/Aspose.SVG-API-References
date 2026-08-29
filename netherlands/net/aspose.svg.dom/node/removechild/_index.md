---
title: "Node.RemoveChild"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Node RemoveChild‑methode. Verwijdert een kindknoop uit de DOM en retourneert de verwijderde knoop."
type: docs
weight: 270
url: /nl/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

Verwijdert een kindknooppunt uit de DOM en retourneert het verwijderde knooppunt.

Opmerking: Zolang er een referentie naar het verwijderde kind wordt bewaard, bestaat het nog in het geheugen, maar maakt het geen deel meer uit van de DOM. Het kan later in de code opnieuw worden gebruikt. Als de retourwaarde van `RemoveChild` niet wordt opgeslagen en er geen andere referentie wordt bewaard, wordt het automatisch uit het geheugen verwijderd na een korte tijd.

```csharp
public Node RemoveChild(Node child)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| child | Node | Een [`Node`](../) die de kindknoop is die uit de DOM moet worden verwijderd. |

### Retourwaarde

In tegenstelling tot [`CloneNode`](../clonenode/) behoudt de retourwaarde de [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/)‑objecten die eraan gekoppeld zijn.

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
