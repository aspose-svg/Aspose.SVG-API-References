---
title: "Node.AppendChild"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Node AppendChild method. Voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst AppendChild deze van zijn huidige positie naar de nieuwe positie; er is geen vereiste om de knoop van zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd."
type: docs
weight: 170
url: /nl/net/aspose.svg.dom/node/appendchild/
---
## Node.AppendChild method

Voegt een knoop toe aan het einde van de lijst met kinderen van een opgegeven bovenliggende knoop. Als het opgegeven kind een verwijzing is naar een bestaande knoop in het document, verplaatst `AppendChild` deze van zijn huidige positie naar de nieuwe positie (er is geen vereiste om de knoop van zijn bovenliggende knoop te verwijderen voordat hij aan een andere knoop wordt toegevoegd).

Dit betekent dat een knoop niet op twee plaatsen in het document tegelijk kan staan. Dus als de knoop al een bovenliggende knoop heeft, wordt de knoop eerst verwijderd en vervolgens op de nieuwe positie toegevoegd. De [`CloneNode`](../clonenode/)‑methode kan worden gebruikt om een kopie van de knoop te maken voordat deze onder de nieuwe bovenliggende knoop wordt toegevoegd. Kopieën gemaakt met [`CloneNode`](../clonenode/) worden niet automatisch gesynchroniseerd.

```csharp
public Node AppendChild(Node node)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | Node | De knoop die moet worden toegevoegd aan de opgegeven bovenliggende knoop (meestal een element). |

### Retourwaarde

Een knoop die het toegevoegde kind is, behalve wanneer het kind een [`DocumentFragment`](../../documentfragment/) is, in dat geval wordt het lege [`DocumentFragment`](../../documentfragment/) geretourneerd.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| DOMException | Wordt gegooid wanneer de beperkingen van de DOM-boom worden geschonden. |

### Zie ook

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
