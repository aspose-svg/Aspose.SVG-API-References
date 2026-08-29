---
title: "SplinePathBuilder.Build"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Build класса SplinePathBuilder. Создает плавный путь через последовательность точек, преобразуя центростремительные сплайны CatmullRom в кривые Безье. Этот метод обеспечивает естественный и плавный переход через каждую точку, создавая SVG‑путь, который точно следует предоставленному трассировочному следу."
type: docs
weight: 50
url: /ru/net/aspose.svg.imagevectorization/splinepathbuilder/build/
---
## SplinePathBuilder.Build method

Создаёт плавный путь через последовательность точек, преобразуя центростремительные сплайны Catmull–Rom в кривые Безье. Этот метод обеспечивает естественный и плавный переход через каждую точку, создавая SVG‑путь, который точно следует предоставленной трассе.

```csharp
public string Build(IEnumerable<PointF> trace)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| трасса | IEnumerable`1 | Последовательность точек, которые необходимо интерполировать в плавный путь. |

### Возвращаемое значение

Строка, представляющая данные SVG‑пути, содержащая команды кривых Безье и координаты, приближающие центростремительный сплайн Catmull–Rom.

### См. также

* class [SplinePathBuilder](../)
* namespace [Aspose.Svg.ImageVectorization](../../../aspose.svg.imagevectorization/)
* assembly [Aspose.SVG](../../../)
