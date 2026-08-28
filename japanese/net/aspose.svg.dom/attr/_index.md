---
title: "Attr クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Attr クラス。Attr インターフェイスは Element オブジェクト内の属性を表します。通常、属性の許容値はドキュメントに関連付けられたスキーマで定義されています。"
type: docs
weight: 2350
url: /ja/net/aspose.svg.dom/attr/
---
## Attr class

Attr インターフェイスは Element オブジェクト内の属性を表します。通常、その属性の許容値はドキュメントに関連付けられたスキーマで定義されます。

```csharp
public sealed class Attr : Node
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | ノードを含むドキュメントの絶対ベース URL を返します。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 指定された要素の子ノードのライブ [`NodeList`](../../aspose.svg.collections/nodelist/) を返します。最初の子ノードはインデックス0が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | ツリー内でノードの最初の子ノードを返します。子が存在しない場合は null を返します。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | ノードの最後の子ノードを返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| override [LocalName](../../aspose.svg.dom/attr/localname/) { get; } | このノードの修飾名のローカル部分を返します。ELEMENT_NODE と ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードの場合、常に null が返されます。 |
| [Name](../../aspose.svg.dom/attr/name/) { get; } | この属性の名前を返します。 |
| override [NamespaceURI](../../aspose.svg.dom/attr/namespaceuri/) { get; } | このノードの名前空間 URI、または未指定の場合は null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 指定されたノードの直後にある、親の [`ChildNodes`](../node/childnodes/) 内のノードを返します。指定ノードが親要素の最後の子である場合は null を返します。 |
| override [NodeName](../../aspose.svg.dom/attr/nodename/) { get; } | このノードの名前（タイプに応じて）。 |
| override [NodeType](../../aspose.svg.dom/attr/nodetype/) { get; } | 基になるオブジェクトのタイプを表すコード。 |
| override [NodeValue](../../aspose.svg.dom/attr/nodevalue/) { get; set; } | このノードの値（タイプに応じて）。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [OwnerElement](../../aspose.svg.dom/attr/ownerelement/) { get; } | この属性が付属している Element ノード、または属性が使用されていない場合は null。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | DOM ツリー内で指定されたノードの親を返します。 |
| override [Prefix](../../aspose.svg.dom/attr/prefix/) { get; } | このノードの名前空間プレフィックス、または未指定の場合は null。null に設定されている場合、設定しても効果はありません。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 指定されたノードの直前にある、親の [`ChildNodes`](../node/childnodes/) リスト内のノードを返します。指定ノードがリストの最初の場合は null を返します。 |
| [Specified](../../aspose.svg.dom/attr/specified/) { get; } | インスタンスドキュメントでこの属性に明示的に値が設定されていれば true、そうでなければ false。 |
| override [TextContent](../../aspose.svg.dom/attr/textcontent/) { get; set; } | この属性はこのノードとその子孫のテキスト内容を返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードの子がすべて削除され、新しい文字列が空または null でない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |
| [Value](../../aspose.svg.dom/attr/value/) { get; set; } | 取得時には、属性の値が文字列として返されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | 指定された親ノードの子リストの末尾にノードを追加します。指定された子がドキュメント内の既存ノードへの参照である場合、[`AppendChild`](../node/appendchild/) はそのノードを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | このメソッドが呼び出されたノードの複製を返します。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | このメソッドが呼び出されたノードの複製を返します。そのパラメータはノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 指定された[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)にイベントをディスパッチし、（同期的に）影響を受けたEventListenersを適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズおよびオプションのバブリングフェーズを含む）も、[`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)で手動でディスパッチされたイベントに適用されます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | 既存の子ノード child の前にノードを挿入します。child が null の場合、子リストの末尾にノードを挿入します。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子がすでにツリーに存在する場合、まず削除されます。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | このメソッドは、指定された namespaceURI がデフォルトの名前空間かどうかをチェックします。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | 2つのノードが等しいかどうかをテストします。このメソッドはノードの等価性をテストし、同一性（つまり、2つのノードが同じオブジェクトへの参照であるか）ではありません。同一性は Node.isSameNode() でテストできます。同一のノードはすべて等しくなりますが、逆は必ずしも真ではありません。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | このメソッドは === 厳密等価演算子のレガシーエイリアスです。つまり、2つのノードが同一かどうか（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。このメソッドはデフォルトの名前空間宣言を無視します。詳細なアルゴリズムについては「Namespace Prefix Lookup」を参照してください。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | このノードの下にあるサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、テキストノード同士が構造（例：要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけで区切られる\"正規\"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これにより、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。Node.ownerDocument に付随する DOMConfiguration オブジェクトのパラメータ \"normalize-characters\" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | DOM から子ノードを削除し、削除されたノードを返します。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | 子ノード oldChild を newChild に置き換え、子リスト内で置換し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まずそれが削除されます。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | このインスタンスを表す String を返します。 |

### 参照

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
