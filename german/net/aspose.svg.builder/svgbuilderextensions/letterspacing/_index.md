---
title: "SVGBuilderExtensions.LetterSpacing"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions LetterSpacing-Methode. Setzt das letter-spacing-Attribut für ein SVG-Element mithilfe eines numerischen Werts und eines bestimmten Längentyps."
type: docs
weight: 1100
url: /de/net/aspose.svg.builder/svgbuilderextensions/letterspacing/
---
## LetterSpacing<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#letterspacing_1}

Setzt das Attribut 'letter-spacing' für ein SVG-Element mit einem numerischen Wert und einem bestimmten Längentyp.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der einzustellende Buchstabenabstandswert. |
| type | Der Längentyp (z. B. px, em). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [LengthType](../../lengthtype/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## LetterSpacing<TBuilder>(*this TBuilder, [Spacing](../../spacing/)*) {#letterspacing}

Setzt das Attribut 'letter-spacing' für ein SVG-Element unter Verwendung eines vordefinierten Abstandswerts.

```csharp
public static TBuilder LetterSpacing<TBuilder>(this TBuilder builder, Spacing value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der einzustellende vordefinierte Abstandswert. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [Spacing](../../spacing/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
