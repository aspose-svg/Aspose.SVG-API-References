---
title: "ICSSStyleSheet Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet interface. De CSSStyleSheet interface is een concrete interface die wordt gebruikt om een CSS-stijlblad te vertegenwoordigen, d.w.z. een stijlblad waarvan het contenttype text/css is."
type: docs
weight: 2660
url: /nl/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

De CSSStyleSheet interface is een concrete interface die wordt gebruikt om een CSS-stylesheet te vertegenwoordigen, d.w.z. een stylesheet waarvan het content‑type "text/css" is.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | De lijst van alle CSS-regels die in het stijlblad zijn opgenomen. Dit omvat zowel regelsets als at-rules. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Als dit stijlblad afkomstig is van een @import-regel, zal het ownerRule-attribuut de CSSImportRule bevatten. In dat geval zal het ownerNode-attribuut in de StyleSheet interface null zijn. Als het stijlblad afkomstig is van een element of een verwerkingsinstructie, zal het ownerRule-attribuut null zijn en zal het ownerNode-attribuut de Node bevatten. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | Wordt gebruikt om een regel uit het stijlblad te verwijderen. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | Wordt gebruikt om een nieuwe regel in het stijlblad in te voegen. De nieuwe regel maakt nu deel uit van de cascade. |

### Zie ook

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
