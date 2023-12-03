---
title: Renderer-1.Render
second_title: Aspose.SVG for .NET API Reference
description: Renderer method. Defines method for rendering TSource into specified IDevice
type: docs
weight: 10
url: /net/aspose.svg.rendering/renderer-1/render/
---
## Render(IDevice, TSource) {#render_3}

Defines method for rendering !:TSource into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| source | TSource | The source to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, TSource, TimeSpan) {#render_5}

Defines method for rendering !:TSource into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| source | TSource | The source to render. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, TSource, int) {#render_4}

Defines method for rendering !:TSource into specified [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| source | TSource | The source to render. |
| timeout | Int32 | A number of milliseconds that represents the number of milliseconds to wait, or -1 millisecond to wait indefinitely. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, params TSource[]) {#render_6}

Defines method for rendering multiple !:TSources into specific [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| sources | TSource[] | The sources to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, int, params TSource[]) {#render}

Defines method for rendering multiple !:TSources into specific [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | Int32 | A number of milliseconds that represents the number of milliseconds to wait, or -1 millisecond to wait indefinitely. |
| sources | TSource[] | The sources to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, TimeSpan, params TSource[]) {#render_2}

Defines method for rendering multiple !:TSources into specific [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| timeout | TimeSpan | A TimeSpan that represents the number of milliseconds to wait, or a TimeSpan that represents -1 millisecond to wait indefinitely. |
| sources | TSource[] | The sources to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(IDevice, CancellationToken, params TSource[]) {#render_1}

Defines a method for rendering multiple !:TSources into a specific [`IDevice`](../../idevice/), using a cancellation token to request cancellation of the operation.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| Parameter | Type | Description |
| --- | --- | --- |
| device | IDevice | The output device. |
| cancellationToken | CancellationToken | A CancellationToken to observe while waiting for the task to complete. |
| sources | TSource[] | The sources to render. |

### See Also

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
