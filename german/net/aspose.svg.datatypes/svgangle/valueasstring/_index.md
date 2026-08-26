---
title: "SVGAngle.ValueAsString"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGAngle ValueAsString‑Eigenschaft. Der Winkelwert als Zeichenkette in den durch unitType ausgedrückten Einheiten. Das Setzen dieses Attributs führt dazu, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln."
type: docs
weight: 30
url: /de/net/aspose.svg.datatypes/svgangle/valueasstring/
---
## SVGAngle.ValueAsString property

Der Winkelwert als Zeichenkette, ausgedrückt in den durch unitType angegebenen Einheiten. Das Setzen dieses Attributs führt dazu, dass value, valueInSpecifiedUnits und unitType automatisch aktualisiert werden, um diese Einstellung widerzuspiegeln.

```csharp
public string ValueAsString { get; set; }
```

### Property Value

Der Wert als Zeichenkette.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`SYNTAX_ERR`](../../../aspose.svg.dom/domexception/syntax_err/) ausgelöst, wenn die zugewiesene Zeichenkette nicht als gültiger Winkel geparst werden kann. |
| [DOMException](../../../aspose.svg.dom/domexception/) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/) Wird ausgelöst, wenn der Winkel einem schreibgeschützten Attribut entspricht oder das Objekt selbst schreibgeschützt ist. |

### Siehe auch

* class [SVGAngle](../)
* namespace [Aspose.Svg.DataTypes](../../../aspose.svg.datatypes/)
* assembly [Aspose.SVG](../../../)
