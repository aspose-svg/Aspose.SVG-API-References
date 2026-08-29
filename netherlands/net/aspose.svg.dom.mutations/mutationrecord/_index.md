---
title: "MutationRecord Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Mutations.MutationRecord klasse. Een MutationRecord vertegenwoordigt een individuele DOM-mutatie. Het is het object dat wordt doorgegeven aan de MutationCallback van MutationObservers."
type: docs
weight: 3130
url: /nl/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

Een MutationRecord vertegenwoordigt een individuele DOM-mutatie. Het is het object dat wordt doorgegeven aan de [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/).

```csharp
public class MutationRecord : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Geef de toegevoegde knooppunten terug. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Retourneert de lokale naam van het gewijzigde attribuut, en anders null. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Retourneert de namespace van het gewijzigde attribuut, en anders null. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Geef de volgende sibling van de toegevoegde of verwijderde knooppunten terug, of null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | De retourwaarde hangt af van het type. Voor "attributes" is het de waarde van het gewijzigde attribuut vóór de wijziging. Voor "characterData" is het de data van het gewijzigde knooppunt vóór de wijziging. Voor "childList" is het null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Retourneert de vorige sibling van de toegevoegde of verwijderde knooppunten, of null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Geef de verwijderde knooppunten terug. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Retourneert het knooppunt dat door de mutatie werd beïnvloed, afhankelijk van het type. Voor "attributes" is het het element waarvan het attribuut is gewijzigd. Voor "characterData" is het het CharacterData-knooppunt. Voor "childList" is het het knooppunt waarvan de kinderen zijn gewijzigd. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Retourneert "attributes" als het een attribuutmutatie was, "characterData" als het een mutatie van een CharacterData-knooppunt was en "childList" als het een mutatie van de knooptree was. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
