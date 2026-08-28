---
title: "Aspose.Svg.Dom.Traversal"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal 名前空間には、要素間をナビゲートし、ノードとその子を文書順に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。"
type: docs
weight: 120
url: /ja/net/aspose.svg.dom.traversal/
---
**Aspose.Svg.Dom.Traversal** 名前空間には、要素間をナビゲートし、ドキュメント順でノードとその子を走査するイテレータやツリーワーカーを作成するメソッドが含まれています。

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal には、ノードとその子を文書順（深さ優先・先行順走査、つまり文書のテキスト表現における開始タグの出現順と同等）に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトによって実装されます。 |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal インターフェイスは、著者が文書内の要素間を簡単に移動できるようにする読み取り専用属性の集合です。Element Traversal の準拠実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装しなければなりません。 |
| [INodeFilter](./inodefilter/) | フィルタはノードを「除外」する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードを受け入れると判断すれば、走査ロジックはそのノードを返します。そうでなければ、走査は次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。 |
| [INodeIterator](./inodeiterator/) | イテレータはノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が管理する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順走査用の単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal .createNodeIterator() を呼び出すことで作成されます。 |
| [ITraversal](./itraversal/) | イテレータはノードの集合を順に処理するために使用されます。例えば NodeList のノード集合、特定の Node が管理する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は文書順走査用の単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal .createNodeIterator() を呼び出すことで作成されます。 |
| [ITreeWalker](./itreewalker/) | TreeWalker オブジェクトは、whatToShow フラグとフィルタ（存在する場合）で定義された文書のビューを使用して、文書ツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。 |
