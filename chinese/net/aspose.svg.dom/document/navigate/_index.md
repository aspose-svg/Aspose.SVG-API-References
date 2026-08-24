---
title: "Document.Navigate"
second_title: "Aspose.SVG for .NET API 参考"
description: "Document Navigate 方法。将指定的统一资源定位符（URL）处的文档加载到当前实例中，替换之前的内容。"
type: docs
weight: 1010
url: /zh/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。

```csharp
public void Navigate(string address)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 地址 | String | 文档地址。它将与当前目录路径组合形成绝对 URL。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。

```csharp
public void Navigate(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 文档 URL。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。

```csharp
public void Navigate(string content, string baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | String | 用于解析相对资源的基准 URI。它将与当前目录路径组合形成绝对 URL。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。

```csharp
public void Navigate(string content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | URL | 用于解析相对资源的基准 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。

```csharp
public void Navigate(Stream content, string baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | Stream | 文档内容。 |
| baseUri | String | 用于解析相对资源的基准 URI。它将与当前目录路径组合形成绝对 URL。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。

```csharp
public void Navigate(Stream content, Url baseUri)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | Stream | 文档内容。 |
| baseUri | URL | 用于解析相对资源的基准 URI。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

根据指定的请求对象加载文档，替换之前的内容。

```csharp
public void Navigate(RequestMessage request)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 请求 | RequestMessage | 用于加载文档内容的请求对象。 |

### 另请参阅

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 地址 | String | 文档地址。它将与当前目录路径组合形成绝对 URL。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 文档 URL。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | String | 用于解析相对资源的基准 URI。它将与当前目录路径组合形成绝对 URL。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | String | 文档内容。 |
| baseUri | URL | 用于解析相对资源的基准 URI。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | Stream | 文档内容。 |
| baseUri | String | 用于解析相对资源的基准 URI。它将与当前目录路径组合形成绝对 URL。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 内容 | Stream | 文档内容。 |
| baseUri | URL | 用于解析相对资源的基准 URI。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |
| ArgumentNullException | `baseUri` 为 `null`。 |

### 另请参阅

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

根据指定的请求对象加载文档，替换之前的内容。

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 请求 | RequestMessage | 用于加载文档内容的请求对象。 |
| cancellationToken | CancellationToken | 取消令牌。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| OperationCanceledException | 操作已取消。 |

### 另请参阅

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
