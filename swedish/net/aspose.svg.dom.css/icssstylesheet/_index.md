---
title: "ICSSStyleSheet-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet-gränssnitt. CSSStyleSheet-gränssnittet är ett konkret gränssnitt som används för att representera en CSS-stilmall, d.v.s. en stilmall vars innehållstyp är text/css."
type: docs
weight: 2660
url: /sv/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet‑gränssnittet är ett konkret gränssnitt som används för att representera en CSS‑stilmall, d.v.s. en stilmall vars innehållstyp är "text/css".

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | Listan över alla CSS-regler som finns i stilmallen. Detta inkluderar både regeluppsättningar och at-regler. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Om denna stilmall kommer från en @import-regel kommer attributet ownerRule att innehålla CSSImportRule. I så fall kommer attributet ownerNode i StyleSheet-gränssnittet att vara null. Om stilmallen kommer från ett element eller en processinstruktion kommer attributet ownerRule att vara null och attributet ownerNode att innehålla Node. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | Används för att ta bort en regel från stilmallen. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | Används för att infoga en ny regel i stilmallen. Den nya regeln blir nu en del av kaskaden. |

### Se även

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
