---
title: "CSSValueList Class"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.CSSValueList class. De CSSValueList interface biedt de abstractie van een geordende collectie van CSS-waarden."
type: docs
weight: 2500
url: /nl/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

De CSSValueList interface biedt de abstractie van een geordende collectie van CSS‑waarden.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initialiseert een nieuw exemplaar van de `CSSValueList`-klasse. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Initialiseert een nieuw exemplaar van de `CSSValueList`-klasse. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Initialiseert een nieuw exemplaar van de `CSSValueList`-klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | De CSSText-eigenschap van de [`CSSValue`](../cssvalue/) interface vertegenwoordigt de momenteel berekende CSS-eigenschapswaarde. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Een code die het type van de waarde definieert. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | Haalt de [`CSSValue`](../cssvalue/) op op de opgegeven index. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | De alleen-lezen eigenschap length van de CSSValueList interface geeft het aantal CSSValues in de lijst weer. Het bereik van geldige indexwaarden is 0 tot en met length-1. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | Retourneert een enumerator die door de collectie iterereert. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

### Zie ook

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
