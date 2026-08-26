---
title: "SVGBuilderExtensions.TextDecoration"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions TextDecoration-Methode. Setzt das text-decoration-Attribut für ein SVG-Element, das Dekorationen definiert, die dem Text hinzugefügt werden."
type: docs
weight: 2210
url: /de/net/aspose.svg.builder/svgbuilderextensions/textdecoration/
---
## SVGBuilderExtensions.TextDecoration<TBuilder> method

Setzt das Attribut 'text-decoration' für ein SVG-Element und definiert die Dekorationen, die dem Text hinzugefügt werden.

```csharp
public static TBuilder TextDecoration<TBuilder>(this TBuilder builder, bool underline = false, 
    bool overline = false, bool lineThrough = false, bool blink = false)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| unterstreichen | Gibt an, ob der Text unterstrichen werden soll. |
| überstrich | Gibt an, ob der Text einen Überstrich haben soll. |
| durchgestrichen | Gibt an, ob der Text durchgestrichen sein soll. |
| blinken | Gibt an, ob der Text blinken soll (nicht empfohlen zu verwenden). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
