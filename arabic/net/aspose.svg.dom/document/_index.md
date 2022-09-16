---
title: Document
second_title: Aspose.SVG لمرجع .NET API
description: يمثل المستند مستند HTML أو XML أو SVG بأكمله. من الناحية المفاهيمية  فهو جذر شجرة المستند  ويوفر الوصول الأساسي إلى بيانات المستند.
type: docs
weight: 810
url: /ar/net/aspose.svg.dom/document/
---
## Document class

يمثل المستند مستند HTML أو XML أو SVG بأكمله. من الناحية المفاهيمية ، فهو جذر شجرة المستند ، ويوفر الوصول الأساسي إلى بيانات المستند.

```csharp
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## الخصائص

| اسم | وصف |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes) { get; } | خريطة NamedNodeMap تحتوي على سمات هذه العقدة (إذا كانت عنصرًا) أو خالية بخلاف ذلك. |
| override [BaseURI](../../aspose.svg.dom/document/baseuri) { get; } | URI الأساسي المطلق لهذه العقدة أو فارغ إذا لم يتمكن التطبيق من الحصول على URI مطلق. |
| [CharacterSet](../../aspose.svg.dom/document/characterset) { get; } | الحصول على ترميز المستند. |
| [Charset](../../aspose.svg.dom/document/charset) { get; } | الحصول على ترميز المستند. |
| [ChildElementCount](../../aspose.svg.dom/document/childelementcount) { get; } | إرجاع العدد الحالي لعقد العناصر التي هي عناصر فرعية لهذا العنصر. 0 إذا كان هذا العنصر لا يحتوي على عقد فرعية من نوع العقدة 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | قائمة NodeList التي تحتوي على كافة توابع هذه العقدة. إذا لم يكن هناك أطفال ، فهذه قائمة NodeList لا تحتوي على عقد .. |
| [Children](../../aspose.svg.dom/document/children) { get; } | إرجاع العناصر الفرعية . |
| [ContentType](../../aspose.svg.dom/document/contenttype) { get; } | الحصول على نوع محتوى المستند. |
| [Context](../../aspose.svg.dom/document/context) { get; } | يحصل على سياق التصفح الحالي. |
| [DefaultView](../../aspose.svg.dom/document/defaultview) { get; } | السمة الافتراضية للعرض IDL لواجهة المستند ، عند الحصول على ، يجب أن تعيد كائن WindowProxy الخاص بسياق الاستعراض الخاص بهذا المستند ، إذا كان هذا المستند يحتوي على سياق استعراض مرتبط ، أو فارغًا بخلاف ذلك. |
| [Doctype](../../aspose.svg.dom/document/doctype) { get; } | إقرار نوع المستند المرتبط بهذا المستند . |
| [DocumentElement](../../aspose.svg.dom/document/documentelement) { get; } | هذه سمة ملائمة تتيح الوصول المباشر إلى العقدة الفرعية التي تمثل عنصر المستند في المستند. |
| [DocumentURI](../../aspose.svg.dom/document/documenturi) { get; } | مكان المستند أو فارغ إذا لم يتم تعريفه أو إذا تم إنشاء المستند باستخدام DOMImplementation.createDocument. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | الطفل الأول لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [FirstElementChild](../../aspose.svg.dom/document/firstelementchild) { get; } | إرجاع أول عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| [Implementation](../../aspose.svg.dom/document/implementation) { get; } | كائن DOMImplementation الذي يعالج هذا المستند. |
| [InputEncoding](../../aspose.svg.dom/document/inputencoding) { get; } | الحصول على ترميز المستند. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | آخر تابع لهذه العقدة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [LastElementChild](../../aspose.svg.dom/document/lastelementchild) { get; } | إرجاع آخر عقدة عنصر فرعي لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عناصر فرعية. |
| virtual [LocalName](../../aspose.svg.dom/node/localname) { get; } | إرجاع الجزء المحلي من الاسم المؤهل لهذه العقدة . بالنسبة للعقد من أي نوع بخلاف ELEMENT_NODE و ATTRIBUTE_NODE والعقد التي تم إنشاؤها باستخدام طريقة DOM من المستوى 1 ، مثل Document.createElement () ، يكون هذا دائمًا فارغًا. |
| [Location](../../aspose.svg.dom/document/location) { get; } | مكان المستند . |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri) { get; } | معرف مساحة الاسم لهذه العقدة ، أو فارغ إذا كانت غير محددة. |
| [NextElementSibling](../../aspose.svg.dom/document/nextelementsibling) { get; } | إرجاع عقدة العنصر الشقيقة التالية لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي بعد هذا في شجرة المستند. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | العقدة التي تلي هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| override [NodeName](../../aspose.svg.dom/document/nodename) { get; } | اسم هذه العقدة حسب نوعها. |
| override [NodeType](../../aspose.svg.dom/document/nodetype) { get; } | رمز يمثل نوع الكائن الأساسي. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue) { get; set; } | قيمة هذه العقدة حسب نوعها. |
| [Origin](../../aspose.svg.dom/document/origin) { get; } | يحصل على اصل الوثيقة . |
| override [OwnerDocument](../../aspose.svg.dom/document/ownerdocument) { get; } | الحصول على مستند المالك. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | يحصل على الوالد[`Element`](../element) من هذه العقدة. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | أصل هذه العقدة. قد يكون لجميع العقد ، باستثناء Attr و Document و DocumentFragment و Entity و Notation ، أصل. ومع ذلك ، إذا تم إنشاء عقدة للتو ولم تتم إضافتها بعد إلى الشجرة ، أو إذا تمت إزالتها من الشجرة ، فسيكون ذلك فارغًا. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix) { get; set; } | بادئة مساحة الاسم لهذه العقدة ، أو فارغة إذا كانت غير محددة. عندما يتم تعريفه على أنه فارغ ، فإن الإعداد ليس له تأثير |
| [PreviousElementSibling](../../aspose.svg.dom/document/previouselementsibling) { get; } | إرجاع عقدة العنصر الشقيقة السابقة لهذا العنصر. خالية إذا كان هذا العنصر لا يحتوي على عقد شقيقة لعنصر تأتي قبل هذا في شجرة الوثيقة. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | العقدة التي تسبق هذه العقدة مباشرة. إذا لم يكن هناك مثل هذه العقدة ، فإن هذا يعيد قيمة خالية. |
| [ReadyState](../../aspose.svg.dom/document/readystate) { get; } | إرجاع جاهزية المستند. "التحميل" أثناء تحميل المستند ، "تفاعلي" بمجرد الانتهاء من التحليل مع استمرار تحميل الموارد الفرعية ، و "اكتمال" بمجرد تحميله. |
| [StrictErrorChecking](../../aspose.svg.dom/document/stricterrorchecking) { get; set; } | سمة تحدد ما إذا كان التحقق من الخطأ يتم فرضه أم لا. عند التعيين على "خطأ" ، يكون التطبيق مجانيًا لعدم اختبار كل حالة خطأ محتملة يتم تحديدها عادةً على عمليات DOM ، وعدم رفع أي استثناءات DOM على عمليات DOM أو الإبلاغ عن الأخطاء أثناء استخدام Document.normalizeDocument (). في حالة الخطأ ، يكون السلوك غير محدد. هذه السمة صحيحة بشكل افتراضي. |
| [StyleSheets](../../aspose.svg.dom/document/stylesheets) { get; } | قائمة تحتوي على كافة أوراق الأنماط المرتبطة أو المضمنة في مستند بشكل صريح. بالنسبة لمستندات HTML ، يتضمن ذلك أوراق الأنماط الخارجية ، المضمنة عبر عنصر HTML LINK ، وعناصر النمط المضمنة. |
| virtual [TextContent](../../aspose.svg.dom/node/textcontent) { get; set; } | تقوم هذه السمة بإرجاع المحتوى النصي لهذه العقدة وتوابعها. عندما يتم تعريفه على أنه فارغ ، فإن تعيينه ليس له أي تأثير. عند الإعداد ، تتم إزالة أي أطفال محتملين قد تكون هذه العقدة لديهم ، وإذا لم تكن السلسلة الجديدة فارغة أو فارغة ، فسيتم استبدالها بعقدة نصية واحدة تحتوي على السلسلة التي تم تعيين هذه السمة عليها. |
| [XmlStandalone](../../aspose.svg.dom/document/xmlstandalone) { get; set; } | سمة تحدد ، كجزء من إعلان XML ، ما إذا كان هذا المستند مستقلاً. هذا خطأ عندما يكون غير محدد. |
| [XmlVersion](../../aspose.svg.dom/document/xmlversion) { get; set; } | سمة تحدد ، كجزء من إعلان XML ، رقم إصدار هذا المستند. إذا لم يكن هناك إعلان وإذا كان هذا المستند يدعم ميزة "XML" ، فإن القيمة هي "1.0". إذا كان هذا المستند لا يدعم ميزة "XML" ، فستكون القيمة دائمًا خالية. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بتسجيل مستمعي الحدث على هدف الحدث. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | يضيف العقدة newChild إلى نهاية قائمة العناصر الفرعية لهذه العقدة. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)() | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)(bool) | إرجاع نسخة مكررة من هذه العقدة ، على سبيل المثال ، بمثابة مُنشئ نسخة عام للعقد. لا تحتوي العقدة المكررة على أصل (العقدة الأم خالية) ولا توجد بيانات مستخدم. |
| [CreateAttribute](../../aspose.svg.dom/document/createattribute)(string) | لإنشاء Attr بالاسم المحدد . |
| [CreateAttributeNS](../../aspose.svg.dom/document/createattributens)(string, string) | ينشئ سمة للاسم المؤهل المحدد ومساحة URI. |
| [CreateCDATASection](../../aspose.svg.dom/document/createcdatasection)(string) | ينشئ عقدة CDATAS تكون قيمتها هي السلسلة المحددة. |
| [CreateComment](../../aspose.svg.dom/document/createcomment)(string) | يقوم بإنشاء عقدة تعليق بالنظر إلى السلسلة المحددة . |
| [CreateDocumentFragment](../../aspose.svg.dom/document/createdocumentfragment)() | إنشاء كائن DocumentFragment فارغ . |
| [CreateDocumentType](../../aspose.svg.dom/document/createdocumenttype)(string, string, string, string) | ينشئ عقدة DocumentType . |
| [CreateElement](../../aspose.svg.dom/document/createelement)(string) | لتكوين عنصر من النوع المحدد. لاحظ أن المثيل الذي تم إرجاعه يطبق واجهة العنصر ، لذلك يمكن تحديد السمات مباشرة على الكائن الذي تم إرجاعه. |
| [CreateElementNS](../../aspose.svg.dom/document/createelementns)(string, string) | ينشئ عنصرًا للاسم المؤهل المحدد ومساحة الاسم URI. |
| [CreateEntityReference](../../aspose.svg.dom/document/createentityreference)(string) | إنشاء كائن EntityReference. بالإضافة إلى ذلك ، إذا كان الكيان المُشار إليه معروفًا ، فستكون القائمة الفرعية لعقدة EntityReference مماثلة لقائمة عقدة الكيان المقابلة. |
| [CreateEvent](../../aspose.svg.dom/document/createevent)(string) | ينشئ ملف[`Event`](../../aspose.svg.dom.events/event) من النوع الذي يدعمه التنفيذ . |
| [CreateExpression](../../aspose.svg.dom/document/createexpression)(string, IXPathNSResolver) | لتكوين تعبير XPath تم تحليله باستخدام مساحات الأسماء التي تم حلها. يعد هذا مفيدًا عندما يُعاد استخدام تعبير في أحد التطبيقات لأنه يجعل من الممكن تجميع سلسلة التعبير في نموذج داخلي أكثر كفاءة و حل جميع بادئات مساحة الاسم التي تحدث داخل التعبير. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator)(Node) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator_1)(Node, long) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNodeIterator](../../aspose.svg.dom/document/createnodeiterator#createnodeiterator_2)(Node, long, INodeFilter) | قم بإنشاء NodeIterator جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateNSResolver](../../aspose.svg.dom/document/creatensresolver)(Node) | تتكيف مع أي عقدة DOM لتحليل مساحات الأسماء بحيث يمكن بسهولة تقييم تعبير XPath بالنسبة إلى سياق العقدة حيث ظهر داخل المستند. يعمل هذا المحول مثل طريقة DOM المستوى 3`lookupNamespaceURI` على العقد في حل مساحة الاسمURI من بادئة معينة باستخدام المعلومات الحالية المتاحة في التسلسل الهرمي للعقدة في time lookupNamespaceURI ، يتم أيضًا حل بادئة xml الضمنية بشكل صحيح. |
| [CreateProcessingInstruction](../../aspose.svg.dom/document/createprocessinginstruction)(string, string) | ينشئ عقدة ProcessingInstruction مع إعطاء الاسم المحدد وسلاسل البيانات. |
| [CreateTextNode](../../aspose.svg.dom/document/createtextnode)(string) | يقوم بإنشاء عقدة نصية بالسلسلة المحددة . |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker)(Node) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker_1)(Node, long) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [CreateTreeWalker](../../aspose.svg.dom/document/createtreewalker#createtreewalker_2)(Node, long, INodeFilter) | قم بإنشاء TreeWalker جديد فوق الشجرة الفرعية التي تم تحديد جذرها في العقدة المحددة. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | تسمح هذه الطريقة بإرسال الأحداث إلى نموذج حدث عمليات التنفيذ. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | تنفيذ مهام محددة بواسطة التطبيق مرتبطة بتحرير الموارد غير المُدارة أو تحريرها أو إعادة تعيينها. |
| [Evaluate](../../aspose.svg.dom/document/evaluate)(string, Node, IXPathNSResolver, XPathResultType, object) | بتقييم سلسلة تعبير XPath وإرجاع نتيجة من النوع المحدد إن أمكن. |
| [GetElementById](../../aspose.svg.dom/document/getelementbyid)(string) | إرجاع العنصر الذي يحتوي على سمة معرف بالقيمة المحددة. إذا لم يكن هذا العنصر موجودًا ، فسيتم إرجاعه فارغًا. إذا كان هناك أكثر من عنصر واحد يحتوي على سمة معرف بهذه القيمة ، فإن ما يتم إرجاعه يكون غير محدد. |
| [GetElementsByClassName](../../aspose.svg.dom/document/getelementsbyclassname)(string) | إرجاع كائن NodeList مباشر يحتوي على جميع العناصر في المستند التي تحتوي على جميع الفئات المحددة في الوسيطة . http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/document/getelementsbytagname)(string) | إرجاع قائمة NodeList لجميع العناصر بترتيب المستند مع اسم علامة محدد ومضمنة في المستند. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/document/getelementsbytagnamens)(string, string) | إرجاع NodeList لجميع العناصر مع اسم محلي محدد ومساحة اسم URI بترتيب المستند. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | تُستخدم هذه الطريقة لاسترداد كائن ECMAScriptType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes)() | إرجاع ما إذا كانت هذه العقدة (إذا كانت عنصرًا) لها أي سمات |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | إرجاع ما إذا كان لهذه العقدة أي توابع. |
| [ImportNode](../../aspose.svg.dom/document/importnode)(Node, bool) | يستورد عقدة من مستند آخر إلى هذا المستند ، بدون تغيير أو إزالة العقدة المصدر من المستند الأصلي ؛ هذه الطريقة تنشئ نسخة جديدة من العقدة المصدر. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | يقوم بإدراج العقدة قبل تابع العقدة الفرعية الموجودة. إذا كان الطفل فارغًا ، فقم بإدراج العقدة في نهاية قائمة العناصر الفرعية . إذا كان الكائن الفرعي عبارة عن كائن DocumentFragment ، فسيتم إدراج جميع توابعه ، بالترتيب نفسه ، قبل التابع. إذا كان الطفل موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | يتحقق هذا الأسلوب مما إذا كانت مساحة الاسم المحددة هي مساحة الاسم الافتراضية أم لا. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | اختبار ما إذا كانت العقدتان متساويتان. تختبر هذه الطريقة المساواة بين العقد ، وليس التماثل (أي ما إذا كانت العقدتان مرجعيتان لنفس الكائن) والتي يمكن اختبارها باستخدام Node.isSameNode (). جميع العقد التي هي نفسها ستكون متساوية أيضًا ، على الرغم من أن العكس قد لا يكون صحيحًا. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | إرجاع ما إذا كانت هذه العقدة هي نفس العقدة المحددة. توفر هذه الطريقة طريقة لتحديد ما إذا كان مرجعان للعقدة يتم إرجاعهما بواسطة مرجع التطبيق نفس الكائن. عندما يكون مراجعان للعقدة مراجع لنفس الكائن ، حتى لو كان ذلك من خلال وكيل ، يمكن استخدام المراجع بشكل تبادلي تمامًا ، بحيث يكون لجميع السمات نفس القيم واستدعاء نفس طريقة DOM على أي مرجع يكون له نفس التأثير دائمًا. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | ابحث عن مساحة الاسم URI المرتبطة بالبادئة المحددة ، بدءًا من هذه العقدة. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | ابحث عن البادئة المرتبطة بمساحة الاسم المحددة URI ، بدءًا من هذه العقدة. يتم تجاهل تعريفات مساحة الاسم الافتراضية بهذه الطريقة. راجع بحث بادئة مساحة الاسم للحصول على تفاصيل حول الخوارزمية المستخدمة بواسطة هذه الطريقة. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate)(RequestMessage) | يتم تحميل المستند بناءً على كائن الطلب المحدد ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_4)(string) | تحميل المستند في محدد موقع المعلومات (URL) المحدد في المثيل الحالي ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_1)(Url) | تحميل المستند في محدد موقع المعلومات (URL) المحدد في المثيل الحالي ، مع استبدال المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_3)(Stream, string) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق . |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_2)(Stream, Url) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق . |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_6)(string, string) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. |
| [Navigate](../../aspose.svg.dom/document/navigate#navigate_5)(string, Url) | تحميل المستند من محتوى محدد واستخدام baseUri لحل الموارد ذات الصلة ، واستبدال المحتوى السابق. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | وضع جميع العقد النصية في العمق الكامل للشجرة الفرعية أسفل هذه العقدة ، بما في ذلك عقد السمات ، في نموذج "عادي" حيث تفصل البنية فقط (على سبيل المثال ، العناصر والتعليقات وتعليمات المعالجة وأقسام CDATA ومراجع الكيانات) النص العقد ، أي لا توجد عقد نصية متجاورة ولا عقد نصية فارغة. يمكن استخدام هذا للتأكد من أن عرض DOM للمستند هو نفسه كما لو تم حفظه وإعادة تحميله ، ويكون مفيدًا عندما تكون العمليات (مثل عمليات بحث XPointer [XPointer]) التي تعتمد على بنية شجرة وثيقة معينة يستخدم. إذا كانت المعلمة "تطبيع الأحرف" لكائن DOMConfiguration المرفقة بـ Node.ownerDocument صحيحة ، فإن هذه الطريقة ستعمل أيضًا على تسوية أحرف العقد النصية بشكل كامل. |
| [QuerySelector](../../aspose.svg.dom/document/queryselector)(string) | إرجاع العنصر الأول في المستند الذي يتطابق مع selector |
| [QuerySelectorAll](../../aspose.svg.dom/document/queryselectorall)(string) | إرجاع قائمة NodeList لجميع العناصر الموجودة في المستند ، والتي تطابق selector |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | يزيل العقدة الفرعية التي أشار إليها oldChild من قائمة الأطفال ، ويعيدها . |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | تسمح هذه الطريقة بإزالة مستمعي الحدث من هدف الحدث. إذا كان[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) تمت إزالته من ملف[`EventTarget`](../eventtarget) أثناء معالجة حدث ، لن يتم تشغيله من خلال الإجراءات الحالية. لا يمكن استدعاء مستمعي الأحداث بعد إزالتها. |
| virtual [RenderTo](../../aspose.svg.dom/document/renderto)(IDevice) | تُستخدم هذه الطريقة لتقديم محتويات المستند الحالي إلى جهاز رسومي محدد. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | يستبدل العقدة الفرعية oldChild بـ newChild في قائمة الأطفال ، ويعيد العقدة oldChild. إذا كان newChild هو كائن DocumentFragment ، فسيتم استبدال oldChild بكافة العناصر الفرعية DocumentFragment ، والتي يتم إدراجها بنفس الترتيب. إذا كان الطفل الجديد موجودًا بالفعل في الشجرة ، فسيتم إزالته أولاً. |
| override [ToString](../../aspose.svg.dom/node/tostring)() | إرجاع أString الذي يمثل هذا المثال. |
| [Write](../../aspose.svg.dom/document/write)(params string[]) | اكتب سلسلة نصية إلى تدفق مستند تم فتحه بواسطة open (). لاحظ أن الوظيفة ستنتج document الذي لا يكون بالضرورة مدفوعًا بـ DTD وبالتالي قد ينتج عن ذلك نتيجة غير صالحة في سياق المستند. |
| [WriteLn](../../aspose.svg.dom/document/writeln)(params string[]) | اكتب سلسلة نصية متبوعة بحرف سطر جديد إلى دفق document مفتوح بواسطة open (). لاحظ أن الوظيفة will تنتج مستندًا ليس بالضرورة مدفوعًا بـ DTD و لذلك قد ينتج نتيجة غير صالحة في سياق document |

### أنظر أيضا

* class [Node](../node)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent)
* interface [IDocumentStyle](../../aspose.svg.dom.css/idocumentstyle)
* interface [IDocumentTraversal](../../aspose.svg.dom.traversal/idocumenttraversal)
* interface [IGlobalEventHandlers](../iglobaleventhandlers)
* interface [INonElementParentNode](../inonelementparentnode)
* interface [IParentNode](../iparentnode)
* interface [IXPathEvaluator](../../aspose.svg.dom.xpath/ixpathevaluator)
* مساحة الاسم [Aspose.Svg.Dom](../../aspose.svg.dom)
* المجسم [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
