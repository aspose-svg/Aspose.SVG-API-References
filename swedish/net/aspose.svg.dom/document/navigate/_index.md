---
title: "Document.Navigate"
second_title: "Aspose.SVG för .NET API-referens"
description: "Document Navigate‑metod. Laddar dokumentet från den angivna Uniform Resource Locator‑URL:en i den aktuella instansen och ersätter det tidigare innehållet."
type: docs
weight: 1010
url: /sv/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(string address)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | String | Dokumentadressen. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(Url url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Dokumentets URL. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, string baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Dokumentets innehåll. |
| baseUri | URL | Bas‑URI för att lösa relativa resurser. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | Stream | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | Stream | Dokumentets innehåll. |
| baseUri | URL | Bas‑URI för att lösa relativa resurser. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| begäran | RequestMessage | Begärandeobjektet som används för att ladda dokumentinnehåll. |

### Se även

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| adress | String | Dokumentadressen. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

Laddar dokumentet från den angivna Uniform Resource Locator (URL) till den aktuella instansen och ersätter det tidigare innehållet.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | URL | Dokumentets URL. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | String | Dokumentets innehåll. |
| baseUri | URL | Bas‑URI för att lösa relativa resurser. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | Stream | Dokumentets innehåll. |
| baseUri | String | Bas‑URI för att lösa relativa resurser. Den kommer att kombineras med den aktuella katalogsökvägen för att bilda en absolut URL. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

Laddar dokumentet från angivet innehåll och använder baseUri för att lösa relativa resurser, vilket ersätter det tidigare innehållet. Dokumentladdning startar från den aktuella positionen i strömmen.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| innehåll | Stream | Dokumentets innehåll. |
| baseUri | URL | Bas‑URI för att lösa relativa resurser. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |
| ArgumentNullException | `baseUri` är `null`. |

### Se även

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

Laddar dokumentet baserat på det angivna begärande objektet och ersätter det tidigare innehållet.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| begäran | RequestMessage | Begärandeobjektet som används för att ladda dokumentinnehåll. |
| cancellationToken | CancellationToken | Avbrytningstoken. |

### Undantag

| undantag | villkor |
| --- | --- |
| OperationCanceledException | Operationen avbröts. |

### Se även

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
