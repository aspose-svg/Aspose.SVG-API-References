---
title: "Aspose.Svg.Dom"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom Document Object Model 名前空間は、任意の HTML、XML、または SVG ドキュメントを表現し操作する API を提供します。DOM はブラウザで読み込まれるドキュメントモデルで、ドキュメントをノードツリーとして表現し、各ノードは要素、テキスト文字列、コメントなどドキュメントの一部を表します。"
type: docs
weight: 70
url: /ja/net/aspose.svg.dom/
---
**Aspose.Svg.Dom (Document Object Model)** 名前空間は、任意の HTML、XML、または SVG ドキュメントを表現し、操作する API を提供します。DOM はブラウザで読み込まれるドキュメントモデルで、ドキュメントをノードツリーとして表現し、各ノードはドキュメントの一部（例：要素、テキスト文字列、コメント）を表します。

## クラス

| クラス | 説明 |
| --- | --- |
| [Attr](./attr/) | Attr インターフェイスは Element オブジェクト内の属性を表します。通常、その属性の許容値はドキュメントに関連付けられたスキーマで定義されます。 |
| [CDATASection](./cdatasection/) | CDATA セクションは、マークアップと見なされる可能性のある文字を含むテキストブロックをエスケープするために使用されます。 |
| [CharacterData](./characterdata/) | CharacterData は Node を拡張し、DOM の文字データにアクセスするための属性とメソッドのセットを提供します。 |
| [Comment](./comment/) | CharacterData から継承し、コメントの内容、すなわち開始 '' と終了 '' の間のすべての文字を表します。 |
| [Document](./document/) | Document は HTML、XML、または SVG ドキュメント全体を表します。概念的には、ドキュメントツリーのルートであり、ドキュメントのデータへの主要なアクセス手段を提供します。 |
| [DocumentFragment](./documentfragment/) | DocumentFragment は「軽量」または「最小」な Document オブジェクトです。ドキュメントのツリーの一部を抽出したり、新しいフラグメントを作成したりしたいというケースは非常に一般的です。 |
| [DocumentType](./documenttype/) | DocumentType は、ドキュメントに定義されたエンティティの一覧へのインターフェイスを提供します。 |
| [DOMException](./domexception/) | DOMException インターフェイスは、Web API のメソッド呼び出しやプロパティへのアクセスに起因して発生する異常事象（例外と呼ばれる）を表します。これは、Web API におけるエラー状態の記述方法そのものです。 |
| [DOMObject](./domobject/) | DOMObject 型は、Document Object Model 全体の基底オブジェクトを表すために使用されます。Java および ECMAScript では、DOMObject は Object 型にバインドされています。 |
| [Element](./element/) | Element インターフェイスは、HTML または XML ドキュメント内の要素を表します。 |
| [Entity](./entity/) | XML ドキュメント内の、解析済みまたは未解析の既知エンティティを表します。 |
| [EntityReference](./entityreference/) | EntityReference ノードは、ツリー内のエンティティ参照を表すために使用できます。 |
| [EventTarget](./eventtarget/) | DOM イベントモデルをサポートする実装において、すべてのノードは [`EventTarget`](../aspose.svg.dom/eventtarget/) インターフェイスを実装しています。そのため、このインターフェイスは Node インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用することで取得できます。このインターフェイスは [`EventTarget`](../aspose.svg.dom/eventtarget/) 上でイベントリスナーの登録と削除を行い、[`IEventTarget`](../aspose.svg.dom.events/ieventtarget/) へイベントをディスパッチすることを可能にします。 |
| [Node](./node/) | Node インターフェイスは、Document Object Model 全体の主要なデータ型であり、ドキュメントツリー内の単一ノードを表します。 |
| [Notation](./notation/) | DTD で宣言された表記（notation）を表します。 |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction は「処理指示」を表し、XML ではドキュメントテキスト内にプロセッサ固有の情報を保持する手段として使用されます。 |
| [QualifiedName](./qualifiedname/) | HTML の修飾名（qualified name）を表します。 |
| [ShadowRoot](./shadowroot/) | ShadowRoot はシャドウツリーのルートノードです。 |
| [Text](./text/) | Text インターフェイスは CharacterData を継承し、Element または Attr のテキストコンテンツ（XML では文字データと呼ばれる）を表します。 |
| [TypeInfo](./typeinfo/) | TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | 閲覧コンテキストは、[`Document`](../aspose.svg.dom/document/) オブジェクトがユーザーに提示される環境です。 |
| [IChildNode](./ichildnode/) | 親を持つことができる [`Node`](../aspose.svg.dom/node/) が実装すべき [`IChildNode`](../aspose.svg.dom/ichildnode/) インターフェイスを定義します。 |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation インターフェイスは、特定の Document Object Model インスタンスに依存しない操作を実行するための多数のメソッドを提供します。 |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | システムイベントハンドリングをサポートするすべての要素が継承しなければならないインターフェイスを表します。 |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | [`IChildNode`](../aspose.svg.dom/ichildnode/) で、[`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node/) ではないものを定義します。 |
| [INonElementParentNode](./inonelementparentnode/) | [`IParentNode`](../aspose.svg.dom/iparentnode/) で、Element 型ではないものを定義します。 |
| [IParentNode](./iparentnode/) | 任意の可能な親が実装する [`IParentNode`](../aspose.svg.dom/iparentnode/) インターフェイスを定義します。 |
| [IStorage](./istorage/) | Web Storage API のこのインターフェイスは、特定のドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様をご覧ください: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot が動作できるモード。 |
