---
title: "Document クラス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Document クラス。Document は HTML、XML、または SVG ドキュメント全体を表します。概念的にはドキュメントツリーのルートであり、ドキュメントのデータへの主要なアクセスを提供します。"
type: docs
weight: 2810
url: /ja/net/aspose.svg.dom/document/
---
## Document class

Document は HTML、XML、または SVG ドキュメント全体を表します。概念的には、ドキュメントツリーのルートであり、ドキュメントのデータへの主要なアクセス手段を提供します。

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | このノードの絶対ベース URI、または実装が絶対 URI を取得できなかった場合は null です。 |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | ドキュメントのエンコーディングを取得します。 |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | ドキュメントのエンコーディングを取得します。 |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | 指定された要素の子ノードのライブ [`NodeList`](../../aspose.svg.collections/nodelist/) を返します。最初の子ノードはインデックス0が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [Children](../../aspose.svg.dom/document/children/) { get; } | 子要素を返します。 |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | ドキュメントのコンテンツタイプを取得します。 |
| [Context](../../aspose.svg.dom/document/context/) { get; } | 現在のブラウジング コンテキストを取得します。 |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | Document インターフェイスの defaultView IDL 属性は、取得時に、この Document に関連付けられた閲覧コンテキストがある場合はその閲覧コンテキストの WindowProxy オブジェクトを返し、そうでない場合は null を返さなければなりません。 |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | この文書に関連付けられた文書型宣言 (Document Type Declaration)。 |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | これは、文書のドキュメント要素である子ノードへ直接アクセスできる便利な属性です。 |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | 文書の位置、または未定義の場合や Document が DOMImplementation.createDocument を使用して作成された場合は null。 |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | ツリー内でノードの最初の子ノードを返します。子が存在しない場合は null を返します。 |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。子要素がない場合は null。 |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | この文書を処理する DOMImplementation オブジェクト。 |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | ドキュメントのエンコーディングを取得します。 |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | ノードの最後の子ノードを返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。子要素がない場合は null。 |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../node/element_node/) と [`ATTRIBUTE_NODE`](../node/attribute_node/) 以外のタイプのノードや、[`CreateElement`](./createelement/) のような DOM Level 1 メソッドで作成されたノードについては、常に null です。 |
| [Location](../../aspose.svg.dom/document/location/) { get; } | 文書の位置。 |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | 要素の名前空間 URI を返します。要素が名前空間に属さない場合は null を返します。 |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。文書ツリー内でこの要素の後に来る要素の兄弟ノードがない場合は null。 |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | 指定されたノードの直後にある、親の [`ChildNodes`](../node/childnodes/) 内のノードを返します。指定ノードが親要素の最後の子である場合は null を返します。 |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | このノードの名前（タイプに応じて）。 |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | 基になるオブジェクトのタイプを表すコード。 |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | 現在のノードの値を取得または設定します。 |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | 文書のオリジンを取得します。 |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | 所有者文書を取得します。 |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | DOM ツリー内で指定されたノードの親を返します。 |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | 指定された要素の名前空間プレフィックスを返します。プレフィックスが指定されていない場合は null を返します。 |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。文書ツリー内でこの要素の前に来る要素の兄弟ノードがない場合は null。 |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | 指定されたノードの直前にある、親の [`ChildNodes`](../node/childnodes/) リスト内のノードを返します。指定ノードがリストの最初の場合は null を返します。 |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | 文書の準備状態を返します。Document が読み込み中のときは "loading"、解析が完了しサブリソースの読み込みが続いているときは "interactive"、読み込みが完了したときは "complete"。 |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | エラーチェックを強制するかどうかを指定する属性です。false に設定された場合、実装は通常 DOM 操作で定義されるすべてのエラーケースをテストせず、DOM 操作で DOMException を発生させず、Document.normalizeDocument() 使用時にエラーを報告しない自由があります。エラーが発生した場合の動作は未定義です。この属性はデフォルトで true です。 |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | 文書に明示的にリンクまたは埋め込まれたすべてのスタイルシートを含むリストです。HTML 文書の場合、HTML LINK 要素で含まれる外部スタイルシートとインライン STYLE 要素が含まれます。 |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | ノードおよびその子孫のテキストコンテンツを表します。 |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | XML 宣言の一部として、この文書がスタンドアロンかどうかを指定する属性です。指定されていない場合は false になります。 |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | XML 宣言の一部として、この文書のバージョン番号を指定する属性です。宣言がなく、かつこの文書が "XML" 機能をサポートしている場合、値は "1.0" です。この文書が "XML" 機能をサポートしていない場合、値は常に null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | 指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | 指定された親ノードの子リストの末尾にノードを追加します。指定された子がドキュメント内の既存ノードへの参照である場合、[`AppendChild`](../node/appendchild/) はそのノードを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | このメソッドが呼び出されたノードの複製を返します。 |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | このメソッドが呼び出されたノードの複製を返します。そのパラメータはノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | このメソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [`Attr`](../attr/) クラスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | このメソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [`Attr`](../attr/) クラスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | 指定された文字列を値とする CDATASection ノードを作成します。 |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | 指定された文字列を内容とする Comment ノードを作成します。 |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | DOM ノードを追加してオフスクリーンの DOM ツリーを構築できる、新しい空の [`DocumentFragment`](../documentfragment/) を作成します。 |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | このメソッドは [`DocumentType`](../documenttype/) オブジェクトを返します。このオブジェクトは文書作成時に [`CreateDocument`](../idomimplementation/createdocument/) と共に使用することも、[`InsertBefore`](../node/insertbefore/) や [`ReplaceChild`](../node/replacechild/) などのメソッドで文書に挿入することもできます。 |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | localName で指定された HTML 要素を作成します。localName が認識されない場合は HTMLUnknownElement を作成します。 |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | 指定された修飾名と名前空間 URI の要素を作成します。 |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | EntityReference オブジェクトを作成します。さらに、参照されたエンティティが既知の場合、EntityReference ノードの子リストは対応する Entity ノードのものと同じにされます。 |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | 実装がサポートするタイプの [`Event`](../../aspose.svg.dom.events/event/) を作成します。 |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | Creates a parsed XPath expression with resolved namespaces. This is useful when an expression will be reused in an application since it makes it possible to compile the expression string into a more efficient internal form and preresolve all namespace prefixes which occur within the expression. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | 指定された名前とデータ文字列を使用して ProcessingInstruction ノードを作成します。 |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | 指定された文字列を使用して Text ノードを作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | 指定された[`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)にイベントをディスパッチし、（同期的に）影響を受けたEventListenersを適切な順序で呼び出します。通常のイベント処理規則（キャプチャフェーズおよびオプションのバブリングフェーズを含む）も、[`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/)で手動でディスパッチされたイベントに適用されます。 |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | アンマネージド リソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | Evaluates an XPath expression string and returns a result of the specified type if possible. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | このメソッドは、指定された文字列と一致する id プロパティを持つ要素を表す [`Element`](../element/) オブジェクトを返します。要素の ID は指定された場合は一意である必要があるため、特定の要素に素早くアクセスする便利な方法です。 |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | このメソッドは、指定されたすべてのクラス名を持つすべての子要素の配列に似たオブジェクトを返します。 |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | このメソッドは、指定されたタグ名を持つ要素の [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) を返します。 |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | 指定された名前空間に属し、指定されたタグ名を持つ要素のリストを返します。ルートノードを含む文書全体が検索されます。 |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの型を取得するために使用されます。 |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | 指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | 別のドキュメントからノードをこのドキュメントにインポートしますが、元のドキュメントのソースノードは変更または削除されません。このメソッドはソースノードの新しいコピーを作成します。 |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | 既存の子ノード child の前にノードを挿入します。child が null の場合、子リストの末尾にノードを挿入します。child が DocumentFragment オブジェクトの場合、そのすべての子が同じ順序で child の前に挿入されます。子がすでにツリーに存在する場合、まず削除されます。 |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | このメソッドは、指定された namespaceURI がデフォルトの名前空間かどうかをチェックします。 |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | 2つのノードが等しいかどうかをテストします。このメソッドはノードの等価性をテストし、同一性（つまり、2つのノードが同じオブジェクトへの参照であるか）ではありません。同一性は Node.isSameNode() でテストできます。同一のノードはすべて等しくなりますが、逆は必ずしも真ではありません。 |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | このメソッドは === 厳密等価演算子のレガシーエイリアスです。つまり、2つのノードが同一かどうか（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。このメソッドはデフォルトの名前空間宣言を無視します。詳細なアルゴリズムについては「Namespace Prefix Lookup」を参照してください。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | 指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | 指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスにロードし、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントのロードはストリームの現在位置から開始されます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | 指定されたリクエストオブジェクトに基づいてドキュメントを非同期にロードします。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスに非同期でロードします。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | 指定された Uniform Resource Locator (URL) からドキュメントを現在のインスタンスに非同期でロードします。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。 |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | 指定されたコンテンツからドキュメントをロードし、baseUri を使用して相対リソースを解決する処理を非同期で行います。 |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | このノードの下にあるサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、テキストノード同士が構造（例：要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけで区切られる\"正規\"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これにより、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。Node.ownerDocument に付随する DOMConfiguration オブジェクトのパラメータ \"normalize-characters\" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | セレクタに一致するドキュメント内の最初の Element を返します。 |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | セレクタに一致するドキュメント内のすべての Element の NodeList を返します。 |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | DOM から子ノードを削除し、削除されたノードを返します。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | このメソッドはイベントターゲットからイベントリスナーを削除することを可能にします。[`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) がイベント処理中に[`EventTarget`](../eventtarget/) から削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | このメソッドは、現在のドキュメントの内容を指定されたグラフィカルデバイスにレンダリングするために使用されます。 |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | 子ノード oldChild を newChild に置き換え、子リスト内で置換し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まずそれが削除されます。 |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | このインスタンスを表す String を返します。 |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | open() で開かれたドキュメントストリームにテキスト文字列を書き込みます。なお、この関数は必ずしも DTD に従って生成されるわけではなく、ドキュメントのコンテキストでは無効な結果になる可能性があります。 |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | open() で開かれたドキュメントストリームにテキスト文字列と改行文字を書き込みます。なお、この関数は必ずしも DTD に従って生成されるわけではなく、ドキュメントのコンテキストでは無効な結果になる可能性があります。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | OnAbort イベントのハンドラを取得または設定します。 |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | OnBlur イベントのハンドラを取得または設定します。 |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | OnCancel イベントのハンドラを取得または設定します。 |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | OnCanplay イベントのハンドラを取得または設定します。 |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | OnCanPlayThrough イベントのハンドラを取得または設定します。 |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | OnChange イベントのハンドラを取得または設定します。 |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | OnClick イベントのハンドラを取得または設定します。 |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | OnCueChange イベントのハンドラを取得または設定します。 |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | OnDblClick イベントのハンドラを取得または設定します。 |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | OnDurationChange イベントのハンドラを取得または設定します。 |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | OnEmptied イベントのハンドラを取得または設定します。 |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | OnEnded イベントのハンドラを取得または設定します。 |
| event [OnError](../../aspose.svg.dom/document/onerror/) | OnError イベントのハンドラを取得または設定します。 |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | OnFocus イベントのハンドラを取得または設定します。 |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | OnInput イベントのハンドラを取得または設定します。 |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | OnInvalid イベントのハンドラを取得または設定します。 |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | OnKeyDown イベントのハンドラを取得または設定します。 |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | OnKeyPress イベントのハンドラを取得または設定します。 |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | OnKeyUp イベントのハンドラを取得または設定します。 |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | OnLoad イベントのハンドラを取得または設定します。 |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | OnLoadedData イベントのハンドラを取得または設定します。 |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | OnLoadedMetadata イベントのハンドラを取得または設定します。 |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | OnLoadStart イベントのハンドラを取得または設定します。 |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | OnMouseDown イベントのハンドラを取得または設定します。 |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | OnMouseEnter イベントのハンドラを取得または設定します。 |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | OnMouseLeave イベントのハンドラを取得または設定します。 |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | OnMouseMove イベントのハンドラを取得または設定します。 |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | OnMouseOut イベントのハンドラを取得または設定します。 |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | OnMouseOver イベントのハンドラを取得または設定します。 |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | OnMouseUp イベントのハンドラを取得または設定します。 |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | OnMouseWheel イベントのハンドラを取得または設定します。 |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | OnPause イベントのハンドラを取得または設定します。 |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | OnPlay イベントのハンドラを取得または設定します。 |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | OnPlaying イベントのハンドラを取得または設定します。 |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | OnProgress イベントのハンドラを取得または設定します。 |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | OnRateChange イベントのハンドラを取得または設定します。 |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | OnReadyStateChange イベントのハンドラを取得または設定します。 |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | OnReset イベントのハンドラを取得または設定します。 |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | OnResize イベントのハンドラを取得または設定します。 |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | OnScroll イベントのハンドラを取得または設定します。 |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | OnSeeked イベントのハンドラを取得または設定します。 |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | OnSeeking イベントのハンドラを取得または設定します。 |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | OnSelect イベントのハンドラを取得または設定します。 |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | OnShow イベントのハンドラを取得または設定します。 |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | OnStalled イベントのハンドラを取得または設定します。 |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | OnSubmit イベントのハンドラを取得または設定します。 |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | OnSuspend イベントのハンドラを取得または設定します。 |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | OnTimeUpdate イベントのハンドラを取得または設定します。 |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | OnToggle イベントのハンドラを取得または設定します。 |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | OnVolumeChange イベントのハンドラを取得または設定します。 |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | OnWaiting イベントのハンドラを取得または設定します。 |

### 参照

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
