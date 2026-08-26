---
title: "SVGException Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.SVGException Klasse. Diese Ausnahme wird ausgelöst, wenn eine bestimmte SVG-Operation nicht ausgeführt werden kann."
type: docs
weight: 5300
url: /de/net/aspose.svg/svgexception/
---
## SVGException class

Diese Ausnahme wird ausgelöst, wenn eine bestimmte SVG‑Operation nicht ausgeführt werden kann.

```csharp
public class SVGException : PlatformException
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | Initialisiert eine neue Instanz der `SVGException`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | Ein Code, der den Grund identifiziert, warum die angeforderte Operation nicht ausgeführt werden konnte. Der Wert dieses Members ist einer der Konstanten in der SVGException-Codegruppe. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | Wird ausgelöst, wenn einem Vorgang ein ungültiger Wert übergeben oder einem Attribut zugewiesen wird. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | Wird ausgelöst, wenn versucht wird, eine nicht invertierbare Matrix zu invertieren. |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | Wird ausgelöst, wenn einem Vorgang ein Objekt des falschen Typs übergeben wird. |

### Siehe auch

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
