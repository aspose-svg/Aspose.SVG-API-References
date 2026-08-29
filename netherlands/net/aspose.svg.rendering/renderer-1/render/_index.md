---
title: "Renderer-1.Render"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Renderer Render-methode. Definieert een methode voor het renderen van TSource naar het opgegeven IDevice"
type: docs
weight: 10
url: /nl/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

Definieert een methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| bron | TSource | De bron om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

Definieert een methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| bron | TSource | De bron om te renderen. |
| timeout | TimeSpan | Een TimeSpan die het aantal milliseconden vertegenwoordigt om te wachten, of een TimeSpan die -1 milliseconde vertegenwoordigt om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

Definieert een methode voor het renderen van *TSource* naar het opgegeven [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| bron | TSource | De bron om te renderen. |
| timeout | Int32 | Een aantal milliseconden dat het aantal milliseconden vertegenwoordigt om te wachten, of -1 milliseconde om onbeperkt te wachten. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

Definieert een methode voor het renderen van meerdere *TSource*s naar een specifiek [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| bronnen | TSource[] | De bronnen om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

Definieert een methode voor het renderen van meerdere *TSource*s naar een specifiek [`IDevice`](../../idevice/).

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| timeout | Int32 | Een aantal milliseconden dat het aantal milliseconden vertegenwoordigt om te wachten, of -1 milliseconde om onbeperkt te wachten. |
| bronnen | TSource[] | De bronnen om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

Definieert een methode voor het renderen van meerdere *TSource*s naar een specifiek [`IDevice`](../../idevice/).

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| timeout | TimeSpan | Een TimeSpan die het aantal milliseconden vertegenwoordigt om te wachten, of een TimeSpan die -1 milliseconde vertegenwoordigt om onbeperkt te wachten. |
| bronnen | TSource[] | De bronnen om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

Definieert een methode voor het renderen van meerdere *TSource*s naar een specifiek [`IDevice`](../../idevice/), met behulp van een cancellation token om annulering van de bewerking aan te vragen.

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| apparaat | IDevice | Het uitvoerapparaat. |
| cancellationToken | CancellationToken | Een CancellationToken om te observeren terwijl men wacht tot de taak is voltooid. |
| bronnen | TSource[] | De bronnen om te renderen. |

### Zie ook

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
