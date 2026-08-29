---
title: "Resource.Embed"
second_title: "Aspose.SVG for .NET API 참조"
description: "Resource Embed 메서드. 이 리소스를 부모에 Base64로 인코딩하여 포함합니다. 인코딩 결과는 OutputUrl에 기록됩니다."
type: docs
weight: 60
url: /ko/net/aspose.svg.saving/resource/embed/
---
## Resource.Embed method

이 리소스를 부모에 Base64로 인코딩하여 포함합니다. 인코딩 결과는 [`OutputUrl`](../outputurl/)에 기록됩니다.

```csharp
public Resource Embed(ResourceHandlingContext context)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 컨텍스트 | ResourceHandlingContext | Resource handling 컨텍스트. |

### 반환 값

이 리소스는 메서드 체이닝을 할 수 있도록 합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | 결과를 포함할 위치가 없기 때문에 [`ParentResource`](../../resourcehandlingcontext/parentresource/)가 없을 경우 발생합니다. |

### 또 보기

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
