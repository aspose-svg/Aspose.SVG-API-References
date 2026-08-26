---
title: "SVGLength Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.DataTypes.SVGLength Klasse. Das SVGLength‑Interface entspricht dem Grunddatentyp Länge. Ein SVGLength‑Objekt kann als schreibgeschützt gekennzeichnet werden, was bedeutet, dass Versuche, das Objekt zu ändern, eine unten beschriebene Ausnahme auslösen"
type: docs
weight: 2210
url: /de/net/aspose.svg.datatypes/svglength/
---
## SVGLength class

Das SVGLength interface entspricht dem Grunddatentyp length. Ein SVGLength-Objekt kann als schreibgeschützt gekennzeichnet werden, was bedeutet, dass Versuche, das Objekt zu ändern, eine Ausnahme auslösen, wie unten beschrieben.

```csharp
public class SVGLength : SVGValueType
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [UnitType](../../aspose.svg.datatypes/svglength/unittype/) { get; } | Der Typ des Wertes, wie durch eine der auf diesem Interface definierten SVG_LENGTHTYPE_*‑Konstanten angegeben. |
| [Value](../../aspose.svg.datatypes/svglength/value/) { get; set; } | Der Wert als Gleitkommazahl, in Benutzereinheiten. Das Setzen dieses Attributs führt dazu, dass valueInSpecifiedUnits und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueAsString](../../aspose.svg.datatypes/svglength/valueasstring/) { get; set; } | Der Wert als Zeichenkette, in den durch unitType ausgedrückten Einheiten. Das Setzen dieses Attributs führt dazu, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |
| [ValueInSpecifiedUnits](../../aspose.svg.datatypes/svglength/valueinspecifiedunits/) { get; set; } | Der Wert als Gleitkommazahl, in den durch unitType ausgedrückten Einheiten. Das Setzen dieses Attributs führt dazu, dass value und valueAsString automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ConvertToSpecifiedUnits](../../aspose.svg.datatypes/svglength/converttospecifiedunits/)(*ushort*) | Den gleichen zugrunde liegenden gespeicherten Wert beibehalten, aber den gespeicherten Einheitentyp auf den angegebenen unitType zurücksetzen. Objektattribute unitType, valueInSpecifiedUnits und valueAsString können durch diese Methode geändert werden. Zum Beispiel, wenn der ursprüngliche Wert \"0.5cm\" war und die Methode aufgerufen wird, um in Millimeter zu konvertieren, dann würde unitType zu SVG_LENGTHTYPE_MM geändert, valueInSpecifiedUnits würde auf den numerischen Wert 5 geändert und valueAsString würde zu \"5mm\" geändert. |
| [Dispose](../../aspose.svg.datatypes/svgvaluetype/dispose/)() | Gibt nicht verwaltete und – optional – verwaltete Ressourcen frei. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| [NewValueSpecifiedUnits](../../aspose.svg.datatypes/svglength/newvaluespecifiedunits/)(*ushort, float*) | Setzen Sie den Wert als Zahl mit einem zugehörigen unitType zurück, wodurch die Werte für alle Attribute des Objekts ersetzt werden. |
| override [ToString](../../aspose.svg.datatypes/svglength/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_LENGTHTYPE_CM](../../aspose.svg.datatypes/svglength/svg_lengthtype_cm/) | Ein Wert wurde mit den in CSS2 definierten cm‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EMS](../../aspose.svg.datatypes/svglength/svg_lengthtype_ems/) | Ein Wert wurde mit den in CSS2 definierten em‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_EXS](../../aspose.svg.datatypes/svglength/svg_lengthtype_exs/) | Ein Wert wurde mit den in CSS2 definierten ex‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_IN](../../aspose.svg.datatypes/svglength/svg_lengthtype_in/) | Ein Wert wurde mit den in CSS2 definierten in‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_MM](../../aspose.svg.datatypes/svglength/svg_lengthtype_mm/) | Ein Wert wurde mit den in CSS2 definierten mm‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_NUMBER](../../aspose.svg.datatypes/svglength/svg_lengthtype_number/) | Es wurde kein Einheitentyp angegeben (d.h., ein einheitenloser Wert wurde angegeben), was einen Wert in Benutzereinheiten bedeutet. |
| const [SVG_LENGTHTYPE_PC](../../aspose.svg.datatypes/svglength/svg_lengthtype_pc/) | Ein Wert wurde mit den in CSS2 definierten pc‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PERCENTAGE](../../aspose.svg.datatypes/svglength/svg_lengthtype_percentage/) | Ein Prozentwert wurde angegeben. |
| const [SVG_LENGTHTYPE_PT](../../aspose.svg.datatypes/svglength/svg_lengthtype_pt/) | Ein Wert wurde mit den in CSS2 definierten pt‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_PX](../../aspose.svg.datatypes/svglength/svg_lengthtype_px/) | Ein Wert wurde mit den in CSS2 definierten px‑Einheiten angegeben. |
| const [SVG_LENGTHTYPE_UNKNOWN](../../aspose.svg.datatypes/svglength/svg_lengthtype_unknown/) | Der Einheitstyp ist keiner der vordefinierten Einheitstypen. Es ist ungültig, zu versuchen, einen neuen Wert dieses Typs zu definieren oder einen bestehenden Wert zu diesem Typ zu wechseln. |

### Siehe auch

* class [SVGValueType](../svgvaluetype/)
* namespace [Aspose.Svg.DataTypes](../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../)
