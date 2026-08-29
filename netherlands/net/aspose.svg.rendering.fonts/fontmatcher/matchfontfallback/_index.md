---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "FontMatcher MatchFontFallback methode. Deze methode wordt aangeroepen als er geen geschikt lettertype wordt gevonden in de lettertype‑zoekmappen. Het moet een true type font retourneren op basis van de fontMatchingProperties die charCode kan renderen of null als zo'n lettertype niet beschikbaar is"
type: docs
weight: 10
url: /nl/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Deze methode wordt aangeroepen als er geen geschikt lettertype wordt gevonden in de lettertype‑zoekmappen. Het moet een true‑type lettertype retourneren op basis van de *fontMatchingProperties* die *charCode* kan renderen, of `null` als zo'n lettertype niet beschikbaar is.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschappen van het overeenkomende lettertype. |
| charCode | Int32 | Code van het teken dat zal worden gerenderd met het overeenkomende lettertype. |

### Retourwaarde

Een byte‑array met de lettertype‑gegevens of `null`.

### Zie ook

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
