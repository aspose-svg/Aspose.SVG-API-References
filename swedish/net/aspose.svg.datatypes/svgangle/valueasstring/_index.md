---
title: "SVGAngle.ValueAsString"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGAngle ValueAsString‑egenskap. Vinkelvärdet som en sträng i de enheter som uttrycks av unitType. Att sätta detta attribut kommer automatiskt att uppdatera valueInSpecifiedUnits och unitType för att återspegla denna inställning."
type: docs
weight: 30
url: /sv/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

Vinkelvärdet som en sträng, i de enheter som uttrycks av unitType. Att sätta detta attribut kommer att automatiskt uppdatera value, valueInSpecifiedUnits och unitType för att återspegla denna inställning.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

Värdet som sträng.

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) Uppstår om den tilldelade strängen inte kan parsas som en giltig vinkel. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Uppstår när vinkeln motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
