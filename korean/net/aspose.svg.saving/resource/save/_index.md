---
title: "Resource.Save"
second_title: "Aspose.SVG for .NET API 참조"
description: "Resource Save 메서드. 제공된 스트림에 리소스를 저장합니다."
type: docs
weight: 70
url: /ko/net/aspose.svg.saving/resource/save/
---
## Resource.Save method

제공된 스트림에 리소스를 저장합니다.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 리소스가 저장될 스트림입니다. |
| 컨텍스트 | ResourceHandlingContext | Resource handling 컨텍스트. |

### 반환 값

이 리소스는 메서드 체이닝을 할 수 있도록 합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| InvalidOperationException | [`OutputUrl`](../outputurl/)이 `null`인 경우 발생합니다. 리소스를 저장하기 전에 [`OutputUrl`](../outputurl/)를 지정해야 합니다. 그렇지 않으면 이 리소스를 참조하는 리소스에서 올바른 참조를 지정할 수 없습니다. |

### 또 보기

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Svg.Saving](../../../aspose.svg.saving/)
* assembly [Aspose.SVG](../../../)
