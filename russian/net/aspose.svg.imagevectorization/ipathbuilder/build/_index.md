---
title: "IPathBuilder.Build"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Build интерфейса IPathBuilder. Оптимизирует заданную трассу в сегмент SVG‑пути, используя минимальное количество команд линий и кривых Безье для точного представления."
type: docs
weight: 10
url: /ru/net/aspose.svg.imagevectorization/ipathbuilder/build/
---
## IPathBuilder.Build method

Оптимизирует заданную трассировку в сегмент SVG‑пути, используя минимальное количество команд линий и кривых Безье для точного представления.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| трасса | IEnumerable`1 | Последовательность точек, описывающих трассу, которую необходимо оптимизировать в SVG‑путь. |

### Возвращаемое значение

Строка, представляющая сегмент пути SVG, эффективно приближающая оригинальный след с минимальным количеством команд линий и кривых Безье.

### См. также

* interface [IPathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
