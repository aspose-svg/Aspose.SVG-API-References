---
title: "OneOf-3.Match"
second_title: "Aspose.SVG for .NET API 참조"
description: "OneOf Match 메서드. 값의 기본 유형에 따라 제공된 함수 중 하나를 실행합니다."
type: docs
weight: 20
url: /ko/net/aspose.svg.builder/oneof-3/match/
---
## OneOf<T1,T2,T3>.Match<TResult> method

값의 기본 유형에 따라 제공된 함수 중 하나를 실행합니다.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2, 
    Func<T3, TResult> func3)
```

| 매개변수 | 설명 |
| --- | --- |
| TResult | 함수들의 반환 타입입니다. |
| func1 | 값이 T1 유형인 경우 실행할 함수입니다. |
| func2 | 값이 T2 유형인 경우 실행할 함수입니다. |
| func3 | 값이 T3 유형인 경우 실행할 함수입니다. |

### 반환 값

실행된 함수의 결과입니다.

### 또 보기

* class [OneOf&lt;T1,T2,T3&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
