---
title: "SVGBuilderExtensions.StrokeDashArray"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions StrokeDashArray-Methode. Setzt das stroke-dasharray-Attribut für ein SVG-Element, das das Muster aus Strichen und Lücken definiert, das zum Zeichnen des Strichs verwendet wird."
type: docs
weight: 2090
url: /de/net/aspose.svg.builder/svgbuilderextensions/strokedasharray/
---
## StrokeDashArray<TBuilder>(*this TBuilder, params double[]*) {#strokedasharray_1}

Setzt das Attribut 'stroke-dasharray' für ein SVG-Element und definiert das Muster aus Strichen und Lücken, das zum Zeichnen der Kontur verwendet wird.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, params double[] dashArray)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| dashArray | Das Array der Strichlängen. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## StrokeDashArray<TBuilder>(*this TBuilder, [Dash](../../dash/)*) {#strokedasharray}

Setzt das Attribut 'stroke-dasharray' für ein SVG-Element unter Verwendung eines vordefinierten Strichmusters.

```csharp
public static TBuilder StrokeDashArray<TBuilder>(this TBuilder builder, Dash value)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Das zu setzende Strichmuster. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [Dash](../../dash/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
