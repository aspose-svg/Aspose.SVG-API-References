---
title: "Event.PreventDefault"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Event PreventDefault. إذا كان الحدث قابلًا للإلغاء تُستخدم طريقة PreventDefault للدلالة على أن الحدث سيُلغى مما يعني أن أي إجراء افتراضي عادةً ما تتخذه التنفيذ نتيجةً للحدث لن يحدث"
type: docs
weight: 120
url: /ar/net/aspose.svg.dom.events/event/preventdefault/
---
## Event.PreventDefault method

إذا كان الحدث قابلًا للإلغاء، تُستخدم طريقة `PreventDefault` للدلالة على أن الحدث سيُلغى، مما يعني أن أي إجراء افتراضي عادةً ما تتخذه التنفيذ نتيجةً للحدث لن يحدث.

```csharp
public void PreventDefault()
```

## ملاحظات

إذا تم استدعاء طريقة `PreventDefault` في أي مرحلة من تدفق الحدث، يُلغى الحدث. أي إجراء افتراضي مرتبط بالحدث لن يحدث. استدعاء هذه الطريقة لحدث غير قابل للإلغاء لا يؤثر. بمجرد استدعاء `PreventDefault` ستظل سارية طوال ما تبقى من انتشار الحدث. يمكن استخدام هذه الطريقة في أي مرحلة من تدفق الحدث.

### انظر أيضًا

* class [Event](../)
* namespace [Aspose.Svg.Dom.Events](../../../aspose.svg.dom.events/)
* assembly [Aspose.SVG](../../../)
