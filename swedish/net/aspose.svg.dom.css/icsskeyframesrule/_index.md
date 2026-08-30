---
title: "ICSSKeyframesRule‑gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule‑gränssnitt. CSSKeyframesRule‑gränssnittet representerar en komplett uppsättning nyckelramar för en enskild animation."
type: docs
weight: 2580
url: /sv/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule-gränssnittet representerar en komplett uppsättning nyckelbilder för en enskild animation.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Detta attribut ger åtkomst till nyckelramarna i listan. |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Detta attribut är namnet på nyckelramarna, som används av egenskapen ‘animation-name’. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | Metoden appendRule lägger till den angivna CSSKeyframeRule i listan vid den angivna nyckeln. |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | Metoden deleteRule tar bort CSSKeyframeRule med den angivna nyckeln. Om en regel med denna nyckel inte finns gör metoden ingenting. |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | Metoden findRule returnerar regeln med en nyckel som matchar den angivna nyckeln. Om ingen sådan regel finns returneras ett null‑värde. |

### Se även

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
