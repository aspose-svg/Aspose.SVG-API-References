---
title: "فئة CharacterData"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.CharacterData. تُوسِّع CharacterData الفئة Node بمجموعة من السمات والطرق للوصول إلى بيانات الأحرف في DOM."
type: docs
weight: 2450
url: /ar/net/aspose.svg.dom/characterdata/
---
## CharacterData class

واجهة CharacterData تمتد من Node وتوفر مجموعة من السمات والطرق للوصول إلى بيانات الأحرف في الـ DOM.

```csharp
public abstract class CharacterData : Node
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | تُعيد [`NodeList`](../../aspose.svg.collections/nodelist/) حيًا لعقد الأطفال للعنصر المحدد حيث يُعطى أول عقدة طفل الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| virtual [Data](../../aspose.svg.dom/characterdata/data/) { get; set; } | بيانات الأحرف للعقدة التي تنفّذ هذه الواجهة. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم تكن للعقدة أي أطفال. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [Length](../../aspose.svg.dom/characterdata/length/) { get; } | عدد الوحدات ذات 16 بت المتاحة عبر الخاصية data وطريقة substringData أدناه. قد تكون قيمتها صفرًا، أي أن عقد CharacterData قد تكون فارغة. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | يعيد الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../node/element_node/) و[`ATTRIBUTE_NODE`](../node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة من مستوى DOM 1، مثل [`CreateElement`](../document/createelement/)، يكون دائمًا null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | يعيد URI مساحة الاسم للعنصر، أو null إذا لم يكن العنصر في مساحة اسم. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | يعيد العقدة التي تلي المحددة مباشرةً في عنصر الأب الخاص بهما [`ChildNodes`](../node/childnodes/)، أو يعيد null إذا كانت العقدة المحددة هي آخر طفل في عنصر الأب. |
| abstract [NodeName](../../aspose.svg.dom/node/nodename/) { get; } | يرجع اسم العقدة الحالية كسلسلة. |
| abstract [NodeType](../../aspose.svg.dom/node/nodetype/) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | يعيد أو يضبط قيمة العقدة الحالية. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | يعيد كائن المستند الأعلى المستوى للعقدة. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | يعيد العنصر الأب لعقدة DOM [`Element`](../element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | يعيد أب العقدة المحددة في شجرة DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | يعيد بادئة مساحة الاسم للعنصر المحدد، أو null إذا لم يتم تحديد بادئة. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | يعيد العقدة التي تسبق المحددة مباشرةً في قائمة [`ChildNodes`](../node/childnodes/) لعنصر الأب، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | يمثل محتوى النص للعقدة وتفرعاتها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | يضيف عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة في المستند، فإن [`AppendChild`](../node/appendchild/) ينقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| virtual [AppendData](../../aspose.svg.dom/characterdata/appenddata/)(*string*) | أضف السلسلة إلى نهاية بيانات الأحرف للعقدة. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضاً أم لا. |
| virtual [DeleteData](../../aspose.svg.dom/characterdata/deletedata/)(*int, int*) | أزل نطاقًا من الوحدات ذات 16 بت من العقدة. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | يبثّ حدثًا إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُبث يدويًا باستخدام [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | يعيد قيمة منطقية تشير إلى ما إذا كانت الـ[`Node`](../node/) المعطاة تحتوي على عقد أطفال أم لا. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | يدرج العقدة قبل عقدة الطفل الموجودة child. إذا كان child null، يُدرج العقدة في نهاية قائمة الأطفال. إذا كان child كائن DocumentFragment، تُدرج جميع أطفاله، بنفس الترتيب، قبل child. إذا كان الطفل موجوداً بالفعل في الشجرة، يُزال أولاً. |
| virtual [InsertData](../../aspose.svg.dom/characterdata/insertdata/)(*int, string*) | أدرج سلسلة عند الإزاحة المحددة بوحدات 16 بت. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | تتحقق هذه الطريقة مما إذا كان الـnamespaceURI المحدد هو مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | يفحص ما إذا كان العقدان متساويتين. تختبر هذه الطريقة مساواة العقد، وليس تماثلهما (أي ما إذا كانت العقدان إشارة إلى نفس الكائن) والذي يمكن اختباره باستخدام Node.isSameNode(). جميع العقد المتطابقة ستكون متساوية أيضاً، رغم أن العكس قد لا يكون صحيحاً. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | الطريقة هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كان العقدان نفسهما (بمعنى آخر، ما إذا كانا يشيران إلى نفس الكائن). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | ابحث عن URI مساحة الاسم المرتبط بالبادئة المعطاة، بدءاً من هذه العقدة. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | ابحث عن البادئة المرتبطة بـ URI مساحة الاسم المعطى، بدءاً من هذه العقدة. تتجاهل هذه الطريقة إعلانات مساحة الاسم الافتراضية. راجع Namespace Prefix Lookup للحصول على تفاصيل حول الخوارزمية المستخدمة في هذه الطريقة. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | يضع جميع عقد النص في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في صيغة "عادية" حيث يفصل الهيكل فقط (مثل العناصر، التعليقات، تعليمات المعالجة، أقسام CDATA، وإشارات الكيانات) بين عقد النص، أي لا توجد عقد نص متجاورة ولا عقد نص فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل "normalize-characters" لكائن DOMConfiguration المرتبط بـ Node.ownerDocument صحيحاً، فإن هذه الطريقة ستقوم أيضاً بتطبيع أحرف عقد النص بالكامل. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | يزيل عقدة فرعية من الـ DOM ويعيد العقدة التي تم إزالتها. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويعيد عقدة oldChild. إذا كان newChild كائنًا من نوع DocumentFragment، يتم استبدال oldChild بجميع أطفال DocumentFragment، التي تُدرج بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| virtual [ReplaceData](../../aspose.svg.dom/characterdata/replacedata/)(*int, int, string*) | استبدل الأحرف التي تبدأ عند الإزاحة المحددة بوحدات 16 بت بالسلسلة المحددة. |
| virtual [SubstringData](../../aspose.svg.dom/characterdata/substringdata/)(*int, int*) | يستخرج نطاقًا من البيانات من العقدة. |
| override [ToString](../../aspose.svg.dom/characterdata/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

### انظر أيضًا

* class [Node](../node/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
