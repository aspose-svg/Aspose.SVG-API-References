---
title: "SVGTransform.Matrix"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGTransform Matrix-eigenschap. De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat elke wijziging die aan het SVGTransform-object wordt aangebracht onmiddellijk wordt weerspiegeld in het matrixobject en omgekeerd. Als het matrixobject direct wordt gewijzigd, d.w.z. zonder de methoden op de SVGTransform-interface te gebruiken, verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a b c d e f-waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiewaarde a 1 b 0 c 0 en d 1. Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalwaarden b 0 c 0 e 0 en f 0. Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a b c en d de matrix die resulteert in de gegeven scheefheid 0 en f 0. Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a b c d e en f gezamenlijk de matrix die resulteert in de opgegeven rotatie. Wanneer de rotatie rond het centrumpunt 0 0 plaatsvindt, zullen e en f nul zijn."
type: docs
weight: 20
url: /nl/net/aspose.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

De matrix die deze transformatie vertegenwoordigt. Het matrixobject is live, wat betekent dat elke wijziging aan het SVGTransform-object onmiddellijk wordt weerspiegeld in het matrixobject en omgekeerd. Als het matrixobject rechtstreeks wordt gewijzigd (d.w.z. zonder de methoden op de SVGTransform-interface zelf te gebruiken), verandert het type van de SVGTransform naar SVG_TRANSFORM_MATRIX. Voor SVG_TRANSFORM_MATRIX bevat de matrix de a, b, c, d, e, f-waarden die door de gebruiker zijn opgegeven. Voor SVG_TRANSFORM_TRANSLATE vertegenwoordigen e en f de translatiewaarden (a= 1, b= 0, c= 0 en d = 1). Voor SVG_TRANSFORM_SCALE vertegenwoordigen a en d de schaalwaarden (b= 0, c= 0, e= 0 en f = 0). Voor SVG_TRANSFORM_SKEWX en SVG_TRANSFORM_SKEWY vertegenwoordigen a, b, c en d de matrix die resulteert in de opgegeven scheefstand (e= 0 en f = 0). Voor SVG_TRANSFORM_ROTATE vertegenwoordigen a, b, c, d, e en f samen de matrix die resulteert in de opgegeven rotatie. Wanneer de rotatie rond het middelpunt (0, 0) plaatsvindt, zullen e en f nul zijn.

```csharp
public SVGMatrix Matrix { get; }
```

### Property Value

De matrix die deze transformatie vertegenwoordigt.

### Zie ook

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
