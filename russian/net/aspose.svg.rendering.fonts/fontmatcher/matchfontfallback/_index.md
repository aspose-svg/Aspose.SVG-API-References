---
title: "FontMatcher.MatchFontFallback"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод MatchFontFallback класса FontMatcher. Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт типа true type на основе fontMatchingProperties, который может отображать charCode, или null, если такой шрифт недоступен."
type: docs
weight: 10
url: /ru/net/aspose.svg.rendering.fonts/fontmatcher/matchfontfallback/
---
## FontMatcher.MatchFontFallback method

Этот метод вызывается, если в папках поиска шрифтов не найден подходящий шрифт. Он должен возвращать шрифт истинного типа на основе *fontMatchingProperties*, который может отрисовать *charCode*, или `null`, если такой шрифт недоступен.

```csharp
public abstract byte[] MatchFontFallback(FontMatchingProperties fontMatchingProperties, 
    int charCode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fontMatchingProperties | FontMatchingProperties | Свойства найденного шрифта. |
| charCode | Int32 | Код символа, который будет отрисован с использованием найденного шрифта. |

### Возвращаемое значение

Массив байтов, содержащий данные шрифтов, или `null`.

### См. также

* class [FontMatchingProperties](../../fontmatchingproperties/)
* class [FontMatcher](../)
* namespace [Aspose.Svg.Rendering.Fonts](../../../aspose.svg.rendering.fonts/)
* assembly [Aspose.SVG](../../../)
