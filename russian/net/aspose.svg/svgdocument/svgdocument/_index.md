---
title: "SVGDocument"
second_title: "Aspose.SVG для .NET справочник API"
description: "Конструктор SVGDocument. Инициализирует новый экземпляр класса SVGDocument"
type: docs
weight: 10
url: /ru/net/aspose.svg/svgdocument/svgdocument/
---
## SVGDocument() {#constructor}

Инициализирует новый экземпляр класса [`SVGDocument`](../).

```csharp
public SVGDocument()
```

### См. также

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*[Configuration](../../configuration/)*) {#constructor_1}

Инициализирует новый экземпляр класса [`SVGDocument`](../).

```csharp
public SVGDocument(Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| configuration | Конфигурация | Конфигурация. |

### См. также

* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string*) {#constructor_10}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string address)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | String | Адрес документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |

### См. также

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*[Url](../../url/)*) {#constructor_4}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(Url url)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |

### См. также

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string, [Configuration](../../configuration/)*) {#constructor_11}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string address, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| address | String | Адрес документа. Он будет объединён с путем текущего каталога для формирования абсолютного URL. |
| configuration | Конфигурация | Конфигурация. |

### См. также

* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*[Url](../../url/), [Configuration](../../configuration/)*) {#constructor_5}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(Url url, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | Url | URL документа. |
| configuration | Конфигурация | Конфигурация. |

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*Stream, string*) {#constructor_8}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ждёт загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Или вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке.

```csharp
public SVGDocument(Stream content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*Stream, string, [Configuration](../../configuration/)*) {#constructor_9}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ждёт загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Или вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке.

```csharp
public SVGDocument(Stream content, string baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Конфигурация | Конфигурация. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*Stream, [Url](../../url/)*) {#constructor_6}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ждёт загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Или вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке.

```csharp
public SVGDocument(Stream content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | Url | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*Stream, [Url](../../url/), [Configuration](../../configuration/)*) {#constructor_7}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ждёт загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Или вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/). Загрузка документа начинается с текущей позиции в потоке.

```csharp
public SVGDocument(Stream content, Url baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | Stream | Содержимое документа. |
| baseUri | Url | Базовый URI документа. |
| configuration | Конфигурация | Конфигурация. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string, string*) {#constructor_14}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string content, string baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string, string, [Configuration](../../configuration/)*) {#constructor_15}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string content, string baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | String | Базовый URI документа. Он будет объединён с путём текущего каталога для формирования абсолютного URL. |
| configuration | Конфигурация | Конфигурация. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string, [Url](../../url/)*) {#constructor_12}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string content, Url baseUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | Url | Базовый URI документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*string, [Url](../../url/), [Configuration](../../configuration/)*) {#constructor_13}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(string content, Url baseUri, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| content | String | Содержимое документа. |
| baseUri | Url | Базовый URI документа. |
| configuration | Конфигурация | Конфигурация. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | `baseUri` равно `null`. |

### См. также

* class [Url](../../url/)
* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#constructor_2}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(RequestMessage request)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | Запрос. |

### См. также

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SVGDocument(*[RequestMessage](../../../aspose.svg.net/requestmessage/), [Configuration](../../configuration/)*) {#constructor_3}

Инициализирует новый экземпляр класса [`SVGDocument`](../). Конструктор работает синхронно, он ожидает загрузки всех внешних ресурсов (изображений, скриптов и т.д.). Чтобы загрузить документ асинхронно, используйте метод [`Navigate`](../../../aspose.svg.dom/document/navigate/) или его перегрузки. Либо вы можете отключить загрузку некоторых внешних ресурсов, установив соответствующие флаги в [`Security`](../../../aspose.svg.dom/ibrowsingcontext/security/).

```csharp
public SVGDocument(RequestMessage request, Configuration configuration)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| request | RequestMessage | Запрос. |
| configuration | Конфигурация | Конфигурация. |

### См. также

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Configuration](../../configuration/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
