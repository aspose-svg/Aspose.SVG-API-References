---
title: "Node.Normalize"
second_title: "Aspose.SVG for .NET API 参考"
description: "Node.Normalize 方法。将此节点下子树的全部深度中的所有 Text 节点（包括属性节点）转换为一种普通形式，在该形式中，仅保留结构，例如元素、注释、处理指令、CDATA 区段和实体引用，并将 Text 节点分离，即不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要使用依赖特定文档树结构的操作（如 XPointer 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 normalize-characters 为 true，则此方法还会完全规范化 Text 节点的字符。"
type: docs
weight: 260
url: /zh/net/aspose.svg.dom/node/normalize/
---
## Node.Normalize method

将此节点下子树的所有 Text 节点（包括属性节点）全部置于一种 "普通" 形式，即仅由结构（例如元素、注释、处理指令、CDATA 区段和实体引用）分隔 Text 节点，确保不存在相邻的 Text 节点或空的 Text 节点。此操作可用于确保文档的 DOM 视图与保存后重新加载时的视图相同，并在需要依赖特定文档树结构的操作（如 XPointer [XPointer] 查找）时非常有用。如果附加到 Node.ownerDocument 的 DOMConfiguration 对象的参数 "normalize-characters" 为 true，则此方法还会完全规范化 Text 节点的字符。

```csharp
public void Normalize()
```

### 另请参阅

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
