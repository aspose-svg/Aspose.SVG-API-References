---
title: "ShapeRendering 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.ShapeRendering 열거형. SVG 요소에 대한 도형 렌더링 모드를 지정합니다"
type: docs
weight: 1720
url: /ko/net/aspose.svg.builder/shaperendering/
---
## ShapeRendering enumeration

SVG 요소에 대한 형태 렌더링 모드를 지정합니다.

```csharp
public enum ShapeRendering
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Auto | `0` | 브라우저는 도형을 렌더링할 때 속도, 부드러움 및 기하학적 정밀도 사이에서 균형을 맞춥니다. |
| OptimizeSpeed | `1` | 브라우저는 기하학적 정밀도와 부드러움보다 렌더링 속도를 강조합니다. 이 모드는 더 빠른 렌더링을 제공하지만 형태가 덜 정확해질 수 있습니다. |
| CrispEdges | `2` | 브라우저는 날카로운 모서리와 코너를 보존하려고 시도합니다. 이 모드는 직선과 모서리가 있는 그래픽을 렌더링할 때 유용합니다. |
| GeometricPrecision | `3` | 브라우저는 속도를 희생하고 렌더링에서 기하학적 정밀도를 강조합니다. 이 모드는 정밀한 기하학이 중요한 고품질 렌더링에 적합합니다. |

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
