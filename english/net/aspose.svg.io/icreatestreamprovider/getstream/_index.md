---
title: ICreateStreamProvider.GetStream
second_title: Aspose.SVG for .NET API Reference
description: ICreateStreamProvider GetStream method. Provides a stream for rendering
type: docs
weight: 10
url: /net/aspose.svg.io/icreatestreamprovider/getstream/
---
## GetStream(*string, string*) {#getstream}

Provides a stream for rendering.

```csharp
public Stream GetStream(string name, string extension)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the stream. |
| extension | String | The file name extension to use if a file stream is being created. |

### Return Value

A Stream object that is used for writing data during the rendering operations.

### See Also

* interface [ICreateStreamProvider](../)
* namespace [Aspose.Svg.IO](../../../aspose.svg.io/)
* assembly [Aspose.SVG](../../../)

---

## GetStream(*string, string, int*) {#getstream_1}

Provides a stream for rendering.

```csharp
public Stream GetStream(string name, string extension, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the stream. |
| extension | String | The file name extension to use if a file stream is being created. |
| page | Int32 | The page number of the document. |

### Return Value

A Stream object that is used for writing data during the rendering operations.

### See Also

* interface [ICreateStreamProvider](../)
* namespace [Aspose.Svg.IO](../../../aspose.svg.io/)
* assembly [Aspose.SVG](../../../)
