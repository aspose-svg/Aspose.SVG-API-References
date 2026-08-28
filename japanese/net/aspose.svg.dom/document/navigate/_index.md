---
title: "Document.Navigate"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Document Navigate メソッド。指定された Uniform Resource Locator URL のドキュメントを現在のインスタンスに読み込み、以前のコンテンツを置き換えます。"
type: docs
weight: 1010
url: /ja/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。

```csharp
public void Navigate(string address)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | String | ドキュメントのアドレス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。

```csharp
public void Navigate(Url url)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URLです。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```csharp
public void Navigate(string content, string baseUri)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```csharp
public void Navigate(string content, Url baseUri)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。

```csharp
public void Navigate(Stream content, string baseUri)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容です。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。

```csharp
public void Navigate(Stream content, Url baseUri)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容です。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。

```csharp
public void Navigate(RequestMessage request)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| request | RequestMessage | ドキュメントコンテンツを読み込むために使用されるリクエストオブジェクト。 |

### 参照

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | String | ドキュメントのアドレス。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | ドキュメントの URLです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | String | ドキュメントの内容です。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容です。 |
| baseUri | String | 相対リソースを解決するためのベース URI。現在のディレクトリパスと結合され、絶対 URL が形成されます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| content | Stream | ドキュメントの内容です。 |
| baseUri | Url | 相対リソースを解決するためのベース URI。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |
| ArgumentNullException | `baseUri` は `null`です。 |

### 参照

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| request | RequestMessage | ドキュメントコンテンツを読み込むために使用されるリクエストオブジェクト。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| OperationCanceledException | 操作がキャンセルされました。 |

### 参照

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
