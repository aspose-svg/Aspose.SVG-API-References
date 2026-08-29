---
title: "Document.Navigate"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Document Navigate methode. Laadt het document op de opgegeven Uniform Resource Locator‑URL in de huidige instantie, waarbij de vorige inhoud wordt vervangen."
type: docs
weight: 1010
url: /nl/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string address)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | String | Het documentadres. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(Url url)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De document-URL. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string content, string baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stream | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stream | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| request | RequestMessage | Het request‑object dat wordt gebruikt om documentinhoud te laden. |

### Zie ook

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | String | Het documentadres. Het wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

Laadt het document op de opgegeven Uniform Resource Locator (URL) in de huidige instantie, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | Url | De document-URL. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | String | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stream | De documentinhoud. |
| baseUri | String | De basis-URI om relatieve bronnen op te lossen. Deze wordt gecombineerd met het huidige mappad om een absolute URL te vormen. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

Laadt het document vanuit de opgegeven inhoud en gebruikt baseUri om relatieve bronnen op te lossen, waarbij de vorige inhoud wordt vervangen. Het laden van het document start vanaf de huidige positie in de stream.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inhoud | Stream | De documentinhoud. |
| baseUri | Url | De basis-URI om relatieve bronnen op te lossen. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |
| ArgumentNullException | `baseUri` is `null`. |

### Zie ook

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

Laadt het document op basis van het opgegeven request‑object, waarbij de vorige inhoud wordt vervangen.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| request | RequestMessage | Het request‑object dat wordt gebruikt om documentinhoud te laden. |
| cancellationToken | CancellationToken | Het annulerings-token. |

### Uitzonderingen

| exceptie | conditie |
| --- | --- |
| OperationCanceledException | Operatie is geannuleerd. |

### Zie ook

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
