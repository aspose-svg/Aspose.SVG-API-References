---
title: Class SVGSVGElement
second_title: .NET API 참조용 Aspose.SVG
description: Aspose.Svg.SVGSVGElement 수업. 핵심 인터페이스 정의는 svg 요소에 해당하는 인터페이스인 SVGSVGElement 인터페이스입니다. 이 인터페이스에는 매트릭스 작업 및 시각적 렌더링 장치에서 다시 그리는 시간을 제어하는 기능과 같이 일반적으로 사용되는 다양한 기타 유틸리티 메서드가 포함되어 있습니다.
type: docs
weight: 3440
url: /ko/net/aspose.svg/svgsvgelement/
---
## SVGSVGElement class

핵심 인터페이스 정의는 'svg' 요소에 해당하는 인터페이스인 SVGSVGElement 인터페이스입니다. 이 인터페이스에는 매트릭스 작업 및 시각적 렌더링 장치에서 다시 그리는 시간을 제어하는 기능과 같이 일반적으로 사용되는 다양한 기타 유틸리티 메서드가 포함되어 있습니다.

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | 이 노드의 속성을 포함하는 NamedNodeMap(요소인 경우) 또는 그렇지 않은 경우 null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | 이 노드의 절대 기본 URI 또는 구현이 절대 URI를 얻을 수 없는 경우 null입니다. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | 이 요소의 자식인 요소 노드의 현재 수를 반환합니다. 이 요소에 nodeType이 1. 인 하위 노드가 없는 경우 0입니다. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 이 노드의 모든 자식을 포함하는 NodeList입니다. 자식이 없으면 노드가 없는 NodeList입니다.. |
| [Children](../../aspose.svg.dom/element/children/) { get; } | 현재 요소의 하위 요소를 반환합니다. |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | "class" 특성을 구문 분석하여 받은 토큰을 포함하는 라이브 DOMTokenList를 반환합니다. |
| [ClassName](../../aspose.svg/svgelement/classname/) { get; } | 지정된 요소의 속성 'class'에 해당합니다. |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | 요소의 클래스 특성입니다. 이 속성은 여러 언어에서 노출되는 "class" 키워드와 충돌하기 위해 due 로 이름이 변경되었습니다. See HTML 4.01의 클래스 속성 정의. |
| [CurrentScale](../../aspose.svg/svgsvgelement/currentscale/) { get; set; } | 가장 바깥쪽 svg 요소에서 이 속성은 확대 및 패닝에 설명된 대로 사용자 확대 및 패닝 작업을 고려하기 위해 초기 보기에 상대적인 현재 배율 인수를 나타냅니다. DOM 속성 currentScale 및 currentTranslate는 2x3 행렬 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]와 동일합니다. "확대"가 활성화된 경우(예: zoomAndPan="magnify") SVG 문서 조각의 가장 바깥쪽 수준(즉, 가장 바깥쪽 svg 요소 외부)에 추가 변환이 배치된 것처럼 효과가 나타납니다. 액세스할 때 가장 바깥쪽 svg 요소가 아닌 'svg' 요소, 이 속성의 동작은 정의되지 않습니다. |
| [CurrentTranslate](../../aspose.svg/svgsvgelement/currenttranslate/) { get; } | 가장 바깥쪽 svg 요소에서 사용자 "배율"을 고려한 해당 변환 요소입니다. 가장 바깥쪽 svg 요소가 아닌 'svg' 요소에서 액세스할 때 이 특성이 어떤 동작을 하는지는 정의되지 않습니다. |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement/) { get; } | 가장 먼 조상 'svg' 요소. 현재 요소가 가장 바깥쪽 svg 요소인 경우 Null입니다. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 이 노드의 첫 번째 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | 이 요소의 첫 번째 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| [Height](../../aspose.svg/svgsvgelement/height/) { get; } | 지정된 'svg' 요소의 '높이' 속성에 해당합니다. |
| [Id](../../aspose.svg/svgelement/id/) { get; set; } | 주어진 요소의 'id' 속성 값 또는 'id'가 없으면 빈 문자열. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | 요소의 내용을 나타내는 HTML 또는 XML의 조각을 반환합니다. 지정된 문자열에서 구문 분석된 노드로 요소의 내용을 대체하도록 설정할 수 있습니다. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 이 노드의 마지막 자식입니다. 해당 노드가 없으면 null을 반환합니다. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | 이 요소의 마지막 자식 요소 노드를 반환합니다. 이 요소에 자식 요소가 없으면 null입니다. |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | 이 노드의 정규화된 이름의 로컬 부분을 반환합니다. ELEMENT_NODE 및 ATTRIBUTE_NODE 이외의 모든 유형의 노드와 Document.createElement()와 같은 DOM 수준 1 메서드로 생성된 노드의 경우 이것은 항상 null입니다. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | 이 노드의 네임스페이스 URI 또는 지정되지 않은 경우 null입니다. |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement/) { get; } | 현재 뷰포트를 설정한 요소. 종종 가장 가까운 조상 'svg' 요소입니다. 현재 요소가 가장 바깥쪽 svg 요소인 경우 Null입니다. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | 이 요소의 다음 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 항목 뒤에 오는 요소 형제 노드가 없는 경우 null입니다. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 이 노드 바로 다음의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | 유형에 따라 이 노드의 이름입니다. |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | 기본 개체의 유형을 나타내는 코드입니다. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 유형에 따라 이 노드의 값입니다. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | 요소와 그 내용을 나타내는 HTML 또는 XML 조각을 반환합니다. 지정된 문자열에서 구문 분석된 노드로 요소를 대체하도록 설정할 수 있습니다. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | 이 노드와 연결된 문서 개체입니다. 이는 새 노드를 만드는 데 사용되는 Document 객체이기도 합니다. 이 노드가 Document 또는 아직 Document와 함께 사용되지 않는 DocumentType인 경우 null입니다. |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement/) { get; } | 가장 가까운 조상 'svg' 요소. 지정된 요소가 가장 바깥쪽 svg 요소인 경우 null입니다. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 부모를 가져옵니다[`Element`](../../aspose.svg.dom/element/) 이 노드의. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 이 노드의 부모입니다. Attr, Document, DocumentFragment, Entity 및 Notation을 제외한 모든 노드에는 부모가 있을 수 있습니다. 그러나 노드가 방금 생성되어 아직 트리에 추가되지 않았거나 트리에서 제거된 경우 null입니다. |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | 이 노드의 네임스페이스 접두사 또는 지정되지 않은 경우 null입니다. null로 정의했을 때 설정해도 아무런 효과가 없다 |
| [PreserveAspectRatio](../../aspose.svg/svgsvgelement/preserveaspectratio/) { get; } | 지정된 요소의 'preserveAspectRatio' 속성에 해당합니다. |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | 이 요소의 이전 형제 요소 노드를 반환합니다. 이 요소에 문서 트리에서 이 요소 앞에 오는 요소 형제 노드가 없는 경우 null입니다. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 이 노드 바로 앞의 노드입니다. 해당 노드가 없으면 null을 반환합니다. |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions/) { get; } | 지정된 요소의 'requiredExtensions' 속성에 해당합니다. |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures/) { get; } | 지정된 요소의 'requiredFeatures' 속성에 해당합니다. |
| [SchemaTypeInfo](../../aspose.svg.dom/element/schematypeinfo/) { get; } | 이 요소와 관련된 유형 정보입니다. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | 이 요소에 저장된 shadowRoot를 반환하거나 닫혀 있으면 null을 반환합니다. |
| [Style](../../aspose.svg/svgelement/style/) { get; } | 지정된 요소의 '스타일' 속성에 해당합니다. 사용자 에이전트가 CSS를 사용한 스타일 지정을 지원하지 않는 경우 이 속성의 값은 항상 null이어야 합니다. |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage/) { get; } | 지정된 요소의 'systemLanguage' 속성에 해당합니다. |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | 요소의 이름입니다. |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | 이 속성은 이 노드와 그 자손의 텍스트 내용을 반환합니다. null로 정의된 경우 설정해도 아무런 효과가 없습니다. 설정 시 이 노드가 가질 수 있는 모든 가능한 자식이 제거되고 새 문자열이 비어 있거나 null이 아닌 경우 이 속성이 설정된 문자열을 포함하는 단일 텍스트 노드로 대체됩니다. |
| [Transform](../../aspose.svg/svggraphicselement/transform/) { get; } | 지정된 요소의 '변환' 속성에 해당합니다. |
| [ViewBox](../../aspose.svg/svgsvgelement/viewbox/) { get; } | 지정된 요소의 속성 'viewBox'에 해당합니다. |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement/) { get; } | 현재 뷰포트를 설정한 요소. 종종 가장 가까운 조상 'svg' 요소입니다. 지정된 요소가 가장 바깥쪽 svg 요소인 경우 null입니다. |
| [Width](../../aspose.svg/svgsvgelement/width/) { get; } | 지정된 'svg' 요소의 '너비' 속성에 해당합니다. |
| [X](../../aspose.svg/svgsvgelement/x/) { get; } | 지정된 'svg' 요소의 속성 'x'에 해당합니다. |
| [Y](../../aspose.svg/svgsvgelement/y/) { get; } | 지정된 'svg' 요소의 속성 'y'에 해당합니다. |
| [ZoomAndPan](../../aspose.svg/svgsvgelement/zoomandpan/) { get; set; } | 지정된 요소의 'zoomAndPan' 속성에 해당합니다. 값은 이 인터페이스에 정의된 SVG_ZOOMANDPAN_* 상수 중 하나여야 합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | 이 메서드를 사용하면 이벤트 대상에 이벤트 리스너를 등록할 수 있습니다. |
| [AnimationsPaused](../../aspose.svg/svgsvgelement/animationspaused/)() | 이 SVG 문서 조각이 일시 중지된 상태이면 true를 반환합니다. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | 이 노드의 자식 목록 끝에 newChild 노드를 추가합니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(ShadowRootMode) | 섀도우 루트를 생성하고 현재 요소에 연결합니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | 이 노드의 복제본을 반환합니다. 즉, 노드의 일반 복사 생성자 역할을 합니다. 중복 노드에는 부모가 없고(parentNode는 null임) 사용자 데이터가 없습니다. |
| [CreateEvent](../../aspose.svg/svgsvgelement/createevent/)(string) | 생성[`Event`](../../aspose.svg.dom.events/event/) 구현에서 지원하는 유형입니다. |
| [CreateSVGAngle](../../aspose.svg/svgsvgelement/createsvgangle/)() | 문서 트리 외부에 SVGAngle 개체를 만듭니다. 객체는 값 0도(단위 없음)로 초기화됩니다. |
| [CreateSVGLength](../../aspose.svg/svgsvgelement/createsvglength/)() | 문서 트리 외부에 SVGLength 개체를 만듭니다. 개체가 0 사용자 단위 값으로 초기화됩니다. |
| [CreateSVGMatrix](../../aspose.svg/svgsvgelement/createsvgmatrix/)() | 문서 트리 외부에 SVGMatrix 객체를 생성합니다. 개체가 항등 행렬로 초기화됩니다. |
| [CreateSVGNumber](../../aspose.svg/svgsvgelement/createsvgnumber/)() | 문서 트리 외부에 SVGNumber 객체를 만듭니다. 개체가 0 값으로 초기화됩니다. |
| [CreateSVGPoint](../../aspose.svg/svgsvgelement/createsvgpoint/)() | 문서 트리 외부에 SVGPoint 개체를 만듭니다. 객체는 사용자 좌표계의 점(0,0)으로 초기화됩니다. |
| [CreateSVGRect](../../aspose.svg/svgsvgelement/createsvgrect/)() | 문서 트리 외부에 SVGRect 개체를 만듭니다. 모든 값이 0 사용자 단위로 설정되도록 개체가 초기화됩니다. |
| [CreateSVGTransform](../../aspose.svg/svgsvgelement/createsvgtransform/)() | 문서 트리 외부에 SVGTransform 개체를 만듭니다. 개체가 항등 행렬 변환(SVG_TRANSFORM_MATRIX)으로 초기화됩니다. |
| [CreateSVGTransformFromMatrix](../../aspose.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | 문서 트리 외부에 SVGTransform 개체를 만듭니다. 객체는 주어진 매트릭스 변환(즉, SVG_TRANSFORM_MATRIX)으로 초기화됩니다. 매개변수 행렬의 값이 복사되고 행렬 매개변수는 SVGTransform::matrix. 로 채택되지 않습니다. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | 이 메서드를 사용하면 구현 이벤트 모델로 이벤트를 보낼 수 있습니다. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 관리되지 않는 리소스 해제, 해제 또는 재설정과 관련된 응용 프로그램 정의 작업을 수행합니다. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(string) | 이름으로 속성 값을 검색합니다. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(string) | 이름으로 속성 노드를 검색합니다. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(string, string) | 로컬 이름 및 네임스페이스 URI로 Attr 노드를 검색합니다. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(string, string) | 로컬 이름과 네임스페이스 URI로 속성 값을 검색합니다. |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox/)() | 포함된 모든 그래픽 요소의 지오메트리에서 현재 사용자 공간(즉, '변환' 속성을 적용한 후)의 타이트한 바운딩 박스를 반환합니다. 스트로크, 클리핑, 마스킹 및 필터 효과는 제외됩니다. 요소가 아직 렌더링되지 않은 경우에도 getBBox는 메서드가 호출된 시점의 실제 경계 상자를 반환해야 합니다. |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm/)() | 최근 사용자 단위(즉, '변환' 속성이 있는 경우 적용 후)에서 가장 가까운 뷰포트 요소에 대한 뷰포트 좌표계로의 변환 행렬을 반환합니다. |
| [GetCurrentTime](../../aspose.svg/svgsvgelement/getcurrenttime/)() | 현재 SVG 문서 조각의 시작 시간을 기준으로 현재 시간을 초 단위로 반환합니다. 문서 타임라인이 시작되기 전에 getCurrentTime이 호출되면(예: 문서의 SVGLoad 이벤트가 전달되기 전에 'script' 요소에서 실행되는 스크립트에 의해) 0이 반환됩니다. |
| [GetElementById](../../aspose.svg/svgsvgelement/getelementbyid/)(string) | id가 elementId에 의해 제공되는 요소에 대해 이 SVG 문서 조각을 검색합니다(즉, 검색은 문서 트리의 하위 집합으로 제한됨). 요소가 발견되면 해당 요소가 반환됩니다. 해당 요소가 없으면 null을 반환합니다. 둘 이상의 요소에 이 id. 가 있으면 동작이 정의되지 않습니다. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(string) | 인수에 지정된 모든 클래스가 있는 문서의 모든 요소를 포함하는 라이브 NodeList 개체를 반환합니다. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(string) | 지정된 태그 이름을 가진 모든 하위 요소의 NodeList를 문서 순서대로 반환합니다. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(string, string) | 지정된 로컬 이름과 네임스페이스 URI를 가진 모든 하위 요소의 NodeList를 문서 순서대로 반환합니다. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 이 메서드는 ECMAScript 개체를 검색하는 데 사용됩니다.Type . |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm/)() | 현재 사용자 단위(즉, '변환' 속성이 있는 경우 적용 후)에서 상위 사용자 에이전트의 "픽셀" 알림으로의 변환 매트릭스를 반환합니다. 디스플레이 장치의 경우 이상적으로는 물리적 화면 픽셀을 나타냅니다. 물리적 픽셀 크기를 알 수 없는 다른 장치나 환경의 경우 "픽셀"의 CSS2 정의와 유사한 알고리즘을 대신 사용할 수 있습니다. 이 요소가 문서 트리에 연결되지 않은 경우 null이 반환됩니다. 이 방법은 getClientCTM으로 더 적절하게 이름이 지정되었을 수 있지만 getScreenCTM이라는 이름은 역사적인 이유로 유지됩니다. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(string) | 지정된 이름을 가진 속성이 이 요소에 지정되거나 기본값이 있으면 true를 반환하고 그렇지 않으면 false를 반환합니다. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(string, string) | 지정된 로컬 이름 및 네임스페이스 URI가 있는 속성이 이 요소에 지정되거나 기본값이 있으면 true를 반환하고 그렇지 않으면 false를 반환합니다. |
| override [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | 이 노드(요소인 경우)에 속성이 있는지 여부를 반환합니다. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 이 노드에 자식이 있는지 여부를 반환합니다. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | 기존 자식 노드 자식 앞에 노드를 삽입합니다. child가 null이면 children 목록 끝에 노드를 삽입합니다. child가 DocumentFragment 객체이면 모든 자식이 동일한 순서로 child 앞에 삽입됩니다. 자식이 이미 트리에 있으면 먼저 제거됩니다. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | 이 메서드는 지정된 namespaceURI가 기본 네임스페이스인지 확인합니다. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | 두 노드가 같은지 테스트합니다. 이 메서드는 Node.isSameNode()로 테스트할 수 있는 동일성(즉, 두 노드가 동일한 객체에 대한 참조인지 여부)이 아니라 노드의 동일성을 테스트합니다. 동일한 모든 노드는 동일하지만 그 반대는 참이 아닐 수 있습니다. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | 이 노드가 주어진 노드와 동일한 노드인지 여부를 반환합니다. 이 메서드는 구현에서 반환된 두 개의 노드 참조가 동일한 개체를 참조하는지 여부를 확인하는 방법을 제공합니다. 두 노드 참조가 동일한 개체에 대한 참조인 경우 프록시를 통하더라도 참조는 완전히 상호 교환 가능하게 사용될 수 있으므로 모든 속성이 동일한 값을 가지며 두 참조에서 동일한 DOM 메서드를 호출하면 항상 정확히 동일한 효과가 발생합니다. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | 이 노드에서 시작하여 지정된 접두사에 연결된 네임스페이스 URI를 찾습니다. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | 이 노드에서 시작하여 지정된 네임스페이스 URI에 연결된 접두사를 찾습니다. 기본 네임스페이스 선언은 이 메서드에서 무시됩니다. 이 메서드에서 사용하는 알고리즘에 대한 자세한 내용은 Namespace Prefix Lookup을 참조하십시오. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 특성 노드를 포함하여 이 노드 아래 하위 트리의 전체 깊이에 있는 모든 텍스트 노드를 구조(예: 요소, 주석, 처리 명령, CDATA 섹션 및 엔터티 참조)만이 텍스트를 구분하는 "일반" 형식으로 넣습니다. 노드, 즉 인접한 Text 노드나 빈 Text 노드가 없습니다. 이는 문서의 DOM 보기가 저장되고 다시 로드된 것과 동일하도록 하는 데 사용할 수 있으며 특정 문서 트리 구조에 의존하는 작업(예: XPointer [XPointer] 조회)이 다음과 같은 경우에 유용합니다. 사용할 수 있습니다. Node.ownerDocument에 연결된 DOMConfiguration 개체의 "normalize-characters" 매개 변수가 true이면 이 메서드는 Text 노드의 문자도 완전히 정규화합니다. |
| [PauseAnimations](../../aspose.svg/svgsvgelement/pauseanimations/)() | 이 'svg' 요소에 해당하는 SVG 문서 조각 내에서 정의된 현재 실행 중인 모든 애니메이션을 일시 중지(즉, 일시 중지)하여 이 문서 조각에 해당하는 애니메이션 시계가 일시 중지가 해제될 때까지 그대로 유지되도록 합니다. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(string) | selector 와 일치하는 문서의 첫 번째 요소를 반환합니다. |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(string) | selector 와 일치하는 문서의 모든 요소의 NodeList를 반환합니다. |
| [Remove](../../aspose.svg.dom/element/remove/)() | 이 인스턴스를 제거합니다. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(string) | 이름으로 속성을 제거합니다. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(Attr) | 지정된 속성 노드를 제거합니다. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(string, string) | 로컬 이름 및 네임스페이스 URI로 특성을 제거합니다. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | 자식 목록에서 oldChild로 표시된 자식 노드를 제거하고 반환합니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../../aspose.svg.dom/eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../../aspose.svg.dom/eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | 이 방법을 사용하면 이벤트 대상에서 이벤트 리스너를 제거할 수 있습니다. [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 에서 제거됩니다.[`EventTarget`](../../aspose.svg.dom/eventtarget/) 이벤트를 처리하는 동안에는 현재 작업에 의해 트리거되지 않습니다. 이벤트 리스너는 제거된 후에는 호출할 수 없습니다. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | 자식 목록에서 자식 노드 oldChild를 newChild로 바꾸고 oldChild 노드를 반환합니다. newChild가 DocumentFragment 객체이면 oldChild는 동일한 순서로 삽입되는 모든 DocumentFragment 자식으로 대체됩니다. newChild가 이미 트리에 있으면 먼저 제거됩니다. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(string, string) | 새 속성을 추가합니다. 해당 이름의 속성이 이미 요소에 있는 경우 해당 값은 parameter 값으로 변경됩니다. |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(Attr) | 새 특성 노드를 추가합니다. 해당 이름(nodeName)을 가진 속성이 이미 요소에 있는 경우 새 속성으로 대체됩니다. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(Attr) | 새 속성을 추가합니다. 해당 로컬 이름 및 해당 네임스페이스 URI를 가진 속성이 이미 요소에 있는 경우 새 속성으로 대체됩니다. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(string, string, string) | 새 속성을 추가합니다. 동일한 로컬 이름과 네임스페이스 URI를 가진 속성이 요소에 이미 있는 경우 해당 접두어는 qualifiedName의 접두어 부분으로 변경되고 해당 값은 value 매개 변수로 변경됩니다. |
| [SetCurrentTime](../../aspose.svg/svgsvgelement/setcurrenttime/)(float) | 이 SVG 문서 조각의 시계를 조정하여 새로운 현재 시간을 설정합니다. 문서 타임라인이 시작되기 전에 setCurrentTime이 호출되면(예를 들어 문서의 SVGLoad 이벤트가 전달되기 전에 'script' 요소에서 실행되는 스크립트에 의해) 메서드의 마지막 호출에 있는 초 값은 문서가 실행되는 시간을 제공합니다. 문서 타임라인이 시작되면 검색합니다. |
| [SetIdAttribute](../../aspose.svg.dom/element/setidattribute/)(string, bool) | 매개변수 isId가 참이면 이 메소드는 지정된 속성을 사용자 정의 ID 속성으로 선언합니다. |
| [SetIdAttributeNode](../../aspose.svg.dom/element/setidattributenode/)(Attr, bool) | 매개변수 isId가 참이면 이 메소드는 지정된 속성을 사용자 정의 ID 속성으로 선언합니다. |
| [SetIdAttributeNS](../../aspose.svg.dom/element/setidattributens/)(string, string, bool) | 매개변수 isId가 참이면 이 메소드는 지정된 속성을 사용자 정의 ID 속성으로 선언합니다. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 반환String 이 instance. 를 나타냅니다. |
| [UnpauseAnimations](../../aspose.svg/svgsvgelement/unpauseanimations/)() | SVG 문서 조각 내에 정의된 현재 실행 중인 애니메이션을 일시 중지 해제(즉, 일시 중지 해제)하여 애니메이션 시계가 일시 중지된 시간부터 계속되도록 합니다. |

### 또한보십시오

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IViewCSS](../../aspose.svg.dom.css/iviewcss/)
* interface [IDocumentCSS](../../aspose.svg.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* 네임스페이스 [Aspose.Svg](../../aspose.svg/)
* 집회 [Aspose.SVG](../../)


