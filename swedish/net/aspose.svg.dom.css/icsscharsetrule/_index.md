---
title: "ICSSCharsetRule-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSCharsetRule-gränssnitt. CSSCharsetRule-gränssnittet representerar en teckenkodningsregel i ett CSS-stilmall. Värdet på attributet encoding påverkar inte kodningen av textdata i DOM-objekten; denna kodning är alltid UTF-16. Efter att en stilmall har lästs in är värdet på attributet encoding det värde som hittas i teckenkodningsregeln. Om det inte fanns någon teckenkodning i det ursprungliga dokumentet skapas ingen CSSCharsetRule. Värdet på attributet encoding kan också användas som en ledtråd för kodningen som används vid serialisering av stilmallen."
type: docs
weight: 2530
url: /sv/net/aspose.svg.dom.css/icsscharsetrule/
---
## ICSSCharsetRule interface

CSSCharsetRule-gränssnittet representerar en @charset‑regel i ett CSS‑formatark. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att ett formatark har lästs in är värdet på kodningsattributet det värde som finns i @charset‑regeln. Om det inte fanns någon @charset i originaldokumentet skapas inget CSSCharsetRule. Värdet på kodningsattributet kan även användas som en ledtråd för den kodning som används vid serialisering av formatarket.

```csharp
public interface ICSSCharsetRule : ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Encoding](../../aspose.svg.dom.css/icsscharsetrule/encoding/) { get; set; } | Kodningsinformationen som används i denna @charset-regel. |

### Se även

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
