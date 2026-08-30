---
title: "ICSSStyleDeclaration gränssnitt"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration gränssnitt. CSSStyleDeclaration-gränssnittet representerar ett enskilt CSS-deklarationsblock. Detta gränssnitt kan användas för att bestämma stilegenskaperna som för närvarande är satta i ett block eller för att explicit sätta stilegenskaper inom blocket."
type: docs
weight: 2640
url: /sv/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration‑gränssnittet representerar ett enskilt CSS‑deklarationsblock. Detta gränssnitt kan användas för att avgöra vilka stilegenskaper som för närvarande är satta i ett block eller för att explicit sätta stilegenskaper i blocket.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | Den parsbara textrepresentationen av deklarationsblocket (exklusive de omgivande klammerparenteserna). Att sätta detta attribut kommer att leda till att det nya värdet parsas och att alla egenskaper i deklarationsblocket återställs, inklusive borttagning eller tillägg av egenskaper. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Används för att hämta de egenskaper som har satts explicit i detta deklarationsblock. Ordningen på de egenskaper som hämtas med denna metod behöver inte vara den ordning de sattes i. Denna metod kan användas för att iterera över alla egenskaper i detta deklarationsblock. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Antalet egenskaper som har satts explicit i detta deklarationsblock. Intervallet för giltiga index är 0 till längd‑1 inklusive. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | CSS-regeln som innehåller detta deklarationsblock eller null om detta CSSStyleDeclaration inte är kopplat till en CSSRule. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Används för att hämta objektrepresentationen av värdet för en CSS-egenskap om den har satts explicit inom detta deklarationsblock. Denna metod returnerar null om egenskapen är en förkortningsegenskap. Värden för förkortningsegenskaper kan endast nås och modifieras som strängar, med hjälp av metoderna getPropertyValue och setProperty. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Används för att hämta prioriteten för en CSS-egenskap (t.ex. qualifieraren "important") om egenskapen har satts explicit i detta deklarationsblock. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Används för att hämta värdet för en CSS-egenskap om den har satts explicit inom detta deklarationsblock. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Används för att ta bort en CSS-egenskap om den har satts explicit inom detta deklarationsblock. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Används för att sätta ett egenskapsvärde med standardprioritet inom detta deklarationsblock. Standardprioriteten är inte "important", d.v.s. String.Empty. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Används för att sätta ett egenskapsvärde och prioritet inom detta deklarationsblock. |

### Se även

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
