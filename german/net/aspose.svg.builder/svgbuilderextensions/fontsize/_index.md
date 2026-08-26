---
title: "SVGBuilderExtensions.FontSize"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions FontSize‑Methode. Setzt das font-size‑Attribut für ein SVG‑Element unter Verwendung eines numerischen Werts und eines bestimmten Längentyps."
type: docs
weight: 890
url: /de/net/aspose.svg.builder/svgbuilderextensions/fontsize/
---
## FontSize<TBuilder>(*this TBuilder, double, [LengthType](../../lengthtype/)*) {#fontsize_1}

Setzt das Attribut 'font-size' für ein SVG-Element mit einem numerischen Wert und einem spezifischen Längentyp.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, double value, 
    LengthType type = LengthType.Px)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der festzulegende Schriftgrößenwert. |
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

## FontSize<TBuilder>(*this TBuilder, [FontSize](../../fontsize/)*) {#fontsize}

Setzt das Attribut 'font-size' für ein SVG-Element mit einem vordefinierten Schriftgrößenwert.

```csharp
public static TBuilder FontSize<TBuilder>(this TBuilder builder, FontSize value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Der vordefinierte Schriftgrößenwert, der gesetzt werden soll. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [FontSize](../../fontsize/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
