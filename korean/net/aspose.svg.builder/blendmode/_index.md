---
title: "BlendMode 열거형"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Builder.BlendMode 열거형. SVG에서 이미지 또는 요소를 결합할 때 사용할 수 있는 블렌딩 모드를 지정합니다."
type: docs
weight: 80
url: /ko/net/aspose.svg.builder/blendmode/
---
## BlendMode enumeration

SVG에서 이미지 또는 요소를 결합할 때 사용할 수 있는 블렌딩 모드를 지정합니다.

```csharp
public enum BlendMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Normal | `0` | 소스 이미지를 그대로 표시하며, 블렌딩을 적용하지 않습니다. |
| Multiply | `1` | 소스 이미지와 배경의 색상을 곱합니다. 결과는 더 어두운 이미지가 됩니다. |
| Screen | `2` | 소스 이미지의 어두운 부분을 밝게 만들고 밝은 부분은 그대로 유지합니다. |
| Overlay | `3` | Multiply와 Screen 블렌드 모드를 결합하여 대비를 강화합니다. |
| Darken | `4` | 소스 이미지의 색상을 기반으로 배경을 어둡게 합니다. |
| Lighten | `5` | 소스 이미지의 색상을 기반으로 배경을 밝게 합니다. |
| ColorDodge | `6` | 소스 이미지를 반영하도록 배경을 밝게 합니다. |
| ColorBurn | `7` | 소스 이미지를 반영하도록 배경을 어둡게 합니다. |
| HardLight | `8` | 소스 이미지의 밝기를 기반으로 하드 라이트 효과를 생성합니다. |
| SoftLight | `9` | 소스 이미지의 밝기를 기반으로 소프트 라이트 효과를 생성합니다. |
| Difference | `10` | 소스 이미지와 배경 사이의 차이를 강조합니다. |
| Exclusion | `11` | Difference와 유사하지만 대비가 낮은 효과를 생성합니다. |
| Hue | `12` | 소스 이미지의 색조를 배경의 휘도와 채도와 결합하여 사용합니다. |
| Saturation | `13` | 소스 이미지의 채도를 배경의 색조와 휘도와 결합하여 사용합니다. |
| Color | `14` | 소스 이미지의 색조와 채도를 배경의 휘도와 결합하여 사용합니다. |
| Luminosity | `15` | 소스 이미지의 휘도를 배경의 색조와 채도와 결합하여 사용합니다. |

## 비고

SVG의 블렌딩 모드는 두 레이어가 서로 어떻게 혼합되는지를 결정하는 데 사용됩니다. 이 열거형은 혼합된 레이어의 색상이 어떻게 섞이고 다양한 시각 효과를 생성할지 제어하는 다양한 옵션을 제공합니다.

### 또 보기

* namespace [Aspose.Svg.Builder](../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../)
