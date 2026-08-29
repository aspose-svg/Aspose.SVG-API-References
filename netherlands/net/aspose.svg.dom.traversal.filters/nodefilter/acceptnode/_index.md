---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "NodeFilter AcceptNode method. Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; normaal wordt hij niet direct vanuit gebruikerscode aangeroepen. Je kunt dit echter wel doen als je dezelfde filter wilt gebruiken om je eigen toepassingslogica te sturen."
type: docs
weight: 10
url: /nl/net/aspose.svg.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dat wel kunt doen als je dezelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.)

```csharp
public abstract short AcceptNode(Node n)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| n | Node | knooppunt om te controleren of het door het filter komt of niet. |

### Retourwaarde

een constante om te bepalen of het knooppunt wordt geaccepteerd, afgewezen of overgeslagen, zoals hierboven gedefinieerd.

### Zie ook

* class [Node](../../../aspose.svg.dom/node/)
* class [NodeFilter](../)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../../)
