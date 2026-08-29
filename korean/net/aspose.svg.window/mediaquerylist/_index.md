---
title: "MediaQueryList 클래스"
second_title: "Aspose.SVG for .NET API 참조"
description: "Aspose.Svg.Window.MediaQueryList 클래스. MediaQueryList 객체는 문서에 적용된 미디어 쿼리 정보를 저장하며, 문서 상태에 대한 즉시 및 이벤트 기반 매칭을 모두 지원합니다. CSSOM View Module 사양을 참조하십시오 https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs
weight: 5960
url: /ko/net/aspose.svg.window/mediaquerylist/
---
## MediaQueryList class

MediaQueryList 객체는 문서에 적용된 미디어 쿼리 정보를 저장하며, 문서 상태에 대한 즉시 및 이벤트 기반 매칭을 모두 지원합니다. CSSOM View Module 사양을 확인하십시오: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```csharp
public class MediaQueryList : EventTarget
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.svg.window/mediaquerylist/document/) { get; } | Context 객체와 연결된 문서입니다. |
| [Matches](../../aspose.svg.window/mediaquerylist/matches/) { get; } | 문서가 현재 미디어 쿼리 목록과 일치하면 true를 반환하고, 그렇지 않으면 false를 반환하는 부울 값입니다. |
| [Media](../../aspose.svg.window/mediaquerylist/media/) { get; } | 직렬화된 미디어 쿼리를 나타내는 문자열입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 지정된 이벤트가 대상에 전달될 때마다 호출되는 함수를 설정합니다. |
| [AddListener](../../aspose.svg.window/mediaquerylist/addlistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList 일치 상태 변경 이벤트 리스너를 추가합니다. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 지정된 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)에 이벤트를 디스패치하고, (동기식으로) 영향을 받은 EventListeners를 적절한 순서대로 호출합니다. 캡처 및 선택적 버블링 단계 등을 포함한 일반 이벤트 처리 규칙은 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)를 사용해 수동으로 디스패치된 이벤트에도 적용됩니다. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 관리되지 않는 리소스를 해제, 릴리스 또는 재설정과 관련된 애플리케이션 정의 작업을 수행합니다. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 객체 유형을 검색하는 데 사용됩니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 상태에서 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)가 [`EventTarget`](../../aspose.svg.dom/eventtarget/)에서 제거되면 현재 동작에 의해 트리거되지 않습니다. 제거된 후에는 이벤트 리스너가 다시 호출될 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 상태에서 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)가 [`EventTarget`](../../aspose.svg.dom/eventtarget/)에서 제거되면 현재 동작에 의해 트리거되지 않습니다. 제거된 후에는 이벤트 리스너가 다시 호출될 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 이 메서드는 이벤트 대상에서 이벤트 리스너를 제거할 수 있게 합니다. 이벤트를 처리 중인 상태에서 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)가 [`EventTarget`](../../aspose.svg.dom/eventtarget/)에서 제거되면 현재 동작에 의해 트리거되지 않습니다. 제거된 후에는 이벤트 리스너가 다시 호출될 수 없습니다. |
| [RemoveListener](../../aspose.svg.window/mediaquerylist/removelistener/)(*[IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | MediaQueryList 일치 상태 변경 이벤트 리스너를 제거합니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnChange](../../aspose.svg.window/mediaquerylist/onchange/) | MediaQueryList의 일치 상태가 변경될 때 발생하는 이벤트입니다. |

### 또 보기

* class [EventTarget](../../aspose.svg.dom/eventtarget/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
