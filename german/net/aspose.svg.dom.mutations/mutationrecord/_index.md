---
title: Class MutationRecord
second_title: Aspose.SVG für .NET-API-Referenz
description: Aspose.Svg.Dom.Mutations.MutationRecord klas. Ein MutationRecord repräsentiert eine einzelne DOMMutation. Es ist das Objekt an das übergeben wirdMutationObserver SMutationCallback .
type: docs
weight: 1140
url: /de/net/aspose.svg.dom.mutations/mutationrecord/
---
## MutationRecord class

Ein MutationRecord repräsentiert eine einzelne DOM-Mutation. Es ist das Objekt, an das übergeben wird[`MutationObserver`](../mutationobserver/) S[`MutationCallback`](../mutationcallback/) .

```csharp
public class MutationRecord : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AddedNodes](../../aspose.svg.dom.mutations/mutationrecord/addednodes/) { get; } | Gibt die hinzugefügten Knoten zurück. |
| [AttributeName](../../aspose.svg.dom.mutations/mutationrecord/attributename/) { get; } | Gibt den lokalen Namen des geänderten Attributs zurück, andernfalls null. |
| [AttributeNamespace](../../aspose.svg.dom.mutations/mutationrecord/attributenamespace/) { get; } | Gibt den Namespace des geänderten Attributs zurück, andernfalls null. |
| [NextSibling](../../aspose.svg.dom.mutations/mutationrecord/nextsibling/) { get; } | Gibt das nächste gleichgeordnete Element der hinzugefügten oder entfernten Knoten zurück oder null. |
| [OldValue](../../aspose.svg.dom.mutations/mutationrecord/oldvalue/) { get; } | Der Rückgabewert ist typabhängig. Bei „attributes“ ist es der Wert des geänderten Attributs vor der Änderung. Bei „characterData“ sind es die Daten des geänderten Knotens vor der Änderung. Bei „childList“ ist es null. |
| [PreviousSibling](../../aspose.svg.dom.mutations/mutationrecord/previoussibling/) { get; } | Gibt das vorherige gleichgeordnete Element der hinzugefügten oder entfernten Knoten oder null zurück. |
| [RemovedNodes](../../aspose.svg.dom.mutations/mutationrecord/removednodes/) { get; } | Gibt die entfernten Knoten zurück. |
| [Target](../../aspose.svg.dom.mutations/mutationrecord/target/) { get; } | Gibt je nach Typ den von der Mutation betroffenen Knoten zurück. Bei „Attributen“ ist es das Element, dessen Attribut sich geändert hat. Für "characterData" ist es der CharacterData-Knoten. Bei „childList“ ist es der Knoten, dessen Kinder sich geändert haben. |
| [Type](../../aspose.svg.dom.mutations/mutationrecord/type/) { get; } | Gibt „attributes“ zurück, wenn es sich um eine Attributmutation handelte, „characterData“, wenn es sich um eine Mutation zu einem CharacterData-Knoten handelte, und „childList“, wenn es sich um eine Mutation zum Knotenbaum handelte. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird zum Abrufen des ECMAScript-Objekts verwendetType . |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namensraum [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* Montage [Aspose.SVG](../../)


