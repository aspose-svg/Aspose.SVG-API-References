---
title: "MutationObserverInit-klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Mutations.MutationObserverInit class. Denna klass representerar en samling av alternativ som används för att konfigurera MutationObserver"
type: docs
weight: 3120
url: /sv/net/aspose.svg.dom.mutations/mutationobserverinit/
---
## MutationObserverInit class

Denna klass representerar en samling av alternativ som används för att konfigurera [`MutationObserver`](../mutationobserver/).

```csharp
public class MutationObserverInit : IDictionary<string, object>
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [MutationObserverInit](mutationobserverinit/)() | Initierar en ny instans av klassen `MutationObserverInit`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttributeFilter](../../aspose.svg.dom.mutations/mutationobserverinit/attributefilter/) { get; set; } | Ställ in till en lista med attributens lokala namn (utan namnrymd) om inte alla attributmutationer behöver observeras och attribut är true eller utelämnat. |
| [AttributeOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/attributeoldvalue/) { get; set; } | Ställ in till true om attribut är true eller utelämnat och målobjektets attributvärde före mutationen måste registreras. |
| [Attributes](../../aspose.svg.dom.mutations/mutationobserverinit/attributes/) { get; set; } | Ställ in till true om mutationer av målobjektets attribut ska observeras. Kan utelämnas om attributeOldValue och/eller attributeFilter anges. |
| [CharacterData](../../aspose.svg.dom.mutations/mutationobserverinit/characterdata/) { get; set; } | Ställ in till true om mutationer av målobjektets data ska observeras. Kan utelämnas om characterDataOldValue anges. |
| [CharacterDataOldValue](../../aspose.svg.dom.mutations/mutationobserverinit/characterdataoldvalue/) { get; set; } | Ställ in till true om characterData är true eller utelämnat och målobjektets data före mutationen måste registreras. |
| [ChildList](../../aspose.svg.dom.mutations/mutationobserverinit/childlist/) { get; set; } | Ställ in till true om mutationer av målobjektets barn ska observeras. |
| [Count](../../aspose.svg.dom.mutations/mutationobserverinit/count/) { get; } | Hämtar antalet nyckel/värde-par som finns i samlingen `MutationObserverInit`. |
| [IsReadOnly](../../aspose.svg.dom.mutations/mutationobserverinit/isreadonly/) { get; } | Avgör om samlingen `MutationObserverInit` är muterbar. |
| [Item](../../aspose.svg.dom.mutations/mutationobserverinit/item/) { get; set; } | Hämtar eller anger elementet med den angivna nyckeln. |
| [Keys](../../aspose.svg.dom.mutations/mutationobserverinit/keys/) { get; } | Hämtar en samling som innehåller nycklarna i `MutationObserverInit`-samlingen. |
| [Subtree](../../aspose.svg.dom.mutations/mutationobserverinit/subtree/) { get; set; } | Ställ in till true om mutationer inte bara på målobjektet utan även på målobjektets underordnade ska observeras |
| [Values](../../aspose.svg.dom.mutations/mutationobserverinit/values/) { get; } | Hämtar en samling som innehåller värdena i `MutationObserverInit`-samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add)(*KeyValuePair&lt;string, object&gt;*) | Lägger till ett element i `MutationObserverInit`-samlingen. |
| [Add](../../aspose.svg.dom.mutations/mutationobserverinit/add/#add_1)(*string, object*) | Lägger till den angivna nyckeln och värdet i `MutationObserverInit`-samlingen. |
| [Clear](../../aspose.svg.dom.mutations/mutationobserverinit/clear/)() | Tar bort alla element från `MutationObserverInit`-samlingen. |
| [Contains](../../aspose.svg.dom.mutations/mutationobserverinit/contains/)(*KeyValuePair&lt;string, object&gt;*) | Avgör om `MutationObserverInit` innehåller det angivna nyckel/värde-paret. |
| [ContainsKey](../../aspose.svg.dom.mutations/mutationobserverinit/containskey/)(*string*) | Avgör om `MutationObserverInit`-samlingen innehåller en angiven nyckel. |
| [CopyTo](../../aspose.svg.dom.mutations/mutationobserverinit/copyto/)(*KeyValuePair&lt;string, object&gt;[], int*) | Kopierar `MutationObserverInit`-elementen till en befintlig endimensionell array, med start vid det angivna arrayindexet. |
| [GetEnumerator](../../aspose.svg.dom.mutations/mutationobserverinit/getenumerator/)() | Returnerar en enumerator som itererar igenom `MutationObserverInit`-elementen. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove)(*KeyValuePair&lt;string, object&gt;*) | Tar bort det angivna nyckel/värde-paret från `MutationObserverInit`-samlingen. |
| [Remove](../../aspose.svg.dom.mutations/mutationobserverinit/remove/#remove_1)(*string*) | Tar bort värdet som är associerat med den angivna nyckeln från `MutationObserverInit`-samlingen. |
| [TryGetValue](../../aspose.svg.dom.mutations/mutationobserverinit/trygetvalue/)(*string, out object*) | Hämtar värdet som är associerat med den angivna nyckeln. |

### Se även

* namespace [Aspose.Svg.Dom.Mutations](../../aspose.svg.dom.mutations/)
* assembly [Aspose.SVG](../../)
