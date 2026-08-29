---
title: "리소스 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Saving.Resource 클래스. 이 클래스는 리소스를 설명하고 이를 처리하기 위한 메서드를 제공합니다."
type: docs
weight: 5710
url: /ko/net/aspose.svg.saving/resource/
---
## Resource class

이 클래스는 리소스를 설명하고 이를 처리하기 위한 메서드를 제공합니다.

```csharp
public class Resource
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [MimeType](../../aspose.svg.saving/resource/mimetype/) { get; } | 이 리소스의 !:Html.MimeType을 반환합니다. 리소스를 찾을 수 없는 경우 `null`일 수 있습니다. |
| [OriginalReference](../../aspose.svg.saving/resource/originalreference/) { get; } | 이 리소스에 대한 원래 참조를 포함하는 문자열을 반환합니다. |
| [OriginalUrl](../../aspose.svg.saving/resource/originalurl/) { get; } | 이 리소스가 위치한 위치를 나타내는 URL을 반환합니다. |
| [OutputUrl](../../aspose.svg.saving/resource/outputurl/) { get; set; } | 처리 후 리소스가 위치하게 될 URL을 가져오거나 설정합니다. |
| [Status](../../aspose.svg.saving/resource/status/) { get; } | 리소스의 현재 상태를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Embed](../../aspose.svg.saving/resource/embed/)(*[ResourceHandlingContext](../resourcehandlingcontext/)*) | 이 리소스를 Base64로 인코딩하여 부모에 포함합니다. 인코딩 결과는 [`OutputUrl`](./outputurl/)에 기록됩니다. |
| [Save](../../aspose.svg.saving/resource/save/)(*Stream, [ResourceHandlingContext](../resourcehandlingcontext/)*) | 제공된 스트림에 리소스를 저장합니다. |
| [WithOutputUrl](../../aspose.svg.saving/resource/withoutputurl/)(*[Url](../../aspose.svg/url/)*) | 처리 후 리소스가 위치하게 될 새로운 URL을 지정합니다. |

### 또 보기

* namespace [Aspose.Svg.Saving](../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../)
