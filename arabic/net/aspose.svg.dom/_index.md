---
title: "Aspose.Svg.Dom"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "مساحة الاسم Document Object Model الخاصة بـ Aspose.Svg.Dom توفر API تمثل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يتم تحميله في المتصفح ويمثل المستند كشجرة عقد حيث تمثل كل عقدة جزءًا من المستند مثل عنصر أو سلسلة نصية أو تعليق."
type: docs
weight: 70
url: /ar/net/aspose.svg.dom/
---
مساحة الاسم **Aspose.Svg.Dom (Document Object Model)** توفر API تمثل وتتفاعل مع أي مستندات HTML أو XML أو SVG. الـ DOM هو نموذج مستند يتم تحميله في المتصفح ويمثل المستند كشجرة عقد، حيث تمثل كل عقدة جزءًا من المستند (مثل عنصر، سلسلة نصية، أو تعليق).

## الفئات

| الفئة | الوصف |
| --- | --- |
| [Attr](./attr/) | واجهة Attr تمثل سمة في كائن Element. عادةً ما يتم تعريف القيم المسموح بها للسمة في مخطط مرتبط بالمستند. |
| [CDATASection](./cdatasection/) | تُستخدم أقسام CDATA للهروب من كتل النص التي تحتوي على أحرف قد تُعتبر عادةً تعليمات ترميز. |
| [CharacterData](./characterdata/) | واجهة CharacterData تمتد من Node وتوفر مجموعة من السمات والطرق للوصول إلى بيانات الأحرف في الـ DOM. |
| [Comment](./comment/) | ورثت من CharacterData وتمثل محتوى تعليق، أي جميع الأحرف بين البداية ''. |
| [Document](./document/) | واجهة Document تمثل المستند الكامل HTML أو XML أو SVG. مفهومياً، هي جذر شجرة المستند، وتوفر الوصول الأساسي إلى بيانات المستند. |
| [DocumentFragment](./documentfragment/) | DocumentFragment هو كائن مستند "خفيف الوزن" أو "حد أدنى". من الشائع جداً الرغبة في استخراج جزء من شجرة المستند أو إنشاء قطعة جديدة من المستند. |
| [DocumentType](./documenttype/) | واجهة DocumentType توفر واجهة إلى قائمة الكيانات المعرفة للمستند. |
| [DOMException](./domexception/) | واجهة DOMException تمثل حدثًا غير طبيعي (يسمى استثناء) يحدث نتيجة استدعاء طريقة أو الوصول إلى خاصية في واجهة برمجة تطبيقات الويب. هذا هو الأساس في وصف حالات الخطأ في واجهات برمجة تطبيقات الويب. |
| [DOMObject](./domobject/) | نوع DOMObject يُستخدم لتمثيل كائن أساسي لكامل نموذج كائن المستند. بالنسبة لـ Java و ECMAScript، يتم ربط DOMObject بنوع Object. |
| [Element](./element/) | واجهة Element تمثل عنصرًا في مستند HTML أو XML. |
| [Entity](./entity/) | يمثل كيانًا معروفًا، إما مُحللاً أو غير مُحلل، في مستند XML. |
| [EntityReference](./entityreference/) | قد تُستخدم عقد EntityReference لتمثيل إشارة كيان في الشجرة. |
| [EventTarget](./eventtarget/) | The واجهة [`EventTarget`](../aspose.svg.dom/eventtarget/) يتم تنفيذها من قبل جميع العقد في تنفيذ يدعم نموذج أحداث DOM. لذلك، يمكن الحصول على هذه الواجهة باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة العقدة. تسمح الواجهة بتسجيل وإزالة مستمعي الأحداث على [`EventTarget`](../aspose.svg.dom/eventtarget/) وإرسال الأحداث إلى ذلك [`IEventTarget`](../aspose.svg.dom.events/ieventtarget/). |
| [Node](./node/) | واجهة Node هي النوع الأساسي للبيانات لكامل نموذج كائن المستند. تمثل عقدة واحدة في شجرة المستند. |
| [Notation](./notation/) | يمثل تدوينًا تم إعلانه في DTD. |
| [ProcessingInstruction](./processinginstruction/) | تمثل ProcessingInstruction "تعليمة معالجة"، وتُستخدم في XML كطريقة للحفاظ على معلومات خاصة بالمعالج في نص المستند. |
| [QualifiedName](./qualifiedname/) | يمثل اسمًا مؤهلاً في HTML. |
| [ShadowRoot](./shadowroot/) | ShadowRoot هو عقدة جذرية لشجرة الظل. |
| [Text](./text/) | واجهة Text ترث من CharacterData وتمثل المحتوى النصي (المعروف ببيانات الأحرف في XML) لعنصر Element أو Attr. |
| [TypeInfo](./typeinfo/) | تمثل TypeInfo نوعًا مُشارًا إليه من عقد Element أو Attr، محددًا في المخططات المرتبطة بالمستند. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | سياق التصفح هو بيئة تُعرض فيها كائنات [`Document`](../aspose.svg.dom/document/) للمستخدم. |
| [IChildNode](./ichildnode/) | يعرّف واجهة [`IChildNode`](../aspose.svg.dom/ichildnode/) التي يجب أن تُطبقها [`Node`](../aspose.svg.dom/node/) التي يمكن أن يكون لها أب. |
| [IDOMImplementation](./idomimplementation/) | توفر واجهة DOMImplementation عددًا من الطرق لتنفيذ عمليات مستقلة عن أي نسخة معينة من نموذج كائن المستند. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | يمثل واجهة يجب أن يرثها جميع العناصر التي تدعم معالجة أحداث النظام. |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | يعرّف [`IChildNode`](../aspose.svg.dom/ichildnode/) التي ليست [`DOCUMENT_TYPE_NODE`](../aspose.svg.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | يعرّف [`IParentNode`](../aspose.svg.dom/iparentnode/) التي ليست من نوع Element. |
| [IParentNode](./iparentnode/) | يعرّف واجهة [`IParentNode`](../aspose.svg.dom/iparentnode/) التي تُطبقها أي من الآباء المحتملين. |
| [IStorage](./istorage/) | توفر هذه الواجهة في Web Storage API إمكانية الوصول إلى جلسة أو تخزين محلي لنطاق معين. راجع مواصفة Web Storage: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | الأوضاع التي يمكن أن يعمل فيها ShadowRoot. |
