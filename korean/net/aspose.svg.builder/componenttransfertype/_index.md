---
title: "ComponentTransferType 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.ComponentTransferType 열거형. SVG의 FeComponentTransfer 필터 기본 요소에 적용되는 구성 요소 전송 함수의 유형을 지정합니다."
type: docs
weight: 170
url: /ko/net/aspose.svg.builder/componenttransfertype/
---
## ComponentTransferType enumeration

SVG의 FeComponentTransfer 필터 프리미티브에 적용될 구성 요소 전송 함수 유형을 지정합니다.

```csharp
public enum ComponentTransferType
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Identity | `0` | 입력 그래픽에 변화가 없음을 나타냅니다. 이것이 기본 유형입니다. |
| Table | `1` | 필터 내에서 함수를 정의하기 위해 조회 테이블을 사용합니다. |
| Discrete | `2` | 필터에서 함수를 정의하기 위해 이산 값 집합을 사용합니다. |
| Linear | `3` | 필터 내 구성 요소의 선형 변환을 정의합니다. |
| Gamma | `4` | 필터에서 감마 보정 변환을 정의합니다. |

## 비고

FeComponentTransfer 필터 기본 요소는 다양한 전송 함수 유형을 사용하여 그래픽 요소의 색 구성 요소(RGB 및 알파)를 개별적으로 조작할 수 있게 합니다. 각 유형은 필터 내 색 구성 요소 변환을 위한 고유한 계산 방법을 정의합니다.

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
