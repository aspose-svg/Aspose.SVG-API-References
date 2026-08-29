---
title: "SVGStyleElementBuilder.AddRule"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGStyleElementBuilder AddRule. Добавляет CSS‑правило в элемент стиля."
type: docs
weight: 30
url: /ru/net/aspose.svg.builder/svgstyleelementbuilder/addrule/
---
## AddRule(*string, string*) {#addrule_1}

Добавляет правило CSS к элементу style.

```csharp
public SVGStyleElementBuilder AddRule(string selector, string rules)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | String | CSS‑селектор для правила. |
| rules | String | CSS‑правила в виде строки. |

### Возвращаемое значение

Экземпляр SVGStyleElementBuilder для цепочечного вызова.

### См. также

* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)

---

## AddRule(*string, Action&lt;RuleBuilder&gt;*) {#addrule}

Добавляет правило CSS к элементу style, используя RuleBuilder.

```csharp
public SVGStyleElementBuilder AddRule(string selector, Action<RuleBuilder> configureRule)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| selector | String | CSS‑селектор для правила. |
| configureRule | Action`1 | Делегат для настройки правила с использованием RuleBuilder. |

### Возвращаемое значение

Экземпляр SVGStyleElementBuilder для цепочечного вызова.

### См. также

* class [RuleBuilder](../../rulebuilder/)
* class [SVGStyleElementBuilder](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
