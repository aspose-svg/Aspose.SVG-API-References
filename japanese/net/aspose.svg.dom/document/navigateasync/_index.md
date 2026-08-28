---
title: "Document.NavigateAsync"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document NavigateAsync メソッド。指定された Uniform Resource Locator URL のドキュメントを非同期に現在のインスタンスにロードします。"
type: docs
weight: 1020
url: /ja/net/aspose.svg.dom/document/navigateasync/
---
## NavigateAsync(*string, CancellationToken*) {#navigateasync_6}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスに非同期でロードします。

```csharp
public Task NavigateAsync(string address, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | String | ドキュメントのアドレスです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_1}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスに非同期でロードします。

```csharp
public Task NavigateAsync(Url url, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URLです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*string, string, CancellationToken*) {#navigateasync_5}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。

```csharp
public Task NavigateAsync(string content, string baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | String | ベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_4}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。

```csharp
public Task NavigateAsync(string content, Url baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | Url | ベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*Stream, string, CancellationToken*) {#navigateasync_3}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。

```csharp
public Task NavigateAsync(Stream content, string baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントのコンテンツストリームです。 |
| baseUri | String | ベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigateasync_2}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。

```csharp
public Task NavigateAsync(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントのコンテンツストリームです。 |
| baseUri | Url | ベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## NavigateAsync(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigateasync}

指定されたリクエストオブジェクトに基づいてドキュメントを非同期にロードします。

```csharp
public Task NavigateAsync(RequestMessage request, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| request | RequestMessage | リクエストオブジェクトです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 戻り値

非同期操作を表すタスクです。

### 参照

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
