---
title: "Renderer-1.Render"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Renderer Render. تحدد طريقة لتصيير TSource إلى IDevice المحدد."
type: docs
weight: 10
url: /ar/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

تحدد طريقة لتصيير *TSource* إلى IDevice المحدد [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| المصدر | TSource | المصدر لتصيره. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

تحدد طريقة لتصيير *TSource* إلى IDevice المحدد [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| المصدر | TSource | المصدر لتصيره. |
| timeout | TimeSpan | TimeSpan يمثل عدد المللي ثانية للانتظار، أو TimeSpan يمثل -1 مللي ثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

تحدد طريقة لتصيير *TSource* إلى IDevice المحدد [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| المصدر | TSource | المصدر لتصيره. |
| timeout | Int32 | عدد المللي ثانية الذي يمثل عدد المللي ثانية للانتظار، أو -1 مللي ثانية للانتظار إلى أجل غير مسمى. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

تحدد طريقة لتصيير عدة *TSource*s إلى IDevice محدد [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| المصادر | TSource[] | المصادر لتصيرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

تحدد طريقة لتصيير عدة *TSource*s إلى IDevice محدد [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| timeout | Int32 | عدد المللي ثانية الذي يمثل عدد المللي ثانية للانتظار، أو -1 مللي ثانية للانتظار إلى أجل غير مسمى. |
| المصادر | TSource[] | المصادر لتصيرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

تحدد طريقة لتصيير عدة *TSource*s إلى IDevice محدد [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| timeout | TimeSpan | TimeSpan يمثل عدد المللي ثانية للانتظار، أو TimeSpan يمثل -1 مللي ثانية للانتظار إلى أجل غير مسمى. |
| المصادر | TSource[] | المصادر لتصيرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

تحدد طريقة لتصير عدة *TSource*s إلى IDevice محدد [`IDevice`](../../idevice/)، باستخدام رمز إلغاء لطلب إلغاء العملية.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الجهاز | IDevice | جهاز الإخراج. |
| cancellationToken | CancellationToken | CancellationToken للمراقبة أثناء انتظار إكمال المهمة. |
| المصادر | TSource[] | المصادر لتصيرها. |

### انظر أيضًا

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
