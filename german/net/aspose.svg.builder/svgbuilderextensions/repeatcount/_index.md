---
title: "SVGBuilderExtensions.RepeatCount"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions RepeatCount-Methode. Legt das Attribut repeatCount fest, das definiert, wie oft die Animation wiederholt werden soll."
type: docs
weight: 1950
url: /de/net/aspose.svg.builder/svgbuilderextensions/repeatcount/
---
## RepeatCount<TBuilder>(*this TBuilder, int*) {#repeatcount_1}

Setzt das 'repeatCount'-Attribut und definiert, wie oft die Animation wiederholt werden soll.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, int value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die Anzahl der Wiederholungen der Animation. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatCount<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatcount}

Setzt das 'repeatCount'-Attribut und definiert eine unbestimmte Wiederholungszahl für die Animation mithilfe eines vordefinierten Enums.

```csharp
public static TBuilder RepeatCount<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Der vordefinierte unbestimmte Wiederholungswert für die Animation. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
