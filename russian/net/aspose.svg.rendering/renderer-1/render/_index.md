---
title: "Renderer-1.Render"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Renderer Render. Определяет метод для рендеринга TSource в указанный IDevice"
type: docs
weight: 10
url: /ru/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| источник | TSource | Источник для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| источник | TSource | Источник для рендеринга. |
| timeout | TimeSpan | Объект TimeSpan, представляющий количество миллисекунд ожидания, или объект TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

Определяет метод для рендеринга *TSource* в указанный [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| источник | TSource | Источник для рендеринга. |
| timeout | Int32 | Количество миллисекунд, представляющее количество миллисекунд ожидания, или -1 миллисекунда для бесконечного ожидания. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| источники | TSource[] | Источники для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| timeout | Int32 | Количество миллисекунд, представляющее количество миллисекунд ожидания, или -1 миллисекунда для бесконечного ожидания. |
| источники | TSource[] | Источники для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| timeout | TimeSpan | Объект TimeSpan, представляющий количество миллисекунд ожидания, или объект TimeSpan, представляющий -1 миллисекунду для бесконечного ожидания. |
| источники | TSource[] | Источники для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

Определяет метод для рендеринга нескольких *TSource*s в конкретный [`IDevice`](../../idevice/), используя токен отмены для запроса отмены операции.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| устройство | IDevice | Выходное устройство. |
| cancellationToken | CancellationToken | Токен CancellationToken, наблюдаемый во время ожидания завершения задачи. |
| источники | TSource[] | Источники для рендеринга. |

### См. также

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
