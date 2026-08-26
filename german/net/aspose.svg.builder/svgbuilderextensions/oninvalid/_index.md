---
title: "SVGBuilderExtensions.OnInvalid"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions OnInvalid-Methode. Setzt das oninvalid-Ereignisattribut zur Behandlung ungültiger Ereignisse bei Formularelementen."
type: docs
weight: 1480
url: /de/net/aspose.svg.builder/svgbuilderextensions/oninvalid/
---
## SVGBuilderExtensions.OnInvalid<TBuilder> method

Legt das 'oninvalid'-Ereignisattribut fest, um ungültige Ereignisse bei Formularelementen zu behandeln.

```csharp
public static TBuilder OnInvalid<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die JavaScript-Funktion oder das Skript, das ausgeführt wird, wenn der Wert des Elements ungültig ist. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
