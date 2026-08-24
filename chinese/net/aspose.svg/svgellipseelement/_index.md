---
title: "SVGEllipseElement 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.SVGEllipseElement 类。SVGEllipseElement 接口对应于 ellipse 元素。"
type: docs
weight: 5290
url: /zh/net/aspose.svg/svgellipseelement/
---
## SVGEllipseElement class

该 SVGEllipseElement 接口对应于 ‘ellipse’ 元素。

```csharp
public class SVGEllipseElement : SVGGeometryElement
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | 一个 NamedNodeMap，包含此节点的属性（如果它是 Element），否则为 null。 |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | 返回包含该节点的文档的绝对基础 URL。 |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | 返回当前作为此元素子节点的元素节点数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 返回给定元素的子节点的实时 [`NodeList`](../../aspose.svg.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [Children](../../aspose.svg.dom/element/children/) { get; } | 返回当前元素的子元素。 |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | 返回一个实时的 DOMTokenList，其中包含从解析 \"class\" 属性获得的标记。 |
| [ClassName](../../aspose.svg/svgelement/classname/) { get; } | 对应于给定元素的 ‘class’ 属性。 |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | 元素的 class 属性。由于许多语言中 \"class\" 关键字的冲突，此属性已被重命名。请参阅 HTML 4.01 中的 class 属性定义。 |
| [Cx](../../aspose.svg/svgellipseelement/cx/) { get; } | 对应于给定 ‘circle’ 元素的属性 ‘cx’。 |
| [Cy](../../aspose.svg/svgellipseelement/cy/) { get; } | 对应于给定 ‘circle’ 元素的属性 ‘cy’。 |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement/) { get; } | 最远的祖先 ‘svg’ 元素。如果当前元素是最外层的 svg 元素，则为 Null。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [Id](../../aspose.svg/svgelement/id/) { get; set; } | 给定元素的 ‘id’ 属性的值，如果不存在 ‘id’，则为空字符串。 |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | 返回表示元素内容的 HTML 或 XML 片段。可以设置，以使用从给定字符串解析的节点替换元素的内容。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 返回节点的最后一个子节点。如果其父节点是元素，则该子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | 返回此节点的限定名称的本地部分。对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点，以及使用 DOM Level 1 方法（如 Document.createElement()）创建的节点，此值始终为 null。 |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | 此节点的命名空间 URI，如果未指定则为 null。 |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement/) { get; } | 建立当前视口的元素。通常是最近的祖先 ‘svg’ 元素。如果当前元素是最外层的 svg 元素，则为 null。 |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有后续的元素兄弟节点，则为 null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 返回其父节点的 [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) 中紧随指定节点之后的节点；如果指定节点是父元素中的最后一个子节点，则返回 null。 |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 返回或设置当前节点的值。 |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | 返回表示元素及其内容的 HTML 或 XML 片段。可以设置，以使用从给定字符串解析的节点替换该元素。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | 返回该节点的顶层文档对象。 |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement/) { get; } | 最近的祖先 ‘svg’ 元素。如果给定元素是最外层的 svg 元素，则为 Null。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 返回 DOM 节点的父级 [`Element`](../../aspose.svg.dom/element/)，如果节点没有父节点或其父节点不是 DOM 元素，则返回 null。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 返回 DOM 树中指定节点的父节点。 |
| [PathLength](../../aspose.svg/svggeometryelement/pathlength/) { get; } | 对应于给定元素上的属性 pathLength。 |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | 此节点的命名空间前缀，如果未指定则为 null。当其被定义为 null 时，设置它不会产生任何效果。 |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有前面的元素兄弟节点，则为 null。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 返回其父节点的 [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) 列表中紧挨在指定节点之前的节点；如果指定节点是列表中的第一个，则返回 null。 |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions/) { get; } | 对应于给定元素的 ‘requiredExtensions’ 属性。 |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures/) { get; } | 对应于给定元素的 ‘requiredFeatures’ 属性。 |
| [Rx](../../aspose.svg/svgellipseelement/rx/) { get; } | 对应于给定 ‘circle’ 元素的属性 ‘cx’。 |
| [Ry](../../aspose.svg/svgellipseelement/ry/) { get; } | 对应于给定 ‘circle’ 元素的属性 ‘ry’。 |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | 返回存储在此元素上的 shadowRoot，如果已关闭则返回 null。 |
| [Style](../../aspose.svg/svgelement/style/) { get; } | 对应于给定元素的 ‘style’ 属性。如果用户代理不支持 CSS 样式，则此属性必须始终为 null。 |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage/) { get; } | 对应于给定元素的 ‘systemLanguage’ 属性。 |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | 元素的名称。 |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | 此属性返回该节点及其后代的文本内容。当其被定义为 null 时，设置它不会产生任何效果。设置时，节点可能拥有的所有子节点都会被移除，如果新字符串非空且非 null，则会被一个包含该字符串的单一 Text 节点所取代。 |
| [Transform](../../aspose.svg/svggraphicselement/transform/) { get; } | 对应给定元素上的属性 ‘transform’。 |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement/) { get; } | 确定当前视口的元素。通常为最近的祖先 ‘svg’ 元素。如果给定元素是最外层的 svg 元素，则为 Null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | 将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已有节点的引用，[`AppendChild`](../../aspose.svg.dom/node/appendchild/) 会将其从当前位置移动到新位置（在将节点追加到其他节点之前，无需先从其父节点中移除）。 |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../../aspose.svg.dom/shadowrootmode/)*) | 创建 shadow root 并将其附加到当前元素。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 返回调用此方法的节点的副本。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | 返回调用此方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [Combine](../../aspose.svg/svggeometryelement/combine/)(*[SVGGeometryElement](../svggeometryelement/), [BooleanPathOp](../../aspose.svg.rendering/booleanpathop/)*) | 使用布尔运算将此几何体与另一个 SVG 几何体组合，并返回包含结果的新 `<path>` 元素。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 在指定的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) 上分派事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | 按名称检索属性值。 |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | 以字符串数组形式返回元素的属性名称。如果元素没有属性，则返回空数组。 |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | 按名称检索属性节点。 |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | 按本地名称和命名空间 URI 检索 Attr 节点。 |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | 按本地名称和命名空间 URI 检索属性值。 |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox/)() | 返回当前用户坐标空间（即在应用了 ‘transform’ 属性后，如果有的话）中所有包含的图形元素的几何形状的紧凑边界框（不包括描边、裁剪、遮罩和滤镜效果）。请注意，getBBox 必须在调用时返回实际的边界框，即使该元素尚未渲染。 |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm/)() | 返回从当前用户单位（即在应用了 ‘transform’ 属性后，如果有的话）到最近的 nearestViewportElement 的视口坐标系的变换矩阵。 |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | 返回包含 [`element`](../../aspose.svg.dom/element/) 中所有具有参数中指定的全部类的元素的 [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) 对象。 |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | 返回按文档顺序包含具有给定标签名的所有 [`elements`](../../aspose.svg.dom/element/) 的 [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) 对象。 |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | 返回按文档顺序包含具有给定本地名称和命名空间 URI 字符串的所有 [`elements`](../../aspose.svg.dom/element/) 的 [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) 对象。 |
| [GetEquivalentPath](../../aspose.svg/svggeometryelement/getequivalentpath/)() | 返回一个新的 [`SVGPathSegList`](../../aspose.svg.paths/svgpathseglist/) 实例，该实例将 [`SVGGeometryElement`](../svggeometryelement/) 表示为路径段。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [GetPointAtLength](../../aspose.svg/svggeometryelement/getpointatlength/)(*float*) | 返回用户空间中的 (x,y) 坐标，该坐标是沿路径的距离单位，使用用户代理的路径距离算法。 |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm/)() | 返回从当前用户单位（即在应用了 ‘transform’ 属性后，如果有的话）到父用户代理所感知的 \"像素\" 的变换矩阵。对于显示设备，这理想情况下代表物理屏幕像素。对于其他设备或物理像素大小未知的环境，可以使用类似 CSS2 对 \"像素\" 定义的算法。若该元素未挂载到文档树中，则返回 null。该方法本可以更恰当地命名为 getClientCTM，但出于历史原因仍保留为 getScreenCTM。 |
| [GetTotalLength](../../aspose.svg/svggeometryelement/gettotallength/)() | 返回用户代理使用路径距离算法计算的路径总长度值，以当前用户坐标系中的距离表示。 |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | 当此元素上指定了具有给定名称的属性或该属性具有默认值时返回 true，否则返回 false。 |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | 当此元素上指定了具有给定本地名称和命名空间 URI 的属性或该属性具有默认值时返回 true，否则返回 false。 |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | 返回此节点（如果它是元素）是否具有任何属性 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 返回一个布尔值，指示给定的 [`Node`](../../aspose.svg.dom/node/) 是否拥有子节点。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 在现有子节点 child 之前插入该节点。如果 child 为 null，则将节点插入到子节点列表的末尾。如果 child 是 DocumentFragment 对象，则其所有子节点按相同顺序在 child 之前插入。如果该子节点已经在树中，则会先将其移除。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | 测试两个节点是否相等。此方法测试节点的相等性，而非同一性（即两个节点是否引用同一对象），后者可通过 Node.isSameNode() 进行测试。所有相同的节点也会相等，但反之未必成立。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | 该方法是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换句话说，它们是否引用同一对象）。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | 从此节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | 从此节点开始查找与给定命名空间 URI 关联的前缀。此方法会忽略默认命名空间声明。有关此方法使用的算法细节，请参阅 Namespace Prefix Lookup。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 将此节点下子树的所有 Text 节点（包括属性节点）全部置于一种 "普通" 形式，即仅由结构（例如元素、注释、处理指令、CDATA 区段和实体引用）分隔 Text 节点，确保不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | 返回文档中匹配选择器的第一个 Element。 |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | 返回文档中匹配选择器的所有 Elements 的 NodeList。 |
| [Remove](../../aspose.svg.dom/element/remove/)() | 删除此实例。 |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | 按名称删除属性。 |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | 删除指定的属性节点。 |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | 按本地名称和命名空间 URI 删除属性。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | 从 DOM 中移除一个子节点并返回被移除的节点。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，oldChild 将被 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | 添加新属性。如果元素中已存在具有该名称的属性，则其值将更改为 value 参数的值。 |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | 添加新属性节点。如果元素中已存在具有该名称（nodeName）的属性，则它将被新属性替换。 |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../../aspose.svg.dom/attr/)*) | 添加新属性。如果元素中已存在具有该本地名称和命名空间 URI 的属性，则它将被新属性替换。 |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | 添加新属性。如果元素上已存在具有相同本地名称和命名空间 URI 的属性，则其前缀将更改为 qualifiedName 的前缀部分，且其值将更改为 value 参数的值。 |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string*) | 如果未提供 force，则“切换” qualifiedName：如果它已存在则移除，若不存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。 |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string, bool*) | 如果未提供 force，则“切换” qualifiedName：如果它已存在则移除，若不存在则添加。如果 force 为 true，则添加 qualifiedName；如果 force 为 false，则移除 qualifiedName。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [SVGGeometryElement](../svggeometryelement/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
