---
title: Interface ICSSKeyframesRule
second_title: Aspose.SVG för .NET API Referens
description: Aspose.Svg.Dom.Css.ICSSKeyframesRule gränssnitt. CSSKeyframesRulegränssnittet representerar en komplett uppsättning nyckelbildrutor för en enda animation
type: docs
weight: 580
url: /sv/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframesRule-gränssnittet representerar en komplett uppsättning nyckelbildrutor för en enda animation

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Det här attributet ger åtkomst till nyckelbildrutorna i listan |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Det här attributet är namnet på nyckelbildrutorna, som används av egenskapen 'animation-name'. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(string) | AppendRule-metoden lägger till den skickade CSSKeyframeRule i listan vid den passerade key |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(string) | Metoden deleteRule tar bort CSSKeyframeRule med den godkända nyckeln. Om en regel med denna nyckel inte finns, gör metoden ingenting |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(string) | Metoden findRule returnerar regeln med en nyckel som matchar den godkända nyckeln. Om det inte finns någon sådan regel returneras ett nollvärde |

### Se även

* interface [ICSSRule](../icssrule/)
* namnutrymme [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* hopsättning [Aspose.SVG](../../)


