---
title: "SVGBuilderExtensions.RepeatDur"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGBuilderExtensions RepeatDur 方法。设置 repeatDur 属性，指定动画应重复的总时长"
type: docs
weight: 1960
url: /zh/net/aspose.svg.builder/svgbuilderextensions/repeatdur/
---
## RepeatDur<TBuilder>(*this TBuilder, TimeSpan*) {#repeatdur_1}

设置 'repeatDur' 属性，指定动画应重复的总持续时间。

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, TimeSpan duration)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| duration | 动画重复的总时长。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## RepeatDur<TBuilder>(*this TBuilder, [IndefiniteRepeat](../../indefiniterepeat/)*) {#repeatdur}

设置 'repeatDur' 属性，使用预定义的枚举为动画指定无限的总持续时间。

```csharp
public static TBuilder RepeatDur<TBuilder>(this TBuilder builder, IndefiniteRepeat value)
    where TBuilder : ISVGElementBuilder, IAnimationTimingAttributeSetter
```

| 参数 | 描述 |
| --- | --- |
| TBuilder | SVG 元素构建器的类型。 |
| 构建器 | SVG 元素构建器。 |
| value | 预定义的无限总时长，用于动画重复。 |

### 返回值

用于链式调用的构建器实例。

### 另请参阅

* enum [IndefiniteRepeat](../../indefiniterepeat/)
* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IAnimationTimingAttributeSetter](../../ianimationtimingattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
