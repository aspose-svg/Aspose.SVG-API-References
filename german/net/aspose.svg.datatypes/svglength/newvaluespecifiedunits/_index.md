---
title: "SVGLength.NewValueSpecifiedUnits"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGLength NewValueSpecifiedUnits Methode. Setzt den Wert als Zahl mit einem zugehörigen unitType zurück und ersetzt damit die Werte aller Attribute des Objekts."
type: docs
weight: 60
url: /de/net/aspose.svg.datatypes/svglength/newvaluespecifiedunits/
---
## SVGLength.NewValueSpecifiedUnits method

Setzen Sie den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte für alle Attribute des Objekts ersetzt werden.

```csharp
public void NewValueSpecifiedUnits(ushort unitType, float valueInSpecifiedUnits)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp für den Wert. |
| valueInSpecifiedUnits | Single | Der neue Wert.. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) ausgelöst, wenn unitType SVG_LENGTHTYPE_UNKNOWN ist oder keine gültige Einheitstyp‑Konstante (eine der anderen SVG_LENGTHTYPE_*‑Konstanten, die in diesem Interface definiert sind). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn die Länge einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
