---
title: "SVGGraphicsElement.GetScreenCTM"
second_title: "Aspose.SVG for .NET API 参考"
description: "SVGGraphicsElement GetScreenCTM 方法。返回从当前用户单位（即在对 transform 属性（如果有）应用后）到父级用户代理感知的像素的变换矩阵。对于显示设备，这理想情况下代表物理屏幕像素。对于物理像素大小未知的其他设备或环境，则可以使用类似 CSS2 像素定义的算法。请注意，如果该元素未挂入文档树，则返回 null。该方法本可以更恰当地命名为 getClientCTM，但出于历史原因仍保留为 getScreenCTM。"
type: docs
weight: 90
url: /zh/net/aspose.svg/svggraphicselement/getscreenctm/
---
## SVGGraphicsElement.GetScreenCTM method

返回从当前用户单位（即在应用了 ‘transform’ 属性后，如果有的话）到父用户代理所感知的 \"像素\" 的变换矩阵。对于显示设备，这理想情况下代表物理屏幕像素。对于其他设备或物理像素大小未知的环境，可以使用类似 CSS2 对 \"像素\" 定义的算法。若该元素未挂载到文档树中，则返回 null。该方法本可以更恰当地命名为 getClientCTM，但出于历史原因仍保留为 getScreenCTM。

```csharp
public SVGMatrix GetScreenCTM()
```

### 返回值

一个定义给定变换矩阵的 SVGMatrix 对象。

### 另请参阅

* class [SVGMatrix](../../../aspose.svg.datatypes/svgmatrix/)
* class [SVGGraphicsElement](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
