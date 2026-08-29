---
title: "ResourceHandler 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Saving.ResourceHandlers.ResourceHandler 클래스. 이 클래스는 리소스를 처리하는 역할을 합니다. 리소스에 대해 수행될 작업과 상위 리소스에 기록될 참조를 제어할 수 있는 메서드를 제공합니다"
type: docs
weight: 5730
url: /ko/net/aspose.svg.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

이 클래스는 리소스를 처리하는 역할을 합니다. [`Resource`](../../aspose.svg.saving/resource/)에 대해 수행될 작업과 상위 [`Resource`](../../aspose.svg.saving/resource/)에 기록될 참조를 제어할 수 있는 메서드를 제공합니다.

```csharp
public abstract class ResourceHandler
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| abstract [HandleResource](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 이 메서드는 리소스를 처리하는 역할을 합니다. 여기에서 [`Resource`](../../aspose.svg.saving/resource/)를 스트림에 저장하거나 상위 리소스에 포함시킬 수 있습니다. |
| virtual [HandleResourceReference](../../aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.svg.saving/resource/), [ResourceHandlingContext](../../aspose.svg.saving/resourcehandlingcontext/)*) | 이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리되는 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다. |

### 또 보기

* namespace [Aspose.Svg.Saving.ResourceHandlers](../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../)
