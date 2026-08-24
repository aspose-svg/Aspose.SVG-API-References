---
title: "SVGDocument.Save"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGDocument Save 方法。将文档保存到由 url 指定的本地文件。文档中使用的所有资源将保存到相邻的文件夹中，该文件夹名称将构建为 output_file_name _files。如果指定的 url 以 .svgz 结尾，文档将保存为压缩的 SVGZ 文件。"
type: docs
weight: 90
url: /zh/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

将文档保存到由 `url` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。如果指定的 `url` 以 ".svgz" 结尾，文档将保存为压缩的 SVGZ 文件。

```csharp
public void Save(Url url)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 本地 URL 到输出文件。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `url` 不是有效的本地文件 URL，则抛出此异常。 |

### 另请参阅

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

将文档保存到由 `path` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。如果指定的 `url` 以 ".svgz" 结尾，文档将保存为压缩的 SVGZ 文件。

```csharp
public void Save(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 本地路径到输出文件。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

使用 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```csharp
public void Save(ResourceHandler resourceHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |

### 另请参阅

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

将文档保存到由 `path` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 本地路径到输出文件。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果指定的 `path` 不是有效的本地文件路径，则抛出此异常。 |
| ArgumentOutOfRangeException | 当当前实现无法识别指定的 *saveFormat* 值时抛出此异常。 |

### 另请参阅

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

使用 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 当当前实现无法识别指定的 *saveFormat* 值时抛出此异常。 |

### 另请参阅

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

将文档保存为 `.svg` 文件到由 *path* 指定的本地路径。任何外部资源都会写入名为 `{output_file_name}_files` 的同级文件夹。

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 目标 `.svg` 文件的绝对或相对路径。 |
| saveOptions | SVGSaveOptions | 控制普通 SVG 序列化的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果 *path* 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

使用 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 资源处理器 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)。 |
| saveOptions | SVGSaveOptions | SVG 保存选项。 |

### 另请参阅

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

将文档保存到由 `url` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 本地 URL 到输出文件。 |
| saveFormat | SVGSaveFormat | 文档保存的格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *url* 未表示有效的本地文件位置时抛出此异常（例如，它为 null、相对路径或指向非文件方案）。 |
| ArgumentOutOfRangeException | 当当前实现无法识别提供的 *saveFormat* 值时抛出此异常。 |

### 另请参阅

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

将文档保存为 `.svg` 文件到 *url*。所有外部资源放置在名为 `{output_file_name}_files` 的同级文件夹中。

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 目标 `.svg` 文件的本地路径。 |
| saveOptions | SVGSaveOptions | 控制普通 SVG 序列化的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果 *url* 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

将文档保存为压缩的 `.svgz` 文件到 *url*。所有外部资源放置在名为 `{output_file_name}_files` 的同级文件夹中。

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| url | URL | 目标 `.svgz` 文件的本地路径。 |
| saveOptions | SVGZSaveOptions | 控制 SVGZ 序列化的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果 *url* 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

使用指定的 [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和相关资源。

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceHandler | ResourceHandler | 用于管理文档资源的资源处理程序，例如文件系统或基于内存的存储。 |
| saveOptions | SVGZSaveOptions | 指定其他保存参数的选项，例如矢量化偏好。 |

### 另请参阅

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

将文档保存为压缩的 `.svgz` 文件到由 *path* 指定的本地路径。任何外部资源都会写入名为 `{output_file_name}_files` 的同级文件夹。

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 目标 `.svgz` 文件的绝对或相对路径。 |
| saveOptions | SVGZSaveOptions | 控制 SVGZ 序列化的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 如果 *path* 不是有效的本地文件路径，则抛出此异常。 |

### 另请参阅

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
