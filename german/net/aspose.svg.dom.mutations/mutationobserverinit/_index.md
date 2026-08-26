---
title: "MutationObserverInit Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Mutations.MutationObserverInit Klasse. Diese Klasse stellt eine Optionssammlung dar, die verwendet wird, um MutationObserver zu konfigurieren"
type: docs
weight: 3120
url: /de/net/aspose.svg.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

Diese Klasse stellt eine Optionssammlung dar, die verwendet wird, um [`MutationObserver`](../mutationobserver/) zu konfigurieren.

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | Initialisiert eine neue Instanz der `MutationObserverInit`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttributeFilter](../../aspose.svg.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | Auf eine Liste von Attribut-Lokalisierungen (ohne Namespace) festlegen, wenn nicht alle Attributmutationen beobachtet werden müssen und attributes wahr oder weggelassen ist. |
| [AttributeOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | Auf true festlegen, wenn attributes wahr oder weggelassen ist und der Attributwert des Ziels vor der Mutation aufgezeichnet werden muss. |
| [Attributes](../../aspose.svg.dom.mutations/mutationobserverinit/attributes/) { get; set; } | Auf true festlegen, wenn Mutationen der Attribute des Ziels beobachtet werden sollen. Kann weggelassen werden, wenn attributeOldValue und/oder attributeFilter angegeben ist. |
| [CharacterData](../../aspose.svg.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | Auf true festlegen, wenn Mutationen der Daten des Ziels beobachtet werden sollen. Kann weggelassen werden, wenn characterDataOldValue angegeben ist. |
| [CharacterDataOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | Auf true festlegen, wenn characterData wahr oder weggelassen ist und die Daten des Ziels vor der Mutation aufgezeichnet werden müssen. |
| [ChildList](../../aspose.svg.dom.mutations/mutationobserverinit/childlist/) { get; set; } | Auf true festlegen, wenn Mutationen der Kindknoten des Ziels beobachtet werden sollen. |
| [Count](../../aspose.svg.dom.mutations/mutationobserverinit/count/) { get; } | Gibt die Anzahl der Schlüssel/Wert-Paare zurück, die in der `MutationObserverInit`-Sammlung enthalten sind. |
| [IsReadOnly](../../aspose.svg.dom.mutations/mutationobserverinit/isreadonly/) { get; } | Bestimmt, ob die `MutationObserverInit`-Sammlung veränderlich ist. |
| [Item](../../aspose.svg.dom.mutations/mutationobserverinit/item/) { get; set; } | Liest das Element mit dem angegebenen Schlüssel aus oder legt es fest. |
| [Keys](../../aspose.svg.dom.mutations/mutationobserverinit/keys/) { get; } | Gibt eine Sammlung zurück, die die Schlüssel in der `MutationObserverInit`-Sammlung enthält. |
| [Subtree](../../aspose.svg.dom.mutations/mutationobserverinit/subtree/) { get; set; } | Auf true festlegen, wenn Mutationen nicht nur am Ziel, sondern auch an dessen Nachkommen beobachtet werden sollen. |
| [Values](../../aspose.svg.dom.mutations/mutationobserverinit/values/) { get; } | Gibt eine Sammlung zurück, die die Werte in der `MutationObserverInit`-Sammlung enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add)(*KeyValuePair&lt;string, object&gt;*) | Fügt ein Element zur `MutationObserverInit`-Sammlung hinzu. |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add_1)(*string, object*) | Fügt den angegebenen Schlüssel und Wert zur `MutationObserverInit`-Sammlung hinzu. |
| [Clear](../../aspose.svg.dom.mutations/mutationobserverinit/clear/)() | Entfernt alle Elemente aus der `MutationObserverInit`-Sammlung. |
| [Contains](../../aspose.svg.dom.mutations/mutationobserverinit/contains/)(*KeyValuePair&lt;string, object&gt;*) | Bestimmt, ob die `MutationObserverInit` das angegebene Schlüssel/Wert-Paar enthält. |
| [ContainsKey](../../aspose.svg.dom.mutations/mutationobserverinit/containskey/)(*string*) | Bestimmt, ob die `MutationObserverInit`-Sammlung einen angegebenen Schlüssel enthält. |
| [CopyTo](../../aspose.svg.dom.mutations/mutationobserverinit/copyto/)(*KeyValuePair&lt;string, object&gt;[], int*) | Kopiert die `MutationObserverInit`-Elemente in ein vorhandenes eindimensionales Array, beginnend beim angegebenen Array-Index. |
| [GetEnumerator](../../aspose.svg.dom.mutations/mutationobserverinit/getenumerator/)() | Gibt einen Enumerator zurück, der die `MutationObserverInit`-Elemente durchläuft. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove)(*KeyValuePair&lt;string, object&gt;*) | Entfernt das angegebene Schlüssel/Wert-Paar aus der `MutationObserverInit`-Sammlung. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove_1)(*string*) | Entfernt den mit dem angegebenen Schlüssel verknüpften Wert aus der `MutationObserverInit`-Sammlung. |
| [TryGetValue](../../aspose.svg.dom.mutations/mutationobserverinit/trygetvalue/)(*string, out object*) | Liefert den mit dem angegebenen Schlüssel verknüpften Wert. |

### Siehe auch

* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
