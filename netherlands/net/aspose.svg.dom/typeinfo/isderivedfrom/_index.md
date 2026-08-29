---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "TypeInfo IsDerivedFrom methode. Deze methode geeft terug of er een afleiding bestaat tussen de referentietype-definitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere type-definitie, d.w.z. diegene die als parameter wordt doorgegeven"
type: docs
weight: 30
url: /nl/net/aspose.svg.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Deze methode geeft terug of er een afleiding bestaat tussen de referentietype-definitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere type-definitie, d.w.z. degene die als parameter wordt doorgegeven.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeNamespaceArg | String | de namespace van de andere type-definitie |
| typeNameArg | String | de naam van de andere type-definitie. |
| derivationMethod | UInt64 | het type afleiding en de voorwaarden die tussen twee typen worden toegepast, zoals beschreven in de lijst met constanten die in deze interface wordt geleverd. |

### Retourwaarde

Als het schema van het document een DTD is of er geen schema aan het document is gekoppeld, zal deze methode altijd false retourneren. Als het schema van het document een XML‑schema is, zal de methode true retourneren als de referentietypedefinitie is afgeleid van de andere typedefinitie volgens de afleidingsparameter. Als de waarde van de parameter 0 is (geen bit is ingesteld op 1 voor de derivationMethod‑parameter), zal de methode true retourneren als de andere typedefinitie kan worden bereikt door recursief elke combinatie van {base type definition}, {item type definition} of {member type definitions} vanuit de referentietypedefinitie te doorlopen.

### Zie ook

* class [TypeInfo](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
