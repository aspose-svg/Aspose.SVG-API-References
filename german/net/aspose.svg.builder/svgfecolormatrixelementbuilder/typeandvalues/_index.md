---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGFEColorMatrixElementBuilder TypeAndValues-Methode. Setzt die Attribute type und values des feColorMatrix-Elements, die die Farbmatrixoperation und ihre Parameter festlegen."
type: docs
weight: 30
url: /de/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Setzt die Attribute 'type' und 'values' des feColorMatrix-Elements und gibt die Farbmatrixoperation sowie deren Parameter an.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | ColorMatrixOperation | Der ColorMatrixOperation-Enum-Wert, der den Typ der Farbmatrixoperation darstellt. |
| values | Double[] | Die Parameter für die Farbmatrixoperation. |

### Rückgabewert

Die aktuelle Builder‑Instanz.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn die bereitgestellten Werte nicht den Anforderungen des angegebenen Typs entsprechen. |
| NotSupportedException | Wird ausgelöst, wenn ein nicht unterstützter Matrix-Operationstyp angegeben wird. |

### Siehe auch

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
