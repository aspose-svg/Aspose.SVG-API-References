---
title: "فئة SVGElementInstance"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "الفئة Aspose.Svg.SVGElementInstance. الكائن الجذر لكل شجرة ظل للعنصر use-element ينفذ الواجهة SVGUseElementShadowRoot. هذه الواجهة لا تعرف حالياً أي امتدادات للخصائص والطرق المعرفة في واجهة ShadowRoot ومزيج DocumentOrShadowRoot. ومع ذلك، الشجرة المتجذرة في هذه العقدة هي للقراءة فقط تماماً من منظور نصوص المؤلف."
type: docs
weight: 5280
url: /ar/net/aspose.svg/svgelementinstance/
---
## SVGElementInstance class

الكائن الجذري لكل شجرة ظل عنصر use يُطبق واجهة SVGUseElementShadowRoot. لا تُعرّف هذه الواجهة حاليًا أي امتدادات للخصائص والطرق المعرفة لواجهة ShadowRoot وخلط DocumentOrShadowRoot. ومع ذلك، الشجرة المتجذرة في هذه العقدة هي للقراءة فقط من منظور سكريبتات المؤلف.

```csharp
public class SVGElementInstance : ShadowRoot
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri/) { get; } | تُعيد عنوان URL الأساسي المطلق للمستند الذي يحتوي على العقدة. |
| [ChildElementCount](../../aspose.svg.dom/documentfragment/childelementcount/) { get; } | يعيد العدد الحالي لعقد العناصر التي هي أبناء هذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | تُعيد [`NodeList`](../../aspose.svg.collections/nodelist/) حيًا لعقد الأطفال للعنصر المحدد حيث يُعطى أول عقدة طفل الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [Children](../../aspose.svg.dom/documentfragment/children/) { get; } | يعيد العناصر الفرعية للعنصر الحالي. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم تكن للعقدة أي أطفال. |
| [FirstElementChild](../../aspose.svg.dom/documentfragment/firstelementchild/) { get; } | يعيد أول عقدة عنصر فرعي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [Host](../../aspose.svg.dom/shadowroot/host/) { get; } | المضيف هو عنصر يحتوي على هذا ShadowRoot. |
| [InnerHTML](../../aspose.svg.dom/documentfragment/innerhtml/) { get; set; } | يعيد جزءًا من HTML أو XML يمثل محتويات العنصر. يمكن تعيينه لاستبدال محتويات العنصر بالعقد التي تم تحليلها من السلسلة المعطاة. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [LastElementChild](../../aspose.svg.dom/documentfragment/lastelementchild/) { get; } | يعيد عقدة العنصر الطفل الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | يرجع الجزء المحلي من الاسم المؤهل لهذا العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../../aspose.svg.dom/node/element_node/) و[`ATTRIBUTE_NODE`](../../aspose.svg.dom/node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة من مستوى DOM 1، مثل [`CreateElement`](../../aspose.svg.dom/document/createelement/)، تكون دائمًا null. |
| [Mode](../../aspose.svg.dom/shadowroot/mode/) { get; } | الوضع الذي يعمل به هذا ShadowRoot. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | يعيد URI مساحة الاسم للعنصر، أو null إذا لم يكن العنصر في مساحة اسم. |
| [NextElementSibling](../../aspose.svg.dom/documentfragment/nextelementsibling/) { get; } | يعيد عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | يرجع العقدة التي تلي المحددة مباشرةً في `ChildNodes` الخاصة بوالدها [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)، أو يرجع null إذا كانت العقدة المحددة هي الطفل الأخير في العنصر الأب. |
| override [NodeName](../../aspose.svg.dom/documentfragment/nodename/) { get; } | اسم هذه العقدة، حسب نوعها. |
| override [NodeType](../../aspose.svg.dom/documentfragment/nodetype/) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | يعيد أو يضبط قيمة العقدة الحالية. |
| [OuterHTML](../../aspose.svg.dom/documentfragment/outerhtml/) { get; set; } | يعيد جزءًا من HTML أو XML يمثل العنصر ومحتوياته. يمكن تعيينه لاستبدال العنصر بالعقد التي تم تحليلها من السلسلة المعطاة. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument/) { get; } | يعيد كائن المستند الأعلى المستوى للعقدة. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | يرجع العنصر الأب لعقدة DOM [`Element`](../../aspose.svg.dom/element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | يعيد أب العقدة المحددة في شجرة DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | يعيد بادئة مساحة الاسم للعنصر المحدد، أو null إذا لم يتم تحديد بادئة. |
| [PreviousElementSibling](../../aspose.svg.dom/documentfragment/previouselementsibling/) { get; } | يعيد عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | يرجع العقدة التي تسبق المحددة مباشرةً في قائمة `ChildNodes` الخاصة بوالدها [`ChildNodes`](../../aspose.svg.dom/node/childnodes/)، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| override [TextContent](../../aspose.svg.dom/documentfragment/textcontent/) { get; set; } | هذه السمة تُعيد محتوى النص لهذه العقدة ونسلها. عندما تُعرّف بأنها null، لا يؤثر ضبطها. عند الضبط، تُزال جميع الأطفال المحتملين لهذه العقدة، وإذا لم تكن السلسلة الجديدة فارغة أو null، تُستبدل بعقدة نص واحدة تحتوي على السلسلة التي تم ضبط السمة إليها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../../aspose.svg.dom/node/)*) | يضيف عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة في المستند، فإن [`AppendChild`](../../aspose.svg.dom/node/appendchild/) ينقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضاً أم لا. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | يبثّ حدثًا إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُبث يدويًا باستخدام [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | يرجع قيمة منطقية تشير إلى ما إذا كانت الـ[`Node`](../../aspose.svg.dom/node/) المعطاة تحتوي على عقد أطفال أم لا. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | يدرج العقدة قبل عقدة الطفل الموجودة child. إذا كان child null، يُدرج العقدة في نهاية قائمة الأطفال. إذا كان child كائن DocumentFragment، تُدرج جميع أطفاله، بنفس الترتيب، قبل child. إذا كان الطفل موجوداً بالفعل في الشجرة، يُزال أولاً. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | تتحقق هذه الطريقة مما إذا كان الـnamespaceURI المحدد هو مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../../aspose.svg.dom/node/)*) | يفحص ما إذا كان العقدان متساويتين. تختبر هذه الطريقة مساواة العقد، وليس تماثلهما (أي ما إذا كانت العقدان إشارة إلى نفس الكائن) والذي يمكن اختباره باستخدام Node.isSameNode(). جميع العقد المتطابقة ستكون متساوية أيضاً، رغم أن العكس قد لا يكون صحيحاً. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../../aspose.svg.dom/node/)*) | الطريقة هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كان العقدان نفسهما (بمعنى آخر، ما إذا كانا يشيران إلى نفس الكائن). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | ابحث عن URI مساحة الاسم المرتبط بالبادئة المعطاة، بدءاً من هذه العقدة. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | ابحث عن البادئة المرتبطة بـ URI مساحة الاسم المعطى، بدءاً من هذه العقدة. تتجاهل هذه الطريقة إعلانات مساحة الاسم الافتراضية. راجع Namespace Prefix Lookup للحصول على تفاصيل حول الخوارزمية المستخدمة في هذه الطريقة. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | يضع جميع عقد النص في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في صيغة "عادية" حيث يفصل الهيكل فقط (مثل العناصر، التعليقات، تعليمات المعالجة، أقسام CDATA، وإشارات الكيانات) بين عقد النص، أي لا توجد عقد نص متجاورة ولا عقد نص فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل "normalize-characters" لكائن DOMConfiguration المرتبط بـ Node.ownerDocument صحيحاً، فإن هذه الطريقة ستقوم أيضاً بتطبيع أحرف عقد النص بالكامل. |
| [QuerySelector](../../aspose.svg.dom/documentfragment/queryselector/)(*string*) | تُرجع أول Element في المستند الذي يطابق المحدد. |
| [QuerySelectorAll](../../aspose.svg.dom/documentfragment/queryselectorall/)(*string*) | تُرجع NodeList لجميع Elements في المستند التي تطابق المحدد. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../../aspose.svg.dom/node/)*) | يزيل عقدة فرعية من الـ DOM ويعيد العقدة التي تم إزالتها. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | تتيح هذه الطريقة إزالة مستمعي الأحداث من هدف الحدث. إذا تمت إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../../aspose.svg.dom/eventtarget/) أثناء معالجته لحدث، فلن يتم تفعيله بواسطة الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتهم. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../../aspose.svg.dom/node/), [Node](../../aspose.svg.dom/node/)*) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويعيد عقدة oldChild. إذا كان newChild كائنًا من نوع DocumentFragment، يتم استبدال oldChild بجميع أطفال DocumentFragment، التي تُدرج بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |

### انظر أيضًا

* class [ShadowRoot](../../aspose.svg.dom/shadowroot/)
* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
