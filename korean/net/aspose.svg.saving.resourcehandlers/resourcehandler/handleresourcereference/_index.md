---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.SVG for .NET API 참조"
description: "ResourceHandler HandleResourceReference 메서드. 이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리 중인 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다."
type: docs
weight: 20
url: /ko/net/aspose.svg.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

이 메서드는 리소스 참조를 처리하는 역할을 합니다. 이 메서드에서 처리되는 리소스에 대한 참조가 어떻게 표시될지 설정할 수 있습니다.

```csharp
public virtual string HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| resource | Resource | 처리될 [`Resource`](../../../aspose.svg.saving/resource/) |
| 컨텍스트 | ResourceHandlingContext | Resource handling 컨텍스트. |

### 반환 값

현재 처리 중인 리소스에 대한 참조를 나타내는 문자열로, 상위 리소스에 기록됩니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | `[`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/)`가 `null`이고 [`Status`](../../../aspose.svg.saving/resource/status/)가 Saved인 경우 발생합니다. 저장된 리소스에 대해 [`OutputUrl`](../../../aspose.svg.saving/resource/outputurl/)를 지정해야 하며, 그렇지 않으면 이 리소스를 참조하는 리소스에서 올바른 참조를 지정할 수 없습니다. |

### 또 보기

* class [Resource](../../../aspose.svg.saving/resource/)
* class [ResourceHandlingContext](../../../aspose.svg.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* namespace [Aspose.Svg.Saving.ResourceHandlers](../../../aspose.svg.saving.resourcehandlers/)
* assembly [Aspose.SVG](../../../)
