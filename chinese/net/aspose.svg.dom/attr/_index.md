---
title: "Attr 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Attr 类。Attr 接口表示 Element 对象中的属性。通常，该属性的可取值在与文档关联的模式中定义。"
type: docs
weight: 2350
url: /zh/net/aspose.svg.dom/attr/
---
## Attr class

该 Attr 接口表示 Element 对象中的属性。通常，该属性的允许值在与文档关联的模式中定义。

```csharp
public sealed class Attr : Node
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | 返回包含该节点的文档的绝对基础 URL。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 返回给定元素的子节点的实时 [`NodeList`](../../aspose.svg.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 返回节点的最后一个子节点。如果其父节点是元素，则该子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| override [LocalName](../../aspose.svg.dom/attr/localname/) { get; } | 返回此节点的限定名称的本地部分。对于除 ELEMENT_NODE 和 ATTRIBUTE_NODE 之外的任何类型的节点，以及使用 DOM Level 1 方法（如 Document.createElement()）创建的节点，此值始终为 null。 |
| [Name](../../aspose.svg.dom/attr/name/) { get; } | 返回此属性的名称。 |
| override [NamespaceURI](../../aspose.svg.dom/attr/namespaceuri/) { get; } | 此节点的命名空间 URI，如果未指定则为 null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 返回在其父节点的 [`ChildNodes`](../node/childnodes/) 中紧随指定节点之后的节点，如果指定节点是父元素的最后一个子节点，则返回 null。 |
| override [NodeName](../../aspose.svg.dom/attr/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.svg.dom/attr/nodetype/) { get; } | 表示底层对象类型的代码。 |
| override [NodeValue](../../aspose.svg.dom/attr/nodevalue/) { get; set; } | 此节点的值，取决于其类型。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | 返回该节点的顶层文档对象。 |
| [OwnerElement](../../aspose.svg.dom/attr/ownerelement/) { get; } | 该属性所附着的 Element 节点，如果该属性未使用则为 null。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 返回 DOM 节点的父级 [`Element`](../element/)，如果节点没有父节点或其父节点不是 DOM Element，则返回 null。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 返回 DOM 树中指定节点的父节点。 |
| override [Prefix](../../aspose.svg.dom/attr/prefix/) { get; } | 此节点的命名空间前缀，如果未指定则为 null。当其被定义为 null 时，设置它不会产生任何效果。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 返回在其父节点的 [`ChildNodes`](../node/childnodes/) 列表中紧邻指定节点之前的节点，如果指定节点是列表中的第一个，则返回 null。 |
| [Specified](../../aspose.svg.dom/attr/specified/) { get; } | 如果在实例文档中显式为此属性赋值则为 true，否则为 false。 |
| override [TextContent](../../aspose.svg.dom/attr/textcontent/) { get; set; } | 此属性返回该节点及其后代的文本内容。当其被定义为 null 时，设置它不会产生任何效果。设置时，节点可能拥有的所有子节点都会被移除，如果新字符串非空且非 null，则会被一个包含该字符串的单一 Text 节点所取代。 |
| [Value](../../aspose.svg.dom/attr/value/) { get; set; } | 检索时，属性的值以字符串形式返回。 |

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
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | 从 DOM 中移除一个子节点并返回被移除的节点。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标中移除事件监听器。如果在处理事件时将一个 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../eventtarget/) 中移除，则它不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，oldChild 将被 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
