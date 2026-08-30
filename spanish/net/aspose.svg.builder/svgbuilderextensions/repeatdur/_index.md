---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Referencia de la API de Aspose.SVG para .NET"
description: "Método SVGBuilderExtensions RepeatDur. Establece el atributo repeatDur que especifica la duración total durante la cual la animación debe repetirse"
type: docs
weight: 1960
url: /es/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

Establece el atributo 'repeatDur', especificando la duración total durante la cual debe repetirse la animación.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| duration | La duración total para repetir la animación. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

Establece el atributo 'repeatDur', especificando una duración total indefinida para la animación usando una enumeración predefinida.

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| Parámetro | Descripción |
| --- | --- |
| TBuilder | El tipo del constructor de elementos SVG. |
| constructor | El constructor de elementos SVG. |
| value | La duración total indefinida predefinida para repetir la animación. |

### Valor de retorno

La instancia del constructor para encadenamiento.

### Ver también

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
