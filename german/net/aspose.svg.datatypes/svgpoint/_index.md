---
title: "SVGPoint Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.DataTypes.SVGPoint Klasse. Viele der SVG‑DOM‑Schnittstellen verweisen auf Objekte der Klasse SVGPoint. Ein SVGPoint ist ein x‑y‑Koordinatenpaar. Bei Matrizenoperationen wird ein SVGPoint als Vektor der Form x y 1 behandelt. Wenn ein SVGRect‑Objekt als schreibgeschützt gekennzeichnet ist, führt der Versuch, einem seiner Attribute einen Wert zuzuweisen, zu einer ausgelösten Ausnahme."
type: docs
weight: 2260
url: /de/net/aspose.svg.datatypes/svgpoint/
---
## SVGPoint class

Viele der SVG DOM Interfaces beziehen sich auf Objekte der Klasse SVGPoint. Ein SVGPoint ist ein (x, y)-Koordinatenpaar. Bei Verwendung in Matrixoperationen wird ein SVGPoint als Vektor der Form behandelt: [x] [y] [1]. Wenn ein SVGRect-Objekt als schreibgeschützt gekennzeichnet ist, führt der Versuch, einem seiner Attribute einen Wert zuzuweisen, zu einer ausgelösten Ausnahme.

```csharp
public class SVGPoint : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [X](../../aspose.svg.datatypes/svgpoint/x/) { get; set; } | Die X‑Koordinate. |
| [Y](../../aspose.svg.datatypes/svgpoint/y/) { get; set; } | Die Y‑Koordinate. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [MatrixTransform](../../aspose.svg.datatypes/svgpoint/matrixtransform/)(*[SVGMatrix](../svgmatrix/)*) | Wendet eine 2 × 3‑Matrixtransformation auf dieses SVGPoint‑Objekt an und gibt ein neues, transformiertes SVGPoint‑Objekt zurück: newpoint = matrix* thispoint |
| override [ToString](../../aspose.svg.datatypes/svgpoint/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
