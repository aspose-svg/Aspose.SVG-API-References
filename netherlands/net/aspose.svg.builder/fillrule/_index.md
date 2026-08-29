---
title: "FillRule Enum"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Builder.FillRule enum. Specificeert de regel om te bepalen welke delen van een vorm binnen of buiten zijn in SVG-graphics"
type: docs
weight: 270
url: /nl/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

Specificeert de regel om te bepalen welke delen van een vorm binnen of buiten liggen in SVG‑graphics.

```csharp
public enum FillRule
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Nonzero | `0` | De non-zero windingregel: Bepaalt de \"insideness\" van een punt in de vorm door een straal van dat punt naar oneindig te tekenen in welke richting dan ook en het aantal padsegmenten van de gegeven vorm te tellen die de straal kruist. Als dit aantal oneven is, ligt het punt binnen; als het even is, ligt het punt buiten. |
| Evenodd | `1` | De even-odd windingregel: Bepaalt de \"insideness\" van een punt in de vorm door een straal van dat punt naar oneindig te tekenen in welke richting dan ook en het aantal padsegmenten van de gegeven vorm te tellen die de straal kruist. Als dit aantal even is, ligt het punt buiten; als het oneven is, ligt het punt binnen. |

### Zie ook

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
