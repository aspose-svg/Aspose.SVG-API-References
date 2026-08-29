---
title: "ICSSStyleDeclaration Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSStyleDeclaration interface. De CSSStyleDeclaration interface vertegenwoordigt een enkel CSS-declaratieblok. Deze interface kan worden gebruikt om de stijl‑eigenschappen die momenteel in een blok zijn ingesteld te bepalen of om stijl‑eigenschappen expliciet binnen het blok in te stellen"
type: docs
weight: 2640
url: /nl/net/aspose.svg.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

De CSSStyleDeclaration interface vertegenwoordigt een enkel CSS-declaratieblok. Deze interface kan worden gebruikt om de stijl‑eigenschappen die momenteel in een blok zijn ingesteld te bepalen of om stijl‑eigenschappen expliciet binnen het blok in te stellen.

```csharp
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<string>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssstyledeclaration/csstext/) { get; set; } | De parseerbare tekstuele weergave van het declaratieblok (exclusief de omringende accolades). Het instellen van dit attribuut resulteert in het parseren van de nieuwe waarde en het resetten van alle eigenschappen in het declaratieblok, inclusief het verwijderen of toevoegen van eigenschappen. |
| [Item](../../aspose.svg.dom.css/icssstyledeclaration/item/) { get; } | Gebruikt om de eigenschappen op te halen die expliciet zijn ingesteld in dit declaratieblok. De volgorde van de opgehaalde eigenschappen met deze methode hoeft niet overeen te komen met de volgorde waarin ze zijn ingesteld. Deze methode kan worden gebruikt om over alle eigenschappen in dit declaratieblok te itereren. |
| [Length](../../aspose.svg.dom.css/icssstyledeclaration/length/) { get; } | Het aantal eigenschappen dat expliciet is ingesteld in dit declaratieblok. Het bereik van geldige indexen is 0 tot en met length-1. |
| [ParentRule](../../aspose.svg.dom.css/icssstyledeclaration/parentrule/) { get; } | De CSS-regel die dit declaratieblok bevat of null als deze CSSStyleDeclaration niet is gekoppeld aan een CSSRule. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [GetPropertyCSSValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertycssvalue/)(*string*) | Gebruikt om de objectrepresentatie van de waarde van een CSS-eigenschap op te halen als deze expliciet is ingesteld binnen dit declaratieblok. Deze methode retourneert null als de eigenschap een verkorte eigenschap is. Waarden van verkorte eigenschappen kunnen alleen als strings worden benaderd en gewijzigd, met behulp van de getPropertyValue- en setProperty-methoden. |
| [GetPropertyPriority](../../aspose.svg.dom.css/icssstyledeclaration/getpropertypriority/)(*string*) | Gebruikt om de prioriteit van een CSS-eigenschap op te halen (bijv. de \"important\" qualifier) als de eigenschap expliciet is ingesteld in dit declaratieblok. |
| [GetPropertyValue](../../aspose.svg.dom.css/icssstyledeclaration/getpropertyvalue/)(*string*) | Gebruikt om de waarde van een CSS-eigenschap op te halen als deze expliciet is ingesteld binnen dit declaratieblok. |
| [RemoveProperty](../../aspose.svg.dom.css/icssstyledeclaration/removeproperty/)(*string*) | Gebruikt om een CSS-eigenschap te verwijderen als deze expliciet is ingesteld binnen dit declaratieblok. |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty)(*string, string*) | Gebruikt om een eigenschapswaarde in te stellen met de standaardprioriteit binnen dit declaratieblok. Standaardprioriteit is niet \"important\", d.w.z. String.Empty |
| [SetProperty](../../aspose.svg.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(*string, string, string*) | Gebruikt om een eigenschapswaarde en prioriteit in te stellen binnen dit declaratieblok. |

### Zie ook

* interface [ICSS2Properties](../icss2properties/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
