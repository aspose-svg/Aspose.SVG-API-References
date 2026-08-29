---
title: "Класс CSSPrimitiveValue"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Dom.Css.CSSPrimitiveValue class. Интерфейс CSSPrimitiveValue представляет отдельное CSS‑значение. Этот интерфейс может использоваться для определения значения конкретного свойства стиля, установленного в блоке, или для явного задания конкретного свойства стиля внутри блока. Экземпляр этого интерфейса может быть получен с помощью метода getPropertyCSSValue интерфейса CSSStyleDeclaration. Объект CSSPrimitiveValue встречается только в контексте CSS‑свойства."
type: docs
weight: 2480
url: /ru/net/aspose.svg.dom.css/cssprimitivevalue/
---
## CSSPrimitiveValue class

Интерфейс CSSPrimitiveValue представляет отдельное значение CSS. Этот интерфейс может использоваться для определения значения конкретного свойства стиля, текущего установленного в блоке, или для явного установки конкретного свойства стиля внутри блока. Экземпляр этого интерфейса может быть получен с помощью метода getPropertyCSSValue интерфейса CSSStyleDeclaration. Объект CSSPrimitiveValue встречается только в контексте свойства CSS.

```csharp
public abstract class CSSPrimitiveValue : CSSValue
```

## Свойства

| Имя | Описание |
| --- | --- |
| abstract [CSSText](../../aspose.svg.dom.css/cssvalue/csstext/) { get; set; } | Свойство CSSText интерфейса [`CSSValue`](../cssvalue/) представляет текущее вычисленное значение свойства CSS. |
| [CSSValueType](../../aspose.svg.dom.css/cssvalue/cssvaluetype/) { get; } | Код, определяющий тип значения. |
| [PrimitiveType](../../aspose.svg.dom.css/cssprimitivevalue/primitivetype/) { get; } | Тип значения, определённый константами, указанными выше. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.svg.dom.css/cssvalue/equals/)(*object*) | Определяет, равен ли указанный объект этому экземпляру. |
| abstract [GetCounterValue](../../aspose.svg.dom.css/cssprimitivevalue/getcountervalue/)() | Этот метод используется для получения значения Counter. Если данное CSS‑значение не содержит значения счётчика, генерируется DOMException. Изменение соответствующего свойства стиля может быть выполнено с помощью интерфейса Counter. |
| abstract [GetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/getfloatvalue/)(*ushort*) | Этот метод используется для получения значения типа float в указанной единице измерения. Если данное CSS‑значение не содержит значения float или не может быть преобразовано в указанную единицу, генерируется DOMException. |
| override [GetHashCode](../../aspose.svg.dom.css/cssvalue/gethashcode/)() | Возвращает хеш‑код для этого экземпляра. |
| abstract [GetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/getintvalue/)(*ushort*) | Этот метод используется для получения значения типа int в указанной единице измерения. Если данное CSS‑значение не содержит значения int или не может быть преобразовано в указанную единицу, генерируется DOMException. |
| override [GetPlatformType](../../aspose.svg.dom.css/cssvalue/getplatformtype/)() | Этот метод используется для получения типа объекта ECMAScript. |
| abstract [GetRectValue](../../aspose.svg.dom.css/cssprimitivevalue/getrectvalue/)() | Этот метод используется для получения значения Rect. Если данное CSS‑значение не содержит значения rect, генерируется DOMException. Изменение соответствующего свойства стиля может быть выполнено с помощью интерфейса Rect. |
| abstract [GetRGBColorValue](../../aspose.svg.dom.css/cssprimitivevalue/getrgbcolorvalue/)() | Этот метод используется для получения цвета RGB. Если данное CSS‑значение не содержит значения цвета RGB, генерируется DOMException. Изменение соответствующего свойства стиля может быть выполнено с помощью интерфейса RGBColor. |
| abstract [GetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/getstringvalue/)() | Этот метод используется для получения строкового значения. Если CSS‑значение не содержит строкового значения, генерируется DOMException. |
| abstract [SetFloatValue](../../aspose.svg.dom.css/cssprimitivevalue/setfloatvalue/)(*ushort, float*) | Метод для установки значения типа float с указанной единицей измерения. Если свойство, к которому привязано это значение, не может принимать указанную единицу или значение float, значение останется неизменным, и будет сгенерирован DOMException. |
| abstract [SetIntValue](../../aspose.svg.dom.css/cssprimitivevalue/setintvalue/)(*ushort, int*) | Метод для установки значения типа int с указанной единицей. Если свойство, связанное с этим значением, не может принять указанную единицу или значение типа int, значение останется неизменным, и будет выброшено DOMException. |
| abstract [SetStringValue](../../aspose.svg.dom.css/cssprimitivevalue/setstringvalue/)(*ushort, string*) | Метод для установки строкового значения с указанной единицей. Если свойство, связанное с этим значением, не может принять указанную единицу или строковое значение, значение останется неизменным, и будет выброшено DOMException. |
| override [ToString](../../aspose.svg.dom.css/cssvalue/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [CSS_ATTR](../../aspose.svg.dom.css/cssprimitivevalue/css_attr/) | Значение представляет собой функцию атрибута. Значение можно получить с помощью метода getStringValue. |
| const [CSS_CH](../../aspose.svg.dom.css/cssprimitivevalue/css_ch/) | Значение — длина (ch). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_CM](../../aspose.svg.dom.css/cssprimitivevalue/css_cm/) | Значение — длина (cm). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_COUNTER](../../aspose.svg.dom.css/cssprimitivevalue/css_counter/) | Значение представляет собой функцию counter или counters. Значение можно получить с помощью метода GetCounterValue. |
| const [CSS_DEG](../../aspose.svg.dom.css/cssprimitivevalue/css_deg/) | Значение — угол (deg). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DIMENSION](../../aspose.svg.dom.css/cssprimitivevalue/css_dimension/) | Значение — число с неизвестным измерением. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_DPCM](../../aspose.svg.dom.css/cssprimitivevalue/css_dpcm/) | Значение — точек на сантиметр (dpcm). |
| const [CSS_DPI](../../aspose.svg.dom.css/cssprimitivevalue/css_dpi/) | Значение — точек на дюйм (dpi). |
| const [CSS_DPPX](../../aspose.svg.dom.css/cssprimitivevalue/css_dppx/) | Значение — точек на единицу ‘px’ (dppx). |
| const [CSS_EMS](../../aspose.svg.dom.css/cssprimitivevalue/css_ems/) | Значение — длина (ems). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_EXS](../../aspose.svg.dom.css/cssprimitivevalue/css_exs/) | Значение — длина (exs). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_FR](../../aspose.svg.dom.css/cssprimitivevalue/css_fr/) | Гибкая длина или flex — это измерение с единицей fr, которое представляет собой долю оставшегося пространства в контейнере сетки. |
| const [CSS_GRAD](../../aspose.svg.dom.css/cssprimitivevalue/css_grad/) | Значение — угол (grad). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_HZ](../../aspose.svg.dom.css/cssprimitivevalue/css_hz/) | Значение — частота (Hz). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_IDENT](../../aspose.svg.dom.css/cssprimitivevalue/css_ident/) | Значение — идентификатор. Значение можно получить с помощью метода getStringValue. |
| const [CSS_IN](../../aspose.svg.dom.css/cssprimitivevalue/css_in/) | Значение — длина (in). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_KHZ](../../aspose.svg.dom.css/cssprimitivevalue/css_khz/) | Значение — частота (kHz). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MM](../../aspose.svg.dom.css/cssprimitivevalue/css_mm/) | Значение — длина (mm). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_MS](../../aspose.svg.dom.css/cssprimitivevalue/css_ms/) | Значение — время (ms). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_NUMBER](../../aspose.svg.dom.css/cssprimitivevalue/css_number/) | Значение — простое число. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PC](../../aspose.svg.dom.css/cssprimitivevalue/css_pc/) | Значение — длина (pc). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PERCENTAGE](../../aspose.svg.dom.css/cssprimitivevalue/css_percentage/) | Значение — процент. Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PT](../../aspose.svg.dom.css/cssprimitivevalue/css_pt/) | Значение — длина (pt). Значение можно получить с помощью метода getFloatValue. |
| const [CSS_PX](../../aspose.svg.dom.css/cssprimitivevalue/css_px/) | Значение — это длина (px). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RAD](../../aspose.svg.dom.css/cssprimitivevalue/css_rad/) | Значение — это угол (rad). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RECT](../../aspose.svg.dom.css/cssprimitivevalue/css_rect/) | Значение — это функция rect. Значение можно получить, используя метод GetRectValue. |
| const [CSS_REM](../../aspose.svg.dom.css/cssprimitivevalue/css_rem/) | Значение — это длина (rem). Значение можно получить, используя метод getFloatValue. |
| const [CSS_RGBCOLOR](../../aspose.svg.dom.css/cssprimitivevalue/css_rgbcolor/) | Значение — это цвет RGB. Значение можно получить, используя метод GetRGBColorValue. |
| const [CSS_S](../../aspose.svg.dom.css/cssprimitivevalue/css_s/) | Значение — это время (s). Значение можно получить, используя метод getFloatValue. |
| const [CSS_STRING](../../aspose.svg.dom.css/cssprimitivevalue/css_string/) | Значение — это STRING. Значение можно получить, используя метод getStringValue. |
| const [CSS_UNKNOWN](../../aspose.svg.dom.css/cssprimitivevalue/css_unknown/) | Значение не является распознанным значением CSS2. Значение можно получить только с помощью атрибута cssText. |
| const [CSS_URI](../../aspose.svg.dom.css/cssprimitivevalue/css_uri/) | Значение — это URI. Значение можно получить, используя метод getStringValue. |
| const [CSS_VH](../../aspose.svg.dom.css/cssprimitivevalue/css_vh/) | Значение — это процент от полной высоты области просмотра. |
| const [CSS_VMAX](../../aspose.svg.dom.css/cssprimitivevalue/css_vmax/) | Значение — это процент от ширины или высоты области просмотра, в зависимости от того, что больше. |
| const [CSS_VMIN](../../aspose.svg.dom.css/cssprimitivevalue/css_vmin/) | Значение — это процент от ширины или высоты области просмотра, в зависимости от того, что меньше. |
| const [CSS_VW](../../aspose.svg.dom.css/cssprimitivevalue/css_vw/) | Значение — это процент от полной ширины области просмотра. |
| const [CSS_X](../../aspose.svg.dom.css/cssprimitivevalue/css_x/) | Значение — это точек на единицу ‘px’ (x). |

### См. также

* class [CSSValue](../cssvalue/)
* namespace [Aspose.Svg.Dom.Css](../../aspose.svg.dom.css/)
* assembly [Aspose.SVG](../../)
