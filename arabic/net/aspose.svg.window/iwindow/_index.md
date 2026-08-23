---
title: "واجهة IWindow"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "واجهة Aspose.Svg.Window.IWindow. يمثل كائن النافذة نافذة تحتوي على مستند DOM"
type: docs
weight: 5920
url: /ar/net/aspose.svg.window/iwindow/
---
## IWindow interface

كائن النافذة يمثل نافذة تحتوي على مستند DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | يجب أن تُعيد خاصية document كائن Document الأحدث لكائن Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | كائن frameElement الخاص بمستند. |
| [LocalStorage](../../aspose.svg.window/iwindow/localstorage/) { get; } | يعيد كائن Storage يتيح لك حفظ أزواج المفتاح/القيمة في وكيل المستخدم. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | يجب أن تُعيد خاصية location في واجهة Window كائن Location الخاص بوثيقة كائن Window ذلك. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | يجب أن تُعيد خاصية name لكائن Window، عند القراءة، الاسم الحالي لسياق التصفح، وعند الكتابة، تعيين اسم سياق التصفح إلى القيمة الجديدة. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | يجب أن تُعيد خاصية opener في كائن Window، عند القراءة، كائن WindowProxy لسياق التصفح الذي تم إنشاء سياق التصفح الحالي منه (سياق التصفح المفتوح)، إذا كان موجودًا ولا يزال متاحًا، ولم يتخلى سياق التصفح الحالي عن المفتاح؛ وإلا تُعيد null. عند الكتابة، إذا كانت القيمة الجديدة null يجب على سياق التصفح الحالي التخلي عن المفتاح؛ وإذا كانت القيمة شيء آخر يجب على وكيل المستخدم استدعاء الطريقة الداخلية [[DefineOwnProperty]] لكائن Window، مع تمرير اسم الخاصية \"opener\" كمفتاح الخاصية، ووصف الخاصية { [[Value]]: value, [[Writable]]: true, [[Enumerable]]: true, [[Configurable]]: true } حيث value هي القيمة الجديدة. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | يجب أن تُعيد خاصية parent في كائن Window الخاص بمستند في سياق تصفح b كائن WindowProxy لسياق التصفح الأب، إذا كان موجودًا (أي إذا كان b سياق تصفح فرعي)، أو كائن WindowProxy لسياق التصفح b نفسه، وإلا (أي إذا كان سياق تصفحًا أعلى مستوى أو سياقًا متداخلًا منفصلًا). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | يعيد كائن WindowProxy لسياق تصفح كائن Window. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | يجب أن تُعيد خاصية top في كائن Window الخاص بمستند في سياق تصفح b كائن WindowProxy لسياق التصفح الأعلى مستوى (والذي سيكون كائن WindowProxy الخاص به إذا كان سياق تصفحًا أعلى مستوى)، إذا كان لديه واحد، أو كائن WindowProxy الخاص به وإلا (مثلًا إذا كان سياقًا متداخلًا منفصلًا). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | يعيد كائن WindowProxy لسياق تصفح كائن Window. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(*string*) | يعرض تنبيهًا مودالي مع الرسالة المعطاة، وينتظر من المستخدم إغلاقه. |
| [Atob](../../aspose.svg.window/iwindow/atob/)(*string*) | يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي على بيانات ثنائية مشفرة بقاعدة64، يفك تشفيرها، ويعيد سلسلة تتكون من أحرف في النطاق U+0000 إلى U+00FF، كل منها يمثل بايتًا ثنائيًا بقيم 0x00 إلى 0xFF على التوالي، المقابلة لتلك البيانات الثنائية. |
| [Btoa](../../aspose.svg.window/iwindow/btoa/)(*string*) | يأخذ بيانات الإدخال على شكل سلسلة Unicode تحتوي فقط على الأحرف في النطاق U+0000 إلى U+00FF، كل منها يمثل بايت ثنائي بقيم 0x00 إلى 0xFF على التوالي، ويحولها إلى تمثيل base64، والذي يُرجعه. |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(*string*) | يعرض نافذة منبثقة نمطية OK/Cancel مع الرسالة المعطاة، ينتظر المستخدم لإغلاقها، ويُرجع true إذا نقر المستخدم على OK وfalse إذا نقر على Cancel. |
| [MatchMedia](../../aspose.svg.window/iwindow/matchmedia/)(*string*) | يرجع كائن MediaQueryList جديد يمكن استخدامه بعد ذلك لتحديد ما إذا كان المستند يطابق سلسلة استعلام الوسائط، وكذلك لمراقبة المستند لاكتشاف متى يطابق (أو يتوقف عن المطابقة) ذلك الاستعلام. راجع مواصفة CSSOM View Module: [https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface](https://www.w3.org/TR/cssom-view/#extensions-to-the-window-interface) |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(*string, string*) | يعرض نافذة منبثقة حقل نصي نمطية مع الرسالة المعطاة، ينتظر المستخدم لإغلاقها، ويُرجع القيمة التي أدخلها المستخدم. إذا ألغى المستخدم النافذة، يُرجع null بدلاً من ذلك. إذا كان الوسيط الثاني موجودًا، تُستخدم القيمة المعطاة كقيمة افتراضية. |

### انظر أيضًا

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* namespace [Aspose.Svg.Window](../../aspose.svg.window/)
* assembly [Aspose.SVG](../../)
