---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "FontMatcher MatchFontFallback-Methode. Diese Methode wird aufgerufen, wenn im Schriftarten‑Suchordner keine geeignete Schriftart gefunden wird. Sie sollte eine true type font basierend auf den fontMatchingProperties zurückgeben, die charCode rendern kann, oder null, wenn eine solche Schriftart nicht verfügbar ist."
type: docs
weight: 10
url: /de/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Diese Methode wird aufgerufen, wenn im Schriftarten‑Suchordner keine passende Schrift gefunden wird. Sie sollte eine echte Schriftart basierend auf den *fontMatchingProperties* zurückgeben, die *charCode* rendern kann, oder `null`, wenn eine solche Schrift nicht verfügbar ist.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschaften der übereinstimmenden Schriftart. |
| charCode | Int32 | Code des Zeichens, das mit der übereinstimmenden Schriftart gerendert wird. |

### Rückgabewert

Ein Byte‑Array, das die Schriftartdaten enthält, oder `null`.

### Siehe auch

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
