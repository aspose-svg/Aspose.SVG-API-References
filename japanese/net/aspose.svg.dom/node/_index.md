---
title: "Node クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Node クラス。Node インターフェイスは、ドキュメント オブジェクト モデル全体の主要なデータ型です。ドキュメント ツリー内の単一ノードを表します。"
type: docs
weight: 3140
url: /ja/net/aspose.svg.dom/node/
---
## Node class

Node インターフェイスは、Document Object Model 全体の主要なデータ型であり、ドキュメントツリー内の単一ノードを表します。

```csharp
public abstract class Node : EventTarget, IXPathNSResolver
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | ノードを含むドキュメントの絶対ベース URL を返します。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 指定された要素の子ノードのライブ [`NodeList`](../../aspose.svg.collections/nodelist/) を返します。最初の子ノードはインデックス0が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | ツリー内でノードの最初の子ノードを返します。子が存在しない場合は null を返します。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | ノードの最後の子ノードを返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](./element_node/) と [`ATTRIBUTE_NODE`](./attribute_node/) 以外のタイプのノードや、[`CreateElement`](../document/createelement/) のような DOM Level 1 メソッドで作成されたノードについては、常に null が返されます。 |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 要素の名前空間 URI を返します。要素が名前空間に属さない場合は null を返します。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 指定されたノードの直後にある、親の [`ChildNodes`](./childnodes/) 内のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | 現在のノードの名前を文字列として返します。 |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | 基になるオブジェクトのタイプを表すコード。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 現在のノードの値を取得または設定します。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | DOM ツリー内で指定されたノードの親を返します。 |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 指定された要素の名前空間プレフィックスを返します。プレフィックスが指定されていない場合は null を返します。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 指定されたノードの直前にある、親の [`ChildNodes`](./childnodes/) リスト内のノードを返します。指定されたノードがそのリストの最初の要素である場合は null を返します。 |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | ノードおよびその子孫のテキストコンテンツを表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*Node*) | 指定された親ノードの子ノードリストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、[`AppendChild`](./appendchild/) はそのノードを現在の位置から新しい位置へ移動させます（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode)() | このメソッドが呼び出されたノードの複製を返します。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/#clonenode_1)(*bool*) | このメソッドが呼び出されたノードの複製を返します。そのパラメータはノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 指定された[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)にイベントをディスパッチし、（同期的に）影響を受けたEventListenersを適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズおよびオプションのバブリングフェーズを含む）も、[`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)で手動でディスパッチされたイベントに適用されます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 指定された `Node` が子ノードを持つかどうかを示すブール値を返します。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*Node, Node*) | 既存の子ノード child の前にノードを挿入します。child が null の場合、子リストの末尾にノードを挿入します。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子がすでにツリーに存在する場合、まず削除されます。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | このメソッドは、指定された namespaceURI がデフォルトの名前空間かどうかをチェックします。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*Node*) | 2つのノードが等しいかどうかをテストします。このメソッドはノードの等価性をテストし、同一性（つまり、2つのノードが同じオブジェクトへの参照であるか）ではありません。同一性は Node.isSameNode() でテストできます。同一のノードはすべて等しくなりますが、逆は必ずしも真ではありません。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*Node*) | このメソッドは === 厳密等価演算子のレガシーエイリアスです。つまり、2つのノードが同一かどうか（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。このメソッドはデフォルトの名前空間宣言を無視します。詳細なアルゴリズムについては「Namespace Prefix Lookup」を参照してください。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | このノードの下にあるサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、テキストノード同士が構造（例：要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけで区切られる\"正規\"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これにより、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。Node.ownerDocument に付随する DOMConfiguration オブジェクトのパラメータ \"normalize-characters\" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*Node*) | DOM から子ノードを削除し、削除されたノードを返します。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*Node, Node*) | 子ノード oldChild を newChild に置き換え、子リスト内で置換し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まずそれが削除されます。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | このインスタンスを表す String を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [ATTRIBUTE_NODE](../../aspose.svg.dom/node/attribute_node/) | 属性ノード |
| const [CDATA_SECTION_NODE](../../aspose.svg.dom/node/cdata_section_node/) | CDATA セクションノード |
| const [COMMENT_NODE](../../aspose.svg.dom/node/comment_node/) | コメントノード |
| const [DOCUMENT_FRAGMENT_NODE](../../aspose.svg.dom/node/document_fragment_node/) | ドキュメントフラグメントノード |
| const [DOCUMENT_NODE](../../aspose.svg.dom/node/document_node/) | ドキュメントノード |
| const [DOCUMENT_TYPE_NODE](../../aspose.svg.dom/node/document_type_node/) | ドキュメントタイプノード |
| const [ELEMENT_NODE](../../aspose.svg.dom/node/element_node/) | 要素ノード |
| const [ENTITY_NODE](../../aspose.svg.dom/node/entity_node/) | エンティティノード |
| const [ENTITY_REFERENCE_NODE](../../aspose.svg.dom/node/entity_reference_node/) | エンティティ参照ノード |
| const [NOTATION_NODE](../../aspose.svg.dom/node/notation_node/) | 表記ノード |
| const [PROCESSING_INSTRUCTION_NODE](../../aspose.svg.dom/node/processing_instruction_node/) | 処理命令ノード |
| const [TEXT_NODE](../../aspose.svg.dom/node/text_node/) | テキストノード |

### 参照

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
