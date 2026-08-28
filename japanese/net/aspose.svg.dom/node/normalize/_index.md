---
title: "Node.Normalize"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Node Normalize メソッド。このノード以下のサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、構造（要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけが Text ノードを分離する正規形に変換します。つまり、隣接した Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証し、特定のドキュメントツリー構造に依存する XPointer ルックアップなどの操作に有用です。Node.ownerDocument に添付された DOMConfiguration オブジェクトのパラメータ normalize-characters が true の場合、このメソッドは Text ノードの文字も完全に正規化します。"
type: docs
weight: 260
url: /ja/net/aspose.svg.dom/node/normalize/
---
## Node.Normalize method

このノードの下にあるサブツリー全体の深さにあるすべての Text ノード（属性ノードを含む）を、テキストノード同士が構造（例：要素、コメント、処理命令、CDATA セクション、エンティティ参照）だけで区切られる\"正規\"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これにより、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。Node.ownerDocument に付随する DOMConfiguration オブジェクトのパラメータ \"normalize-characters\" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。

```csharp
public void Normalize()
```

### 参照

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
