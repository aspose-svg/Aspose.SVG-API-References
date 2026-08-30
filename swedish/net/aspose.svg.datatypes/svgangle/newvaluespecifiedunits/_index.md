---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGAngle NewValueSpecifiedUnits‑metod. Återställer värdet som ett tal med en associerad unitType och ersätter därmed värdena för alla attribut på objektet."
type: docs
weight: 60
url: /sv/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newUnitType | UInt16 | Enhetstypen för värdet (t.ex. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Vinkelvärdet. |

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) Uppstår om unitType är SVG_ANGLETYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_ANGLETYPE_*‑konstanterna som definieras på detta gränssnitt). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Uppstår när vinkeln motsvarar ett skrivskyddat attribut eller när själva objektet är skrivskyddat. |

### Se även

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
