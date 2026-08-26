---
title: "SVGTransform Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.DataTypes.SVGTransform Klasse. SVGTransform ist die Schnittstelle für eine der Komponenten-Transformationen innerhalb einer SVGTransformList, sodass ein SVGTransform-Objekt einer einzelnen Komponente entspricht, z. B. Skalierung oder Matrix innerhalb einer Transformationsattributspezifikation"
type: docs
weight: 2310
url: /de/net/aspose.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform ist das Interface für eine der Komponenten-Transformationen innerhalb einer SVGTransformList; ein SVGTransform-Objekt entspricht also einer einzelnen Komponente (z. B. 'scale(…)' oder 'matrix(…)') innerhalb einer ‘transform’-Attributspezifikation.

```csharp
public class SVGTransform : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Angle](../../aspose.svg.datatypes/svgtransform/angle/) { get; } | Ein Komfortattribut für SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY. Es enthält den angegebenen Winkel. Für SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE und SVG_TRANSFORM_SCALE ist der Winkel null. |
| [Matrix](../../aspose.svg.datatypes/svgtransform/matrix/) { get; } | Die Matrix, die diese Transformation darstellt. Das Matrixobjekt ist live, d. h. alle Änderungen am SVGTransform‑Objekt werden sofort im Matrixobjekt widergespiegelt und umgekehrt. Wird das Matrixobjekt direkt geändert (d. h. ohne die Methoden der SVGTransform‑Schnittstelle zu verwenden), ändert sich der Typ des SVGTransform zu SVG_TRANSFORM_MATRIX. Für SVG_TRANSFORM_MATRIX enthält die Matrix die vom Benutzer angegebenen Werte a, b, c, d, e, f. Für SVG_TRANSFORM_TRANSLATE stellen e und f die Translationsbeträge dar (a = 1, b = 0, c = 0 und d = 1). Für SVG_TRANSFORM_SCALE stellen a und d die Skalierungsbeträge dar (b = 0, c = 0, e = 0 und f = 0). Für SVG_TRANSFORM_SKEWX und SVG_TRANSFORM_SKEWY stellen a, b, c und d die Matrix dar, die die angegebene Schrägstellung ergibt (e = 0 und f = 0). Für SVG_TRANSFORM_ROTATE stellen a, b, c, d, e und f zusammen die Matrix dar, die die angegebene Drehung ergibt. Wenn die Drehung um den Mittelpunkt (0, 0) erfolgt, sind e und f null. |
| [Type](../../aspose.svg.datatypes/svgtransform/type/) { get; } | Der Typ des Wertes, wie durch eine der auf dieser Schnittstelle definierten SVG_TRANSFORM_*‑Konstanten angegeben. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [SetMatrix](../../aspose.svg.datatypes/svgtransform/setmatrix/)(*[SVGMatrix](../svgmatrix/)*) | Setzt den Transformationstyp auf SVG_TRANSFORM_MATRIX, wobei der Parameter matrix die neue Transformation definiert. Die Werte aus dem Parameter matrix werden kopiert, der Matrix-Parameter ersetzt nicht SVGTransform::matrix. |
| [SetRotate](../../aspose.svg.datatypes/svgtransform/setrotate/)(*float, float, float*) | Setzt den Transformationstyp auf SVG_TRANSFORM_ROTATE, wobei der Parameter angle den Rotationswinkel definiert und die Parameter cx und cy das optionale Rotationszentrum festlegen. |
| [SetScale](../../aspose.svg.datatypes/svgtransform/setscale/)(*float, float*) | Setzt den Transformationstyp auf SVG_TRANSFORM_SCALE, wobei die Parameter sx und sy die Skalierungsbeträge definieren. |
| [SetSkewX](../../aspose.svg.datatypes/svgtransform/setskewx/)(*float*) | Setzt den Transformationstyp auf SVG_TRANSFORM_SKEWX, wobei der Parameter angle die Menge der Schrägstellung definiert. |
| [SetSkewY](../../aspose.svg.datatypes/svgtransform/setskewy/)(*float*) | Setzt den Transformationstyp auf SVG_TRANSFORM_SKEWY, wobei der Parameter angle die Menge der Schrägstellung definiert. |
| [SetTranslate](../../aspose.svg.datatypes/svgtransform/settranslate/)(*float, float*) | Setzt den Transformationstyp auf SVG_TRANSFORM_TRANSLATE, wobei die Parameter tx und ty die Übersetzungsbeträge definieren. |
| override [ToString](../../aspose.svg.datatypes/svgtransform/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.svg.datatypes/svgtransform/svg_transform_matrix/) | Eine 'matrix(…)'‑Transformation. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.svg.datatypes/svgtransform/svg_transform_rotate/) | Eine 'rotate(…)'‑Transformation. |
| const [SVG_TRANSFORM_SCALE](../../aspose.svg.datatypes/svgtransform/svg_transform_scale/) | Eine 'scale(…)'‑Transformation. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.svg.datatypes/svgtransform/svg_transform_skewx/) | Eine 'skewX(…)'‑Transformation. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.svg.datatypes/svgtransform/svg_transform_skewy/) | Eine 'skewY(…)'‑Transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.svg.datatypes/svgtransform/svg_transform_translate/) | Eine 'translate(…)'‑Transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.svg.datatypes/svgtransform/svg_transform_unknown/) | Der Einheitstyp ist keiner der vordefinierten Typen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
