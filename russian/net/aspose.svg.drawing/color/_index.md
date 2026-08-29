---
title: "Color Класс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Drawing.Color класс. Класс Color позволяет задавать цвета как значения Red-Green-Blue RGB, значения Hue-Saturation-Luminosity HSL, значения Hue-Saturation-Value HSV, значения Hue-Whiteness-Blackness HWB, значения lightness-A-B LAB, значения Luminance-Chroma-Hue LCH, значения Cyan-Magenta-Yellow-Key CMYK, значения Natural colors NCOL или по имени цвета. Также доступен альфа‑канал для указания прозрачности."
type: docs
weight: 3390
url: /ru/net/aspose.svg.drawing/color/
---
## Color class

Класс Color позволяет задавать цвета в виде значений Red-Green-Blue (RGB), Hue-Saturation-Luminosity (HSL), Hue-Saturation-Value (HSV), Hue-Whiteness-Blackness (HWB), lightness-A-B (LAB), Luminance-Chroma-Hue (LCH), Cyan-Magenta-Yellow-Key (CMYK), Natural colors (NCOL) или по имени цвета. Также доступен альфа‑канал для указания прозрачности.

```csharp
public class Color
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Color](color/#constructor)() | Инициализирует новый экземпляр класса `Color`. По умолчанию цвет черный. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_5)(*float, float, float*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑1. |
| [Color](color/#constructor_3)(*int, int, int*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑255. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑1. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Инициализирует новый экземпляр класса `Color`. Все цветовые компоненты должны находиться в диапазоне 0‑255. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Alpha](../../aspose.svg.drawing/color/alpha/) { get; } | Представляет альфа‑компонент цвета. |
| [Blue](../../aspose.svg.drawing/color/blue/) { get; } | Представляет синий компонент цвета. |
| [Green](../../aspose.svg.drawing/color/green/) { get; } | Представляет зеленый компонент цвета. |
| [Red](../../aspose.svg.drawing/color/red/) { get; } | Представляет красный компонент цвета. |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromCmyk](../../aspose.svg.drawing/color/fromcmyk/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями cyan, magenta, yellow, key (black). |
| static [FromCmyka](../../aspose.svg.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Возвращает новый Color с запрошенными значениями cyan, magenta, yellow, key (black), alpha. |
| static [FromGray](../../aspose.svg.drawing/color/fromgray/)(*float*) | Возвращает новый Color с запрошенным значением gray. |
| static [FromHsl](../../aspose.svg.drawing/color/fromhsl/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями hue, saturation, saturation. |
| static [FromHsla](../../aspose.svg.drawing/color/fromhsla/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями hue, saturation, saturation, alpha. |
| static [FromHsv](../../aspose.svg.drawing/color/fromhsv/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями hue, saturation, value. |
| static [FromHsva](../../aspose.svg.drawing/color/fromhsva/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями hue, saturation, value, alpha. |
| static [FromHwb](../../aspose.svg.drawing/color/fromhwb/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями hue, whiteness, blackness. |
| static [FromHwba](../../aspose.svg.drawing/color/fromhwba/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями hue, whiteness, blackness. |
| static [FromInt](../../aspose.svg.drawing/color/fromint/)(*int*) | Возвращает новый Color с запрошенным значением ARGB. |
| static [FromLab](../../aspose.svg.drawing/color/fromlab/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями lightness, A, B. |
| static [FromLaba](../../aspose.svg.drawing/color/fromlaba/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями lightness, A, B, alpha. |
| static [FromLch](../../aspose.svg.drawing/color/fromlch/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями luminance, chroma, hue. |
| static [FromLcha](../../aspose.svg.drawing/color/fromlcha/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями luminance, chroma, hue, alpha. |
| static [FromOklab](../../aspose.svg.drawing/color/fromoklab/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями lightness, A, B для модели OKLAB. |
| static [FromOklaba](../../aspose.svg.drawing/color/fromoklaba/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями lightness, A, B, alpha для модели OKLAB. |
| static [FromOklch](../../aspose.svg.drawing/color/fromoklch/)(*float, float, float*) | Возвращает новый Color с запрошенными значениями luminance, chroma, hue для модели OKLAB. |
| static [FromOklcha](../../aspose.svg.drawing/color/fromoklcha/)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями luminance, chroma, hue, alpha для модели OKLAB. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны находиться в диапазоне 0-255. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны находиться в диапазоне 0-1. |
| static [FromRgb](../../aspose.svg.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Возвращает новый Color с запрошенными значениями ged, green, blue. Все компоненты цвета должны находиться в диапазоне 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Возвращает новый Color с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны находиться в диапазоне 0-255. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Возвращает новый Color с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны находиться в диапазоне 0-1. |
| static [FromRgba](../../aspose.svg.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Возвращает новый Color с запрошенными значениями ged, green, blue, alpha. Все компоненты цвета должны находиться в диапазоне 0-255. |
| static [FromString](../../aspose.svg.drawing/color/fromstring/)(*string*) | Разбирает строку, содержащую CSS-цвет, и возвращает новый Color. |
| static [FromUint](../../aspose.svg.drawing/color/fromuint/)(*uint*) | Возвращает новый Color с запрошенным значением ARGB. |
| [AddLuminosity](../../aspose.svg.drawing/color/addluminosity/)(*float*) | Создаёт копию Color с суммой её яркости и значения дельты. |
| [Convert](../../aspose.svg.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Возвращает компоненты цвета в формате указанной цветовой модели. |
| override [Equals](../../aspose.svg.drawing/color/equals/)(*object*) | Определяет, равен ли указанный `Color` этому экземпляру. |
| [GetComplementary](../../aspose.svg.drawing/color/getcomplementary/)() | Возвращает новый цвет, находящийся на противоположной стороне цветового круга от оригинала. |
| override [GetHashCode](../../aspose.svg.drawing/color/gethashcode/)() | Возвращает хеш-код. |
| [GetHue](../../aspose.svg.drawing/color/gethue/)() | Возвращает Hue цвета Color. |
| [GetLuminosity](../../aspose.svg.drawing/color/getluminosity/)() | Возвращает luminosity цвета Color. |
| [GetSaturation](../../aspose.svg.drawing/color/getsaturation/)() | Возвращает saturation цвета Color. |
| [ToInt](../../aspose.svg.drawing/color/toint/)() | Кодирует компоненты ARGB цвета Color в тип int. |
| [ToName](../../aspose.svg.drawing/color/toname/)() | Возвращает имя цвета, если оно совпадает с цветом из списка именованных цветов CSS, иначе возвращает пустую строку. |
| [ToNaturalColorString](../../aspose.svg.drawing/color/tonaturalcolorstring/)(*int*) | Возвращает цвет, заданный Natural colors (NCol), используя буквенное обозначение цвета с числом, указывающим расстояние (в процентах) от исходного цвета. |
| [ToRgbaHexString](../../aspose.svg.drawing/color/torgbahexstring/)() | Возвращает шестнадцатеричный цвет, указанный как: #RRGGBBAA. |
| [ToRgbaString](../../aspose.svg.drawing/color/torgbastring/)() | Возвращает строку, содержащую RGBA‑цвет, указанный как: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.svg.drawing/color/torgbhexstring/)() | Возвращает шестнадцатеричный цвет, указанный как: #RRGGBB. |
| [ToRgbString](../../aspose.svg.drawing/color/torgbstring/)() | Возвращает строку, содержащую RGB‑цвет, указанный как: rgb(R, G, B). |
| override [ToString](../../aspose.svg.drawing/color/tostring/)() | Возвращает строку, состоящую из значений компонентов RGBA. |
| [ToUint](../../aspose.svg.drawing/color/touint/)() | Кодирует компоненты ARGB цвета Color в тип unsigned int. |
| [WithAlpha](../../aspose.svg.drawing/color/withalpha/)(*float*) | Создаёт копию цвета Color с указанным альфа‑компонентом. |
| [WithHue](../../aspose.svg.drawing/color/withhue/)(*float*) | Создаёт копию цвета Color с указанным Hue. |
| [WithLuminosity](../../aspose.svg.drawing/color/withluminosity/)(*float*) | Создаёт копию цвета Color с указанной luminosity. |
| [WithSaturation](../../aspose.svg.drawing/color/withsaturation/)(*float*) | Создаёт копию цвета Color с указанной saturation. |

### См. также

* namespace [Aspose.Svg.Drawing](../../aspose.svg.drawing/)
* assembly [Aspose.SVG](../../)
