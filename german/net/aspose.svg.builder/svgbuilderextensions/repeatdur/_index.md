---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "SVGBuilderExtensions RepeatDur-Methode. Setzt das repeatDur-Attribut, das die Gesamtdauer angibt, für die die Animation wiederholt werden soll."
type: docs
weight: 1960
url: /de/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Setzt das 'repeatDur'-Attribut und gibt die Gesamtdauer an, für die die Animation wiederholt werden soll.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| Dauer | Die Gesamtdauer für die Wiederholung der Animation. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Setzt das 'repeatDur'-Attribut und gibt eine unbestimmte Gesamtdauer für die Animation mithilfe eines vordefinierten Enums an.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parameter | Beschreibung |
| --- | --- |
| TBuilder | Der Typ des SVG-Element-Builders. |
| builder | Der SVG-Element-Builder. |
| value | Die vordefinierte unbestimmte Gesamtdauer für die Wiederholung der Animation. |

### Rückgabewert

Die Builder-Instanz für das Chaining.

### Siehe auch

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
