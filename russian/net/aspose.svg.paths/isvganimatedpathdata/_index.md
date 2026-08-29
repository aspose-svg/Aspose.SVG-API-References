---
title: "ISVGAnimatedPathData Интерфейс"
second_title: "Aspose.SVG для .NET справочник API"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData интерфейс. Интерфейс SVGAnimatedPathData поддерживает элементы, которые имеют атрибут d, содержащий данные пути SVG, и поддерживает возможность анимировать этот атрибут"
type: docs
weight: 4550
url: /ru/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

Интерфейс SVGAnimatedPathData поддерживает элементы, имеющие атрибут ‘d’, содержащий данные пути SVG, и поддерживает возможность анимировать этот атрибут.

```csharp
public interface ISVGAnimatedPathData
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | Обеспечивает доступ к текущему анимированному содержимому атрибута ‘d’ в форме, полностью соответствующей синтаксису SVG. Если указанный атрибут или свойство анимируется, содержит текущее анимированное значение атрибута или свойства, и как объект, так и его содержимое доступны только для чтения. Если указанный атрибут или свойство в данный момент не анимируется, содержит то же значение, что и pathSegList. |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | Обеспечивает доступ к базовому (т.е. статическому) содержимому атрибута ‘d’ в форме, полностью соответствующей синтаксису SVG. Таким образом, если атрибут ‘d’ содержит команду "абсолютного перемещения (M)" и команду "абсолютного арка (A)", то pathSegList будет иметь две записи: SVG_PATHSEG_MOVETO_ABS и SVG_PATHSEG_ARC_ABS. |

### См. также

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
