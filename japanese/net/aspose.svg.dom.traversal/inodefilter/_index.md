---
title: "INodeFilter インターフェイス"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Aspose.Svg.Dom.Traversal.INodeFilter インターフェイス。フィルタはノードを除外する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードを受け入れると、トラバーサルロジックはそのノードを返します。そうでなければ、トラバーサルは次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。"
type: docs
weight: 3240
url: /ja/net/aspose.svg.dom.traversal/inodefilter/
---
## INodeFilter interface

フィルタはノードを「除外」する方法を知っているオブジェクトです。NodeIterator または TreeWalker に NodeFilter が与えられた場合、次のノードを返す前にフィルタを適用します。フィルタがノードを受け入れると判断すれば、走査ロジックはそのノードを返します。そうでなければ、走査は次のノードを探し、拒否されたノードが存在しなかったかのように振る舞います。

DOM はフィルタを提供しません。NodeFilter は、ユーザーが独自のフィルタを実装できるインターフェイスにすぎません。

NodeFilter はノード間の走査方法や、走査対象のデータ構造について知る必要はありません。これにより、フィルタの作成が非常に簡単になります。なぜなら、フィルタが行う唯一のことは単一ノードを評価することだからです。1 つのフィルタはさまざまな種類の走査で使用でき、コードの再利用を促進します。

また、[Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) も参照してください。@since DOM Level 2

```csharp
public interface INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AcceptNode](../../aspose.svg.dom.traversal/inodefilter/acceptnode/)(*[Node](../../aspose.svg.dom/node/)*) | 指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。） |

### 参照

* namespace [Aspose.Svg.Dom.Traversal](../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../)
