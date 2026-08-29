---
title: "IWindow.Atob"
second_title: "Aspose.SVG for .NET API 참조"
description: "IWindow Atob 메서드. 입력 데이터를 base64 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 형태로 받아 디코딩하고, 각각 0x00부터 0xFF 값의 바이너리 바이트를 나타내는 U0000부터 U00FF까지의 문자로 구성된 문자열을 반환합니다."
type: docs
weight: 120
url: /ko/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

입력 데이터를 base64 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 형태로 받아 디코딩한 후, 각각 0x00부터 0xFF 값의 바이너리 바이트를 나타내는 U+0000부터 U+00FF까지의 문자로 구성된 문자열을 반환합니다.

```csharp
public string Atob(string data)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | String | base64 인코딩된 바이너리 데이터를 포함하는 Unicode 문자열 |

### 반환 값

U+0000에서 U+00FF 범위의 문자로 구성된 문자열

### 예외

| 예외 | 조건 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | 입력 문자열이 유효한 base64 데이터가 아니면 "InvalidCharacterError" DOMException을 발생시킵니다. |

### 또 보기

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
