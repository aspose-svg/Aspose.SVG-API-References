---
title: "SVGBuilderExtensions.In"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions In-Methode. Setzt das in-Attribut für ein SVG-Filter-Primitive."
type: docs
weight: 1040
url: /de/net/aspose.svg.builder/svgbuilderextensions/in/
---
## In<TBuilder>(*this TBuilder, string*) {#in_1}

Setzt das Attribut 'in' für ein SVG-Filter-Primitive.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| value | Die Quellgrafik oder das Ergebnis des Filter-Primitives, das als Eingabe verwendet wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## In<TBuilder>(*this TBuilder, [FilterInput](../../filterinput/)*) {#in}

Setzt das Attribut 'in' für ein SVG-Filter-Primitive unter Verwendung einer vordefinierten Eingabequelle.

```csharp
public static TBuilder In<TBuilder>(this TBuilder builder, FilterInput input)
    where TBuilder : ISVGElementBuilder, IFilterPrimitiveInAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| input | Die vordefinierte Eingabequelle (z. B. SourceGraphic, SourceAlpha). |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [FilterInput](../../filterinput/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IFilterPrimitiveInAttributeSetter](../../ifilterprimitiveinattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
