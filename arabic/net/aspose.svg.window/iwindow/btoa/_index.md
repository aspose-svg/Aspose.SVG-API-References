---
title: "IWindow.Btoa"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IWindow Btoa. تأخذ البيانات المدخلة على شكل سلسلة Unicode تحتوي فقط على أحرف في النطاق U0000 إلى U00FF، كل حرف يمثل بايت ثنائي بقيمة 0x00 إلى 0xFF على التوالي، وتحوّلها إلى تمثيل base64 وتُعيده."
type: docs
weight: 130
url: /ar/net/aspose.svg.window/iwindow/btoa/
---
## IWindow.Btoa method

يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي فقط على الأحرف في النطاق U+0000 إلى U+00FF، كل منها يمثل بايت ثنائي بقيم 0x00 إلى 0xFF على التوالي، ويحولها إلى تمثيل base64، والذي يُرجعه.

```csharp
public string Btoa(string data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | String | سلسلة Unicode التي تحتوي فقط على أحرف في النطاق U+0000 إلى U+00FF. |

### قيمة الإرجاع

سلسلة base64.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | ترمي استثناء DOMException من النوع \"InvalidCharacterError\" إذا احتوت السلسلة المدخلة أي أحرف خارج النطاق. |

### انظر أيضًا

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
