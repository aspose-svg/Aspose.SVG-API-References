---
title: "Renderer-1.Render"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Renderer Render メソッド。指定された IDevice に TSource をレンダリングするメソッドを定義します。"
type: docs
weight: 10
url: /ja/net/aspose.svg.rendering/renderer-1/render/
---
## Render(*[IDevice](../../idevice/), TSource*) {#render_3}

指定された [`IDevice`](../../idevice/) に *TSource* をレンダリングするメソッドを定義します。

```csharp
public void Render(IDevice device, TSource source)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ソース | TSource | レンダリングするソースです。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, TimeSpan*) {#render_5}

指定された [`IDevice`](../../idevice/) に *TSource* をレンダリングするメソッドを定義します。

```csharp
public void Render(IDevice device, TSource source, TimeSpan timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ソース | TSource | レンダリングするソースです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan です。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TSource, int*) {#render_4}

指定された [`IDevice`](../../idevice/) に *TSource* をレンダリングするメソッドを定義します。

```csharp
public void Render(IDevice device, TSource source, int timeout)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ソース | TSource | レンダリングするソースです。 |
| タイムアウト | Int32 | 待機するミリ秒数を表すミリ秒の数、または無期限に待機するための -1 ミリ秒。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), params TSource[]*) {#render_6}

複数の *TSource* を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```csharp
public void Render(IDevice device, params TSource[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| ソース | TSource[] | レンダリングするソース。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), int, params TSource[]*) {#render}

複数の *TSource* を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```csharp
public void Render(IDevice device, int timeout, params TSource[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | Int32 | 待機するミリ秒数を表すミリ秒の数、または無期限に待機するための -1 ミリ秒。 |
| ソース | TSource[] | レンダリングするソース。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), TimeSpan, params TSource[]*) {#render_2}

複数の *TSource* を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```csharp
public abstract void Render(IDevice device, TimeSpan timeout, params TSource[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| タイムアウト | TimeSpan | 待機するミリ秒数を表す TimeSpan、または無期限に待機することを表す -1 ミリ秒の TimeSpan です。 |
| ソース | TSource[] | レンダリングするソース。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)

---

## Render(*[IDevice](../../idevice/), CancellationToken, params TSource[]*) {#render_1}

キャンセル トークンを使用して操作のキャンセルを要求できるように、複数の *TSource* を特定の [`IDevice`](../../idevice/) にレンダリングするメソッドを定義します。

```csharp
public abstract void Render(IDevice device, CancellationToken cancellationToken, 
    params TSource[] sources)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| デバイス | IDevice | 出力デバイスです。 |
| cancellationToken | CancellationToken | タスクの完了を待機中に監視するための CancellationToken。 |
| ソース | TSource[] | レンダリングするソース。 |

### 参照

* interface [IDevice](../../idevice/)
* class [Renderer&lt;TSource&gt;](../)
* namespace [Aspose.Svg.Rendering](../../../aspose.svg.rendering/)
* assembly [Aspose.SVG](../../../)
