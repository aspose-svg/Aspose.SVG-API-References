---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG för .NET API-referens"
description: "FontMatcher MatchFontFallback method. Denna metod anropas om ingen lämplig teckensnitt hittas i teckensnittens sökmapp. Den ska returnera ett TrueType-teckensnitt baserat på fontMatchingProperties som kan rendera charCode eller null om ett sådant teckensnitt inte är tillgängligt"
type: docs
weight: 10
url: /sv/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Denna metod anropas om det inte finns något lämpligt teckensnitt i teckensnittssökmapparna. Den bör returnera ett TrueType-teckensnitt baserat på *fontMatchingProperties* som kan rendera *charCode*, eller `null` om ett sådant teckensnitt inte är tillgängligt.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Egenskaper för det matchade teckensnittet. |
| charCode | Int32 | Kod för tecknet som kommer att renderas med det matchade teckensnittet. |

### Returvärde

En byte-array som innehåller teckensnittets data eller `null`.

### Se även

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
