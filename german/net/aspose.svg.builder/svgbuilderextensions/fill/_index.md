---
title: "SVGBuilderExtensions.Fill"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions Fill-Methode. Setzt das fill-Attribut, das definiert, wie die Animation Stile außerhalb ihrer aktiven Dauer anwendet."
type: docs
weight: 810
url: /de/net/aspose.svg.builder/svgbuilderextensions/fill/
---
## Fill<TBuilder>(*this TBuilder, [AnimationFill](../../animationfill/)*) {#fill}

Setzt das Attribut 'fill' und definiert, wie die Animation Stile außerhalb ihrer aktiven Dauer anwenden soll.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, AnimationFill value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Das Füllverhalten der Animation. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [AnimationFill](../../animationfill/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Action&lt;PaintBuilder&gt;*) {#fill_2}

Setzt das Attribut 'fill' für ein SVG-Element mit einer benutzerdefinierten Konfiguration.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Action<PaintBuilder> configure)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| konfigurieren | Ein Delegat zum Konfigurieren des PaintBuilder. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* class [PaintBuilder](../../paintbuilder/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, Color*) {#fill_3}

Setzt das Attribut 'fill' für ein SVG-Element mit einer Farbe.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Color color)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| Farbe | Die Farbe, die als Füllung gesetzt wird. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## Fill<TBuilder>(*this TBuilder, [Paint](../../paint/)*) {#fill_1}

Setzt das Attribut 'fill' für ein SVG-Element mit einem vordefinierten Paint-Enum-Wert.

```csharp
public static TBuilder Fill<TBuilder>(this TBuilder builder, Paint paint)
    where TBuilder : IAttributeSetter, IPresentationAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Die Builder-Instanz. |
| paint | Der Paint-Enum-Wert, der gesetzt werden soll. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [Paint](../../paint/)
* interface [IAttributeSetter](../../iattributesetter/)
* interface [IPresentationAttributeSetter](../../ipresentationattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
