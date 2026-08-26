---
title: "SVGAngle Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.DataTypes.SVGAngle Klasse. Das SVGAngle‑Interface entspricht dem Grunddatentyp angle"
type: docs
weight: 2070
url: /de/net/aspose.svg.datatypes/svgangle/
---
## SVGAngle class

Das SVGAngle-Interface entspricht dem Grunddatentyp Winkel.

```csharp
public class SVGAngle : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svgangle/unittype/) { get; } | Der Typ des Wertes, wie durch eine der auf diesem Interface definierten SVG_ANGLETYPE_*‑Konstanten angegeben. |
| [Value](../../aspose.svg.datatypes/svgangle/value/) { get; set; } | Der Winkelwert als Gleitkommawert in Grad. Das Setzen dieses Attributs führt dazu, dass valueInSpecifiedUnits und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueAsString](../../aspose.svg.datatypes/svgangle/valueasstring/) { get; set; } | Der Winkelwert als Zeichenkette, ausgedrückt in den durch unitType angegebenen Einheiten. Das Setzen dieses Attributs führt dazu, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svgangle/valueinspecifiedunits/) { get; set; } | Der Winkelwert als Gleitkommawert, ausgedrückt in den durch unitType angegebenen Einheiten. Das Setzen dieses Attributs führt dazu, dass value und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svgangle/converttospecifiedunits/)(*ushort*) | Behalte denselben zugrunde liegenden gespeicherten Wert bei, setze jedoch den gespeicherten Einheit-Identifier auf den angegebenen unitType zurück. Die Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svgangle/newvaluespecifiedunits/)(*ushort, float*) | Setzen Sie den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte für alle Attribute des Objekts ersetzt werden. |
| override [ToString](../../aspose.svg.datatypes/svgangle/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_ANGLETYPE_DEG](../../aspose.svg.datatypes/svgangle/svg_angletype_deg/) | Der Einheitstyp wurde explizit auf Grad gesetzt. |
| const [SVG_ANGLETYPE_GRAD](../../aspose.svg.datatypes/svgangle/svg_angletype_grad/) | Der Einheitstyp ist Bogenmaß. |
| const [SVG_ANGLETYPE_RAD](../../aspose.svg.datatypes/svgangle/svg_angletype_rad/) | Der Einheitstyp ist Bogenmaß. |
| const [SVG_ANGLETYPE_UNKNOWN](../../aspose.svg.datatypes/svgangle/svg_angletype_unknown/) | Der Einheitstyp ist keiner der vordefinierten Einheitstypen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |
| const [SVG_ANGLETYPE_UNSPECIFIED](../../aspose.svg.datatypes/svgangle/svg_angletype_unspecified/) | Es wurde kein Einheitstyp angegeben (d. h. ein einheitenloser Wert wurde spezifiziert). Für Winkel wird ein einheitenloser Wert genauso behandelt, als wären Grad angegeben. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
