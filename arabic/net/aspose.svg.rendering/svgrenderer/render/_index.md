---
title: "SvgRenderer.Render"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Render في SvgRenderer. تُعرّف طريقة لتصيير مستندات SVG المتعددة في IDevice محدد"
type: docs
weight: 20
url: /ar/net/aspose.svg.rendering/svgrenderer/render/
---
## Render(*[IDevice](../../idevice/), TimeSpan, params SVGDocument[]*) {#render_6}

تُعرّف طريقة لتصيير عدة [`SVGDocument`](../../../aspose.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد.

```csharp
public override void Render(IDevice device, TimeSpan timeout, params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| timeout | TimeSpan | TimeSpan يمثل عدد المللي ثانية للانتظار، أو TimeSpan يمثل -1 مللي ثانية للانتظار إلى أجل غير مسمى. |
| المصادر | SVGDocument[] | مستندات SVG التي سيتم تصييرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params SVGDocument[]*) {#render_5}

تُعرّف طريقة لتصيير عدة [`SVGDocument`](../../../aspose.svg/svgdocument/)s في [`IDevice`](../../idevice/) محدد، باستخدام رمز إلغاء لطلب إلغاء العملية.

```csharp
public override void Render(IDevice device, CancellationToken cancellationToken, 
    params SVGDocument[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | رمز إلغاء لمراقبته أثناء انتظار إكمال المهمة. |
| المصادر | SVGDocument[] | مستندات SVG التي سيتم تصييرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [SVGDocument](../../../aspose.svg/svgdocument/)
* class [SvgRenderer](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
