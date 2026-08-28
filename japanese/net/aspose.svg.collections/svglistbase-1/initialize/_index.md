---
title: "SVGListBase-1.Initialize"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "SVGListBase Initialize メソッド。リスト内の既存のすべての項目をクリアし、パラメータで指定された単一の項目を保持するようにリストを再初期化します。"
type: docs
weight: 80
url: /ja/net/aspose.svg.collections/svglistbase-1/initialize/
---
## SVGListBase<T>.Initialize method

リストから既存のすべての項目をクリアし、パラメータで指定された単一の項目を保持するようにリストを再初期化します。

```csharp
public T Initialize(T newItem)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| newItem | T | リストの唯一のメンバーになるべき項目です。 |

### 戻り値

リストに挿入される項目です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | コード [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.svg.dom/domexception/no_modification_allowed_err/)。リストを変更できないときに発生します。 |

### 参照

* class [SVGListBase&lt;T&gt;](../)
* namespace [Aspose.Svg.Collections](../../../aspose.svg.collections/)
* assembly [Aspose.SVG](../../../)
