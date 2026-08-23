---
title: "IWindow.Opener"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "خاصية IWindow Opener. يجب أن تُعيد سمة opener في تعريف IDL لكائن Window عند القراءة كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه إذا كان موجودًا ولا يزال متاحًا ولم يتخلّص سياق التصفح الحالي من مُفتاحه، وإلا يجب أن تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي أن يتخلّص من مُفتاحه؛ إذا كانت القيمة الجديدة أي شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية DefineOwnProperty لكائن Window مع تمرير اسم الخاصية opener كمفتاح الخاصية ووصف الخاصية Property Descriptor Value value Writable true Enumerable true Configurable true كـ وصف الخاصية حيث value هي القيمة الجديدة."
type: docs
weight: 60
url: /ar/net/aspose.svg.window/iwindow/opener/
---
## IWindow.Opener property

يجب أن تُعيد خاصية opener في كائن Window، عند القراءة، كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق التصفح المفتوح)، إذا كان موجودًا ولا يزال متاحًا، ولم يتخلى سياق التصفح الحالي عن المفتاح؛ وإلا تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي التخلي عن المفتاح؛ وإذا كانت القيمة شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية [[DefineOwnProperty]] لكائن Window، مع تمرير اسم الخاصية \"opener\" كمفتاح الخاصية، ووصف الخاصية { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } حيث value هي القيمة الجديدة.

```csharp
public IWindow Opener { get; }
```

### Property Value

المفتاح.

### انظر أيضًا

* interface [IWindow](../)
* namespace [Aspose.Svg.Window](../../../aspose.svg.window/)
* assembly [Aspose.SVG](../../../)
