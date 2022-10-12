---
title: MatchFontFallback
second_title: Aspose.SVG for .NET API Referansı
description: Yazı tipi arama klasörlerinde uygun yazı tipi bulunamazsa bu yöntem çağrılır. fontMatchingProperties hangi işleyebilircharCode  veyahükümsüz böyle bir yazı tipi mevcut değilse.
type: docs
weight: 10
url: /tr/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Yazı tipi arama klasörlerinde uygun yazı tipi bulunamazsa bu yöntem çağrılır. *fontMatchingProperties* hangi işleyebilir*charCode* , veya`hükümsüz` böyle bir yazı tipi mevcut değilse.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    uint charCode)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Eşleşen yazı tipinin özellikleri. |
| charCode | UInt32 | Eşleşen yazı tipi kullanılarak oluşturulacak karakterin kodu. |

### Geri dönüş değeri

Yazı tipi verilerini içeren bir bayt dizisi veya`hükümsüz`.

### Ayrıca bakınız

* class [FontMatchingProperties](../../fontmatchingproperties)
* class [FontMatcher](../../fontmatcher)
* ad alanı [Aspose.Svg.Rendering.Fonts](../../fontmatcher)
* toplantı [Aspose.SVG](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->