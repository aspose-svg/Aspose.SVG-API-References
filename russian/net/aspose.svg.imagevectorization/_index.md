---
title: "Aspose.Svg.ImageVectorization"
second_title: "Aspose.SVG для .NET справочник API"
description: "Пространство имён Aspose.Svg.ImageVectorization содержит классы для векторизации растровых изображений и их преобразования в SVG‑документы. Этот процесс включает уменьшение битовых карт до геометрических фигур, состоящих из элементов пути, и их сохранение в виде SVG. Пространство имён включает классы для построения сегментов пути, упрощения и сглаживания точек трассировки, а также настройки параметров векторизации."
type: docs
weight: 190
url: /ru/net/aspose.svg.imagevectorization/
---
Пространство имён **Aspose.Svg.ImageVectorization** содержит классы для векторизации растровых изображений и их преобразования в SVG‑документы. Этот процесс включает преобразование битмапов в геометрические формы, состоящие из элементов пути, и их сохранение в виде SVG. Пространство имён включает классы для построения сегментов пути, упрощения и сглаживания точек трассировки, а также настройки параметров векторизации.

## Классы

| Класс | Описание |
| --- | --- |
| [BezierPathBuilder](./bezierpathbuilder/) | Класс [`BezierPathBuilder`](../aspose.svg.imagevectorization/bezierpathbuilder/) отвечает за построение кривой Безье из заданного набора точек. Он аппроксимирует трассировку точек кривой Безье, оптимизируя количество сегментов для точного соответствия оригинальной трассировке при минимизации сложности. |
| [ImageTraceSimplifier](./imagetracesimplifier/) | Класс ImageTraceSimplifier отвечает за уменьшение количества точек в кривой, аппроксимируемой серией точек трассировки. |
| [ImageTraceSmoother](./imagetracesmoother/) | Класс ImageTraceSimplifier отвечает за сглаживание количества точек в кривой, аппроксимируемой серией точек трассировки. Этот класс реализует подход ближайшего соседа. |
| [ImageVectorizer](./imagevectorizer/) | Этот класс ImageVectorizer векторизует растровые изображения, такие как PNG, JPG, GIF, BMP и т.д., и возвращает SVGDocument. Под векторизацией мы понимаем процесс преобразования битмапов в геометрические формы, состоящие из элементов пути и сохраняемые в виде SVG. |
| [ImageVectorizerConfiguration](./imagevectorizerconfiguration/) | Класс [`ImageVectorizerConfiguration`](../aspose.svg.imagevectorization/imagevectorizerconfiguration/) определяет конфигурацию методов и параметров векторизации изображений. Эта конфигурация используется для инициализации ImageVectorizer и предоставляет параметры конфигурации для векторизации изображений. |
| [SplinePathBuilder](./splinepathbuilder/) | Класс [`SplinePathBuilder`](../aspose.svg.imagevectorization/splinepathbuilder/) предназначен для построения гладкого пути путем преобразования центростремительных сплайнов Катмула–Рома в кривые Безье. Он предоставляет метод для генерации пути, который плавно интерполирует набор точек, обеспечивая баланс между точностью к точкам и гладкостью кривой. |
| [StencilConfiguration](./stencilconfiguration/) | Класс [`StencilConfiguration`](../aspose.svg.imagevectorization/stencilconfiguration/) определяет конфигурацию параметров эффекта трафарета. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IImageTraceSimplifier](./iimagetracesimplifier/) | Интерфейс IImageTraceSimplifier отвечает за уменьшение количества точек в трассировке. |
| [IImageTraceSmoother](./iimagetracesmoother/) | Интерфейс IImageTraceSmoother отвечает за сглаживание трассировки. |
| [IPathBuilder](./ipathbuilder/) | Интерфейс IPathBuilder отвечает за построение сегментов пути [`SVGPathSeg`](../aspose.svg.paths/svgpathseg/) из списка точек трассировки. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [StencilType](./stenciltype/) | Перечисление [`StencilType`](../aspose.svg.imagevectorization/stenciltype/) определяет типы трафаретов. |
