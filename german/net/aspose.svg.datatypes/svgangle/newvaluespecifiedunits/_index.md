---
title: "SVGAngle.NewValueSpecifiedUnits"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGAngle NewValueSpecifiedUnits-Methode. Setzt den Wert als Zahl mit einem zugehörigen unitType zurück und ersetzt dadurch die Werte aller Attribute des Objekts."
type: docs
weight: 60
url: /de/net/aspose.svg.datatypes/svgangle/newvaluespecifiedunits/
---
## SVGAngle.NewValueSpecifiedUnits method

Setzen Sie den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte für alle Attribute des Objekts ersetzt werden.

```csharp
public void NewValueSpecifiedUnits(ushort newUnitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newUnitType | UInt16 | Der Einheitstyp für den Wert (z. B. SVG_ANGLETYPE_DEG). |
| valueInSpecifiedUnits | Single | Der Winkelwert. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN ist oder kein gültiger Konstantwert für den Einheitstyp (eine der anderen SVG_ANGLETYPE_* Konstanten, die in diesem Interface definiert sind). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
