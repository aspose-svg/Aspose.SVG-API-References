---
title: "SVGDocument 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.SVGDocument 类。SVGDocument 是 SVG 层次结构的根节点，保存整个内容。除了提供对层次结构的访问外，它还提供一些便利方法，用于从文档中获取特定信息集合。除了加载标准的 .svg 文件外，构造函数和 Navigate 方法都可以加载 gzip 压缩的 .svgz 文件。当 svg 元素作为来自其他命名空间的文档的组件内联嵌入时，例如在 XHTML 文档中内联嵌入 svg 元素时，SVGDocument 对象将不存在，文档对象层次结构的根对象将是其他类型的 Document 对象，如 HTMLDocument 对象。然而，当 XML 文档层次结构的根元素是 svg 元素时（例如查看独立的 SVG 文件，即 MIME 类型为 image/svg+xml 的文件），SVGDocument 对象确实会存在，并且它将是文档对象模型层次结构的根对象。"
type: docs
weight: 5260
url: /zh/net/aspose.svg/svgdocument/
---
## SVGDocument class

`SVGDocument` 是 SVG 层次结构的根节点并保存全部内容。除了提供对层次结构的访问外，它还提供一些便利方法，用于从文档中获取特定信息集合。除了加载标准的 .svg 文件外，构造函数和 [`Navigate`](../../aspose.svg.dom/document/navigate/) 方法都可以加载 gzip 压缩的 .svgz 文件。当 ‘svg’ 元素作为来自其他命名空间的文档的组件内联嵌入时，例如在 XHTML 文档 [XHTML] 中内联嵌入 ‘svg’ 元素时，SVGDocument 对象将不存在；相反，文档对象层次结构的根对象将是其他类型的 Document 对象，如 HTMLDocument 对象。然而，当 XML 文档层次结构的根元素是 ‘svg’ 元素时，例如查看独立的 SVG 文件（即 MIME 类型为 \"image/svg+xml\" 的文件），SVGDocument 对象确实会存在，并且它将是文档对象模型层次结构的根对象。

```csharp
public class SVGDocument : Document, IDocumentCSS
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | 初始化 `SVGDocument` 类的新实例。 |
| [SVGDocument](svgdocument/#constructor_1)(*[Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。 |
| [SVGDocument](svgdocument/#constructor_2)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_10)(*string*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_4)(*[Url](../url/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_3)(*[RequestMessage](../../aspose.svg.net/requestmessage/), [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_8)(*Stream, string*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_6)(*Stream, [Url](../url/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_11)(*string, [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_14)(*string, string*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_12)(*string, [Url](../url/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_5)(*[Url](../url/), [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_9)(*Stream, string, [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_7)(*Stream, [Url](../url/), [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。文档加载从流的当前位置开始。 |
| [SVGDocument](svgdocument/#constructor_15)(*string, string, [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |
| [SVGDocument](svgdocument/#constructor_13)(*string, [Url](../url/), [Configuration](../configuration/)*) | 初始化 `SVGDocument` 类的新实例。构造函数同步工作，会等待所有外部资源（图像、脚本等）加载完成。若要异步加载文档，请使用方法 [`Navigate`](../../aspose.svg.dom/document/navigate/) 或其重载。或者可以通过在 [`Security`](../../aspose.svg.dom/ibrowsingcontext/security/) 中设置相应标志来禁用某些外部资源的加载。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | 此节点的绝对基础 URI，若实现无法获取绝对 URI，则为 null。 |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | 获取文档的编码。 |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | 获取文档的编码。 |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | 返回当前作为此元素子节点的元素节点数量。如果此元素没有 nodeType 为 1 的子节点，则返回 0。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 返回给定元素的子节点的实时 [`NodeList`](../../aspose.svg.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。 |
| [Children](../../aspose.svg.dom/document/children/) { get; } | 返回子元素。 |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | 获取文档的内容类型。 |
| [Context](../../aspose.svg.dom/document/context/) { get; } | 获取当前的浏览上下文。 |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Document 接口的 defaultView IDL 属性，在获取时必须返回该 Document 所关联的浏览上下文的 WindowProxy 对象；如果该 Document 没有关联的浏览上下文，则返回 null。 |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | 与此文档关联的文档类型声明（DTD）。 |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | 这是一个便利属性，允许直接访问文档的文档元素子节点。 |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | 文档的位置；如果未定义或文档是使用 DOMImplementation.createDocument 创建的，则为 null。 |
| [Domain](../../aspose.svg/svgdocument/domain/) { get; } | 提供文档的服务器的域名，如果无法通过域名识别服务器，则为 null 字符串。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | 返回节点在树中的第一个子节点，如果节点没有子节点则返回 null。 |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | 返回此元素的第一个子元素节点。如果此元素没有子元素，则返回 null。 |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | 处理此文档的 DOMImplementation 对象。 |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | 获取文档的编码。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | 返回节点的最后一个子节点。如果其父节点是元素，则该子节点通常是元素节点、文本节点或注释节点。如果没有子元素，则返回 null。 |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | 返回此元素的最后一个子元素节点。如果此元素没有子元素，则返回 null。 |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | 返回此节点的限定名称的本地部分。对于除 [`ELEMENT_NODE`](../../aspose.svg.dom/node/element_node/) 和 [`ATTRIBUTE_NODE`](../../aspose.svg.dom/node/attribute_node/) 之外的任何类型节点，以及使用 DOM Level 1 方法（如 [`CreateElement`](../../aspose.svg.dom/document/createelement/)）创建的节点，此值始终为 null。 |
| [Location](../../aspose.svg.dom/document/location/) { get; } | 文档的位置。 |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 返回元素的命名空间 URI，如果元素不在命名空间中，则返回 null。 |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | 返回此元素的下一个兄弟元素节点。如果此元素在文档树中没有后续的元素兄弟节点，则为 null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 返回其父节点的 [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) 中紧随指定节点之后的节点；如果指定节点是父元素中的最后一个子节点，则返回 null。 |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | 此节点的名称，取决于其类型。 |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | 表示底层对象类型的代码。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 返回或设置当前节点的值。 |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | 获取文档来源。 |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | 获取拥有者文档。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 返回 DOM 节点的父级 [`Element`](../../aspose.svg.dom/element/)，如果节点没有父节点或其父节点不是 DOM 元素，则返回 null。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | 返回 DOM 树中指定节点的父节点。 |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 返回指定元素的命名空间前缀，如果未指定前缀，则返回 null。 |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | 返回此元素的前一个兄弟元素节点。如果此元素在文档树中没有前面的元素兄弟节点，则为 null。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 返回其父节点的 [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) 列表中紧挨在指定节点之前的节点；如果指定节点是列表中的第一个，则返回 null。 |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | 返回文档的就绪状态。当文档正在加载时为 "loading"，解析完成但仍在加载子资源时为 "interactive"，加载完成后为 "complete"。 |
| [Referrer](../../aspose.svg/svgdocument/referrer/) { get; } | 返回链接到此页面的页面的 URI。如果用户直接导航到该页面（未通过链接，而是例如通过书签），则该值为空字符串。 |
| [RootElement](../../aspose.svg/svgdocument/rootelement/) { get; } | 文档层次结构中的根 ‘svg’。 |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | 一个属性，用于指定是否强制进行错误检查。当设置为 false 时，实现可以不检查 DOM 操作中通常定义的每一种可能错误情况，也不在 DOM 操作或使用 Document.normalizeDocument() 时抛出任何 DOMException 或报告错误。出现错误时，行为未定义。此属性默认值为 true。 |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | 一个列表，包含文档中显式链接或嵌入的所有样式表。对于 HTML 文档，这包括通过 HTML LINK 元素包含的外部样式表以及内联 STYLE 元素。 |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | 表示节点及其后代的文本内容。 |
| [Title](../../aspose.svg/svgdocument/title/) { get; } | 文档的标题，由 ‘svg’ 根元素的 ‘title’ 子元素指定（例如，这里是标题……）。 |
| [URL](../../aspose.svg/svgdocument/url/) { get; } | 文档的完整 URI。 |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | 一个属性，作为 XML 声明的一部分，指定此文档是否为独立文档。如果未指定，则为 false。 |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | 一个属性，作为 XML 声明的一部分，指定此文档的版本号。如果没有声明且文档支持 "XML" 功能，则值为 "1.0"。如果文档不支持 "XML" 功能，则值始终为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 设置一个函数，当指定事件被传递到目标时将被调用。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | 将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已有节点的引用，[`AppendChild`](../../aspose.svg.dom/node/appendchild/) 会将其从当前位置移动到新位置（在将节点追加到其他节点之前，无需先从其父节点中移除）。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | 返回调用此方法的节点的副本。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | 返回调用此方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。 |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | 此方法创建一个新的属性节点并返回它。创建的对象是实现了 [`Attr`](../../aspose.svg.dom/attr/) 类的节点。DOM 并不强制规定可以以这种方式向特定元素添加哪种属性。 |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | 此方法创建一个新的属性节点并返回它。创建的对象是实现了 [`Attr`](../../aspose.svg.dom/attr/) 类的节点。DOM 并不强制规定可以以这种方式向特定元素添加哪种属性。 |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | 创建一个 CDATASection 节点，其值为指定的字符串。 |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | 根据指定的字符串创建一个 Comment 节点。 |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | 创建一个新的空的 [`DocumentFragment`](../../aspose.svg.dom/documentfragment/)，可以向其中添加 DOM 节点以构建离屏 DOM 树。 |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | 该方法返回一个 [`DocumentType`](../../aspose.svg.dom/documenttype/) 对象，可在文档创建时与 [`CreateDocument`](../../aspose.svg.dom/idomimplementation/createdocument/) 一起使用，或通过诸如 [`InsertBefore`](../../aspose.svg.dom/node/insertbefore/) 或 [`ReplaceChild`](../../aspose.svg.dom/node/replacechild/) 等方法放入文档中。 |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | 创建由 localName 指定的 HTML 元素，如果未识别 localName，则返回 HTMLUnknownElement。 |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | 创建具有给定限定名称和命名空间 URI 的元素。 |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | 创建一个 EntityReference 对象。此外，如果已知被引用的实体，则 EntityReference 节点的子列表将与相应的 Entity 节点相同。 |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | 创建一个实现支持类型的 [`Event`](../../aspose.svg.dom.events/event/)。 |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | 创建一个已解析命名空间的 XPath 表达式。这在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有命名空间前缀。 |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(*[Node](../../aspose.svg.dom/node/)*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(*[Node](../../aspose.svg.dom/node/), long*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | 在指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../../aspose.svg.dom/node/)*) | 适配任何 DOM 节点以解析命名空间，从而可以相对于该节点在文档中出现的上下文轻松求值 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在节点上解析给定前缀的 namespaceURI，使用调用 lookupNamespaceURI 时节点层次结构中可用的当前信息，并且还能正确解析隐式的 xml 前缀。 |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | 根据指定的名称和数据字符串创建一个 ProcessingInstruction 节点。 |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | 根据指定的字符串创建一个 Text 节点。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(*[Node](../../aspose.svg.dom/node/)*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(*[Node](../../aspose.svg.dom/node/), long*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/)(*[Node](../../aspose.svg.dom/node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | 在指定节点为根的子树上创建一个新的 TreeWalker。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 在指定的 [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/) 上分派事件（同步），按适当顺序调用受影响的 EventListeners。正常的事件处理规则（包括捕获阶段和可选的冒泡阶段）同样适用于使用 [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/) 手动分派的事件。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | 执行应用程序定义的任务，以释放、清理或重置非托管资源。 |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../../aspose.svg.dom/node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | 求值 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。 |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | 此方法返回一个 [`Element`](../../aspose.svg.dom/element/) 对象，表示其 id 属性与指定字符串匹配的元素。由于元素 ID（如果指定）必须唯一，它们是快速访问特定元素的有用方式。 |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | 此方法返回一个类似数组的对象，包含所有具有给定类名的子元素。 |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | 此方法返回一个[`HTMLCollection`](../../aspose.svg.collections/htmlcollection/)，其中包含具有给定标签名的元素。 |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | 返回具有给定标签名且属于指定命名空间的元素列表。会搜索整个文档，包括根节点。 |
| [GetOverrideStyle](../../aspose.svg/svgdocument/getoverridestyle/)(*[Element](../../aspose.svg.dom/element/), string*) | 此方法用于检索指定元素及其指定伪元素的覆盖样式声明。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 返回一个布尔值，指示给定的 [`Node`](../../aspose.svg.dom/node/) 是否拥有子节点。 |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../../aspose.svg.dom/node/), bool*) | 从另一个文档导入节点到此文档，而不改变或删除原始文档中的源节点；此方法会创建源节点的新副本。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 在现有子节点 child 之前插入该节点。如果 child 为 null，则将节点插入到子节点列表的末尾。如果 child 是 DocumentFragment 对象，则其所有子节点按相同顺序在 child 之前插入。如果该子节点已经在树中，则会先将其移除。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | 此方法检查指定的 namespaceURI 是否为默认命名空间。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | 测试两个节点是否相等。此方法测试节点的相等性，而非同一性（即两个节点是否引用同一对象），后者可通过 Node.isSameNode() 进行测试。所有相同的节点也会相等，但反之未必成立。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | 该方法是 === 严格相等运算符的旧别名。即，它测试两个节点是否相同（换句话说，它们是否引用同一对象）。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | 从此节点开始查找与给定前缀关联的命名空间 URI。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | 从此节点开始查找与给定命名空间 URI 关联的前缀。此方法会忽略默认命名空间声明。有关此方法使用的算法细节，请参阅 Namespace Prefix Lookup。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | 根据指定的请求对象加载文档，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string*) | 在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*[Url](../url/)*) | 在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | 根据指定的请求对象加载文档，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*Stream, string*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*Stream, [Url](../url/)*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string, CancellationToken*) | 在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string, string*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string, [Url](../url/)*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*[Url](../url/), CancellationToken*) | 在指定的统一资源定位符（URL）处加载文档到当前实例，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*Stream, string, CancellationToken*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*Stream, [Url](../url/), CancellationToken*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。文档加载从流的当前位置开始。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string, string, CancellationToken*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。 |
| [Navigate](../../aspose.svg.dom/document/navigate/)(*string, [Url](../url/), CancellationToken*) | 从指定内容加载文档并使用 baseUri 解析相对资源，替换之前的内容。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | 异步加载文档，基于指定的请求对象。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*string, CancellationToken*) | 异步加载文档，在指定的统一资源定位符（URL）处加载到当前实例。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*[Url](../url/), CancellationToken*) | 异步加载文档，在指定的统一资源定位符（URL）处加载到当前实例。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*Stream, string, CancellationToken*) | 异步加载文档，从指定内容加载并使用 baseUri 解析相对资源。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*Stream, [Url](../url/), CancellationToken*) | 异步加载文档，从指定内容加载并使用 baseUri 解析相对资源。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*string, string, CancellationToken*) | 异步加载文档，从指定内容加载并使用 baseUri 解析相对资源。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/)(*string, [Url](../url/), CancellationToken*) | 异步加载文档，从指定内容加载并使用 baseUri 解析相对资源。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 将此节点下子树的所有 Text 节点（包括属性节点）全部置于一种 "普通" 形式，即仅由结构（例如元素、注释、处理指令、CDATA 区段和实体引用）分隔 Text 节点，确保不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。 |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | 返回文档中匹配选择器的第一个 Element。 |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | 返回文档中匹配选择器的所有 Elements 的 NodeList。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | 从 DOM 中移除一个子节点并返回被移除的节点。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 此方法允许从事件目标移除事件监听器。如果在处理事件时从 [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) 从 [`EventTarget`](../../aspose.svg.dom/eventtarget/) 中移除，则不会被当前操作触发。事件监听器在被移除后永远不会被调用。 |
| override [RenderTo](../../aspose.svg/svgdocument/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | 此方法用于将当前文档的内容打印到指定设备。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 在子节点列表中用 newChild 替换子节点 oldChild，并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，oldChild 将被 DocumentFragment 的所有子节点替换，这些子节点按相同顺序插入。如果 newChild 已经在树中，则会先将其移除。 |
| [Save](../../aspose.svg/svgdocument/save/#save)(*[ResourceHandler](../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) | 使用 [`ResourceHandler`](../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [Save](../../aspose.svg/svgdocument/save/#save_8)(*string*) | 将文档保存到由 `path` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。如果指定的 `url` 以 ".svgz" 结尾，文档将保存为压缩的 SVGZ 文件。 |
| [Save](../../aspose.svg/svgdocument/save/#save_4)(*[Url](../url/)*) | 将文档保存到由 `url` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。如果指定的 `url` 以 ".svgz" 结尾，文档将保存为压缩的 SVGZ 文件。 |
| [Save](../../aspose.svg/svgdocument/save/#save_1)(*[ResourceHandler](../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../aspose.svg.saving/svgsaveformat/)*) | 使用 [`ResourceHandler`](../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [Save](../../aspose.svg/svgdocument/save/#save_2)(*[ResourceHandler](../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../aspose.svg.saving/svgsaveoptions/)*) | 使用 [`ResourceHandler`](../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和资源。 |
| [Save](../../aspose.svg/svgdocument/save/#save_3)(*[ResourceHandler](../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../aspose.svg.saving/svgzsaveoptions/)*) | 使用指定的 [`ResourceHandler`](../../aspose.svg.saving.resourcehandlers/resourcehandler/) 保存文档内容和相关资源。 |
| [Save](../../aspose.svg/svgdocument/save/#save_9)(*string, [SVGSaveFormat](../../aspose.svg.saving/svgsaveformat/)*) | 将文档保存到由 `path` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。 |
| [Save](../../aspose.svg/svgdocument/save/#save_10)(*string, [SVGSaveOptions](../../aspose.svg.saving/svgsaveoptions/)*) | 将文档保存为 `.svg` 文件到由 *path* 指定的本地路径。任何外部资源都会写入名为 `{output_file_name}_files` 的同级文件夹。 |
| [Save](../../aspose.svg/svgdocument/save/#save_11)(*string, [SVGZSaveOptions](../../aspose.svg.saving/svgzsaveoptions/)*) | 将文档保存为压缩的 `.svgz` 文件到由 *path* 指定的本地路径。任何外部资源都会写入名为 `{output_file_name}_files` 的同级文件夹。 |
| [Save](../../aspose.svg/svgdocument/save/#save_5)(*[Url](../url/), [SVGSaveFormat](../../aspose.svg.saving/svgsaveformat/)*) | 将文档保存到由 `url` 指定的本地文件。文档使用的所有资源将保存到相邻的文件夹中，文件夹名称为：output_file_name + "_files"。 |
| [Save](../../aspose.svg/svgdocument/save/#save_6)(*[Url](../url/), [SVGSaveOptions](../../aspose.svg.saving/svgsaveoptions/)*) | 将文档保存为 `.svg` 文件到 *url*。所有外部资源放置在名为 `{output_file_name}_files` 的同级文件夹中。 |
| [Save](../../aspose.svg/svgdocument/save/#save_7)(*[Url](../url/), [SVGZSaveOptions](../../aspose.svg.saving/svgzsaveoptions/)*) | 将文档保存为压缩的 `.svgz` 文件到 *url*。所有外部资源放置在名为 `{output_file_name}_files` 的同级文件夹中。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | 返回表示此实例的字符串。 |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | 将一段文本写入由 open() 打开的文档流。请注意，该函数生成的文档不一定受 DTD 驱动，可能在文档上下文中产生无效结果。 |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | 将一段文本（后跟换行符）写入由 open() 打开的文档流。请注意，该函数生成的文档不一定受 DTD 驱动，可能在文档上下文中产生无效结果。 |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | 获取或设置 OnAbort 事件的事件处理程序。 |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | 获取或设置 OnBlur 事件的事件处理程序。 |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | 获取或设置 OnCancel 事件的事件处理程序。 |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | 获取或设置 OnCanplay 事件的事件处理程序。 |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | 获取或设置 OnCanPlayThrough 事件的事件处理程序。 |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | 获取或设置 OnChange 事件的事件处理程序。 |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | 获取或设置 OnClick 事件的事件处理程序。 |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | 获取或设置 OnCueChange 事件的事件处理程序。 |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | 获取或设置 OnDblClick 事件的事件处理程序。 |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | 获取或设置 OnDurationChange 事件的事件处理程序。 |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | 获取或设置 OnEmptied 事件的事件处理程序。 |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | 获取或设置 OnEnded 事件的事件处理程序。 |
| event [OnError](../../aspose.svg.dom/document/onerror/) | 获取或设置 OnError 事件的事件处理程序。 |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | 获取或设置 OnFocus 事件的事件处理程序。 |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | 获取或设置 OnInput 事件的事件处理程序。 |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | 获取或设置 OnInvalid 事件的事件处理程序。 |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | 获取或设置 OnKeyDown 事件的事件处理程序。 |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | 获取或设置 OnKeyPress 事件的事件处理程序。 |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | 获取或设置 OnKeyUp 事件的事件处理程序。 |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | 获取或设置 OnLoad 事件的事件处理程序。 |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | 获取或设置 OnLoadedData 事件的事件处理程序。 |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | 获取或设置 OnLoadedMetadata 事件的事件处理程序。 |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | 获取或设置 OnLoadStart 事件的事件处理程序。 |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | 获取或设置 OnMouseDown 事件的事件处理程序。 |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | 获取或设置 OnMouseEnter 事件的事件处理程序。 |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | 获取或设置 OnMouseLeave 事件的事件处理程序。 |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | 获取或设置 OnMouseMove 事件的事件处理程序。 |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | 获取或设置 OnMouseOut 事件的事件处理程序。 |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | 获取或设置 OnMouseOver 事件的事件处理程序。 |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | 获取或设置 OnMouseUp 事件的事件处理程序。 |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | 获取或设置 OnMouseWheel 事件的事件处理程序。 |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | 获取或设置 OnPause 事件的事件处理程序。 |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | 获取或设置 OnPlay 事件的事件处理程序。 |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | 获取或设置 OnPlaying 事件的事件处理程序。 |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | 获取或设置 OnProgress 事件的事件处理程序。 |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | 获取或设置 OnRateChange 事件的事件处理程序。 |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | 获取或设置 OnReadyStateChange 事件的事件处理程序。 |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | 获取或设置 OnReset 事件的事件处理程序。 |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | 获取或设置 OnResize 事件的事件处理程序。 |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | 获取或设置 OnScroll 事件的事件处理程序。 |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | 获取或设置 OnSeeked 事件的事件处理程序。 |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | 获取或设置 OnSeeking 事件的事件处理程序。 |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | 获取或设置 OnSelect 事件的事件处理程序。 |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | 获取或设置 OnShow 事件的事件处理程序。 |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | 获取或设置 OnStalled 事件的事件处理程序。 |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | 获取或设置 OnSubmit 事件的事件处理程序。 |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | 获取或设置 OnSuspend 事件的事件处理程序。 |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | 获取或设置 OnTimeUpdate 事件的事件处理程序。 |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | 获取或设置 OnToggle 事件的事件处理程序。 |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | 获取或设置 OnVolumeChange 事件的事件处理程序。 |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | 获取或设置 OnWaiting 事件的事件处理程序。 |

### 另请参阅

* class [Document](../../aspose.svg.dom/document/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../aspose.svg.dom.css/idocumentcss/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
