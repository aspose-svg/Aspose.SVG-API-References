---
title: "SVGFEColorMatrixElementBuilder.TypeAndValues"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "SVGFEColorMatrixElementBuilder TypeAndValues methode. Stelt de type- en values-attributen van het feColorMatrix-element in, waarmee de kleurmatrixoperatie en de parameters worden gespecificeerd"
type: docs
weight: 30
url: /nl/net/aspose.svg.builder/svgfecolormatrixelementbuilder/typeandvalues/
---
## SVGFEColorMatrixElementBuilder.TypeAndValues method

Stelt de 'type'‑ en 'values'‑attributen van het feColorMatrix‑element in, waarmee de kleurmatrixbewerking en de parameters worden gespecificeerd.

```csharp
public SVGFEColorMatrixElementBuilder TypeAndValues(ColorMatrixOperation type, 
    params double[] values)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | ColorMatrixOperation | De ColorMatrixOperation enum-waarde die het type kleurmatrixoperatie vertegenwoordigt. |
| waarden | Double[] | De parameters voor de kleurmatrixbewerking. |

### Retourwaarde

De huidige builder‑instantie.

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer de opgegeven waarden niet voldoen aan de vereisten van het gespecificeerde type. |
| NotSupportedException | Wordt gegooid wanneer een niet-ondersteund type matrixbewerking wordt opgegeven. |

### Zie ook

* enum [ColorMatrixOperation](../../colormatrixoperation/)
* class [SVGFEColorMatrixElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
