---
title: Class DocumentType
second_title: .NET API 참조용 Aspose.SVG
description: Aspose.Svg.Dom.DocumentType 수업. DocumentType은 document 에 대해 정의된 엔티티 목록에 대한 인터페이스를 제공합니다.
type: docs
weight: 830
url: /ko/net/aspose.svg.dom/documenttype/
---
## DocumentType class

DocumentType은 document 에 대해 정의된 엔티티 목록에 대한 인터페이스를 제공합니다.

```csharp
public class DocumentType : Node
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DocumentType](documenttype/)(string, string, string, string, Document) | 의 새 인스턴스를 초기화합니다.`DocumentType` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | 이 노드의 속성을 포함하는 NamedNodeMap(요소인 경우) 또는 그렇지 않은 경우 null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | 이 노드의 절대 기본 URI 또는 구현이 절대 URI를 얻을 수 없는 경우 null입니다. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 이 노드의 모든 자식을 포함하는 NodeList입니다. 자식이 없으면 노드가 없는 NodeList입니다.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 이 노드의 첫 번째 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| [InternalSubset](../../aspose.svg.dom/documenttype/internalsubset/) { get; } | 내부 하위 집합은 문자열이거나 없는 경우 null입니다. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 이 노드의 마지막 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | 이 노드의 정규화된 이름의 로컬 부분을 반환합니다. ELEMENT_NODE 및 ATTRIBUTE_NODE 이외의 모든 유형의 노드와 Document.createElement()와 같은 DOM 수준 1 메서드로 생성된 노드의 경우 이것은 항상 null입니다. |
| [Name](../../aspose.svg.dom/documenttype/name/) { get; } | DTD의 이름. 즉, DOCTYPE 키워드 바로 뒤에 오는 이름입니다. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 이 노드의 네임스페이스 URI 또는 지정되지 않은 경우 null입니다. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 이 노드 바로 다음의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| override [NodeName](../../aspose.svg.dom/documenttype/nodename/) { get; } | 유형에 따라 이 노드의 이름입니다. |
| override [NodeType](../../aspose.svg.dom/documenttype/nodetype/) { get; } | 기본 개체의 유형을 나타내는 코드입니다. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 유형에 따라 이 노드의 값입니다. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | 이 노드와 연결된 문서 개체입니다. 이는 새 노드를 만드는 데 사용되는 Document 객체이기도 합니다. 이 노드가 Document 또는 아직 Document와 함께 사용되지 않는 DocumentType인 경우 null입니다. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 부모를 가져옵니다[`Element`](../element/) 이 노드의. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 이 노드의 부모입니다. Attr, Document, DocumentFragment, Entity 및 Notation을 제외한 모든 노드에는 부모가 있을 수 있습니다. 그러나 노드가 방금 생성되어 아직 트리에 추가되지 않았거나 트리에서 제거된 경우 null입니다. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 이 노드의 네임스페이스 접두사 또는 지정되지 않은 경우 null입니다. null로 정의했을 때 설정해도 아무런 효과가 없다 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 이 노드 바로 앞의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| [PublicId](../../aspose.svg.dom/documenttype/publicid/) { get; } | 외부 하위 집합의 공용 식별자입니다. |
| [SystemId](../../aspose.svg.dom/documenttype/systemid/) { get; } | 외부 하위 집합의 시스템 식별자입니다. 절대 URI일 수도 있고 아닐 수도 있습니다. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | 이 속성은 이 노드와 그 자손의 텍스트 내용을 반환합니다. null로 정의된 경우 설정해도 아무런 효과가 없습니다. 설정 시 이 노드가 가질 수 있는 모든 가능한 자식이 제거되고 새 문자열이 비어 있거나 null이 아닌 경우 이 속성이 설정된 문자열을 포함하는 단일 텍스트 노드로 대체됩니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | 이 노드의 자식 목록 끝에 newChild 노드를 추가합니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 관리되지 않는 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | 이 노드(요소인 경우)에 속성이 있는지 여부를 반환합니다. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 이 노드에 자식이 있는지 여부를 반환합니다. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | 기존 자식 노드 자식 앞에 노드를 삽입합니다. child가 null이면 children 목록 끝에 노드를 삽입합니다. child가 DocumentFragment 객체이면 모든 자식이 동일한 순서로 child 앞에 삽입됩니다. 자식이 이미 트리에 있으면 먼저 제거됩니다. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | 이 메서드는 지정된 namespaceURI가 기본 네임스페이스인지 확인합니다. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | 두 노드가 같은지 테스트합니다. 이 메서드는 Node.isSameNode()로 테스트할 수 있는 동일성(즉, 두 노드가 동일한 객체에 대한 참조인지 여부)이 아니라 노드의 동일성을 테스트합니다. 동일한 모든 노드는 동일하지만 그 반대는 참이 아닐 수 있습니다. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | 이 노드가 주어진 노드와 동일한 노드인지 여부를 반환합니다. 이 메서드는 구현에서 반환된 두 개의 노드 참조가 동일한 개체를 참조하는지 여부를 확인하는 방법을 제공합니다. 두 노드 참조가 동일한 개체에 대한 참조인 경우 프록시를 통하더라도 참조는 완전히 상호 교환 가능하게 사용될 수 있으므로 모든 속성이 동일한 값을 가지며 두 참조에서 동일한 DOM 메서드를 호출하면 항상 정확히 동일한 효과가 발생합니다. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | 이 노드에서 시작하여 지정된 접두사에 연결된 네임스페이스 URI를 찾습니다. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | 이 노드에서 시작하여 지정된 네임스페이스 URI에 연결된 접두사를 찾습니다. 기본 네임스페이스 선언은 이 메서드에서 무시됩니다. 이 메서드에서 사용하는 알고리즘에 대한 자세한 내용은 Namespace Prefix Lookup을 참조하십시오. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 특성 노드를 포함하여 이 노드 아래 하위 트리의 전체 깊이에 있는 모든 텍스트 노드를 구조(예: 요소, 주석, 처리 명령, CDATA 섹션 및 엔터티 참조)만이 텍스트를 구분하는 "일반" 형식으로 넣습니다. 노드, 즉 인접한 Text 노드나 빈 Text 노드가 없습니다. 이는 문서의 DOM 보기가 저장되고 다시 로드된 것과 동일하도록 하는 데 사용할 수 있으며 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회)이 다음과 같은 경우에 유용합니다. 사용할 수 있습니다. Node.ownerDocument에 연결된 DOMConfiguration 개체의 "normalize-characters" 매개 변수가 true이면 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | 자식 목록에서 oldChild로 표시된 자식 노드를 제거하고 반환합니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | 자식 목록에서 자식 노드 oldChild를 newChild로 바꾸고 oldChild 노드를 반환합니다. newChild가 DocumentFragment 객체이면 oldChild는 동일한 순서로 삽입되는 모든 DocumentFragment 자식으로 대체됩니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| override [ToString](../../aspose.svg.dom/documenttype/tostring/)() | 반환String 이 instance. 를 나타냅니다. |

### 또한보십시오

* class [Node](../node/)
* 네임스페이스 [Aspose.Svg.Dom](../../aspose.svg.dom/)
* 집회 [Aspose.SVG](../../)


