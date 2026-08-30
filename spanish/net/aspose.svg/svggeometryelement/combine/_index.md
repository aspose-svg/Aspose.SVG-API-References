---
title: "SVGGeometryElement.Combine"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGGeometryElement Combine. Combina esta geometría con otra geometría SVG usando una operación booleana y devuelve un nuevo elemento path que contiene el resultado."
type: docs
weight: 20
url: /es/net/aspose.svg/svggeometryelement/combine/
---
## SVGGeometryElement.Combine method

Combina esta geometría con otra geometría SVG usando una operación booleana y devuelve un nuevo elemento `<path>` que contiene el resultado.

```csharp
public SVGPathElement Combine(SVGGeometryElement geometryElement, BooleanPathOp op)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| geometryElement | SVGGeometryElement | La otra geometría con la que combinar. Debe estar en el mismo documento. |
| op | BooleanPathOp | El operador booleano a aplicar: Unión (A UNION B), Diferencia (A - B), Intersección (A INTERSECT B) o Exclusión (XOR). |

### Valor de retorno

Un nuevo [`SVGPathElement`](../../svgpathelement/) cuyo atributo `d` codifica el resultado en el espacio de usuario raíz `<svg>` (px CSS). El elemento no se agrega al DOM.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada si *geometryElement* es nulo. |
| InvalidOperationException | Lanzada si este elemento no tiene documento propietario. |
| NotSupportedException | Lanzada cuando las operaciones de ruta booleanas no están disponibles; esta característica requiere el backend SkiaSharp (instale el paquete Aspose.SVG.Drawing.SkiaSharp). |

### Ver también

* class [SVGPathElement](../../svgpathelement/)
* enum [BooleanPathOp](../../../aspose.svg.rendering/booleanpathop/)
* class [SVGGeometryElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
