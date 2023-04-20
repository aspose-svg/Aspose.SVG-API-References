---
title: SVGDocument.Save
second_title: Aspose.SVG for .NET API リファレンス
description: SVGDocument 方法. で指定されたローカル ファイルにドキュメントを保存しますURL .このドキュメントで使用されるすべてのリソースは隣接するフォルダーの に保存されその名前は次のように構成されます output_file_name  _files.
type: docs
weight: 90
url: /ja/net/aspose.svg/svgdocument/save/
---
## Save(Url) {#save_3}

で指定されたローカル ファイルにドキュメントを保存します。`URL` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(string) {#save_6}

で指定されたローカル ファイルにドキュメントを保存します。`道` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(IOutputStorage) {#save}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |

### 関連項目

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(string, SVGSaveFormat) {#save_7}

で指定されたローカル ファイルにドキュメントを保存します。`道` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(IOutputStorage, SVGSaveFormat) {#save_1}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(string, SVGSaveOptions) {#save_8}

で指定されたローカル ファイルにドキュメントを保存します。`道` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| path | String | 出力ファイルへのローカル パス。 |
| saveOptions | SVGSaveOptions | SVG 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`道`は有効なローカル ファイル パスではありません。 |

### 関連項目

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(IOutputStorage, SVGSaveOptions) {#save_2}

ドキュメントのコンテンツとリソースを出力ストレージに保存します。

```csharp
public void Save(IOutputStorage outputStorage, SVGSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| outputStorage | IOutputStorage | 出力ストレージ[`IOutputStorage`](../../../aspose.svg.io/ioutputstorage/). |
| saveOptions | SVGSaveOptions | SVG 保存オプション。 |

### 関連項目

* interface [IOutputStorage](../../../aspose.svg.io/ioutputstorage/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(Url, SVGSaveFormat) {#save_4}

で指定されたローカル ファイルにドキュメントを保存します。`URL` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveFormat | SVGSaveFormat | ドキュメントが保存される形式。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)

---

## Save(Url, SVGSaveOptions) {#save_5}

で指定されたローカル ファイルにドキュメントを保存します。`URL` .このドキュメントで使用されるすべてのリソースは、隣接するフォルダーの に保存され、その名前は次のように構成されます: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| url | Url | 出力ファイルへのローカル URL。 |
| saveOptions | SVGSaveOptions | SVG 保存オプション。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentException | 指定された場合に発生します`URL`は有効なローカル ファイル URL ではありません。 |

### 関連項目

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* 名前空間 [Aspose.Svg](../../svgdocument/)
* 組み立て [Aspose.SVG](../../../)


