---
title: "ComponentTransferType Enum"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.ComponentTransferType enum. Specificeert het type componentoverdrachtsfunctie dat moet worden toegepast in de FeComponentTransfer-filterprimitief van een SVG"
type: docs
weight: 170
url: /nl/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

Specificeert het type componentoverdrachtsfunctie dat moet worden toegepast in de FeComponentTransfer-filterprimitive van een SVG.

```csharp
public enum ComponentTransferType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Identity | `0` | Stelt geen wijziging in de invoergrafiek voor. Dit is het standaardtype. |
| Table | `1` | Gebruikt een opzoektabel om de functie binnen het filter te definiëren. |
| Discrete | `2` | Gebruikt een reeks discrete waarden om de functie in het filter te definiëren. |
| Linear | `3` | Definieert een lineaire transformatie van het component binnen het filter. |
| Gamma | `4` | Definieert een gamma-correctietransformatie in het filter. |

## Opmerkingen

De FeComponentTransfer filter‑primitive maakt individuele manipulatie van kleurcomponenten (RGB en alfa) van grafische elementen mogelijk met verschillende soorten overdrachtsfuncties. Elk type definieert een aparte berekeningsmethode voor kleurcomponenttransformatie binnen de filter.

### Zie ook

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
