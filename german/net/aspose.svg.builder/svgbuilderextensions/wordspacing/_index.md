---
title: "SVGBuilderExtensions.WordSpacing"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions WordSpacing-Methode. Setzt das word-spacing-Attribut für ein SVG-Element und gibt das Abstandverhalten zwischen Wörtern an."
type: docs
weight: 2340
url: /de/net/aspose.svg.builder/svgbuilderextensions/wordspacing/
---
## WordSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#wordspacing}

Setzt das Attribut 'word-spacing' für ein SVG-Element und gibt das Abstandverhalten zwischen Wörtern an.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der vordefinierte Wortabstandswert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## WordSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#wordspacing_1}

Setzt das Attribut 'word-spacing' für ein SVG-Element und gibt das Abstandverhalten zwischen Wörtern mit einem benutzerdefinierten Wert an.

```csharp
public static TBuilder WordSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Wortabstandswert. |
| type | Der Einheitstyp für den Abstandswert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
