---
title: "DocumentFragment 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.DocumentFragment 类。DocumentFragment 是一种轻量级或最小化的 Document 对象。通常需要提取文档树的一部分或创建文档的新片段。"
type: docs
weight: 2820
url: /zh/net/aspose.svg.dom/documentfragment/
---
## DocumentFragment class

DocumentFragment 是一个“轻量级”或“最小化”的 Document 对象。通常需要能够提取文档树的一部分或创建文档的新片段。

```csharp
public class DocumentFragment : Node, IParentNode
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | 返回包含该节点的文档的绝对基础 URL。 |
| [ChildElementCount](../../aspose.svg.dom/documentfragment/childelementcount/) { get; } | 返回当前作为此元素子节点的元素节点数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 返回给定元素的子节点的实时 [`NodeList`](../../aspose.svg.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [Children](../../aspose.svg.dom/documentfragment/children/) { get; } | 返回当前元素的子元素。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [FirstElementChild](../../aspose.svg.dom/documentfragment/firstelementchild/) { get; } | 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [InnerHTML](../../aspose.svg.dom/documentfragment/innerhtml/) { get; set; } | 返回表示元素内容的 HTML 或 XML 片段。可以设置，以使用从给定字符串解析的节点替换元素的内容。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 返回节点的最后一个子节点。如果其父节点是元素，则该子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| [LastElementChild](../../aspose.svg.dom/documentfragment/lastelementchild/) { get; } | 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | 返回此节点的限定名称的本地部分。对于除 [`ELEMENT_NODE`](../node/element_node/) 和 [`ATTRIBUTE_NODE`](../node/attribute_node/) 之外的任何类型节点，以及使用 DOM Level 1 方法创建的节点，例如 [`CreateElement`](../document/createelement/)，此值始终为 null。 |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 返回元素的命名空间 URI，如果元素不在命名空间中，则返回 null。 |
| [NextElementSibling](../../aspose.svg.dom/documentfragment/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有后续的元素兄弟节点，则为 null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 返回在其父节点的 [`ChildNodes`](../node/childnodes/) 中紧随指定节点之后的节点，如果指定节点是父元素的最后一个子节点，则返回 null。 |
| override [NodeName](../../aspose.svg.dom/documentfragment/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.svg.dom/documentfragment/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 返回或设置当前节点的值。 |
| [OuterHTML](../../aspose.svg.dom/documentfragment/outerhtml/) { get; set; } | 返回表示元素及其内容的 HTML 或 XML 片段。可以设置，以使用从给定字符串解析的节点替换该元素。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | 返回该节点的顶层文档对象。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 返回 DOM 节点的父级 [`Element`](../element/)，如果节点没有父节点或其父节点不是 DOM Element，则返回 null。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 返回 DOM 树中指定节点的父节点。 |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 返回指定元素的命名空间前缀，如果未指定前缀，则返回 null。 |
| [PreviousElementSibling](../../aspose.svg.dom/documentfragment/previouselementsibling/) { get; } | 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有前面的元素兄弟节点，则为 null。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 返回在其父节点的 [`ChildNodes`](../node/childnodes/) 列表中紧邻指定节点之前的节点，如果指定节点是列表中的第一个，则返回 null。 |
| override [TextContent](../../aspose.svg.dom/documentfragment/textcontent/) { get; set; } | 此属性返回该节点及其后代的文本内容。当其被定义为 null 时，设置它不会产生任何效果。设置时，节点可能拥有的所有子节点都会被移除，如果新字符串非空且非 null，则会被一个包含该字符串的单一 Text 节点所取代。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | 将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已有节点的引用，[`AppendChild`](../node/appendchild/) 会将其从当前位置移动到新位置（无需在将节点追加到其他节点之前先将其从父节点中移除）。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 返回调用此方法的节点的副本。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | 返回调用此方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 在指定的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) 上分派事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 返回一个布尔值，指示给定的 [`Node`](../node/) 是否具有子节点。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | 在现有子节点 child 之前插入该节点。如果 child 为 null，则将节点插入到子节点列表的末尾。如果 child 是 DocumentFragment 对象，则其所有子节点按相同顺序在 child 之前插入。如果该子节点已经在树中，则会先将其移除。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | 测试两个节点是否相等。此方法测试节点的相等性，而非同一性（即两个节点是否引用同一对象），后者可通过 Node.isSameNode() 进行测试。所有相同的节点也会相等，但反之未必成立。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | 该方法是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换句话说，它们是否引用同一对象）。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | 从此节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | 从此节点开始查找与给定命名空间 URI 关联的前缀。此方法会忽略默认命名空间声明。有关此方法使用的算法细节，请参阅 Namespace Prefix Lookup。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 将此节点下子树的所有 Text 节点（包括属性节点）全部置于一种 "普通" 形式，即仅由结构（例如元素、注释、处理指令、CDATA 区段和实体引用）分隔 Text 节点，确保不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.svg.dom/documentfragment/queryselector/)(*string*) | 返回文档中匹配选择器的第一个 Element。 |
| [QuerySelectorAll](../../aspose.svg.dom/documentfragment/queryselectorall/)(*string*) | 返回文档中匹配选择器的所有 Elements 的 NodeList。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | 从 DOM 中移除一个子节点并返回被移除的节点。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，oldChild 将被 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [Node](../node/)
* interface [IParentNode](../iparentnode/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
