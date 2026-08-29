---
title: "Document.NavigateAsync"
second_title: "Aspose.SVG for .NET API 참조"
description: "Document NavigateAsync 메서드. 지정된 Uniform Resource Locator URL에서 문서를 비동기적으로 현재 인스턴스로 로드합니다."
type: docs
weight: 1020
url: /ko/net/aspose.svg.dom/document/navigateasync/
---
## NavigateAsync(*string, CancellationToken*) {#navigateasync_6}

지정된 Uniform Resource Locator (URL)에서 문서를 비동기적으로 현재 인스턴스로 로드합니다.

```csharp
public Task NavigateAsync(string address, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 주소 | String | 문서 주소입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_1}

지정된 Uniform Resource Locator (URL)에서 문서를 비동기적으로 현재 인스턴스로 로드합니다.

```csharp
public Task NavigateAsync(Url url, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| URL | Url | 문서 URL입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*string, string, CancellationToken*) {#navigateasync_5}

지정된 콘텐츠에서 문서를 비동기적으로 로드하고 baseUri를 사용하여 상대 리소스를 해결합니다.

```csharp
public Task NavigateAsync(string content, string baseUri, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서 콘텐츠입니다. |
| baseUri | String | 기본 URI. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_4}

지정된 콘텐츠에서 문서를 비동기적으로 로드하고 baseUri를 사용하여 상대 리소스를 해결합니다.

```csharp
public Task NavigateAsync(string content, Url baseUri, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | String | 문서 콘텐츠입니다. |
| baseUri | Url | 기본 URI. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*Stream, string, CancellationToken*) {#navigateasync_3}

지정된 콘텐츠에서 문서를 비동기적으로 로드하고 baseUri를 사용하여 상대 리소스를 해결합니다.

```csharp
public Task NavigateAsync(Stream content, string baseUri, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | 스트림 | 문서 콘텐츠 스트림. |
| baseUri | String | 기본 URI. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_2}

지정된 콘텐츠에서 문서를 비동기적으로 로드하고 baseUri를 사용하여 상대 리소스를 해결합니다.

```csharp
public Task NavigateAsync(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 내용 | 스트림 | 문서 콘텐츠 스트림. |
| baseUri | Url | 기본 URI. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigateasync}

지정된 요청 객체를 기반으로 문서를 비동기적으로 로드합니다.

```csharp
public Task NavigateAsync(RequestMessage request, CancellationToken cancellationToken)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| request | RequestMessage | 요청 객체. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 반환 값

비동기 작업을 나타내는 Task입니다.

### 또 보기

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
