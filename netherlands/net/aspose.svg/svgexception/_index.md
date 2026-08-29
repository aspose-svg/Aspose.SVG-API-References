---
title: "SVGException Klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.SVGException klasse. Deze uitzondering wordt opgegooid wanneer een specifieke SVG‑bewerking niet kan worden uitgevoerd"
type: docs
weight: 5300
url: /nl/net/aspose.svg/svgexception/
---
## SVGException class

Deze uitzondering wordt opgegooid wanneer een specifieke SVG‑bewerking niet kan worden uitgevoerd.

```csharp
public class SVGException : PlatformException
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SVGException](svgexception/)(*ushort*) | Initialiseert een nieuw exemplaar van de `SVGException` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Code](../../aspose.svg/svgexception/code/) { get; } | Een code die de reden identificeert waarom de gevraagde bewerking niet kon worden uitgevoerd. De waarde van dit lid zal een van de constanten in de SVGException‑codegroep zijn. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| virtual [Message](../../system/exception/message/) { get; } |  |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [SVG_INVALID_VALUE_ERR](../../aspose.svg/svgexception/svg_invalid_value_err/) | Opgegooid wanneer een ongeldige waarde wordt doorgegeven aan een bewerking of toegewezen aan een attribuut. |
| const [SVG_MATRIX_NOT_INVERTABLE](../../aspose.svg/svgexception/svg_matrix_not_invertable/) | Opgegooid wanneer een poging wordt gedaan om een matrix te inverteren die niet inverteerbaar is. |
| const [SVG_WRONG_TYPE_ERR](../../aspose.svg/svgexception/svg_wrong_type_err/) | Opgegooid wanneer een object van het verkeerde type wordt doorgegeven aan een bewerking. |

### Zie ook

* class [PlatformException](../platformexception/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
