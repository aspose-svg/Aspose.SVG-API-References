---
title: "SVGGElement クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.SVGGElement クラス。SVGGElement インターフェイスは g 要素に対応します。"
type: docs
weight: 5330
url: /ja/net/aspose.svg/svggelement/
---
## SVGGElement class

SVGGElement インターフェイスは ‘g’ 要素に対応します。

```csharp
public class SVGGElement : SVGGraphicsElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Attributes](../../aspose.svg.dom/element/attributes/) { get; } | このノードの属性を含む NamedNodeMap（ノードが Element の場合）または、それ以外の場合は null を返します。 |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | ノードを含むドキュメントの絶対ベース URL を返します。 |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 指定された要素の子ノードのライブ [`NodeList`](../../aspose.svg.collections/nodelist/) を返します。最初の子ノードはインデックス0が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [Children](../../aspose.svg.dom/element/children/) { get; } | 現在の要素の子要素を返します。 |
| [ClassList](../../aspose.svg.dom/element/classlist/) { get; } | 「class」属性の解析から得られたトークンを含むライブ DOMTokenList を返します。 |
| [ClassName](../../aspose.svg/svgelement/classname/) { get; } | 指定された要素の属性 ‘class’ に対応します。 |
| [ClassName](../../aspose.svg.dom/element/classname/) { get; set; } | 要素の class 属性。この属性は、多くの言語で公開されている "class" キーワードとの競合のため名前が変更されました。HTML 4.01 の class 属性の定義を参照してください。 |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement/) { get; } | 最も遠い祖先の ‘svg’ 要素。現在の要素が最上位の svg 要素である場合は Null です。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | ツリー内でノードの最初の子ノードを返します。子が存在しない場合は null を返します。 |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。子要素がない場合は null。 |
| [Id](../../aspose.svg/svgelement/id/) { get; set; } | 指定された要素の ‘id’ 属性の値、または ‘id’ が存在しない場合は空文字列です。 |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml/) { get; set; } | 要素の内容を表す HTML または XML のフラグメントを返します。設定可能で、指定された文字列から解析されたノードで要素の内容を置き換えることができます。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | ノードの最後の子ノードを返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。子要素がない場合は null。 |
| override [LocalName](../../aspose.svg.dom/element/localname/) { get; } | このノードの修飾名のローカル部分を返します。ELEMENT_NODE と ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードの場合、常に null が返されます。 |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri/) { get; } | このノードの名前空間 URI、または未指定の場合は null。 |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement/) { get; } | 現在のビューポートを確立した要素。通常は最も近い祖先の ‘svg’ 要素です。現在の要素が最上位の svg 要素である場合は Null です。 |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。文書ツリー内でこの要素の後に来る要素の兄弟ノードがない場合は null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 指定されたノードの直後にある、親の [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) 内のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| override [NodeName](../../aspose.svg.dom/element/nodename/) { get; } | このノードの名前（タイプに応じて）。 |
| override [NodeType](../../aspose.svg.dom/element/nodetype/) { get; } | 基になるオブジェクトのタイプを表すコード。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 現在のノードの値を取得または設定します。 |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml/) { get; set; } | 要素とその内容を表す HTML または XML のフラグメントを返します。設定可能で、指定された文字列から解析されたノードで要素自体を置き換えることができます。 |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement/) { get; } | 最も近い先祖の ‘svg’ 要素。対象の要素が最外層の svg 要素である場合は null です。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | DOM ノードの親である [`Element`](../../aspose.svg.dom/element/) を返します。ノードに親がない場合、または親が DOM Element でない場合は null を返します。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | DOM ツリー内で指定されたノードの親を返します。 |
| override [Prefix](../../aspose.svg.dom/element/prefix/) { get; } | このノードの名前空間プレフィックス、または未指定の場合は null。null に設定されている場合、設定しても効果はありません。 |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。文書ツリー内でこの要素の前に来る要素の兄弟ノードがない場合は null。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 指定されたノードの直前にある、親の [`ChildNodes`](../../aspose.svg.dom/node/childnodes/) リスト内のノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions/) { get; } | 指定された要素の属性 ‘requiredExtensions’ に対応します。 |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures/) { get; } | 指定された要素の属性 ‘requiredFeatures’ に対応します。 |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot/) { get; } | この要素に格納されている shadowRoot を返します。閉じている場合は null を返します。 |
| [Style](../../aspose.svg/svgelement/style/) { get; } | 指定された要素の属性 ‘style’ に対応します。ユーザーエージェントが CSS によるスタイリングをサポートしていない場合、この属性は常に null の値を持たなければなりません。 |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage/) { get; } | 指定された要素の属性 ‘systemLanguage’ に対応します。 |
| [TagName](../../aspose.svg.dom/element/tagname/) { get; } | 要素の名前。 |
| override [TextContent](../../aspose.svg.dom/element/textcontent/) { get; set; } | この属性はこのノードとその子孫のテキスト内容を返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードの子がすべて削除され、新しい文字列が空または null でない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |
| [Transform](../../aspose.svg/svggraphicselement/transform/) { get; } | 指定された要素の属性 ‘transform’ に対応します。 |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement/) { get; } | 現在のビューポートを確立した要素。多くの場合、最も近い先祖の ‘svg’ 要素です。対象の要素が最外層の svg 要素である場合は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | 指定された親ノードの子ノードリストの末尾にノードを追加します。指定された子がドキュメント内の既存ノードへの参照である場合、[`AppendChild`](../../aspose.svg.dom/node/appendchild/) はそのノードを現在の位置から新しい位置へ移動させます（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow/)(*[ShadowRootMode](../../aspose.svg.dom/shadowrootmode/)*) | shadow root を作成し、現在の要素にアタッチします。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | このメソッドが呼び出されたノードの複製を返します。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | このメソッドが呼び出されたノードの複製を返します。そのパラメータはノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 指定された[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)にイベントをディスパッチし、（同期的に）影響を受けたEventListenersを適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズおよびオプションのバブリングフェーズを含む）も、[`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)で手動でディスパッチされたイベントに適用されます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetAttribute](../../aspose.svg.dom/element/getattribute/)(*string*) | 名前で属性値を取得します。 |
| [GetAttributeNames](../../aspose.svg.dom/element/getattributenames/)() | 要素の属性名を文字列の配列として返します。要素に属性がない場合は空の配列を返します。 |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode/)(*string*) | 名前で属性ノードを取得します。 |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens/)(*string, string*) | ローカル名と名前空間 URI で Attr ノードを取得します。 |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens/)(*string, string*) | ローカル名と名前空間 URI によって属性値を取得します。 |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox/)() | すべての含まれるグラフィック要素のジオメトリに対し、現在のユーザー空間（つまり、存在する場合は ‘transform’ 属性が適用された後）でのタイトなバウンディングボックスを返します（ストローク、クリッピング、マスク、フィルター効果は除外）。なお、要素がまだ描画されていない場合でも、メソッドが呼び出された時点の実際のバウンディングボックスを getBBox が返す必要があります。 |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm/)() | 現在のユーザー単位（つまり、存在する場合は ‘transform’ 属性が適用された後）から nearestViewportElement のビューポート座標系への変換行列を返します。 |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname/)(*string*) | 引数で指定されたすべてのクラスを持つ、[`element`](../../aspose.svg.dom/element/) 内のすべての要素を含む [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) オブジェクトを返します。 |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname/)(*string*) | 指定されたタグ名を持つすべての[`elements`](../../aspose.svg.dom/element/) を含む[`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) オブジェクトを、文書順で返します。 |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens/)(*string, string*) | 指定されたローカル名と名前空間URI文字列を持つすべての[`elements`](../../aspose.svg.dom/element/) を含む[`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) オブジェクトを、文書順で返します。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm/)() | 現在のユーザー単位（つまり、存在する場合は ‘transform’ 属性が適用された後）から親ユーザーエージェントの「pixel」の概念への変換行列を返します。表示デバイスの場合、理想的には物理的な画面ピクセルを表します。物理的なピクセルサイズが不明な他のデバイスや環境では、CSS2 の「pixel」定義に類似したアルゴリズムを使用できます。要素がドキュメントツリーに接続されていない場合は null が返されます。このメソッドは本来 getClientCTM と名付ける方が適切ですが、歴史的理由により getScreenCTM という名前が維持されています。 |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute/)(*string*) | この要素に指定された名前の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens/)(*string, string*) | この要素に指定されたローカル名と名前空間 URI の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [HasAttributes](../../aspose.svg.dom/element/hasattributes/)() | このノード（要素の場合）が属性を持っているかどうかを返します |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 指定された[`Node`](../../aspose.svg.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 既存の子ノード child の前にノードを挿入します。child が null の場合、子リストの末尾にノードを挿入します。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子がすでにツリーに存在する場合、まず削除されます。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | このメソッドは、指定された namespaceURI がデフォルトの名前空間かどうかをチェックします。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | 2つのノードが等しいかどうかをテストします。このメソッドはノードの等価性をテストし、同一性（つまり、2つのノードが同じオブジェクトへの参照であるか）ではありません。同一性は Node.isSameNode() でテストできます。同一のノードはすべて等しくなりますが、逆は必ずしも真ではありません。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | このメソッドは === 厳密等価演算子のレガシーエイリアスです。つまり、2つのノードが同一かどうか（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。このメソッドはデフォルトの名前空間宣言を無視します。詳細なアルゴリズムについては「Namespace Prefix Lookup」を参照してください。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | このノードの下にあるサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、テキストノード同士が構造（例：要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけで区切られる\"正規\"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これにより、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。Node.ownerDocument に付随する DOMConfiguration オブジェクトのパラメータ \"normalize-characters\" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [QuerySelector](../../aspose.svg.dom/element/queryselector/)(*string*) | セレクタに一致するドキュメント内の最初の Element を返します。 |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall/)(*string*) | セレクタに一致するドキュメント内のすべての Element の NodeList を返します。 |
| [Remove](../../aspose.svg.dom/element/remove/)() | このインスタンスを削除します。 |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute/)(*string*) | 名前で属性を削除します。 |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | 指定された属性ノードを削除します。 |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens/)(*string, string*) | ローカル名と名前空間 URI で属性を削除します。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | DOM から子ノードを削除し、削除されたノードを返します。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/)がイベントを処理中に[`EventTarget`](../../aspose.svg.dom/eventtarget/)から削除された場合、現在のアクションによってトリガーされることはありません。イベントリスナーは削除された後は決して呼び出されません。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | 子ノード oldChild を newChild に置き換え、子リスト内で置換し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まずそれが削除されます。 |
| [SetAttribute](../../aspose.svg.dom/element/setattribute/)(*string, string*) | 新しい属性を追加します。要素に同名の属性が既に存在する場合、その値は value パラメータの値に変更されます |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode/)(*[Attr](../../aspose.svg.dom/attr/)*) | 新しい属性ノードを追加します。要素に同名（nodeName）の属性が既に存在する場合、新しい属性で置き換えられます。 |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens/)(*[Attr](../../aspose.svg.dom/attr/)*) | 新しい属性を追加します。要素に同じローカル名と名前空間 URI の属性が既に存在する場合、新しい属性で置き換えられます。 |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens/)(*string, string, string*) | 新しい属性を追加します。要素に同じローカル名と名前空間 URI の属性が既に存在する場合、そのプレフィックスは qualifiedName のプレフィックス部分に変更され、値は value パラメータの値に変更されます。 |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string*) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [ToggleAttribute](../../aspose.svg.dom/element/toggleattribute/)(*string, bool*) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | このインスタンスを表す String を返します。 |

### 参照

* class [SVGGraphicsElement](../svggraphicselement/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
