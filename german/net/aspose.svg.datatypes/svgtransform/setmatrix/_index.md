---
title: "SVGTransform.SetMatrix"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGTransform SetMatrix Methode. Setzt den Transformationstyp auf SVG_TRANSFORM_MATRIX mit dem Parameter matrix, der die neue Transformation definiert. Die Werte aus dem Parameter matrix werden kopiert; der matrix-Parameter ersetzt nicht SVGTransformmatrix."
type: docs
weight: 40
url: /de/net/aspose.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

Setzt den Transformationstyp auf SVG_TRANSFORM_MATRIX, wobei der Parameter matrix die neue Transformation definiert. Die Werte aus dem Parameter matrix werden kopiert, der Matrix-Parameter ersetzt nicht SVGTransform::matrix.

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Matrix | SVGMatrix | Die neue Matrix für die Transformation. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Wird ausgelöst, wenn versucht wird, den Wert eines schreibgeschützten Attributs zu ändern. |

### Siehe auch

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
