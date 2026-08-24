---
title: "NodeFilter 类"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter 类。过滤器是能够过滤节点的对象。"
type: docs
weight: 3210
url: /zh/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

过滤器是知道如何 "filter out" 节点的对象。

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | 测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用；通常不会直接从用户代码调用。（如果您想使用相同的过滤器来指导自己的应用逻辑，也可以这样做。） |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的类型。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | 接受该节点。为 NodeIterator 或 TreeWalker 定义的导航方法将返回此节点。 |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | 拒绝该节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不会返回此节点。对于 TreeWalker，该节点的子节点也将被拒绝。NodeIterator 将其视为 FILTER_SKIP 的同义词。 |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | 跳过此单个节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不会返回此节点。对于 NodeIterator 和 TreeWalker，仍会考虑该节点的子节点。 |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | 显示所有节点。 |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | 显示属性节点。仅在以属性节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，表示属性节点将在迭代或遍历的首位出现。由于属性永远不是其他节点的子节点，在遍历文档树时它们不会出现。 |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | 显示 CDATASection 节点。 |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | 显示注释节点。 |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | 显示 Document 节点。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | 显示 DocumentFragment 节点。 |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | 显示 DocumentType 节点。 |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | 显示 Element 节点。 |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | 显示 Entity 节点。仅在使用 Entity 节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，这意味着 Entity 节点将在遍历的第一个位置出现。由于实体不是文档树的一部分，它们在遍历文档树时不会出现。 |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | 显示 EntityReference 节点。 |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | 显示 Notation 节点。仅在使用 Notation 节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，这意味着 Notation 节点将在遍历的第一个位置出现。由于符号不是文档树的一部分，它们在遍历文档树时不会出现。 |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | 显示 ProcessingInstruction 节点。 |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | 显示 Text 节点。 |

### 另请参阅

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
