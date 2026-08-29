---
title: "FileSystemResourceHandler 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Saving.ResourceHandlers.FileSystemResourceHandler 클래스. 이 클래스는 리소스를 로컬 파일 시스템에 저장하도록 설계된 ResourceHandler 클래스의 구현입니다"
type: docs
weight: 5720
url: /ko/net/aspose.svg.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

이 클래스는 리소스를 로컬 파일 시스템에 저장하도록 설계된 [`ResourceHandler`](../resourcehandler/) 클래스의 구현입니다.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | `FileSystemResourceHandler` 클래스의 새 인스턴스를 초기화합니다. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.svg/url/)*) | `FileSystemResourceHandler` 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [HandleResource](../../aspose.svg.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 이 메서드는 리소스를 처리하는 역할을 합니다. 여기에서 [`Resource`](../../aspose.svg.saving/resource/)를 스트림에 저장하거나 상위 리소스에 포함시킬 수 있습니다. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리되는 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다. |

### 또 보기

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
