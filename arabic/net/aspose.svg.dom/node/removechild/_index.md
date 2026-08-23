---
title: "Node.RemoveChild"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Node RemoveChild. تُزيل عقدة فرعية من DOM وتُرجع العقدة المُزالة."
type: docs
weight: 270
url: /ar/net/aspose.svg.dom/node/removechild/
---
## Node.RemoveChild method

يزيل عقدة فرعية من الـ DOM ويعيد العقدة التي تم إزالتها.

ملاحظة: طالما تم الاحتفاظ بإشارة إلى العنصر الفرعي المُزال، يظل موجودًا في الذاكرة، لكنه لم يعد جزءًا من DOM. يمكن إعادة استخدامه لاحقًا في الشيفرة. إذا لم يتم تخزين القيمة المرجعة من `RemoveChild`، ولم تُحفظ أي إشارة أخرى، فسيتم حذفها تلقائيًا من الذاكرة بعد وقت قصير.

```csharp
public Node RemoveChild(Node child)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| child | Node | `[`Node`](../)` هو العقدة الفرعية التي سيتم إزالتها من DOM. |

### قيمة الإرجاع

على عكس [`CloneNode`](../clonenode/)، القيمة المرجعة تحتفظ بكائنات [`EventListener`](../../../aspose.svg.dom.events/ieventlistener/) المرتبطة بها.

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
