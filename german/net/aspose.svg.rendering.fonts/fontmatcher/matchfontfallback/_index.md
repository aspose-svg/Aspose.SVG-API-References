---
title: FontMatcher.MatchFontFallback
second_title: Aspose.SVG für .NET-API-Referenz
description: FontMatcher methode. Diese Methode wird aufgerufen wenn in den SchriftartenSuchordnern keine geeignete Schriftart gefunden wird. Sie sollte basierend auf der True TypeSchriftart zurückgebenfontMatchingProperties was rendern kanncharCode  oderNull wenn eine solche Schriftart nicht verfügbar ist.
type: docs
weight: 10
url: /de/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Diese Methode wird aufgerufen, wenn in den Schriftarten-Suchordnern keine geeignete Schriftart gefunden wird. Sie sollte basierend auf der True Type-Schriftart zurückgeben*fontMatchingProperties* was rendern kann*charCode* , oder`Null` wenn eine solche Schriftart nicht verfügbar ist.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eigenschaften der übereinstimmenden Schriftart. |
| charCode | UInt32 | Code des Zeichens, das mit der angepassten Schriftart gerendert wird. |

### Rückgabewert

Ein Byte-Array mit den Schriftdaten oder`Null`.

### Siehe auch

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namensraum [Aspose.Svg.Rendering.Fonts](../../fontmatcher/)
* Montage [Aspose.SVG](../../../)


