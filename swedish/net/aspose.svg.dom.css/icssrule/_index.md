---
title: "ICSSRule-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSRule interface. CSSRule‑gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑satser. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificerats i ett CSS‑stilmall även om regeln inte känns igen av parsern. Oidentifierade regler representeras med ICSSUnknownRule‑gränssnittet."
type: docs
weight: 2620
url: /sv/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

CSSRule-gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑uttalanden. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificerats i en CSS-stilmall, även om regeln inte känns igen av parsern. Oidentifierade regler representeras med ICSSUnknownRule‑gränssnittet.

```csharp
public interface ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | Den parsbara textrepresentationen av regeln. Detta återspeglar regelns aktuella tillstånd och inte dess ursprungliga värde. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | Om denna regel finns inuti en annan regel (t.ex. en stilregel i ett @media‑block) är detta den omgivande regeln. Om regeln inte är inbäddad i någon annan regel returneras null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | Stilmallen som innehåller denna regel. |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | Typen av regeln, som definierats ovan. Förväntningen är att bindningsspecifika cast‑metoder kan användas för att kasta ner från en instans av CSSRule‑gränssnittet till det specifika härledda gränssnitt som typen antyder. |

### Se även

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
