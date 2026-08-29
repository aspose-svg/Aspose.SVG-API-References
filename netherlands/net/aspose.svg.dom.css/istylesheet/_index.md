---
title: "IStyleSheet Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.IStyleSheet interface. De StyleSheet interface is de abstracte basisinterface voor elk type stylesheet. Het vertegenwoordigt een enkele stylesheet die is gekoppeld aan een gestructureerd document"
type: docs
weight: 2740
url: /nl/net/aspose.svg.dom.css/istylesheet/
---
## IStyleSheet interface

De StyleSheet interface is de abstracte basisinterface voor elk type stylesheet. Het vertegenwoordigt een enkele stylesheet die is gekoppeld aan een gestructureerd document.

```csharp
public interface IStyleSheet
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Disabled](../../aspose.svg.dom.css/istylesheet/disabled/) { get; set; } | false als de stylesheet is toegepast op het document. true als dat niet het geval is. Het wijzigen van dit attribuut kan een nieuwe resolutie van stijl voor het document veroorzaken. Een stylesheet wordt alleen toegepast als zowel een geschikte mediumdefinitie aanwezig is als het disabled-attribuut false is. Dus, als het medium niet van toepassing is op de huidige user agent, wordt het disabled-attribuut genegeerd. |
| [Href](../../aspose.svg.dom.css/istylesheet/href/) { get; } | Als het stijlblad een gekoppeld stijlblad is, is de waarde van zijn attribuut de locatie. Voor inline stijlbladen is de waarde van dit attribuut null. |
| [Media](../../aspose.svg.dom.css/istylesheet/media/) { get; } | Het beoogde bestemmingsmedium voor stijl‑informatie. |
| [OwnerNode](../../aspose.svg.dom.css/istylesheet/ownernode/) { get; } | Het knooppunt dat dit stijlblad aan het document koppelt. Voor HTML kan dit het overeenkomstige LINK‑ of STYLE‑element zijn. Voor XML kan dit de koppel‑verwerkingsinstructie zijn. Voor stijlbladen die door andere stijlbladen worden opgenomen, is de waarde van dit attribuut null. |
| [ParentStyleSheet](../../aspose.svg.dom.css/istylesheet/parentstylesheet/) { get; } | Voor stijlblad‑talen die het concept van stijlblad‑inclusie ondersteunen, vertegenwoordigt dit attribuut het includerende stijlblad, indien aanwezig. Als het stijlblad een top‑level stijlblad is, of de stijlblad‑taal geen inclusie ondersteunt, is de waarde van dit attribuut null. |
| [Title](../../aspose.svg.dom.css/istylesheet/title/) { get; } | De adviserende titel. |
| [Type](../../aspose.svg.dom.css/istylesheet/type/) { get; } | Dit geeft de stijlbladtaal voor dit stijlblad aan. De stijlbladtaal wordt gespecificeerd als een content‑type (bijv. "text/css"). |

### Zie ook

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
