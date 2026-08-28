---
title: "Element.ToggleAttribute"
second_title: ".NET 用 Aspose.SVG API リファレンス"
description: "Element ToggleAttribute メソッド。force が指定されていない場合、qualifiedName をトグルし、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。"
type: docs
weight: 440
url: /ja/net/aspose.svg.dom/element/toggleattribute/
---
## ToggleAttribute(*string*) {#toggleattribute}

force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。

```csharp
public bool ToggleAttribute(string qualifiedName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | String | 属性 QualifiedName。 |

### 戻り値

qualifiedName が現在存在すれば true を返し、そうでなければ false を返します。

### 参照

* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## ToggleAttribute(*string, bool*) {#toggleattribute_1}

force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。

```csharp
public bool ToggleAttribute(string qualifiedName, bool force)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| qualifiedName | String | 属性 QualifiedName。 |
| force | Boolean | 属性をトグルするための force オプション。 |

### 戻り値

qualifiedName が現在存在すれば true を返し、そうでなければ false を返します。

### 参照

* class [Element](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
