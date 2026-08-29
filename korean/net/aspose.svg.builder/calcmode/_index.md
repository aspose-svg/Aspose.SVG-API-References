---
title: "CalcMode 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.CalcMode 열거형. SVG 애니메이션에서 값을 보간하기 위한 계산 모드를 지정합니다."
type: docs
weight: 90
url: /ko/net/aspose.svg.builder/calcmode/
---
## CalcMode enumeration

SVG 애니메이션에서 값 보간을 위한 계산 모드를 지정합니다.

```csharp
public enum CalcMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Discrete | `0` | 애니메이션이 보간 없이 한 값에서 다음 값으로 바로 점프합니다. |
| Linear | `1` | 애니메이션 값이 애니메이션 기간 전체에 걸쳐 선형으로 보간됩니다. |
| Paced | `2` | 애니메이션이 전체 동안 진행이 고르게 되도록 속도가 조절됩니다. |
| Spline | `3` | 애니메이션이 값을 보간하기 위해 큐빅 베지어 스플라인을 사용합니다. |

## 비고

계산 모드는 SVG 애니메이션이 애니메이션 진행 중 값 사이를 어떻게 전환하는지를 결정합니다. 다양한 모드를 사용하여 여러 효과를 만들고 애니메이션의 속도와 부드러움을 제어할 수 있습니다.

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
