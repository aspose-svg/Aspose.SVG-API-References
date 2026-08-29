---
title: "Document.Navigate"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Document Navigate. Загружает документ по указанному URL (Uniform Resource Locator) в текущий экземпляр, заменяя предыдущее содержимое."
type: docs
weight: 1010
url: /ru/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(string address)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | String | Адрес документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путем текущего каталога, чтобы сформировать абсолютный URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путем текущего каталога, чтобы сформировать абсолютный URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое.

```csharp
public void Navigate(RequestMessage request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | Объект запроса, используемый для загрузки содержимого документа. |

### См. также

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | String | Адрес документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

Загружает документ по указанному унифицированному указателю ресурса (URL) в текущий экземпляр, заменяя предыдущее содержимое.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путем текущего каталога, чтобы сформировать абсолютный URL. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | String | Базовый URI для разрешения относительных ресурсов. Он будет объединён с путем текущего каталога, чтобы сформировать абсолютный URL. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

Загружает документ из указанного содержимого, используя baseUri для разрешения относительных ресурсов, заменяя предыдущее содержимое. Загрузка документа начинается с текущей позиции в потоке.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | Url | Базовый URI для разрешения относительных ресурсов. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

Загружает документ на основе указанного объекта запроса, заменяя предыдущее содержимое.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | Объект запроса, используемый для загрузки содержимого документа. |
| cancellationToken | CancellationToken | Токен отмены. |

### Исключения

| исключение | условие |
| --- | --- |
| OperationCanceledException | Операция была отменена. |

### См. также

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
