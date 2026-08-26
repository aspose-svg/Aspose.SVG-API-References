---
title: "ICSSStyleSheet Schnittstelle"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSStyleSheet Schnittstelle. Die CSSStyleSheet Schnittstelle ist eine konkrete Schnittstelle, die verwendet wird, um ein CSS-Stylesheet darzustellen, d. h. ein Stylesheet, dessen Content‑Typ text/css ist."
type: docs
weight: 2660
url: /de/net/aspose.svg.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Das CSSStyleSheet-Interface ist ein konkretes Interface, das verwendet wird, um ein CSS-Stylesheet zu repräsentieren, d. h. ein Stylesheet, dessen Inhaltstyp "text/css" ist.

```csharp
public interface ICSSStyleSheet : IStyleSheet
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icssstylesheet/cssrules/) { get; } | Die Liste aller CSS-Regeln, die im Stylesheet enthalten sind. Dies umfasst sowohl Regelsets als auch At‑Rules. |
| [OwnerRule](../../aspose.svg.dom.css/icssstylesheet/ownerrule/) { get; } | Wenn dieses Stylesheet aus einer @import‑Regel stammt, enthält das ownerRule‑Attribut das CSSImportRule. In diesem Fall ist das ownerNode‑Attribut in der StyleSheet‑Schnittstelle null. Wenn das Stylesheet aus einem Element oder einer Verarbeitungsanweisung stammt, ist das ownerRule‑Attribut null und das ownerNode‑Attribut enthält den Node. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [DeleteRule](../../aspose.svg.dom.css/icssstylesheet/deleterule/)(*int*) | Wird verwendet, um eine Regel aus dem Stylesheet zu löschen. |
| [InsertRule](../../aspose.svg.dom.css/icssstylesheet/insertrule/)(*string, int*) | Wird verwendet, um eine neue Regel in das Stylesheet einzufügen. Die neue Regel wird nun Teil der Kaskade. |

### Siehe auch

* interface [IStyleSheet](../istylesheet/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
