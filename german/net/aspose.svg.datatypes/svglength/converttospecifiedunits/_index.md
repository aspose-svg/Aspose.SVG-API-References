---
title: "SVGLength.ConvertToSpecifiedUnits"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGLength ConvertToSpecifiedUnits Methode. Bewahrt den gleichen zugrunde liegenden gespeicherten Wert, setzt jedoch den gespeicherten Einheitbezeichner auf den angegebenen unitType zurück. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert 0,5 cm war und die Methode aufgerufen wird, um in Millimeter zu konvertieren, dann wird unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits wird auf den numerischen Wert 5 gesetzt und valueAsString wird zu 5mm geändert."
type: docs
weight: 50
url: /de/net/aspose.svg.datatypes/svglength/converttospecifiedunits/
---
## SVGLength.ConvertToSpecifiedUnits method

Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber den gespeicherten Einheitentyp auf den angegebenen unitType zurücksetzen. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert \"0.5cm\" war und die Methode aufgerufen wird, um in Millimeter zu konvertieren, dann würde unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde auf den numerischen Wert 5 geändert und valueAsString würde zu \"5mm\" geändert.

```csharp
public void ConvertToSpecifiedUnits(ushort unitType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unitType | UInt16 | Der Einheitstyp, zu dem gewechselt werden soll (z. B. SVG_LENGTHTYPE_MM). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NOT_SUPPORTED_ERR`](../../../aspose.svg.dom/domexception/not_supported_err/) ausgelöst, wenn unitType SVG_LENGTHTYPE_UNKNOWN ist oder keine gültige Einheitstyp‑Konstante (eine der anderen SVG_LENGTHTYPE_*‑Konstanten, die in diesem Interface definiert sind). |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn die Länge einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGLength](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
