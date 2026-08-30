---
title: "ICSSImportRule-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSImportRule-gränssnitt. CSSImportRule-gränssnittet representerar en importregel i ett CSS-stilmall. Importregeln används för att importera stilregler från andra stilmallar."
type: docs
weight: 2560
url: /sv/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

CSSImportRule-gränssnittet representerar en @import-regel i en CSS-stilmall. @import-regeln används för att importera stilregler från andra stilmallar.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | Platsen för den stilmall som ska importeras. Attributet kommer inte att innehålla "url(...)"-specifieraren runt URI:n. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | En lista över medietyper som denna stilmall kan användas för. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | Stilmallen som refereras av denna regel, om den har laddats. Värdet för detta attribut är null om stilmallen ännu inte har laddats eller om den inte kommer att laddas (t.ex. om stilmallen är för en medietyp som inte stöds av användaragenten). |

### Se även

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
