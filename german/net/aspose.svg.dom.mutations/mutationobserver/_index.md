---
title: "MutationObserver Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Mutations.MutationObserver Klasse. Ein MutationObserver-Objekt kann verwendet werden, um Mutationen am Baum von Node zu beobachten."
type: docs
weight: 3110
url: /de/net/aspose.svg.dom.mutations/mutationobserver/
---
## MutationObserver class

Ein `MutationObserver`‑Objekt kann verwendet werden, um Mutationen am Baum von [`Node`](../../aspose.svg.dom/node/) zu beobachten.

```csharp
public class MutationObserver : DOMObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MutationObserver](mutationobserver/)(*[MutationCallback](../mutationcallback/)*) | Konstruiert ein MutationObserver‑Objekt und setzt dessen [`MutationCallback`](../mutationcallback/) auf callback. Der Callback wird mit einer Liste von MutationRecord‑Objekten als erstem Argument und dem konstruierten MutationObserver‑Objekt als zweitem Argument aufgerufen. Er wird aufgerufen, nachdem die mit der [`Observe`](./observe/)-Methode registrierten Knoten mutiert wurden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Disconnect](../../aspose.svg.dom.mutations/mutationobserver/disconnect/)() | Stoppt den Beobachter daran, irgendwelche Mutationen zu beobachten. Bis die observe()-Methode erneut verwendet wird, wird der Callback des Beobachters nicht aufgerufen. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe)(*[Node](../../aspose.svg.dom/node/)*) | Weist den User‑Agent an, ein angegebenes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch die Optionen (ein Objekt) angegebenen Kriterien zu melden. Das options‑Argument ermöglicht das Festlegen von Beobachtungsoptionen für Mutationen über Objektmitglieder. |
| [Observe](../../aspose.svg.dom.mutations/mutationobserver/observe/#observe_1)(*[Node](../../aspose.svg.dom/node/), [MutationObserverInit](../mutationobserverinit/)*) | Weist den User‑Agent an, ein angegebenes Ziel (einen Knoten) zu beobachten und alle Mutationen basierend auf den durch die Optionen (ein Objekt) angegebenen Kriterien zu melden. Das options‑Argument ermöglicht das Festlegen von Beobachtungsoptionen für Mutationen über Objektmitglieder. |
| [TakeRecords](../../aspose.svg.dom.mutations/mutationobserver/takerecords/)() | Die Methode gibt eine Kopie der Aufzeichnungswarteschlange zurück und leert anschließend die Aufzeichnungswarteschlange. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
