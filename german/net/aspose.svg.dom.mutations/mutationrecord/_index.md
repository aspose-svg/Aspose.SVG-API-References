---
title: "MutationRecord Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Mutations.MutationRecord Klasse. Ein MutationRecord stellt eine einzelne DOM-Mutation dar. Es ist das Objekt, das an den MutationObservers MutationCallback übergeben wird."
type: docs
weight: 3130
url: /de/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

Ein MutationRecord stellt eine einzelne DOM-Mutation dar. Es ist das Objekt, das an den [`MutationObserver`](../mutationobserver/)'s [`MutationCallback`](../mutationcallback/) übergeben wird.

```csharp
public class MutationRecord : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Gib die hinzugefügten Knoten zurück. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Gibt den lokalen Namen des geänderten Attributs zurück, andernfalls null. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Gibt den Namespace des geänderten Attributs zurück, andernfalls null. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Gib das nächste Geschwisterelement der hinzugefügten oder entfernten Knoten zurück, oder null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | Der Rückgabewert hängt vom Typ ab. Für "attributes" ist es der Wert des geänderten Attributs vor der Änderung. Für "characterData" sind es die Daten des geänderten Knotens vor der Änderung. Für "childList" ist er null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Gibt das vorherige Geschwisterelement der hinzugefügten oder entfernten Knoten zurück, oder null. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Gib die entfernten Knoten zurück. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Gibt den Knoten zurück, den die Mutation betroffen hat, abhängig vom Typ. Für "attributes" ist es das Element, dessen Attribut geändert wurde. Für "characterData" ist es der CharacterData‑Knoten. Für "childList" ist es der Knoten, dessen Kinder geändert wurden. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Gibt "attributes" zurück, wenn es sich um eine Attributmutation handelte, "characterData", wenn es eine Mutation an einem CharacterData‑Knoten war, und "childList", wenn es eine Mutation am Knotenbaum war. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
