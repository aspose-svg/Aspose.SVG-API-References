---
title: "IWindow.Atob"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة IWindow Atob. تأخذ البيانات المدخلة على شكل سلسلة Unicode تحتوي على بيانات ثنائية مُشفّرة بـ base64، تفكّ شفرتها وتُعيد سلسلة تتكون من أحرف في النطاق U0000 إلى U00FF، كل حرف يمثل بايت ثنائي بقيمة 0x00 إلى 0xFF على التوالي وفقًا لتلك البيانات الثنائية."
type: docs
weight: 120
url: /ar/net/aspose.svg.window/iwindow/atob/
---
## IWindow.Atob method

يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مشفرة بقاعدة64، يفك تشفيرها، ويعيد سلسلة تتكون من أحرف في النطاق U+0000 إلى U+00FF، كل منها يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، المقابلة لتلك البيانات الثنائية.

```csharp
public string Atob(string data)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | String | سلسلة Unicode التي تحتوي على بيانات ثنائية مُشفّرة بـ base64. |

### قيمة الإرجاع

السلسلة التي تتكون من أحرف في النطاق U+0000 إلى U+00FF.

### استثناءات

| استثناء | شرط |
| --- | --- |
| [DOMException](../../../aspose.svg.dom/domexception/) | ترمي استثناء DOMException من النوع \"InvalidCharacterError\" إذا لم تكن السلسلة المدخلة بيانات base64 صالحة. |

### انظر أيضًا

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
