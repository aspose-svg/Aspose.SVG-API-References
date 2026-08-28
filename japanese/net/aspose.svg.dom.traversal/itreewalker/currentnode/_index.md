---
title: "ITreeWalker.CurrentNode"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "ITreeWalker CurrentNode プロパティ。TreeWalker が現在位置しているノードです。DOM ツリーの変更により、現在のノードが TreeWalker の関連フィルタで受け入れられなくなることがあります。currentNode は、ルートノードで指定されたサブツリー内にあるかどうか、またはフィルタや whatToShow フラグで受け入れられるかに関係なく、任意のノードに明示的に設定することもできます。さらに、要求された方向にフィルタを適用してトラバーサルが不可能な場合でも、currentNode は変更されません"
type: docs
weight: 10
url: /ja/net/aspose.svg.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker が現在位置しているノードです。DOM ツリーの変更により、現在のノードが TreeWalker に関連付けられたフィルタによってもはや受け入れられなくなることがあります。currentNode は、ルートノードで指定されたサブツリー内にあるかどうか、またはフィルタや whatToShow フラグで受け入れられるかどうかに関係なく、任意のノードに明示的に設定することもできます。さらに、currentNode が現在のビューの一部でなくても、要求された方向のフィルタを適用して走査が続行されます。走査が不可能な場合、currentNode は変更されません。

```csharp
public Node CurrentNode { get; set; }
```

### Property Value

現在のノード。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | NOT_SUPPORTED_ERR: currentNode を null に設定しようとした場合に発生します。 |

### 参照

* class [Node](../../../aspose.svg.dom/node/)
* interface [ITreeWalker](../)
* namespace [Aspose.Svg.Dom.Traversal](../../../aspose.svg.dom.traversal/)
* assembly [Aspose.SVG](../../../)
