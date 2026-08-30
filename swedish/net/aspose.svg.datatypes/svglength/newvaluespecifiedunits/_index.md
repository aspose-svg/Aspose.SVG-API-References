---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG för .NET API-referens"
description: "SVGLength NewValueSpecifiedUnits-metod. Återställer värdet som ett tal med en associerad enhetstyp och ersätter därmed värdena för alla attribut på objektet."
type: docs
weight: 60
url: /sv/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Återställ värdet som ett tal med en associerad unitType, vilket ersätter värdena för alla attribut på objektet.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unitType | UInt16 | Enhetstypen för värdet. |
| valueInSpecifiedUnits | Single | Det nya värdet.. |

### Undantag

| undantag | villkor |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) kastas om unitType är SVG_LENGTHTYPE_UNKNOWN eller inte är en giltig enhetstypkonstant (en av de andra SVG_LENGTHTYPE_*-konstanterna som definieras på detta gränssnitt). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Kod [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Uppstår när längden motsvarar ett skrivskyddat attribut eller när objektet självt är skrivskyddat. |

### Se även

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
