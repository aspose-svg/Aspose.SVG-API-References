---
title: "ClipRule 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.ClipRule 열거형. SVG 그래픽에서 경로를 클리핑하는 방식을 결정하는 규칙을 정의합니다."
type: docs
weight: 120
url: /ko/net/aspose.svg.builder/cliprule/
---
## ClipRule enumeration

SVG 그래픽에서 경로를 클리핑하는 방법을 결정하는 규칙을 정의합니다.

```csharp
public enum ClipRule
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Nonzero | `0` | 경로를 클리핑하기 위한 비영(Nonzero) 와인딩 규칙입니다. |
| Evenodd | `1` | 경로를 클리핑하기 위한 짝-홀수(even-odd) 와인딩 규칙입니다. |

## 비고

SVG의 클립 규칙 속성은 경로가 어떻게 클리핑되는지를 결정합니다. 경로가 자신과 교차하거나 여러 경로가 결합될 때 특히 중요합니다. 이 규칙은 경로의 어느 부분이 \"inside\"(내부)이며 채워지거나(또는 보이게) 해야 하고, 어느 부분이 \"outside\"(외부)이며 클리핑되거나(또는 보이지 않게) 해야 하는지를 판단하는 데 도움을 줍니다.

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
