---
title: "CSSValue‑klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.CSSValue‑klasse. Vertegenwoordigt een eenvoudige of complexe waarde. Een CSSValue‑object komt alleen voor in de context van een CSS‑eigenschap."
type: docs
weight: 2490
url: /nl/net/aspose.svg.dom.css/cssvalue/
---
## CSSValue class

Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue‑object komt alleen voor in de context van een CSS‑eigenschap.

```csharp
public abstract class CSSValue : DOMObject
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | De CSSText‑eigenschap van de `CSSValue`‑interface vertegenwoordigt de momenteel berekende CSS‑eigenschapwaarde. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Een code die het type van de waarde definieert. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Bepaalt of het opgegeven Object gelijk is aan deze instantie. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Retourneert een hashcode voor deze instantie. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript‑objecttype op te halen. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |
| [operator ==](../../aspose.svg.dom.css/cssvalue/op_equality/) | Implementeert de operator ==. |
| [operator !=](../../aspose.svg.dom.css/cssvalue/op_inequality/) | Implementeert de operator !=. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.svg.dom.css/cssvalue/css_custom/) | De waarde is een aangepaste waarde. |
| const [CSS_INHERIT](../../aspose.svg.dom.css/cssvalue/css_inherit/) | De waarde is geërfd en de cssText bevat "inherit". |
| const [CSS_PRIMITIVE_VALUE](../../aspose.svg.dom.css/cssvalue/css_primitive_value/) | De waarde is een primitieve waarde en een instantie van de CSSPrimitiveValue‑interface kan verkregen worden door bindings‑specifieke cast‑methoden te gebruiken op deze instantie van de CSSValue‑interface. |
| const [CSS_VALUE_LIST](../../aspose.svg.dom.css/cssvalue/css_value_list/) | De waarde is een CSSValue-lijst en een instantie van de CSSValueList-interface kan worden verkregen door bindingspecifieke castmethoden te gebruiken op deze instantie van de CSSValue-interface. |

### Zie ook

* class [DOMObject](../../aspose.svg.dom/domobject/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
