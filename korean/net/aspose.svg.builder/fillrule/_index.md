---
title: "FillRule 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.FillRule 열거형. SVG 그래픽에서 도형의 어느 부분이 내부인지 외부인지를 결정하는 규칙을 지정합니다."
type: docs
weight: 270
url: /ko/net/aspose.svg.builder/fillrule/
---
## FillRule enumeration

SVG 그래픽에서 도형의 어느 부분이 내부인지 외부인지를 결정하는 규칙을 지정합니다.

```csharp
public enum FillRule
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Nonzero | `0` | 비영점 와인딩 규칙: 해당 점에서 무한대까지 임의의 방향으로 광선을 그려 주어진 도형의 경로 세그먼트와 교차하는 횟수를 세어 점의 "내부 여부"를 결정합니다. 이 횟수가 홀수이면 점은 내부에; 짝수이면 외부에 있습니다. |
| Evenodd | `1` | 짝수-홀수 와인딩 규칙: 해당 점에서 무한대까지 임의의 방향으로 광선을 그려 주어진 도형의 경로 세그먼트와 교차하는 횟수를 세어 점의 "내부 여부"를 결정합니다. 이 횟수가 짝수이면 점은 외부에; 홀수이면 내부에 있습니다. |

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
