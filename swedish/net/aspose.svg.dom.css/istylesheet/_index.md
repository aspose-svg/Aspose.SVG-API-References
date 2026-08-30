---
title: "IStyleSheet-gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.IStyleSheet gränssnitt. StyleSheet-gränssnittet är det abstrakta baskränssnittet för alla typer av stilmallar. Det representerar en enskild stilmall som är associerad med ett strukturerat dokument."
type: docs
weight: 2740
url: /sv/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilmallar. Det representerar en enskild stilmall som är associerad med ett strukturerat dokument.

```csharp
public interface IStyleSheet
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false om stilmallen tillämpas på dokumentet. true om den inte gör det. Att ändra detta attribut kan leda till en ny stilupplösning för dokumentet. En stilmall tillämpas endast om både en lämplig mediumdefinition är närvarande och attributet disabled är false. Så, om mediet inte gäller för den aktuella användaragenten, ignoreras attributet disabled. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | Om stilmallen är en länkad stilmall är värdet på dess attribut dess plats. För inbäddade stilmallar är värdet på detta attribut null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | Den avsedda destinationsmediet för stilinformation. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | Noden som kopplar denna stilmall till dokumentet. För HTML kan detta vara motsvarande LINK- eller STYLE-element. För XML kan det vara den länkande processinstruktionen. För stilmallar som inkluderas av andra stilmallar är värdet på detta attribut null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | För stilmallspråk som stödjer konceptet med stilmallsinkludering representerar detta attribut den inkluderande stilmallen, om en sådan finns. Om stilmallen är en toppnivåstilmall, eller om stilmallspråket inte stödjer inkludering, är värdet på detta attribut null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | Den rådgivande titeln. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | Detta specificerar stilmallspråket för denna stilmall. Stilmallspråket anges som en innehållstyp (t.ex. "text/css"). |

### Se även

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
