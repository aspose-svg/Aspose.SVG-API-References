---
title: "Renderer-1.Render"
second_title: "Aspose.SVG for .NET API 参考"
description: "Renderer Render 方法。定义将 TSource 渲染到指定 IDevice 的方法"
type: docs
weight: 10
url: /zh/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

定义将 *TSource* 渲染到指定 [`IDevice`](../../idevice/) 的方法。

```csharp
public void Render(IDevice device, TSource source)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 源 | TSource | 要渲染的源。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

定义将 *TSource* 渲染到指定 [`IDevice`](../../idevice/) 的方法。

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 源 | TSource | 要渲染的源。 |
| 超时 | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

定义将 *TSource* 渲染到指定 [`IDevice`](../../idevice/) 的方法。

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 源 | TSource | 要渲染的源。 |
| 超时 | Int32 | 一个毫秒数，表示要等待的毫秒数，或 -1 毫秒以无限期等待。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

定义将多个 *TSource* 渲染到特定 [`IDevice`](../../idevice/) 的方法。

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 源 | TSource[] | 要渲染的源。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

定义将多个 *TSource* 渲染到特定 [`IDevice`](../../idevice/) 的方法。

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 超时 | Int32 | 一个毫秒数，表示要等待的毫秒数，或 -1 毫秒以无限期等待。 |
| 源 | TSource[] | 要渲染的源。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

定义将多个 *TSource* 渲染到特定 [`IDevice`](../../idevice/) 的方法。

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| 超时 | TimeSpan | 一个 TimeSpan，表示要等待的毫秒数，或表示 -1 毫秒以无限期等待的 TimeSpan。 |
| 源 | TSource[] | 要渲染的源。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

定义一个方法，将多个 *TSource* 渲染到特定 [`IDevice`](../../idevice/)，使用取消令牌请求取消操作。

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 设备 | IDevice | 输出设备。 |
| cancellationToken | CancellationToken | 在等待任务完成期间用于观察的 CancellationToken。 |
| 源 | TSource[] | 要渲染的源。 |

### 另请参阅

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
