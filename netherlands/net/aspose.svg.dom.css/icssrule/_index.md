---
title: "ICSSRule interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSRule interface. De CSSRule-interface is de abstracte basisinterface voor elk type CSS-statement. Dit omvat zowel regelsets als at-rules. Van een implementatie wordt verwacht dat deze alle regels die in een CSS-stylesheet zijn gespecificeerd behoudt, zelfs als de regel niet wordt herkend door de parser. Niet-herkende regels worden weergegeven met behulp van de ICSSUnknownRule-interface."
type: docs
weight: 2620
url: /nl/net/aspose.svg.dom.css/icssrule/
---
## ICSSRule interface

De CSSRule interface is de abstracte basisinterface voor elk type CSS‑statement. Dit omvat zowel regelsets als at-rules. Van een implementatie wordt verwacht alle regels die in een CSS-stylesheet zijn gespecificeerd te behouden, zelfs als de regel niet door de parser wordt herkend. Niet-herkende regels worden weergegeven met behulp van de ICSSUnknownRule interface.

```csharp
public interface ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSText](../../aspose.svg.dom.css/icssrule/csstext/) { get; set; } | De parseerbare tekstuele weergave van de regel. Dit weerspiegelt de huidige staat van de regel en niet de oorspronkelijke waarde. |
| [ParentRule](../../aspose.svg.dom.css/icssrule/parentrule/) { get; } | Als deze regel zich binnen een andere regel bevindt (bijv. een stijlregel binnen een @media-blok), is dit de omvattende regel. Als deze regel niet genest is binnen andere regels, wordt null geretourneerd. |
| [ParentStyleSheet](../../aspose.svg.dom.css/icssrule/parentstylesheet/) { get; } | Het stylesheet dat deze regel bevat. |
| [Type](../../aspose.svg.dom.css/icssrule/type/) { get; } | Het type van de regel, zoals hierboven gedefinieerd. Er wordt verwacht dat bindingspecifieke castmethoden kunnen worden gebruikt om van een instantie van de CSSRule-interface naar de specifieke afgeleide interface die door het type wordt geïmpliceerd, te casten. |

### Zie ook

* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
