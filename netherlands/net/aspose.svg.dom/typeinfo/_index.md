---
title: "TypeInfo Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.TypeInfo klasse. De TypeInfo vertegenwoordigt een type dat wordt gerefereerd vanuit Element- of Attr-knooppunten gespecificeerd in de schema's die aan het document zijn gekoppeld"
type: docs
weight: 3280
url: /nl/net/aspose.svg.dom/typeinfo/
---
## TypeInfo class

De TypeInfo stelt een type voor dat wordt gerefereerd vanuit Element‑ of Attr‑knooppunten, gespecificeerd in de schema's die aan het document zijn gekoppeld.

```csharp
public class TypeInfo : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [TypeName](../../aspose.svg.dom/typeinfo/typename/) { get; } | De naam van een type dat is gedeclareerd voor het gekoppelde element of attribuut, of null als onbekend. |
| [TypeNamespace](../../aspose.svg.dom/typeinfo/typenamespace/) { get; } | Haalt de type-namespace op. De namespace van het type dat is gedeclareerd voor het gekoppelde element of attribuut of null als het element geen declaratie heeft of als er geen namespace-informatie beschikbaar is. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| [IsDerivedFrom](../../aspose.svg.dom/typeinfo/isderivedfrom/)(*string, string, ulong*) | Deze methode geeft terug of er een afleiding bestaat tussen de referentietype-definitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere type-definitie, d.w.z. degene die als parameter wordt doorgegeven. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DERIVATION_EXTENSION](../../aspose.svg.dom/typeinfo/derivation_extension/) | Als het schema van het document een XML-schema is [XML Schema Part 1], vertegenwoordigt deze constante de afleiding door extensie. |
| const [DERIVATION_LIST](../../aspose.svg.dom/typeinfo/derivation_list/) | Als het schema van het document een XML-schema is [XML Schema Part 1], vertegenwoordigt deze constante de lijst. |
| const [DERIVATION_RESTRICTION](../../aspose.svg.dom/typeinfo/derivation_restriction/) | Als het schema van het document een XML-schema is [XML Schema Part 1], vertegenwoordigt deze constante de afleiding door restrictie als complexe types betrokken zijn, of een restrictie als eenvoudige types betrokken zijn. |
| const [DERIVATION_UNION](../../aspose.svg.dom/typeinfo/derivation_union/) | Als het schema van het document een XML-schema is [XML Schema Part 1], vertegenwoordigt deze constante de unie als eenvoudige types betrokken zijn. |

### Zie ook

* class [DOMObject](../domobject/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
