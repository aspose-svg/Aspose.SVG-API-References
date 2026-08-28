---
title: "SVGDocument.Save"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGDocument Save メソッド。`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、output_file_name_files という名前の隣接フォルダーに保存されます。指定された `url` が .svgz で終わる場合、ドキュメントは圧縮 SVGZ ファイルとして保存されます。"
type: docs
weight: 90
url: /ja/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは隣接フォルダーに保存され、その名前は output_file_name + \"_files\" となります。指定された `url` が \".svgz\" で終わる場合、ドキュメントは圧縮 SVGZ ファイルとして保存されます。

```csharp
public void Save(Url url)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `url` が有効なローカルファイル URL でない場合にスローされます。 |

### 参照

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

`path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは隣接フォルダーに保存され、その名前は output_file_name + \"_files\" となります。指定された `url` が \".svgz\" で終わる場合、ドキュメントは圧縮 SVGZ ファイルとして保存されます。

```csharp
public void Save(string path)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合にスローされます。 |

### 参照

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

[`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) を使用してドキュメントのコンテンツとリソースを保存します。

```csharp
public void Save(ResourceHandler resourceHandler)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |

### 参照

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

`path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは隣接フォルダーに保存され、その名前は output_file_name + \"_files\" となります。

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカルパス。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 指定された `path` が有効なローカルファイルパスでない場合にスローされます。 |
| ArgumentOutOfRangeException | 指定された *saveFormat* の値が現在の実装で認識されない場合にスローされます。 |

### 参照

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

[`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) を使用してドキュメントのコンテンツとリソースを保存します。

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 指定された *saveFormat* の値が現在の実装で認識されない場合にスローされます。 |

### 参照

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

*path* で指定されたローカルパスにドキュメントを `.svg` ファイルとして保存します。外部リソースはすべて `{output_file_name}_files` という名前の兄弟フォルダーに書き込まれます。

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | String | 対象 `.svg` ファイルの絶対パスまたは相対パス。 |
| saveOptions | SVGSaveOptions | プレーン SVG のシリアライズを制御するオプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *path* が有効なローカルファイルパスでない場合にスローされます。 |

### 参照

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

[`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) を使用してドキュメントのコンテンツとリソースを保存します。

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | リソースハンドラ [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | SVGSaveOptions | SVG 保存オプション。 |

### 参照

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

`url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは隣接フォルダーに保存され、その名前は output_file_name + \"_files\" となります。

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *url* が有効なローカルファイルの場所を表さない場合にスローされます（例: null、相対パス、またはファイルスキームでない場所）。 |
| ArgumentOutOfRangeException | 提供された *saveFormat* の値が現在の実装で認識されない場合にスローされます。 |

### 参照

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

*url* にドキュメントを `.svg` ファイルとして保存します。すべての外部リソースは `{output_file_name}_files` という名前の兄弟フォルダーに配置されます。

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 対象 `.svg` ファイルのローカルパス。 |
| saveOptions | SVGSaveOptions | プレーン SVG のシリアライズを制御するオプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *url* が有効なローカルファイルパスでない場合にスローされます。 |

### 参照

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

*url* にドキュメントを圧縮 `.svgz` ファイルとして保存します。すべての外部リソースは `{output_file_name}_files` という名前の兄弟フォルダーに配置されます。

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| url | Url | 対象 `.svgz` ファイルのローカルパス。 |
| saveOptions | SVGZSaveOptions | SVGZ シリアライズを制御するオプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *url* が有効なローカルファイルパスでない場合にスローされます。 |

### 参照

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

指定された [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) を使用して、ドキュメントの内容と関連リソースを保存します。

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | ファイルシステムやメモリベースのストレージなど、ドキュメントリソースを管理するリソースハンドラです。 |
| saveOptions | SVGZSaveOptions | ベクトル化の設定など、追加の保存パラメータを指定するオプション。 |

### 参照

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

*path* で指定されたローカルパスにドキュメントを圧縮 `.svgz` ファイルとして保存します。外部リソースはすべて `{output_file_name}_files` という名前の兄弟フォルダーに書き込まれます。

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| path | String | 対象 `.svgz` ファイルの絶対パスまたは相対パス。 |
| saveOptions | SVGZSaveOptions | SVGZ シリアライズを制御するオプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | *path* が有効なローカルファイルパスでない場合にスローされます。 |

### 参照

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
