---
title: "MutationObserver Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Mutations.MutationObserver klasse. Een MutationObserver-object kan worden gebruikt om mutaties in de boom van Node te observeren."
type: docs
weight: 3110
url: /nl/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

Een `MutationObserver`-object kan worden gebruikt om mutaties in de boom van [`Node`](../../aspose.svg.dom/node/) te observeren.

```csharp
public class MutationObserver : DOMObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Construeert een MutationObserver-object en stelt zijn [`MutationCallback`](../mutationcallback/) in op callback. De callback wordt aangeroepen met een lijst van MutationRecord-objecten als eerste argument en het geconstrueerde MutationObserver-object als tweede argument. Het wordt aangeroepen nadat knooppunten die zijn geregistreerd met de [`Observe`](./observe/)-methode, zijn gemuteerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | Stopt de observer met het observeren van mutaties. Totdat de observe()‑methode opnieuw wordt gebruikt, wordt de callback van de observer niet aangeroepen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | Instrueert de user agent om een gegeven doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria die zijn opgegeven door opties (een object). Het opties‑argument maakt het mogelijk om mutatie‑observatie‑opties in te stellen via object‑leden. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Instrueert de user agent om een gegeven doel (een knooppunt) te observeren en eventuele mutaties te rapporteren op basis van de criteria die zijn opgegeven door opties (een object). Het opties‑argument maakt het mogelijk om mutatie‑observatie‑opties in te stellen via object‑leden. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | De methode retourneert een kopie van de record‑wachtrij en maakt vervolgens de record‑wachtrij leeg. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
