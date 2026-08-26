---
title: "Document.Navigate"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Document Navigate‑Methode. Lädt das Dokument unter der angegebenen Uniform Resource Locator‑URL in die aktuelle Instanz und ersetzt den vorherigen Inhalt."
type: docs
weight: 1010
url: /de/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(string address)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Adresse | String | Die Dokumentadresse. Sie wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(Url url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Die Dokument-URL. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, string baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | String | Der Basis‑URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | URL | Der Basis‑URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | String | Der Basis‑URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | URL | Der Basis‑URI zum Auflösen relativer Ressourcen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(RequestMessage request)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anfrage | RequestMessage | Das Anforderungsobjekt, das zum Laden des Dokumentinhalts verwendet wird. |

### Siehe auch

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Adresse | String | Die Dokumentadresse. Sie wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

Lädt das Dokument unter der angegebenen Uniform Resource Locator (URL) in die aktuelle Instanz und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| URL | URL | Die Dokument-URL. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | String | Der Basis‑URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | String | Der Dokumentinhalt. |
| baseUri | URL | Der Basis‑URI zum Auflösen relativer Ressourcen. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | String | Der Basis‑URI zum Auflösen relativer Ressourcen. Er wird mit dem aktuellen Verzeichnispfad kombiniert, um eine absolute URL zu bilden. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

Lädt das Dokument aus dem angegebenen Inhalt und verwendet baseUri, um relative Ressourcen aufzulösen, wobei der vorherige Inhalt ersetzt wird. Das Laden des Dokuments beginnt an der aktuellen Position im Stream.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Inhalt | Strom | Der Dokumentinhalt. |
| baseUri | URL | Der Basis‑URI zum Auflösen relativer Ressourcen. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |
| ArgumentNullException | `baseUri` ist `null`. |

### Siehe auch

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

Lädt das Dokument basierend auf dem angegebenen Anforderungsobjekt und ersetzt den vorherigen Inhalt.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anfrage | RequestMessage | Das Anforderungsobjekt, das zum Laden des Dokumentinhalts verwendet wird. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| OperationCanceledException | Der Vorgang wurde abgebrochen. |

### Siehe auch

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
