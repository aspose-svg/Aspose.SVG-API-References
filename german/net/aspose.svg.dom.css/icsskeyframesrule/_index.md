---
title: "ICSSKeyframesRule‑Interface"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule‑Interface. Das CSSKeyframesRule‑Interface stellt einen vollständigen Satz von Keyframes für eine einzelne Animation dar."
type: docs
weight: 2580
url: /de/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

Das CSSKeyframesRule-Interface repräsentiert einen vollständigen Satz von Keyframes für eine einzelne Animation.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Dieses Attribut ermöglicht den Zugriff auf die Keyframes in der Liste. |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Dieses Attribut ist der Name der Keyframes und wird von der Eigenschaft ‘animation-name’ verwendet. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | Die Methode appendRule fügt die übergebene CSSKeyframeRule an der übergebenen Schlüsselposition in die Liste ein. |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | Die Methode deleteRule löscht die CSSKeyframeRule mit dem übergebenen Schlüssel. Existiert keine Regel mit diesem Schlüssel, tut die Methode nichts. |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | Die Methode findRule gibt die Regel zurück, deren Schlüssel mit dem übergebenen Schlüssel übereinstimmt. Gibt es keine solche Regel, wird ein Nullwert zurückgegeben. |

### Siehe auch

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
