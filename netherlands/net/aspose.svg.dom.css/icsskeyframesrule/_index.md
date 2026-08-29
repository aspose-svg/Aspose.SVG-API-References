---
title: "ICSSKeyframesRule Interface"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.Css.ICSSKeyframesRule interface. De CSSKeyframesRule‑interface vertegenwoordigt een volledige set keyframes voor één animatie."
type: docs
weight: 2580
url: /nl/net/aspose.svg.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

De CSSKeyframesRule interface vertegenwoordigt een volledige set van keyframes voor een enkele animatie.

```csharp
public interface ICSSKeyframesRule : ICSSRule
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CSSRules](../../aspose.svg.dom.css/icsskeyframesrule/cssrules/) { get; } | Dit attribuut geeft toegang tot de keyframes in de lijst. |
| [Name](../../aspose.svg.dom.css/icsskeyframesrule/name/) { get; } | Dit attribuut is de naam van de keyframes, gebruikt door de eigenschap ‘animation-name’. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AppendRule](../../aspose.svg.dom.css/icsskeyframesrule/appendrule/)(*string*) | De appendRule‑methode voegt de meegegeven CSSKeyframeRule toe aan de lijst op de opgegeven sleutel. |
| [DeleteRule](../../aspose.svg.dom.css/icsskeyframesrule/deleterule/)(*string*) | De deleteRule‑methode verwijdert de CSSKeyframeRule met de opgegeven sleutel. Als er geen regel met deze sleutel bestaat, doet de methode niets. |
| [FindRule](../../aspose.svg.dom.css/icsskeyframesrule/findrule/)(*string*) | De findRule‑methode retourneert de regel met een sleutel die overeenkomt met de opgegeven sleutel. Als zo’n regel niet bestaat, wordt een null‑waarde geretourneerd. |

### Zie ook

* interface [ICSSRule](../icssrule/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
