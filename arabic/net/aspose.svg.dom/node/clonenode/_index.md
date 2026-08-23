---
title: "Node.CloneNode"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Node CloneNode. تُعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها"
type: docs
weight: 180
url: /ar/net/aspose.svg.dom/node/clonenode/
---
## CloneNode() {#clonenode}

يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها.

إن نسخ عقدة ينسخ جميع سماتها وقيمها، بما في ذلك المستمعين الأصليين (المضمنين). لا ينسخ مستمعي الأحداث المضافين باستخدام [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) أو تلك المعينة لخصائص العنصر (مثال: node.onclick = someFunction). بالإضافة إلى ذلك، بالنسبة لعنصر HTMLCanvasElement، لا يتم نسخ الصورة المرسومة.

```csharp
public Node CloneNode()
```

### قيمة الإرجاع

العقدة الجديدة [`Node`](../) المستنسخة. العقدة المستنسخة لا تملك أبًا ولا تكون جزءًا من المستند، حتى يتم إضافتها إلى عقدة أخرى هي جزء من المستند، باستخدام [`AppendChild`](../appendchild/) أو طريقة مشابهة.

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## CloneNode(*bool*) {#clonenode_1}

يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضاً أم لا.

إن نسخ عقدة ينسخ جميع سماتها وقيمها، بما في ذلك المستمعين الأصليين (المضمنين). لا ينسخ مستمعي الأحداث المضافين باستخدام [`AddEventListener`](../../../aspose.svg.dom.events/ieventtarget/addeventlistener/) أو تلك المعينة لخصائص العنصر (مثال: node.onclick = someFunction). بالإضافة إلى ذلك، بالنسبة لعنصر HTMLCanvasElement، لا يتم نسخ الصورة المرسومة.

```csharp
public Node CloneNode(bool deep)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| deep | Boolean | إذا كان true، فإن العقدة وشجرتها الفرعية بالكامل، بما في ذلك النص الذي قد يكون في عقد الأطفال [`Text`](../../text/)، تُنسخ أيضًا. |

### قيمة الإرجاع

العقدة الجديدة [`Node`](../) المستنسخة. العقدة المستنسخة لا تملك أبًا ولا تكون جزءًا من المستند، حتى يتم إضافتها إلى عقدة أخرى هي جزء من المستند، باستخدام [`AppendChild`](../appendchild/) أو طريقة مشابهة.

### انظر أيضًا

* class [Node](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
