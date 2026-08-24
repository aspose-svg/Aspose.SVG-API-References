---
title: "ISVGAnimatedPathData 接口"
second_title: "Aspose.SVG for .NET API 参考"
description: "Aspose.Svg.Paths.ISVGAnimatedPathData 接口。该 SVGAnimatedPathData 接口支持具有 d 属性（保存 SVG 路径数据）的元素，并支持对该属性进行动画化的功能"
type: docs
weight: 4550
url: /zh/net/aspose.svg.paths/isvganimatedpathdata/
---
## ISVGAnimatedPathData interface

该 SVGAnimatedPathData 接口支持具有 ‘d’ 属性的元素，该属性保存 SVG 路径数据，并支持对该属性进行动画化的能力。

```csharp
public interface ISVGAnimatedPathData
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnimatedPathSegList](../../aspose.svg.paths/isvganimatedpathdata/animatedpathseglist/) { get; } | 提供对 ‘d’ 属性当前动画内容的访问，形式与 SVG 语法一一对应。如果给定的属性或属性正在被动画化，则包含该属性或属性的当前动画值，并且对象本身及其内容均为只读。如果给定的属性或属性当前未被动画化，则其值与 pathSegList 相同。 |
| [PathSegList](../../aspose.svg.paths/isvganimatedpathdata/pathseglist/) { get; } | 提供对 ‘d’ 属性基础（即静态）内容的访问，形式与 SVG 语法一一对应。因此，如果 ‘d’ 属性包含一个"absolute moveto (M)"和一个"absolute arcto (A)"命令，则 pathSegList 将包含两个条目：SVG_PATHSEG_MOVETO_ABS 和 SVG_PATHSEG_ARC_ABS。 |

### 另请参阅

* namespace [Aspose.Svg.Paths](../../aspose.svg.paths/)
* assembly [Aspose.SVG](../../)
