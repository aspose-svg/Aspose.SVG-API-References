---
title: "فئة Document"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "فئة Aspose.Svg.Dom.Document. يمثل المستند كامل مستند HTML أو XML أو SVG. من الناحية المفاهيمية هو جذر شجرة المستند ويوفر الوصول الأساسي إلى بيانات المستند."
type: docs
weight: 2810
url: /ar/net/aspose.svg.dom/document/
---
## Document class

واجهة Document تمثل المستند الكامل HTML أو XML أو SVG. مفهومياً، هي جذر شجرة المستند، وتوفر الوصول الأساسي إلى بيانات المستند.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [BaseURI](../../aspose.svg.dom/document/baseuri/) { get; } | المسار الأساسي المطلق لهذا العقدة أو null إذا لم يتمكن التنفيذ من الحصول على مسار مطلق. |
| [CharacterSet](../../aspose.svg.dom/document/characterset/) { get; } | يحصل على ترميز المستند. |
| [Charset](../../aspose.svg.dom/document/charset/) { get; } | يحصل على ترميز المستند. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount/) { get; } | يعيد العدد الحالي لعقد العناصر التي هي أبناء هذا العنصر. 0 إذا لم يكن لهذا العنصر أي عقدة فرعية من نوع nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes/) { get; } | تُعيد [`NodeList`](../../aspose.svg.collections/nodelist/) حيًا لعقد الأطفال للعنصر المحدد حيث يُعطى أول عقدة طفل الفهرس 0. تشمل عقد الأطفال العناصر والنصوص والتعليقات. |
| [Children](../../aspose.svg.dom/document/children/) { get; } | يعيد العناصر الفرعية. |
| [ContentType](../../aspose.svg.dom/document/contenttype/) { get; } | يحصل على نوع محتوى المستند. |
| [Context](../../aspose.svg.dom/document/context/) { get; } | يحصل على سياق التصفح الحالي. |
| [DefaultView](../../aspose.svg.dom/document/defaultview/) { get; } | خاصية defaultView IDL لواجهة Document، عند الحصول عليها، يجب أن تُعيد كائن WindowProxy لسياق تصفح هذا المستند، إذا كان لهذا المستند سياق تصفح مرتبط، أو null خلاف ذلك. |
| [Doctype](../../aspose.svg.dom/document/doctype/) { get; } | إعلان نوع المستند (Document Type Declaration) المرتبط بهذا المستند. |
| [DocumentElement](../../aspose.svg.dom/document/documentelement/) { get; } | هذه خاصية تسهيلية تسمح بالوصول المباشر إلى العقدة الفرعية التي هي عنصر المستند لهذا المستند. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi/) { get; } | موقع المستند أو null إذا كان غير معرف أو إذا تم إنشاء المستند باستخدام DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild/) { get; } | تُعيد أول طفل للعقدة في الشجرة، أو null إذا لم تكن للعقدة أي أطفال. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild/) { get; } | يعيد أول عقدة عنصر فرعي لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر فرعية. |
| [Implementation](../../aspose.svg.dom/document/implementation/) { get; } | كائن DOMImplementation الذي يتعامل مع هذا المستند. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding/) { get; } | يحصل على ترميز المستند. |
| [LastChild](../../aspose.svg.dom/node/lastchild/) { get; } | تُعيد آخر طفل للعقدة. إذا كان والدها عنصرًا، فإن الطفل يكون عادةً عقدة عنصر أو عقدة نص أو عقدة تعليق. تُعيد null إذا لم توجد عناصر طفل. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild/) { get; } | يعيد عقدة العنصر الطفل الأخير لهذا العنصر. null إذا لم يكن لهذا العنصر أي عناصر طفل. |
| virtual [LocalName](../../aspose.svg.dom/node/localname/) { get; } | يعيد الجزء المحلي من الاسم المؤهل لهذه العقدة. بالنسبة للعقد من أي نوع غير [`ELEMENT_NODE`](../node/element_node/) و[`ATTRIBUTE_NODE`](../node/attribute_node/) والعقد التي تم إنشاؤها باستخدام طريقة من مستوى DOM 1، مثل [`CreateElement`](./createelement/)، تكون القيمة دائمًا null. |
| [Location](../../aspose.svg.dom/document/location/) { get; } | موقع المستند. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri/) { get; } | يعيد URI مساحة الاسم للعنصر، أو null إذا لم يكن العنصر في مساحة اسم. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling/) { get; } | يعيد عقدة العنصر الشقيقة التالية لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي بعده في شجرة المستند. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling/) { get; } | يعيد العقدة التي تلي المحددة مباشرةً في عنصر الأب الخاص بهما [`ChildNodes`](../node/childnodes/)، أو يعيد null إذا كانت العقدة المحددة هي آخر طفل في عنصر الأب. |
| override [NodeName](../../aspose.svg.dom/document/nodename/) { get; } | اسم هذه العقدة، حسب نوعها. |
| override [NodeType](../../aspose.svg.dom/document/nodetype/) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue/) { get; set; } | يعيد أو يضبط قيمة العقدة الحالية. |
| [Origin](../../aspose.svg.dom/document/origin/) { get; } | يحصل على أصل المستند. |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument/) { get; } | يحصل على المستند المالِك. |
| [ParentElement](../../aspose.svg.dom/node/parentelement/) { get; } | يعيد العنصر الأب لعقدة DOM [`Element`](../element/)، أو null إذا لم يكن للعقدة أب، أو إذا كان أبها ليس عنصر DOM. |
| [ParentNode](../../aspose.svg.dom/node/parentnode/) { get; } | يعيد أب العقدة المحددة في شجرة DOM. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix/) { get; set; } | يعيد بادئة مساحة الاسم للعنصر المحدد، أو null إذا لم يتم تحديد بادئة. |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling/) { get; } | يعيد عقدة العنصر الشقيقة السابقة لهذا العنصر. null إذا لم يكن لهذا العنصر أي عقد شقيقة عنصر تأتي قبلها في شجرة المستند. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling/) { get; } | يعيد العقدة التي تسبق المحددة مباشرةً في قائمة [`ChildNodes`](../node/childnodes/) لعنصر الأب، أو null إذا كانت العقدة المحددة هي الأولى في تلك القائمة. |
| [ReadyState](../../aspose.svg.dom/document/readystate/) { get; } | يعيد حالة جاهزية المستند. "loading" أثناء تحميل المستند، "interactive" بمجرد انتهاء التحليل لكنه لا يزال يحمل الموارد الفرعية، و"complete" بمجرد أن يتم التحميل. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking/) { get; set; } | خاصية تحدد ما إذا كان فحص الأخطاء مفروضًا أم لا. عندما تُضبط على false، يكون التنفيذ حرًا في عدم اختبار كل حالة خطأ محتملة عادةً معرفة في عمليات DOM، وعدم رفع أي DOMException أثناء عمليات DOM أو الإبلاغ عن أخطاء أثناء استخدام Document.normalizeDocument(). في حالة حدوث خطأ، يكون السلوك غير معرف. هذه الخاصية true بشكل افتراضي. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets/) { get; } | قائمة تحتوي على جميع أوراق الأنماط المرتبطة صراحةً أو المدمجة في مستند. بالنسبة لمستندات HTML، تشمل ذلك أوراق الأنماط الخارجية، المضمنة عبر عنصر HTML LINK، وعناصر STYLE المضمنة. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent/) { get; set; } | يمثل محتوى النص للعقدة وتفرعاتها. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone/) { get; set; } | خاصية تحدد، كجزء من إعلان XML، ما إذا كان هذا المستند مستقلًا. تكون false عندما لا يتم تحديدها. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion/) { get; set; } | خاصية تحدد، كجزء من إعلان XML، رقم إصدار هذا المستند. إذا لم يكن هناك إعلان وإذا كان هذا المستند يدعم ميزة "XML"، تكون القيمة "1.0". إذا لم يدعم هذا المستند ميزة "XML"، تكون القيمة دائمًا null. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | يضبط دالة سيتم استدعاؤها كلما تم تسليم الحدث المحدد إلى الهدف. |
| [AppendChild](../../aspose.svg.dom/node/appendchild/)(*[Node](../node/)*) | يضيف عقدة إلى نهاية قائمة الأطفال لعقدة أب محددة. إذا كان الطفل المعطى إشارة إلى عقدة موجودة في المستند، فإن [`AppendChild`](../node/appendchild/) ينقلها من موقعها الحالي إلى الموقع الجديد (ليس هناك حاجة لإزالة العقدة من عقدة الأب قبل إلحاقها بعقدة أخرى). |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)() | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. |
| [CloneNode](../../aspose.svg.dom/node/clonenode/)(*bool*) | يعيد نسخة مكررة من العقدة التي تم استدعاء هذه الطريقة عليها. يتحكم معاملها فيما إذا كان الجزء الفرعي الموجود داخل العقدة يُستنسخ أيضاً أم لا. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute/)(*string*) | تنشئ هذه الطريقة عقدة صفة جديدة وتعيدها. الكائن المُنشأ هو عقدة تنفذ فئة [`Attr`](../attr/). لا يفرض DOM نوع الصفات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens/)(*string, string*) | تنشئ هذه الطريقة عقدة صفة جديدة وتعيدها. الكائن المُنشأ هو عقدة تنفذ فئة [`Attr`](../attr/). لا يفرض DOM نوع الصفات التي يمكن إضافتها إلى عنصر معين بهذه الطريقة. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection/)(*string*) | ينشئ عقدة CDATASection تكون قيمتها السلسلة المحددة. |
| [CreateComment](../../aspose.svg.dom/document/createcomment/)(*string*) | ينشئ عقدة Comment بناءً على السلسلة المحددة. |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment/)() | ينشئ [`DocumentFragment`](../documentfragment/) فارغًا جديدًا يمكن إضافة عقد DOM إليه لبناء شجرة DOM غير مرئية. |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype/)(*string, string, string, string*) | تُعيد الطريقة كائن [`DocumentType`](../documenttype/) يمكن إما استخدامه مع [`CreateDocument`](../idomimplementation/createdocument/) عند إنشاء المستند أو وضعه في المستند عبر طرق مثل [`InsertBefore`](../node/insertbefore/) أو [`ReplaceChild`](../node/replacechild/). |
| [CreateElement](../../aspose.svg.dom/document/createelement/)(*string*) | ينشئ عنصر HTML المحدد بـ localName، أو HTMLUnknownElement إذا لم يُعترف بـ localName. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns/)(*string, string*) | ينشئ عنصرًا بالاسم المؤهل المعطى وURI مساحة الاسم. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference/)(*string*) | ينشئ كائن EntityReference. بالإضافة إلى ذلك، إذا كان الكيان المشار إليه معروفًا، تُجعل قائمة الأطفال لعقدة EntityReference مماثلة لتلك الخاصة بعقدة Entity المقابلة. |
| [CreateEvent](../../aspose.svg.dom/document/createevent/)(*string*) | ينشئ [`Event`](../../aspose.svg.dom.events/event/) من نوع يدعمه التنفيذ. |
| [CreateExpression](../../aspose.svg.dom/document/createexpression/)(*string, [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/)*) | ينشئ تعبير XPath محلل مع مساحات أسماء محلولة. هذا مفيد عندما سيتم إعادة استخدام التعبير في تطبيق لأنه يجعل من الممكن تجميع سلسلة التعبير إلى شكل داخلي أكثر كفاءة وإعادة حل جميع مسافات أسماء البادئات التي تظهر داخل التعبير. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator)(*[Node](../node/)*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_1)(*[Node](../node/), long*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator/#createnodeiterator_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | إنشاء NodeIterator جديد على الشجرة الفرعية التي جذورها العقدة المحددة. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver/)(*[Node](../node/)*) | يتكيف مع أي عقدة DOM لحل مساحات الأسماء بحيث يمكن تقييم تعبير XPath بسهولة بالنسبة لسياق العقدة التي ظهرت فيها داخل المستند. يعمل هذا المحول مثل طريقة DOM Level 3 `lookupNamespaceURI` على العقد في حل namespaceURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في تسلسل العقدة الهرمي في الوقت الذي يتم فيه استدعاء lookupNamespaceURI، كما يحل بشكل صحيح البادئة الضمنية xml. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction/)(*string, string*) | ينشئ عقدة ProcessingInstruction بناءً على الاسم والسلاسل البيانات المحددة. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode/)(*string*) | ينشئ عقدة Text بناءً على السلسلة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker)(*[Node](../node/)*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_1)(*[Node](../node/), long*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker/#createtreewalker_2)(*[Node](../node/), long, [INodeFilter](../../aspose.svg.dom.traversal/inodefilter/)*) | إنشاء TreeWalker جديد فوق الشجرة الفرعية المتجذرة في العقدة المحددة. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent/)(*[Event](../../aspose.svg.dom.events/event/)*) | يبثّ حدثًا إلى [`IEventTarget`](../../aspose.svg.dom.events/ieventtarget/)، (متزامنًا) مستدعيًا مستمعي الأحداث المتأثرين بالترتيب المناسب. تُطبق قواعد معالجة الأحداث العادية (بما في ذلك مرحلة الالتقاط والفقاعة الاختيارية) أيضًا على الأحداث التي تُبث يدويًا باستخدام [`DispatchEvent`](../../aspose.svg.dom.events/ieventtarget/dispatchevent/). |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose/)() | ينفّذ مهامًا محددة من قبل التطبيق مرتبطة بتحرير أو إطلاق أو إعادة تعيين الموارد غير المُدارة. |
| [Evaluate](../../aspose.svg.dom/document/evaluate/)(*string, [Node](../node/), [IXPathNSResolver](../../aspose.svg.dom.xpath/ixpathnsresolver/), [XPathResultType](../../aspose.svg.dom.xpath/xpathresulttype/), object*) | يقيم سلسلة تعبير XPath ويعيد نتيجة من النوع المحدد إذا كان ذلك ممكنًا. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid/)(*string*) | تُعيد هذه الطريقة كائن [`Element`](../element/) يمثل العنصر الذي تتطابق خاصية المعرف (id) الخاصة به مع السلسلة المحددة. نظرًا لأن معرفات العناصر يجب أن تكون فريدة إذا تم تحديدها، فهي طريقة مفيدة للوصول إلى عنصر معين بسرعة. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname/)(*string*) | تُعيد هذه الطريقة كائنًا شبيهًا بالمصفوفة يحتوي على جميع العناصر الفرعية التي لديها جميع أسماء الفئات المحددة. |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname/)(*string*) | تُعيد هذه الطريقة [`HTMLCollection`](../../aspose.svg.collections/htmlcollection/) للعناصر التي تحمل اسم الوسم المحدد. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens/)(*string, string*) | تُرجع قائمة بالعناصر التي تحمل اسم الوسم المحدد وتنتمي إلى مساحة الاسم المحددة. يتم البحث في المستند بالكامل، بما في ذلك العقدة الجذرية. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype/)() | يُستخدم هذا الأسلوب لاسترجاع نوع كائن ECMAScript. |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes/)() | يعيد قيمة منطقية تشير إلى ما إذا كانت الـ[`Node`](../node/) المعطاة تحتوي على عقد أطفال أم لا. |
| [ImportNode](../../aspose.svg.dom/document/importnode/)(*[Node](../node/), bool*) | يستورد عقدة من مستند آخر إلى هذا المستند، دون تعديل أو إزالة العقدة المصدر من المستند الأصلي؛ تُنشئ هذه الطريقة نسخة جديدة من العقدة المصدر. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore/)(*[Node](../node/), [Node](../node/)*) | يدرج العقدة قبل عقدة الطفل الموجودة child. إذا كان child null، يُدرج العقدة في نهاية قائمة الأطفال. إذا كان child كائن DocumentFragment، تُدرج جميع أطفاله، بنفس الترتيب، قبل child. إذا كان الطفل موجوداً بالفعل في الشجرة، يُزال أولاً. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace/)(*string*) | تتحقق هذه الطريقة مما إذا كان الـnamespaceURI المحدد هو مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode/)(*[Node](../node/)*) | يفحص ما إذا كان العقدان متساويتين. تختبر هذه الطريقة مساواة العقد، وليس تماثلهما (أي ما إذا كانت العقدان إشارة إلى نفس الكائن) والذي يمكن اختباره باستخدام Node.isSameNode(). جميع العقد المتطابقة ستكون متساوية أيضاً، رغم أن العكس قد لا يكون صحيحاً. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode/)(*[Node](../node/)*) | الطريقة هي اسم مستعار قديم للمشغل الصارم ===. أي أنها تختبر ما إذا كان العقدان نفسهما (بمعنى آخر، ما إذا كانا يشيران إلى نفس الكائن). |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri/)(*string*) | ابحث عن URI مساحة الاسم المرتبط بالبادئة المعطاة، بدءاً من هذه العقدة. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix/)(*string*) | ابحث عن البادئة المرتبطة بـ URI مساحة الاسم المعطى، بدءاً من هذه العقدة. تتجاهل هذه الطريقة إعلانات مساحة الاسم الافتراضية. راجع Namespace Prefix Lookup للحصول على تفاصيل حول الخوارزمية المستخدمة في هذه الطريقة. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate)(*[RequestMessage](../../aspose.svg.net/requestmessage/)*) | يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_8)(*string*) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_2)(*[Url](../../aspose.svg/url/)*) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_1)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_6)(*Stream, string*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_4)(*Stream, [Url](../../aspose.svg/url/)*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_13)(*string, CancellationToken*) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_11)(*string, string*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_9)(*string, [Url](../../aspose.svg/url/)*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_3)(*[Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_7)(*Stream, string, CancellationToken*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_5)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_12)(*string, string, CancellationToken*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate/#navigate_10)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync)(*[RequestMessage](../../aspose.svg.net/requestmessage/), CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن بناءً على كائن الطلب المحدد. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_6)(*string, CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_1)(*[Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_3)(*Stream, string, CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_2)(*Stream, [Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_5)(*string, string, CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية. |
| [NavigateAsync](../../aspose.svg.dom/document/navigateasync/#navigateasync_4)(*string, [Url](../../aspose.svg/url/), CancellationToken*) | يقوم بتحميل المستند بشكل غير متزامن من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية. |
| [Normalize](../../aspose.svg.dom/node/normalize/)() | يضع جميع عقد النص في العمق الكامل للشجرة الفرعية تحت هذه العقدة، بما في ذلك عقد السمات، في صيغة "عادية" حيث يفصل الهيكل فقط (مثل العناصر، التعليقات، تعليمات المعالجة، أقسام CDATA، وإشارات الكيانات) بين عقد النص، أي لا توجد عقد نص متجاورة ولا عقد نص فارغة. يمكن استخدام ذلك لضمان أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله، وهو مفيد عندما تُستخدم عمليات (مثل عمليات البحث XPointer [XPointer]) التي تعتمد على بنية شجرة مستند معينة. إذا كان معامل "normalize-characters" لكائن DOMConfiguration المرتبط بـ Node.ownerDocument صحيحاً، فإن هذه الطريقة ستقوم أيضاً بتطبيع أحرف عقد النص بالكامل. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector/)(*string*) | تُرجع أول Element في المستند الذي يطابق المحدد. |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall/)(*string*) | تُرجع NodeList لجميع Elements في المستند التي تطابق المحدد. |
| [RemoveChild](../../aspose.svg.dom/node/removechild/)(*[Node](../node/)*) | يزيل عقدة فرعية من الـ DOM ويعيد العقدة التي تم إزالتها. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/)*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [DOMEventHandler](../../aspose.svg.dom.events/domeventhandler/), bool*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener/)(*string, [IEventListener](../../aspose.svg.dom.events/ieventlistener/), bool*) | تسمح هذه الطريقة بإزالة مستمعي الأحداث من هدف الحدث. إذا تم إزالة [`IEventListener`](../../aspose.svg.dom.events/ieventlistener/) من [`EventTarget`](../eventtarget/) أثناء معالجة حدث، فلن يتم تفعيلها بالإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث أبداً بعد إزالتهم. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto/)(*[IDevice](../../aspose.svg.rendering/idevice/)*) | تُستخدم هذه الطريقة لعرض محتويات المستند الحالي على جهاز رسومي محدد. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild/)(*[Node](../node/), [Node](../node/)*) | يستبدل عقدة الطفل oldChild بـ newChild في قائمة الأطفال، ويعيد عقدة oldChild. إذا كان newChild كائنًا من نوع DocumentFragment، يتم استبدال oldChild بجميع أطفال DocumentFragment، التي تُدرج بنفس الترتيب. إذا كان newChild موجودًا بالفعل في الشجرة، يتم إزالته أولاً. |
| override [ToString](../../aspose.svg.dom/node/tostring/)() | يرجع سلسلة نصية (String) تمثل هذه الحالة. |
| [Write](../../aspose.svg.dom/document/write/)(*params string[]*) | اكتب سلسلة نصية إلى تدفق المستند المفتوح بواسطة `open()`. لاحظ أن الدالة ستنتج مستندًا قد لا يكون مدفوعًا بملف تعريف النوع (DTD) وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |
| [WriteLn](../../aspose.svg.dom/document/writeln/)(*params string[]*) | اكتب سلسلة نصية متبوعة بحرف سطر جديد إلى تدفق المستند المفتوح بواسطة `open()`. لاحظ أن الدالة ستنتج مستندًا قد لا يكون مدفوعًا بملف تعريف النوع (DTD) وبالتالي قد ينتج نتيجة غير صالحة في سياق المستند. |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [OnAbort](../../aspose.svg.dom/document/onabort/) | يحصل أو يضبط معالج الحدث لحدث OnAbort. |
| event [OnBlur](../../aspose.svg.dom/document/onblur/) | يحصل أو يضبط معالج الحدث لحدث OnBlur. |
| event [OnCancel](../../aspose.svg.dom/document/oncancel/) | يحصل أو يضبط معالج الحدث لحدث OnCancel. |
| event [OnCanplay](../../aspose.svg.dom/document/oncanplay/) | يحصل أو يضبط معالج الحدث لحدث OnCanplay. |
| event [OnCanPlayThrough](../../aspose.svg.dom/document/oncanplaythrough/) | يحصل أو يضبط معالج الحدث لحدث OnCanPlayThrough. |
| event [OnChange](../../aspose.svg.dom/document/onchange/) | يحصل أو يضبط معالج الحدث لحدث OnChange. |
| event [OnClick](../../aspose.svg.dom/document/onclick/) | يحصل أو يضبط معالج الحدث لحدث OnClick. |
| event [OnCueChange](../../aspose.svg.dom/document/oncuechange/) | يحصل أو يضبط معالج الحدث لحدث OnCueChange. |
| event [OnDblClick](../../aspose.svg.dom/document/ondblclick/) | يحصل أو يضبط معالج الحدث لحدث OnDblClick. |
| event [OnDurationChange](../../aspose.svg.dom/document/ondurationchange/) | يحصل أو يضبط معالج الحدث لحدث OnDurationChange. |
| event [OnEmptied](../../aspose.svg.dom/document/onemptied/) | يحصل أو يضبط معالج الحدث لحدث OnEmptied. |
| event [OnEnded](../../aspose.svg.dom/document/onended/) | يحصل أو يضبط معالج الحدث لحدث OnEnded. |
| event [OnError](../../aspose.svg.dom/document/onerror/) | يحصل أو يضبط معالج الحدث لحدث OnError. |
| event [OnFocus](../../aspose.svg.dom/document/onfocus/) | الحصول أو تعيين معالج الحدث لـ OnFocus. |
| event [OnInput](../../aspose.svg.dom/document/oninput/) | الحصول أو تعيين معالج الحدث لـ OnInput. |
| event [OnInvalid](../../aspose.svg.dom/document/oninvalid/) | الحصول أو تعيين معالج الحدث لـ OnInvalid. |
| event [OnKeyDown](../../aspose.svg.dom/document/onkeydown/) | الحصول أو تعيين معالج الحدث لـ OnKeyDown. |
| event [OnKeyPress](../../aspose.svg.dom/document/onkeypress/) | الحصول أو تعيين معالج الحدث لـ OnKeyPress. |
| event [OnKeyUp](../../aspose.svg.dom/document/onkeyup/) | الحصول أو تعيين معالج الحدث لـ OnKeyUp. |
| event [OnLoad](../../aspose.svg.dom/document/onload/) | الحصول أو تعيين معالج الحدث لـ OnLoad. |
| event [OnLoadedData](../../aspose.svg.dom/document/onloadeddata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedData. |
| event [OnLoadedMetadata](../../aspose.svg.dom/document/onloadedmetadata/) | الحصول أو تعيين معالج الحدث لـ OnLoadedMetadata. |
| event [OnLoadStart](../../aspose.svg.dom/document/onloadstart/) | الحصول أو تعيين معالج الحدث لـ OnLoadStart. |
| event [OnMouseDown](../../aspose.svg.dom/document/onmousedown/) | الحصول أو تعيين معالج الحدث لـ OnMouseDown. |
| event [OnMouseEnter](../../aspose.svg.dom/document/onmouseenter/) | الحصول أو تعيين معالج الحدث لـ OnMouseEnter. |
| event [OnMouseLeave](../../aspose.svg.dom/document/onmouseleave/) | الحصول أو تعيين معالج الحدث لـ OnMouseLeave. |
| event [OnMouseMove](../../aspose.svg.dom/document/onmousemove/) | الحصول أو تعيين معالج الحدث لـ OnMouseMove. |
| event [OnMouseOut](../../aspose.svg.dom/document/onmouseout/) | الحصول أو تعيين معالج الحدث لـ OnMouseOut. |
| event [OnMouseOver](../../aspose.svg.dom/document/onmouseover/) | الحصول أو تعيين معالج الحدث لـ OnMouseOver. |
| event [OnMouseUp](../../aspose.svg.dom/document/onmouseup/) | الحصول أو تعيين معالج الحدث لـ OnMouseUp. |
| event [OnMouseWheel](../../aspose.svg.dom/document/onmousewheel/) | الحصول أو تعيين معالج الحدث لـ OnMouseWheel. |
| event [OnPause](../../aspose.svg.dom/document/onpause/) | الحصول أو تعيين معالج الحدث لـ OnPause. |
| event [OnPlay](../../aspose.svg.dom/document/onplay/) | الحصول أو تعيين معالج الحدث لـ OnPlay. |
| event [OnPlaying](../../aspose.svg.dom/document/onplaying/) | الحصول أو تعيين معالج الحدث لـ OnPlaying. |
| event [OnProgress](../../aspose.svg.dom/document/onprogress/) | الحصول أو تعيين معالج الحدث لـ OnProgress. |
| event [OnRateChange](../../aspose.svg.dom/document/onratechange/) | الحصول أو تعيين معالج الحدث لـ OnRateChange. |
| event [OnReadyStateChange](../../aspose.svg.dom/document/onreadystatechange/) | يحصل أو يعيّن معالج الحدث لحدث OnReadyStateChange. |
| event [OnReset](../../aspose.svg.dom/document/onreset/) | الحصول أو تعيين معالج الحدث لـ OnReset. |
| event [OnResize](../../aspose.svg.dom/document/onresize/) | الحصول أو تعيين معالج الحدث لـ OnResize. |
| event [OnScroll](../../aspose.svg.dom/document/onscroll/) | يحصل أو يعيّن معالج الحدث لحدث OnScroll. |
| event [OnSeeked](../../aspose.svg.dom/document/onseeked/) | يحصل أو يعيّن معالج الحدث لحدث OnSeeked. |
| event [OnSeeking](../../aspose.svg.dom/document/onseeking/) | يحصل أو يعيّن معالج الحدث لحدث OnSeeking. |
| event [OnSelect](../../aspose.svg.dom/document/onselect/) | يحصل أو يعيّن معالج الحدث لحدث OnSelect. |
| event [OnShow](../../aspose.svg.dom/document/onshow/) | يحصل أو يعيّن معالج الحدث لحدث OnShow. |
| event [OnStalled](../../aspose.svg.dom/document/onstalled/) | يحصل أو يعيّن معالج الحدث لحدث OnStalled. |
| event [OnSubmit](../../aspose.svg.dom/document/onsubmit/) | يحصل أو يعيّن معالج الحدث لحدث OnSubmit. |
| event [OnSuspend](../../aspose.svg.dom/document/onsuspend/) | يحصل أو يعيّن معالج الحدث لحدث OnSuspend. |
| event [OnTimeUpdate](../../aspose.svg.dom/document/ontimeupdate/) | يحصل أو يعيّن معالج الحدث لحدث OnTimeUpdate. |
| event [OnToggle](../../aspose.svg.dom/document/ontoggle/) | يحصل أو يعيّن معالج الحدث لحدث OnToggle. |
| event [OnVolumeChange](../../aspose.svg.dom/document/onvolumechange/) | يحصل أو يعيّن معالج الحدث لحدث OnVolumeChange. |
| event [OnWaiting](../../aspose.svg.dom/document/onwaiting/) | يحصل أو يعيّن معالج الحدث لحدث OnWaiting. |

### انظر أيضًا

* class [Node](../node/)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
