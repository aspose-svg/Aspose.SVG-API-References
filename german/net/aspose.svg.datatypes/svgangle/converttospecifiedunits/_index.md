---
title: "SVGAngle.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGAngle ConvertToSpecifiedUnits‑Methode. Bewahrt den gleichen zugrunde liegenden gespeicherten Wert, setzt jedoch die gespeicherte Einheitkennung auf den angegebenen unitType zurück. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden."
type: docs
weight: 50
url: /de/net/aspose.svg.datatypes/svgangle/converttospecifiedunits/
---
## SVGAngle.ConvertToSpecifiedUnits method

Behalte denselben zugrunde liegenden gespeicherten Wert bei, setze jedoch den gespeicherten Einheit-Identifier auf den angegebenen unitType zurück. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp, zu dem gewechselt werden soll (z. B. SVG_ANGLETYPE_DEG). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) ausgelöst, wenn unitType SVG_ANGLETYPE_UNKNOWN ist oder kein gültiger Konstantwert für den Einheitstyp (eine der anderen SVG_ANGLETYPE_* Konstanten, die in diesem Interface definiert sind). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
