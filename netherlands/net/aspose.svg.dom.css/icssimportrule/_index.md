---
title: "ICSSImportRule Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSImportRule interface. De CSSImportRule interface vertegenwoordigt een importregel binnen een CSS‑stylesheet. De importregel wordt gebruikt om stijlregels uit andere stylesheets te importeren."
type: docs
weight: 2560
url: /nl/net/aspose.svg.dom.css/icssimportrule/
---
## ICSSImportRule interface

De CSSImportRule interface vertegenwoordigt een @import‑regel binnen een CSS‑stylesheet. De @import‑regel wordt gebruikt om stijlregels van andere stylesheets te importeren.

```csharp
public interface ICSSImportRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Href](../../aspose.svg.dom.css/icssimportrule/href/) { get; } | De locatie van de stylesheet die geïmporteerd moet worden. Het attribuut zal de "url(...)"‑specificatie rond de URI niet bevatten. |
| [Media](../../aspose.svg.dom.css/icssimportrule/media/) { get; } | Een lijst van mediatypen waarvoor deze stylesheet kan worden gebruikt. |
| [StyleSheet](../../aspose.svg.dom.css/icssimportrule/stylesheet/) { get; } | Het stijlblad waarnaar deze regel verwijst, indien het is geladen. De waarde van dit attribuut is null als het stijlblad nog niet is geladen of als het niet zal worden geladen (bijv. als het stijlblad bedoeld is voor een mediatype dat niet wordt ondersteund door de user agent). |

### Zie ook

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
