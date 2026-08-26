---
title: "CSSValueList Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.CSSValueList Klasse. Die CSSValueList Schnittstelle bietet die Abstraktion einer geordneten Sammlung von CSS-Werten."
type: docs
weight: 2500
url: /de/net/aspose.svg.dom.css/cssvaluelist/
---
## CSSValueList class

Das CSSValueList-Interface bietet die Abstraktion einer geordneten Sammlung von CSS-Werten.

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | Initialisiert eine neue Instanz der `CSSValueList` Klasse. |
| [CSSValueList](cssvaluelist/#constructor_1)(*params CSSValue[]*) | Initialisiert eine neue Instanz der `CSSValueList` Klasse. |
| [CSSValueList](cssvaluelist/#constructor_2)(*IEnumerable&lt;CSSValue&gt;*) | Initialisiert eine neue Instanz der `CSSValueList` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [CSSText](../../aspose.svg.dom.css/cssvaluelist/csstext/) { get; set; } | Die CSSText‑Eigenschaft der [`CSSValue`](../cssvalue/) Schnittstelle stellt den aktuell berechneten CSS‑Eigenschaftswert dar. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ein Code, der den Typ des Werts definiert. |
| [Item](../../aspose.svg.dom.css/cssvaluelist/item/) { get; } | Liefert das [`CSSValue`](../cssvalue/) am angegebenen Index. |
| [Length](../../aspose.svg.dom.css/cssvaluelist/length/) { get; } | Die schreibgeschützte Eigenschaft length des CSSValueList-Interfaces gibt die Anzahl der CSSValues in der Liste an. Der gültige Wertebereich der Indizes ist 0 bis length‑1 inklusive. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| [GetEnumerator](../../aspose.svg.dom.css/cssvaluelist/getenumerator/)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvaluelist/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
