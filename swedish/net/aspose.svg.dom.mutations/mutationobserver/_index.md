---
title: "MutationObserver-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Mutations.MutationObserver class. Ett MutationObserver-objekt kan användas för att observera mutationer i trädet av Node"
type: docs
weight: 3110
url: /sv/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

Ett `MutationObserver`-objekt kan användas för att observera mutationer i trädet av [`Node`](../../aspose.svg.dom/node/).

```csharp
public class MutationObserver : DOMObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Skapar ett MutationObserver-objekt och sätter dess [`MutationCallback`](../mutationcallback/) till callback. Callbacken anropas med en lista av MutationRecord-objekt som första argument och det konstruerade MutationObserver-objektet som andra argument. Den anropas efter att noder registrerade med [`Observe`](./observe/)-metoden har muterats. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | Stoppar observatören från att observera några mutationer. Tills observe()-metoden används igen kommer observatörens callback inte att anropas. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | Instruktioner till användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som anges av options (ett objekt). Argumentet options möjliggör att ställa in alternativ för mutationsobservation via objektmedlemmar. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Instruktioner till användaragenten att observera ett givet mål (en nod) och rapportera eventuella mutationer baserat på kriterierna som anges av options (ett objekt). Argumentet options möjliggör att ställa in alternativ för mutationsobservation via objektmedlemmar. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | Metoden returnerar en kopia av postkön och tömmer sedan postkön. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
