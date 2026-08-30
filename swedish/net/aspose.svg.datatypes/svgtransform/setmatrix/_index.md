---
title: "SVGTransform.SetMatrix"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGTransform SetMatrix-metoden. Anger transformtypen till SVG_TRANSFORM_MATRIX med parametern matrix som definierar den nya transformationen. Värdena från parametern matrix kopieras; matrix‑parametern ersätter inte SVGTransformmatrix"
type: docs
weight: 40
url: /sv/net/aspose.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

Ställer in transformtyp till SVG_TRANSFORM_MATRIX med parametern matrix som definierar den nya transformationen. Värdena från parameter‑matrixen kopieras; matrix‑parametern ersätter inte SVGTransform::matrix.

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | SVGMatrix | Den nya matrisen för transformationen. |

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/). Uppstått vid ett försök att ändra värdet på ett skrivskyddat attribut. |

### Se även

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
