---
title: Interface IWindowTimers
second_title: .NET API 참조용 Aspose.SVG
description: Aspose.Svg.Window.IWindowTimers 상호 작용. 작성자가 타이머 기반 콜백을 예약할 수 있습니다.
type: docs
weight: 3840
url: /ko/net/aspose.svg.window/iwindowtimers/
---
## IWindowTimers interface

작성자가 타이머 기반 콜백을 예약할 수 있습니다.

```csharp
public interface IWindowTimers
```

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [ClearInterval](../../aspose.svg.window/iwindowtimers/clearinterval/)(int) | handle 에 의해 식별된 setInterval()로 설정된 시간 제한을 취소합니다. |
| [ClearTimeout](../../aspose.svg.window/iwindowtimers/cleartimeout/)(int) | handle. 로 식별된 setTimeout()으로 설정된 시간 제한을 취소합니다. |
| [SetInterval](../../aspose.svg.window/iwindowtimers/setinterval/)(object, int, params object[]) | 시간 제한 밀리초마다 처리기를 실행하도록 시간 제한을 예약합니다. 모든 인수는 처리기로 바로 전달됩니다. |
| [SetTimeout](../../aspose.svg.window/iwindowtimers/settimeout/)(object, int, params object[]) | 타임아웃 밀리초 후에 핸들러를 실행하도록 타임아웃을 예약합니다. 모든 인수는 처리기로 바로 전달됩니다. |

### 또한보십시오

* 네임스페이스 [Aspose.Svg.Window](../../aspose.svg.window/)
* 집회 [Aspose.SVG](../../)


