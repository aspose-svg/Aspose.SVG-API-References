---
title: "SVGBuilderExtensions.OnWaiting"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод SVGBuilderExtensions OnWaiting. Устанавливает атрибут события onwaiting для обработки событий, когда воспроизведение медиа задерживается из‑за буферизации данных."
type: docs
weight: 1850
url: /ru/net/aspose.svg.builder/svgbuilderextensions/onwaiting/
---
## SVGBuilderExtensions.OnWaiting<TBuilder> method

Устанавливает атрибут события 'onwaiting' для обработки событий, когда воспроизведение медиа задерживается из‑за буферизации данных.

```csharp
public static TBuilder OnWaiting<TBuilder>(this TBuilder builder, string value)
    where TBuilder : ISVGElementBuilder, IGlobalEventAttributeSetter
```

| Параметр | Описание |
| --- | --- |
| TBuilder | Тип билдера SVG‑элемента. |
| билдер | Билдер SVG‑элемента. |
| значение | The JavaScript‑функция или скрипт, который будет выполнен, когда воспроизведение медиа задерживается из‑за буферизации. |

### Возвращаемое значение

Экземпляр билдера для цепочки вызовов.

### См. также

* interface [ISVGElementBuilder](../../isvgelementbuilder/)
* interface [IGlobalEventAttributeSetter](../../iglobaleventattributesetter/)
* class [SVGBuilderExtensions](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
