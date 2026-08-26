---
title: "Renderer-1.Render"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Renderer Render-Methode. Definiert eine Methode zum Rendern von TSource in das angegebene IDevice"
type: docs
weight: 10
url: /de/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| Quelle | TSource | Die Quelle zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| Quelle | TSource | Die Quelle zum Rendern. |
| timeout | TimeSpan | Ein TimeSpan, der die Anzahl der Millisekunden zum Warten darstellt, oder ein TimeSpan, der -1 Millisekunde für unbegrenztes Warten darstellt. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

Definiert eine Methode zum Rendern von *TSource* in das angegebene [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| Quelle | TSource | Die Quelle zum Rendern. |
| timeout | Int32 | Eine Anzahl von Millisekunden, die die zu wartende Zeit angibt, oder -1 Millisekunde für unbegrenztes Warten. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| Quellen | TSource[] | Die Quellen zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | Int32 | Eine Anzahl von Millisekunden, die die zu wartende Zeit angibt, oder -1 Millisekunde für unbegrenztes Warten. |
| Quellen | TSource[] | Die Quellen zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| timeout | TimeSpan | Ein TimeSpan, der die Anzahl der Millisekunden zum Warten darstellt, oder ein TimeSpan, der -1 Millisekunde für unbegrenztes Warten darstellt. |
| Quellen | TSource[] | Die Quellen zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

Definiert eine Methode zum Rendern mehrerer *TSource*s in ein bestimmtes [`IDevice`](../../idevice/), wobei ein CancellationToken verwendet wird, um den Abbruch des Vorgangs anzufordern.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| device | IDevice | Das Ausgabegerät. |
| cancellationToken | CancellationToken | Ein CancellationToken, der während des Wartens auf den Abschluss der Aufgabe beobachtet wird. |
| Quellen | TSource[] | Die Quellen zum Rendern. |

### Siehe auch

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
