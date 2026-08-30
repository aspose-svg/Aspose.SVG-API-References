---
title: "Renderer-1.Render"
second_title: "Aspose.SVG för .NET API-referens"
description: "Renderer Render-metod. Definierar metod för att rendera TSource till angiven IDevice"
type: docs
weight: 10
url: /sv/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

Definierar metod för att rendera *TSource* till angiven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| källa | TSource | Källan att rendera. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

Definierar metod för att rendera *TSource* till angiven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| källa | TSource | Källan att rendera. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

Definierar metod för att rendera *TSource* till angiven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| källa | TSource | Källan att rendera. |
| timeout | Int32 | Ett antal millisekunder som representerar antalet millisekunder att vänta, eller -1 millisekund för att vänta på obestämd tid. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

Definierar metod för att rendera flera *TSource*-objekt till en specifik [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| källor | TSource[] | Källorna att rendera. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

Definierar metod för att rendera flera *TSource*-objekt till en specifik [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| timeout | Int32 | Ett antal millisekunder som representerar antalet millisekunder att vänta, eller -1 millisekund för att vänta på obestämd tid. |
| källor | TSource[] | Källorna att rendera. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

Definierar metod för att rendera flera *TSource*-objekt till en specifik [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| timeout | TimeSpan | En TimeSpan som representerar antalet millisekunder att vänta, eller en TimeSpan som representerar -1 millisekund för att vänta på obestämd tid. |
| källor | TSource[] | Källorna att rendera. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

Definierar en metod för att rendera flera *TSource*-objekt till en specifik [`IDevice`](../../idevice/), med hjälp av en avbokningstoken för att begära avbrytning av operationen.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| device | IDevice | Utdataenheten. |
| cancellationToken | CancellationToken | En CancellationToken att observera medan du väntar på att uppgiften ska slutföras. |
| källor | TSource[] | Källorna att rendera. |

### Se även

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
