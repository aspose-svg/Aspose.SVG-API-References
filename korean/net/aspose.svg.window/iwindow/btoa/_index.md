---
title: "IWindow.Btoa"
second_title: "Aspose.SVG for .NET API 참조"
description: "IWindow Btoa 메서드. 입력 데이터를 U0000부터 U00FF까지의 문자만 포함하는 Unicode 문자열 형태로 받아, 각각 0x00부터 0xFF 값의 바이너리 바이트를 나타내며, 이를 base64 표현으로 변환하여 반환합니다."
type: docs
weight: 130
url: /ko/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

입력 데이터를 U+0000부터 U+00FF까지의 문자만 포함하는 Unicode 문자열 형태로 받아, 각각 0x00부터 0xFF 값의 바이너리 바이트를 나타내며, 이를 base64 표현으로 변환하여 반환합니다.

```csharp
public string Btoa(string data)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | String | U+0000부터 U+00FF까지의 문자만 포함하는 Unicode 문자열. |

### 반환 값

base64 문자열.

### 예외

| 예외 | 조건 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 입력 문자열에 범위를 벗어난 문자가 포함된 경우 "InvalidCharacterError" DOMException 예외를 발생시킵니다. |

### 또 보기

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
