---
title: "MutationRecord-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Mutations.MutationRecord class. En MutationRecord representerar en enskild DOM-mutation. Det är objektet som skickas till MutationObservers MutationCallback"
type: docs
weight: 3130
url: /sv/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

En MutationRecord representerar en enskild DOM-mutation. Det är objektet som skickas till [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Returnera de tillagda noderna. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Returnerar det lokala namnet på det ändrade attributet, och null annars. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Returnerar namnutrymmet för det ändrade attributet, och null annars. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Returnera nästa syskon till de tillagda eller borttagna noderna, eller null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | Returvärdet beror på typ. För "attributes" är det värdet på det ändrade attributet före förändringen. För "characterData" är det data från den ändrade noden före förändringen. För "childList" är det null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Returnerar föregående syskon till de tillagda eller borttagna noderna, eller null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Returnera de borttagna noderna. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Returnerar den nod som mutationen påverkade, beroende på typ. För "attributes" är det elementet vars attribut ändrades. För "characterData" är det CharacterData-noden. För "childList" är det noden vars barn ändrades. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Returnerar "attributes" om det var en attributmutation, "characterData" om det var en mutation av en CharacterData-nod och "childList" om det var en mutation av nodträdet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektets typ. |

### Se även

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
