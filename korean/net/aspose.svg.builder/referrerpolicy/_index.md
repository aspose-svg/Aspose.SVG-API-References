---
title: "ReferrerPolicy 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.ReferrerPolicy 열거형. 리소스를 가져올 때 사용할 레퍼러 정책을 지정합니다."
type: docs
weight: 1020
url: /ko/net/aspose.svg.builder/referrerpolicy/
---
## ReferrerPolicy enumeration

리소스를 가져올 때 사용할 레퍼러 정책을 지정합니다.

```csharp
public enum ReferrerPolicy
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 레퍼러 정책이 설정되지 않았습니다. |
| NoReferrer | `1` | Referer 헤더가 전송되지 않습니다. |
| NoReferrerWhenDowngrade | `2` | Referer 헤더가 보안 수준이 낮은 원본(HTTPS -&gt; HTTP)으로 전송되지 않습니다. |
| SameOrigin | `3` | Referer 헤더가 동일 출처 요청에만 전송됩니다. |
| Origin | `4` | 문서의 원본만 Referer 헤더로 전송됩니다. |
| StrictOrigin | `5` | 보안 컨텍스트에서 문서의 원본만 Referer 헤더로 전송됩니다. |
| OriginWhenCrossOrigin | `6` | 동일 출처 요청에 대해서는 전체 URL이 Referer 헤더로 전송되지만, 교차 출처 요청에 대해서는 원본만 전송됩니다. |
| StrictOriginWhenCrossOrigin | `7` | 동일 출처 요청에 대해서는 문서의 출처만 Referer 헤더로 전송되며, 보안이 취약한 상황에서 교차 출처 요청에는 헤더가 전송되지 않습니다. |
| UnsafeUrl | `8` | 경로와 쿼리 문자열을 포함한 전체 URL이 항상 Referer 헤더로 전송됩니다. |

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
