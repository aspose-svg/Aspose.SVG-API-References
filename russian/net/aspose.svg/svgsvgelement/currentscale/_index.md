---
title: "SVGSVGElement.CurrentScale"
second_title: "Aspose.SVG для .NET справочник API"
description: "Свойство SVGSVGElement CurrentScale. На внешнем (outermost) элементе svg этот атрибут указывает текущий коэффициент масштабирования относительно начального представления, учитывая масштабирование пользователем и операции панорамирования, как описано в разделе «Масштабирование и панорамирование». DOM‑атрибуты currentScale и currentTranslate эквивалентны 2×3 матрице a b c d e f  currentScale 0 0 currentScale currentTranslate.x currentTranslate.y. Если масштабирование включено, т.е. zoomAndPanmagnify, эффект аналогичен добавлению дополнительного преобразования на внешнем уровне фрагмента SVG‑документа, т.е. за пределами внешнего элемента svg. При доступе к этому атрибуту на элементе svg, который не является внешним, поведение атрибута не определено."
type: docs
weight: 10
url: /ru/net/aspose.svg/svgsvgelement/currentscale/
---
## SVGSVGElement.CurrentScale property

На внешнем (самом наружном) элементе svg этот атрибут указывает текущий коэффициент масштабирования относительно начального представления, учитывая увеличение и операции панорамирования пользователем, как описано в разделе «Увеличение и панорамирование». Атрибуты DOM currentScale и currentTranslate эквивалентны 2x3 матрице [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Если "magnification" включено (т.е. zoomAndPan="magnify"), то эффект такой, как будто дополнительное преобразование размещено на самом внешнем уровне фрагмента SVG‑документа (т.е. за пределами внешнего элемента svg). При доступе к элементу ‘svg’, который не является внешним элементом svg, поведение этого атрибута не определено.

```csharp
public float CurrentScale { get; set; }
```

### Property Value

Текущий масштаб.

### См. также

* class [SVGSVGElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
