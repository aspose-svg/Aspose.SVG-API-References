---
title: "NodeFilter クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.Filters.NodeFilter クラス。フィルタはノードを除外する方法を知っているオブジェクトです"
type: docs
weight: 3210
url: /ja/net/aspose.svg.dom.traversal.filters/nodefilter/
---
## NodeFilter class

フィルタはノードを「除外」する方法を知っているオブジェクトです。

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [AcceptNode](../../aspose.svg.dom.traversal.filters/nodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | 指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。） |
| override [GetPlatformType](../../aspose.svg.dom.traversal.filters/nodefilter/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_accept/) | ノードを受け入れます。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返します。 |
| const [FILTER_REJECT](../../aspose.svg.dom.traversal.filters/nodefilter/filter_reject/) | ノードを拒否します。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返しません。TreeWalker では、このノードの子ノードも拒否されます。NodeIterator はこれを FILTER_SKIP の同義語として扱います。 |
| const [FILTER_SKIP](../../aspose.svg.dom.traversal.filters/nodefilter/filter_skip/) | この単一ノードをスキップします。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返しません。NodeIterator と TreeWalker の両方で、このノードの子ノードは引き続き考慮されます。 |
| const [SHOW_ALL](../../aspose.svg.dom.traversal.filters/nodefilter/show_all/) | すべてのノードを表示します。 |
| const [SHOW_ATTRIBUTE](../../aspose.svg.dom.traversal.filters/nodefilter/show_attribute/) | 属性ノードを表示します。これは、属性ノードをルートとしてイテレータまたはツリーワーカーを作成する場合にのみ意味があります。その場合、属性ノードはイテレーションまたはトラバーサルの最初の位置に表示されます。属性は他のノードの子になることはないため、ドキュメントツリーを走査するときには表示されません。 |
| const [SHOW_CDATA_SECTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection ノードを表示します。 |
| const [SHOW_COMMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_comment/) | コメントノードを表示します。 |
| const [SHOW_DOCUMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document/) | Document ノードを表示します。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment ノードを表示します。 |
| const [SHOW_DOCUMENT_TYPE](../../aspose.svg.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType ノードを表示します。 |
| const [SHOW_ELEMENT](../../aspose.svg.dom.traversal.filters/nodefilter/show_element/) | Element ノードを表示します。 |
| const [SHOW_ENTITY](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity/) | エンティティノードを表示します。これは、エンティティノードをルートとしてイテレータまたはツリーワーカーを作成する場合にのみ意味があります。その場合、エンティティノードはトラバーサルの最初の位置に表示されます。エンティティはドキュメントツリーの一部ではないため、ドキュメントツリーを走査するときには表示されません。 |
| const [SHOW_ENTITY_REFERENCE](../../aspose.svg.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference ノードを表示します。 |
| const [SHOW_NOTATION](../../aspose.svg.dom.traversal.filters/nodefilter/show_notation/) | Notation ノードを表示します。これは、Notation ノードをルートとしてイテレータまたはツリーワーカーを作成する場合にのみ意味があります。その場合、Notation ノードはトラバーサルの最初の位置に表示されます。Notation はドキュメントツリーの一部ではないため、ドキュメントツリーを走査するときには表示されません。 |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.svg.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction ノードを表示します。 |
| const [SHOW_TEXT](../../aspose.svg.dom.traversal.filters/nodefilter/show_text/) | テキストノードを表示します。 |

### 参照

* class [DOMObject](../../aspose.svg.dom/domobject/)
* interface [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)
* namespace [Aspose.Svg.Dom.Traversal.Filters](../../aspose.svg.dom.traversal.filters/)
* assembly [Aspose.SVG](../../)
