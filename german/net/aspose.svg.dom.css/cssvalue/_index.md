---
title: "CSSValue Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.Css.CSSValue Klasse. Stellt einen einfachen oder komplexen Wert dar. Ein CSSValue-Objekt tritt nur im Kontext einer CSS-Eigenschaft auf."
type: docs
weight: 2490
url: /de/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Stellt einen einfachen oder komplexen Wert dar. Ein CSSValue‑Objekt tritt nur im Kontext einer CSS‑Property auf.

```csharp
public abstract class CSSValue : DOMObject
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Die CSSText-Eigenschaft des `CSSValue`-Interfaces stellt den aktuell berechneten CSS-Eigenschaftswert dar. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Ein Code, der den Typ des Werts definiert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Gibt einen Hashcode für diese Instanz zurück. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Diese Methode wird verwendet, um den ECMAScript-Objekttyp abzurufen. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | Implementiert den Operator ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | Implementiert den Operator !=. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | Der Wert ist ein benutzerdefinierter Wert. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | Der Wert ist vererbt und das cssText enthält "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | Der Wert ist ein primitiver Wert und eine Instanz des CSSPrimitiveValue-Interfaces kann durch bindungsspezifische Cast-Methoden auf dieser Instanz des CSSValue-Interfaces erhalten werden. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | Der Wert ist eine CSSValue-Liste und eine Instanz des CSSValueList-Interfaces kann durch bindungsspezifische Cast-Methoden auf dieser Instanz des CSSValue-Interfaces erhalten werden. |

### Siehe auch

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
