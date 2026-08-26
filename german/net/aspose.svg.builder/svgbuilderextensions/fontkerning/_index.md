---
title: "SVGBuilderExtensions.FontKerning"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions FontKerning-Methode. Setzt das font-kerning-Attribut für ein SVG-Element unter Verwendung eines numerischen Werts und eines spezifischen LengthType."
type: docs
weight: 880
url: /de/net/aspose.svg.builder/svgbuilderextensions/fontkerning/
---
## FontKerning<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontkerning_1}

Setzt das Attribut 'font-kerning' für ein SVG-Element mit einem numerischen Wert und einem spezifischen Längentyp.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der Kerning-Wert der Schriftart, der festzulegen ist. |
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

## FontKerning<TBuilder>(*this TBuilder, [Kerning](../../kerning/)*) {#fontkerning}

Setzt das Attribut 'font-kerning' für ein SVG-Element mit einem vordefinierten Kerning-Wert.

```csharp
public static TBuilder FontKerning<TBuilder>(this TBuilder builder, Kerning value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der vordefinierte Kerning-Wert, der festzulegen ist. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [Kerning](../../kerning/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
