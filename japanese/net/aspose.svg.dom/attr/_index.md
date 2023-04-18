---
title: Class Attr
second_title: Aspose.SVG for .NET API リファレンス
description: Aspose.Svg.Dom.Attr クラス. Attr インターフェイスはElement オブジェクトの属性を表します通常属性の許容値はドキュメントに関連付けられたスキーマで定義されます.
type: docs
weight: 350
url: /ja/net/aspose.svg.dom/attr/
---
## Attr class

Attr インターフェイスは、Element オブジェクトの属性を表します。通常、属性の許容値は、ドキュメントに関連付けられたスキーマで定義されます.

```csharp
public sealed class Attr : Node
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes/) { get; } | このノードの属性を含む NamedNodeMap (要素の場合)、またはそれ以外の場合は null. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | このノードの絶対ベース URI、または実装が絶対 URI を取得できなかった場合は null。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | このノードのすべての子を含む NodeList。子がない場合、これはノードを含まない NodeList です.. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | このノードの最初の子。そのようなノードがない場合、これは null. を返します。 |
| [IsId](../../aspose.svg.dom/attr/isid/) { get; } | この属性が ID 型 (つまり、所有者要素の識別子を含む) であることがわかっているかどうかを返します。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | このノードの最後の子。そのようなノードがない場合、これは null. を返します。 |
| override [LocalName](../../aspose.svg.dom/attr/localname/) { get; } | このノードの修飾名のローカル部分を返します。 ELEMENT_NODE および ATTRIBUTE_NODE 以外のタイプのノード、および Document.createElement() などの DOM レベル 1 メソッドで作成されたノードの場合、これは常に null です。 |
| [Name](../../aspose.svg.dom/attr/name/) { get; } | この属性の名前を返します。 |
| override [NamespaceURI](../../aspose.svg.dom/attr/namespaceuri/) { get; } | このノードの名前空間 URI、または指定されていない場合は null. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | このノードの直後のノード。そのようなノードがない場合、これは null. を返します。 |
| override [NodeName](../../aspose.svg.dom/attr/nodename/) { get; } | タイプに応じたこのノードの名前. |
| override [NodeType](../../aspose.svg.dom/attr/nodetype/) { get; } | 基礎となるオブジェクトのタイプを表すコード. |
| override [NodeValue](../../aspose.svg.dom/attr/nodevalue/) { get; set; } | タイプに応じたこのノードの値. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | このノードに関連付けられたドキュメント オブジェクト。これは、新しいノードを作成するために使用される Document オブジェクトでもあります。このノードがドキュメントまたはドキュメントでまだ使用されていない DocumentType である場合、これは null. です。 |
| [OwnerElement](../../aspose.svg.dom/attr/ownerelement/) { get; } | このアトリビュートがアタッチされている Element ノード、またはこのアトリビュートが使用されていない場合は null。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | 親を取得します[`Element`](../element/)このノードの. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | このノードの親。 Attr、Document、DocumentFragment、Entity、および Notation を除くすべてのノードは、親を持つことができます。ただし、ノードが作成されたばかりでまだツリーに追加されていない場合、またはツリーから削除されている場合、これは null. です。 |
| override [Prefix](../../aspose.svg.dom/attr/prefix/) { get; } | このノードの名前空間プレフィックス、または指定されていない場合は null。 null と定義されている場合、設定しても効果はありません |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | このノードの直前のノード。そのようなノードがない場合、これは null. を返します。 |
| [SchemaTypeInfo](../../aspose.svg.dom/attr/schematypeinfo/) { get; } | この属性に関連付けられたタイプ情報。 |
| [Specified](../../aspose.svg.dom/attr/specified/) { get; } | この属性がインスタンス ドキュメントで明示的に値を与えられた場合は true、それ以外の場合は false. |
| override [TextContent](../../aspose.svg.dom/attr/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキスト コンテンツを返します。 null として定義されている場合、設定しても効果はありません。設定時に、このノードが持つ可能性のある子はすべて削除され、新しい文字列が空または null でない場合は、この属性が設定されている文字列を含む単一の Text ノードに置き換えられます。 |
| [Value](../../aspose.svg.dom/attr/value/) { get; set; } | 取得時に、属性の値が文字列として返されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(Node) | ノード newChild をこのノードの子のリストの最後に追加します。 newChild がすでにツリーにある場合は、最初に削除されます. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(bool) | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(Event) | このメソッドにより、イベントを実装イベント モデルにディスパッチできます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージ リソースの解放、解放、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes/)() | このノード (エレメントの場合) が属性を持つかどうかを返します |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | このノードに子があるかどうかを返します. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(Node, Node) | 既存の子ノード child の前にノードを挿入します。 child が null の場合、child のリストの最後に node を挿入します。 child が DocumentFragment オブジェクトの場合、すべての子が同じ順序で child の前に挿入されます。子がすでにツリーにある場合は、最初に削除されます. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(string) | このメソッドは、指定された namespaceURI がデフォルトの名前空間であるかどうかをチェックします。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(Node) | 2 つのノードが等しいかどうかをテストします。 このメソッドは、Node.isSameNode() でテストできる同一性 (つまり、2 つのノードが同じオブジェクトへの参照であるかどうか) ではなく、ノードの等しいかどうかをテストします。逆は真ではないかもしれませんが、同じであるすべてのノードも等しくなります. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(Node) | このノードが指定されたノードと同じかどうかを返します。 このメソッドは、実装によって返された 2 つの Node 参照が同じオブジェクトを参照しているかどうかを判断する方法を提供します。 2 つの Node 参照が同じオブジェクトへの参照である場合、たとえプロキシ経由であっても、すべての属性が同じ値を持ち、いずれかの参照で同じ DOM メソッドを呼び出すと、常にまったく同じ効果が得られるように、参照を完全に交換可能に使用できます. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(string) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(string) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。デフォルトの名前空間宣言は、このメソッドによって無視されます。 このメソッドで使用されるアルゴリズムの詳細については、ネームスペース プレフィックス ルックアップを参照してください。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | 属性ノードを含む、このノードの下のサブツリーの深さ全体にあるすべてのテキスト ノードを、構造 (要素、コメント、処理命令、CDATA セクション、およびエンティティ参照など) のみがテキストを分離する「通常の」形式にします。つまり、隣接する Text ノードも空の Text ノードもありません。これは、ドキュメントの DOM ビューが、保存されて再ロードされた場合と同じであることを保証するために使用でき、特定のドキュメント ツリー構造に依存する操作 (XPointer [XPointer] ルックアップなど) が必要な場合に役立ちます。利用される。 Node.ownerDocument に添付された DOMConfiguration オブジェクトのパラメーター「normalize-characters」が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(Node) | oldChild で示される子ノードを子のリストから削除し、それを返します。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)から削除されます[`EventTarget`](../eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)から削除されます[`EventTarget`](../eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)から削除されます[`EventTarget`](../eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(Node, Node) | 子のリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。 newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子に置き換えられ、同じ順序で挿入されます。 newChild がすでにツリーにある場合は、最初に削除されます. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | を返しますStringこのインスタンスを表す. |

### 関連項目

* class [Node](../node/)
* 名前空間 [Aspose.Svg.Dom](../../aspose.svg.dom/)
* 組み立て [Aspose.SVG](../../)


