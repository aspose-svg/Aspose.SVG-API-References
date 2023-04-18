---
title: Class Document
second_title: .NET API 참조용 Aspose.SVG
description: Aspose.Svg.Dom.Document 수업. 문서는 전체 HTML XML 또는 SVG 문서를 나타냅니다. 개념적으로 문서 트리의 루트이며 문서 데이터에 대한 기본 액세스를 제공합니다.
type: docs
weight: 810
url: /ko/net/aspose.svg.dom/document/
---
## Document class

문서는 전체 HTML, XML 또는 SVG 문서를 나타냅니다. 개념적으로 문서 트리의 루트이며 문서 데이터에 대한 기본 액세스를 제공합니다.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | 이 노드의 속성을 포함하는 NamedNodeMap(요소인 경우) 또는 그렇지 않은 경우 null. |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | 이 노드의 절대 기본 URI 또는 구현이 절대 URI를 얻을 수 없는 경우 null입니다. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | 문서의 인코딩을 가져옵니다. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | 문서의 인코딩을 가져옵니다. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | 이 요소의 자식인 요소 노드의 현재 수를 반환합니다. 이 요소에 nodeType이 1. 인 하위 노드가 없는 경우 0입니다. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 이 노드의 모든 자식을 포함하는 NodeList입니다. 자식이 없으면 노드가 없는 NodeList입니다.. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | 하위 요소를 반환합니다. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | 문서 콘텐츠 유형을 가져옵니다. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | 현재 검색 컨텍스트를 가져옵니다. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | 문서 인터페이스의 defaultView IDL 속성은 가져올 때 가 이 문서의 브라우징 컨텍스트의 WindowProxy 객체를 반환해야 하며, 이 문서에 연결된 브라우징 컨텍스트가 있는 경우 , 그렇지 않으면 null을 반환해야 합니다. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | 이 문서와 관련된 문서 유형 선언입니다. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | 문서의 요소인 자식 노드에 직접 접근할 수 있도록 해주는 편의 속성입니다. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | 문서의 위치. 정의되지 않았거나 문서가 DOMImplementation.createDocument. 를 사용하여 생성된 경우 null |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 이 노드의 첫 번째 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | 이 문서를 처리하는 DOMImplementation 개체입니다. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | 문서의 인코딩을 가져옵니다. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 이 노드의 마지막 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | 이 요소의 마지막 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | 이 노드의 정규화된 이름의 로컬 부분을 반환합니다. ELEMENT_NODE 및 ATTRIBUTE_NODE 이외의 모든 유형의 노드와 Document.createElement()와 같은 DOM 수준 1 메서드로 생성된 노드의 경우 이것은 항상 null입니다. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | 문서의 위치입니다. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 이 노드의 네임스페이스 URI 또는 지정되지 않은 경우 null입니다. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | 이 요소의 다음 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 항목 뒤에 오는 요소 형제 노드가 없는 경우 null입니다. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 이 노드 바로 다음의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | 유형에 따라 이 노드의 이름입니다. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | 기본 개체의 유형을 나타내는 코드입니다. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 유형에 따라 이 노드의 값입니다. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | 문서 원본을 가져옵니다. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | 소유자 문서를 가져옵니다. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 부모를 가져옵니다[`Element`](../element/) 이 노드의. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 이 노드의 부모입니다. Attr, Document, DocumentFragment, Entity 및 Notation을 제외한 모든 노드에는 부모가 있을 수 있습니다. 그러나 노드가 방금 생성되어 아직 트리에 추가되지 않았거나 트리에서 제거된 경우 null입니다. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 이 노드의 네임스페이스 접두사 또는 지정되지 않은 경우 null입니다. null로 정의했을 때 설정해도 아무런 효과가 없다 |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | 이 요소의 이전 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 요소 앞에 오는 요소 형제 노드가 없는 경우 null입니다. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 이 노드 바로 앞의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | 문서 준비 상태를 반환합니다. 문서가 로드되는 동안 "로딩", 파싱이 완료되면 "대화형", 그러나 여전히 하위 리소스 로드, 로드되면 "완료". |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | 오류 검사를 적용할지 여부를 지정하는 속성입니다. false로 설정하면 구현 시 DOM 작업에서 일반적으로 정의되는 가능한 모든 오류 사례를 테스트하지 않고 DOM 작업에서 DOMException을 발생시키지 않거나 Document.normalizeDocument()를 사용하는 동안 오류를 보고하지 않습니다. 오류의 경우 동작이 정의되지 않습니다. 이 속성은 기본적으로 true입니다. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | 문서에 명시적으로 연결되거나 포함된 모든 스타일 시트를 포함하는 목록입니다. HTML 문서의 경우 여기에는 HTML LINK 요소와 인라인 STYLE 요소를 통해 포함된 외부 스타일 시트가 포함됩니다. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | 이 속성은 이 노드와 그 자손의 텍스트 내용을 반환합니다. null로 정의된 경우 설정해도 아무런 효과가 없습니다. 설정 시 이 노드가 가질 수 있는 모든 가능한 자식이 제거되고 새 문자열이 비어 있거나 null이 아닌 경우 이 속성이 설정된 문자열을 포함하는 단일 텍스트 노드로 대체됩니다. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | 이 문서가 독립 실행형인지 여부를 XML 선언의 일부로 지정하는 속성입니다. 지정되지 않은 경우 거짓입니다. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | XML 선언의 일부로 이 문서의 버전 번호를 지정하는 속성입니다. 선언이 없고 이 문서가 "XML" 기능을 지원하는 경우 값은 "1.0"입니다. 이 문서가 "XML" 기능을 지원하지 않는 경우 값은 항상 null입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | 이 노드의 자식 목록 끝에 newChild 노드를 추가합니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(string) | 지정된 이름의 속성을 생성합니다. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(string, string) | 지정된 정규화된 이름 및 네임스페이스 URI의 특성을 만듭니다. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(string) | 값이 지정된 문자열인 CDATASection 노드를 생성합니다. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(string) | 지정된 문자열이 지정된 주석 노드를 생성합니다. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | 빈 DocumentFragment 개체를 만듭니다. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(string, string, string, string) | DocumentType 노드를 생성합니다. |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(string) | 지정된 유형의 요소를 생성합니다. 반환된 인스턴스는 요소 인터페이스를 구현하므로 반환된 객체에 속성을 직접 지정할 수 있습니다. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(string, string) | 지정된 정규화된 이름 및 네임스페이스 URI의 요소를 만듭니다. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(string) | EntityReference 개체를 만듭니다. 또한 참조된 엔터티를 알면 EntityReference 노드의 자식 목록을 해당 Entity 노드의 자식 목록과 동일하게 만듭니다. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(string) | 생성[`Event`](../../aspose.svg.dom.events/event/) 구현에서 지원하는 유형입니다. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(string, IXPathNSResolver) | 확인된 네임스페이스를 사용하여 구문 분석된 XPath 식을 만듭니다. 이는 표현식 문자열을 보다 효율적인 내부 형식으로 컴파일하고 표현식 내에서 발생하는 모든 네임스페이스 접두사를 미리 해결할 수 있기 때문에 표현식이 응용 프로그램에서 재사용될 때 유용합니다. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(Node) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 NodeIterator를 만듭니다. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(Node) | XPath 표현식이 문서 내에 나타난 노드의 컨텍스트에 상대적으로 쉽게 평가될 수 있도록 네임스페이스를 해결하기 위해 DOM 노드를 조정합니다. 이 어댑터는 DOM 레벨 3 방법과 같이 작동 합니다.`lookupNamespaceURI` time lookupNamespaceURI가 호출될 때 노드의 계층에서 사용 가능한 현재 정보를 사용하여 지정된 접두사에서 namespaceURI 를 확인하는 노드에서 암시적 xml 접두사. 도 올바르게 확인합니다. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(string, string) | 지정된 이름과 데이터 문자열이 지정된 ProcessingInstruction 노드를 생성합니다. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(string) | 지정된 문자열이 지정된 텍스트 노드를 생성합니다. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(Node) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 관리되지 않는 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | XPath 식 문자열을 평가하고 가능한 경우 지정된 유형의 결과를 반환합니다. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(string) | 주어진 값을 가진 ID 속성을 가진 요소를 반환합니다. 해당 요소가 없으면 null을 반환합니다. 둘 이상의 요소에 해당 값을 가진 ID 특성이 있는 경우 반환되는 값은 정의되지 않습니다. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(string) | 인수에 지정된 모든 클래스가 있는 문서의 모든 요소를 포함하는 라이브 NodeList 개체를 반환합니다. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(string) | 주어진 태그 이름과 함께 문서 순서대로 모든 요소의 NodeList를 반환하고 문서에 포함되어 있습니다. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(string, string) | 지정된 로컬 이름과 네임스페이스 URI를 가진 모든 요소의 NodeList를 문서 순서로 반환합니다. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | 이 노드(요소인 경우)에 속성이 있는지 여부를 반환합니다. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 이 노드에 자식이 있는지 여부를 반환합니다. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(Node, bool) | 원본 문서에서 소스 노드를 변경하거나 제거하지 않고 다른 문서에서 이 문서로 노드를 가져옵니다. 이 방법은 소스 노드의 새 복사본을 생성합니다. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | 기존 자식 노드 자식 앞에 노드를 삽입합니다. child가 null이면 children 목록 끝에 노드를 삽입합니다. child가 DocumentFragment 객체이면 모든 자식이 동일한 순서로 child 앞에 삽입됩니다. 자식이 이미 트리에 있으면 먼저 제거됩니다. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | 이 메서드는 지정된 namespaceURI가 기본 네임스페이스인지 확인합니다. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | 두 노드가 같은지 테스트합니다. 이 메서드는 Node.isSameNode()로 테스트할 수 있는 동일성(즉, 두 노드가 동일한 객체에 대한 참조인지 여부)이 아니라 노드의 동일성을 테스트합니다. 동일한 모든 노드는 동일하지만 그 반대는 참이 아닐 수 있습니다. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | 이 노드가 주어진 노드와 동일한 노드인지 여부를 반환합니다. 이 메서드는 구현에서 반환된 두 개의 노드 참조가 동일한 개체를 참조하는지 여부를 확인하는 방법을 제공합니다. 두 노드 참조가 동일한 개체에 대한 참조인 경우 프록시를 통하더라도 참조는 완전히 상호 교환 가능하게 사용될 수 있으므로 모든 속성이 동일한 값을 가지며 두 참조에서 동일한 DOM 메서드를 호출하면 항상 정확히 동일한 효과가 발생합니다. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | 이 노드에서 시작하여 지정된 접두사에 연결된 네임스페이스 URI를 찾습니다. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | 이 노드에서 시작하여 지정된 네임스페이스 URI에 연결된 접두사를 찾습니다. 기본 네임스페이스 선언은 이 메서드에서 무시됩니다. 이 메서드에서 사용하는 알고리즘에 대한 자세한 내용은 Namespace Prefix Lookup을 참조하십시오. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(RequestMessage) | 지정된 요청 개체를 기반으로 문서를 로드하여 이전 내용을 바꿉니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(string) | 지정된 URL(Uniform Resource Locator)의 문서를 현재 인스턴스로 로드하여 이전 콘텐츠를 바꿉니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(Url) | 지정된 URL(Uniform Resource Locator)의 문서를 현재 인스턴스로 로드하여 이전 콘텐츠를 바꿉니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(Stream, string) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 확인하고 이전 콘텐츠를 바꿉니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(Stream, Url) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 상대 리소스를 확인하고 이전 콘텐츠를 바꿉니다. 문서 로드는 스트림의 현재 위치에서 시작됩니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(string, string) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 관련 리소스를 확인하여 이전 콘텐츠를 바꿉니다. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(string, Url) | 지정된 콘텐츠에서 문서를 로드하고 baseUri를 사용하여 관련 리소스를 확인하여 이전 콘텐츠를 바꿉니다. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 특성 노드를 포함하여 이 노드 아래 하위 트리의 전체 깊이에 있는 모든 텍스트 노드를 구조(예: 요소, 주석, 처리 명령, CDATA 섹션 및 엔터티 참조)만이 텍스트를 구분하는 "일반" 형식으로 넣습니다. 노드, 즉 인접한 Text 노드나 빈 Text 노드가 없습니다. 이는 문서의 DOM 보기가 저장되고 다시 로드된 것과 동일하도록 하는 데 사용할 수 있으며 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회)이 다음과 같은 경우에 유용합니다. 사용할 수 있습니다. Node.ownerDocument에 연결된 DOMConfiguration 개체의 "normalize-characters" 매개 변수가 true이면 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(string) | selector 와 일치하는 문서의 첫 번째 요소를 반환합니다. |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(string) | selector 와 일치하는 문서의 모든 요소의 NodeList를 반환합니다. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | 자식 목록에서 oldChild로 표시된 자식 노드를 제거하고 반환합니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(IDevice) | 이 메서드는 현재 문서의 내용을 지정된 그래픽 장치에 렌더링하는 데 사용됩니다. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | 자식 목록에서 자식 노드 oldChild를 newChild로 바꾸고 oldChild 노드를 반환합니다. newChild가 DocumentFragment 객체이면 oldChild는 동일한 순서로 삽입되는 모든 DocumentFragment 자식으로 대체됩니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 반환String 이 instance. 를 나타냅니다. |
| [Write](../../aspose.svg.dom/document/write/)(params string[]) | open()에 의해 열린 문서 스트림에 텍스트 문자열을 씁니다. 이 함수는 반드시 DTD에 의해 구동되지 않는 document 를 생성하므로 be 가 문서의 컨텍스트에서 잘못된 결과를 생성할 수 있습니다. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(params string[]) | open()에 의해 열린 document 스트림에 개행 문자가 뒤따르는 텍스트 문자열을 씁니다. 함수 will 는 반드시 DTD에 의해 구동되지 않는 문서를 생성하므로 는 the document 의 컨텍스트에서 잘못된 결과를 생성할 수 있습니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | OnAbort 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | OnBlur 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | OnCancel 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | OnCanplay 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | OnCanPlayThrough 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | OnChange 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | OnClick 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | OnCueChange 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | OnDblClick 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | OnDurationChange 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | OnEmptied 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | OnEnded 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | OnError 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | OnFocus 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | OnInput 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | OnInvalid 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | OnKeyDown 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | OnKeyPress 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | OnKeyUp 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | OnLoad 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | OnLoadedData 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | OnLoadedMetadata 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | OnLoadStart 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | OnMouseDown 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | OnMouseEnter 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | OnMouseLeave 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | OnMouseMove 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | OnMouseOut 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | OnMouseOver 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | OnMouseUp 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | OnMouseWheel 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | OnPause 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | OnPlay 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | OnPlaying 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | OnProgress 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | OnRateChange 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | OnReadyStateChange 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | OnReset 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | OnResize 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | OnScroll 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | OnSeeked 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | OnSeeking 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | OnSelect 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | OnShow 이벤트에 대한 이벤트 핸들러를 가져오거나 설정합니다. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | OnStalled 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | OnSubmit 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | OnSuspend 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | OnTimeUpdate 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | OnToggle 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | OnVolumeChange 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | OnWaiting 이벤트에 대한 이벤트 처리기를 가져오거나 설정합니다. |

### 또한보십시오

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* 네임스페이스 [Aspose.Svg.Dom](../../aspose.svg.dom/)
* 집회 [Aspose.SVG](../../)


