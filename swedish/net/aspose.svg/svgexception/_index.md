---
title: "SVGException klass"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.SVGException-klass. Detta undantag kastas när en specifik SVG-operation är omöjlig att utföra"
type: docs
weight: 5300
url: /sv/net/aspose.svg/svgexception/
---
## SVGException class

Detta undantag kastas när en specifik SVG‑operation är omöjlig att utföra.

```csharp
public class SVGException : PlatformException
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | Initierar en ny instans av `SVGException`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | En kod som identifierar orsaken till att den begärda operationen inte kunde utföras. Värdet för detta fält kommer att vara en av konstanterna i SVGException-kodgruppen. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | Kastas när ett ogiltigt värde skickas till en operation eller tilldelas ett attribut. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | Kastas när ett försök görs att invertera en matris som inte är inverterbar. |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | Kastas när ett objekt av fel typ skickas till en operation. |

### Se även

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
