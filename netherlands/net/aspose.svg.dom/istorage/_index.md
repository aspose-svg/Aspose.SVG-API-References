---
title: "IStorage Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.IStorage interface. Deze interface van de Web Storage API biedt toegang tot de sessie‑ of lokale opslag van een bepaald domein. Zie de Web Storage-specificatie https//html.spec.whatwg.org/multipage/webstorage.htmlwebstorage"
type: docs
weight: 3090
url: /nl/net/aspose.svg.dom/istorage/
---
## IStorage interface

Deze interface van de Web Storage‑API biedt toegang tot de sessie‑ of lokale opslag van een bepaald domein. Zie de Web Storage‑specificatie: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage)

```csharp
public interface IStorage
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Length](../../aspose.svg.dom/istorage/length/) { get; } | Retourneert het aantal sleutel/waarde‑paren. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clear](../../aspose.svg.dom/istorage/clear/)() | Verwijdert alle sleutel/waarde‑paren, indien aanwezig. |
| [GetItem](../../aspose.svg.dom/istorage/getitem/)(*string*) | Retourneert de huidige waarde die aan de opgegeven sleutel is gekoppeld, of null als de opgegeven sleutel niet bestaat. |
| [Key](../../aspose.svg.dom/istorage/key/)(*long*) | Retourneert de naam van de n‑de sleutel, of null als n groter dan of gelijk is aan het aantal sleutel/waarde‑paren. |
| [RemoveItem](../../aspose.svg.dom/istorage/removeitem/)(*string*) | Verwijdert het sleutel/waarde‑paar met de opgegeven sleutel, als een dergelijk paar bestaat. |
| [SetItem](../../aspose.svg.dom/istorage/setitem/)(*string, string*) | Stelt de waarde van het door sleutel geïdentificeerde paar in op waarde, en maakt een nieuw sleutel/waarde‑paar aan als er eerder geen paar voor die sleutel bestond. |

### Zie ook

* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
