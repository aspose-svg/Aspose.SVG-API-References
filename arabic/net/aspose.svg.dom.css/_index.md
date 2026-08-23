---
title: "Aspose.Svg.Dom.Css"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "مساحة الأسماء Aspose.Svg.Dom.Css مخصصة لجميع التلاعبات المتعلقة بـ CSS. تركز حول أزواج اسم الخاصية - القيمة المحددة في الوثائق الرسمية لـ CSS."
type: docs
weight: 90
url: /ar/net/aspose.svg.dom.css/
---
مساحة الاسم **Aspose.Svg.Dom.Css** مخصصة لجميع التلاعبات المتعلقة بـ CSS. تركز على أزواج اسم الخاصية - القيمة في CSS المحددة في الوثائق الرسمية لـ CSS.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [Counter](./counter/) | تُستخدم واجهة Counter لتمثيل أي قيمة عدّاد أو قيمة دالة counters. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | تمثل واجهة CSSPrimitiveValue قيمة CSS واحدة. يمكن استخدام هذه الواجهة لتحديد قيمة خاصية نمط معينة تم تعيينها حاليًا في كتلة أو لتعيين خاصية نمط معينة صراحةً داخل الكتلة. يمكن الحصول على مثال من هذه الواجهة عبر طريقة getPropertyCSSValue في واجهة CSSStyleDeclaration. لا يظهر كائن CSSPrimitiveValue إلا في سياق خاصية CSS. |
| [CSSValue](./cssvalue/) | يمثل قيمة بسيطة أو مركبة. لا يظهر كائن CSSValue إلا في سياق خاصية CSS. |
| [CSSValueList](./cssvaluelist/) | توفر واجهة CSSValueList تجريد مجموعة مرتبة من قيم CSS. |
| [Rect](./rect/) | تُستخدم واجهة Rect لتمثيل أي قيمة rect. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، فإن التعديلات التي تُجرى على كائنات CSSPrimitiveValue تُعدّل خاصية النمط. |
| [RGBColor](./rgbcolor/) | تُستخدم واجهة RGBColor لتمثيل أي قيمة لون RGB. تعكس هذه الواجهة القيم في خاصية النمط الأساسية. وبالتالي، فإن التعديلات التي تُجرى على كائنات CSSPrimitiveValue تُعدّل خاصية النمط. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | توفر واجهة للتلاعب بقيم مجموعة خصائص CSS2 في سياق عنصر HTML معين |
| [ICSSCharsetRule](./icsscharsetrule/) | تمثل واجهة CSSCharsetRule قاعدة @charset في ورقة أنماط CSS. لا يؤثر قيمة سمة الترميز على ترميز بيانات النص في كائنات DOM؛ هذا الترميز دائمًا UTF-16. بعد تحميل ورقة الأنماط، تكون قيمة سمة الترميز هي القيمة الموجودة في قاعدة @charset. إذا لم توجد قاعدة @charset في المستند الأصلي، فلن يتم إنشاء CSSCharsetRule. قد تُستخدم قيمة سمة الترميز أيضًا كإشارة للترميز المستخدم عند تسلسل ورقة الأنماط. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | تسمح قاعدة @counter-style للمؤلفين بتعريف نمط عدّاد مخصص. |
| [ICSSFontFaceRule](./icssfontfacerule/) | تمثل واجهة CSSFontFaceRule قاعدة @font-face في ورقة أنماط CSS. تُستخدم قاعدة @font-face للاحتفاظ بمجموعة من أوصاف الخطوط. |
| [ICSSImportRule](./icssimportrule/) | تمثل واجهة CSSImportRule قاعدة @import داخل ورقة أنماط CSS. تُستخدم قاعدة @import لاستيراد قواعد الأنماط من أوراق أنماط أخرى. |
| [ICSSKeyframeRule](./icsskeyframerule/) | تمثل واجهة CSSKeyframeRule قاعدة النمط لمفتاح واحد. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | تمثل واجهة CSSKeyframesRule مجموعة كاملة من إطارات المفاتيح (keyframes) لتصميم واحد. |
| [ICSSMarginRule](./icssmarginrule/) | واجهة CSSMarginRule تمثل قاعدة at-rule للهوامش. |
| [ICSSMediaRule](./icssmediarule/) | واجهة CSSMediaRule تمثل قاعدة @media في ورقة أنماط CSS. يمكن استخدام قاعدة @media لتحديد قواعد الأنماط لأنواع وسائط محددة. |
| [ICSSPageRule](./icsspagerule/) | واجهة CSSPageRule تمثل قاعدة @page داخل ورقة أنماط CSS. تُستخدم قاعدة @page لتحديد الأبعاد، الاتجاه، الهوامش، إلخ، لصندوق الصفحة للوسائط المصفحة. |
| [ICSSRule](./icssrule/) | واجهة CSSRule هي الواجهة الأساسية المجردة لأي نوع من عبارات CSS. وهذا يشمل مجموعات القواعد وat-rules. من المتوقع أن تحتفظ أي تنفيذ بجميع القواعد المحددة في ورقة أنماط CSS، حتى إذا لم يتعرف المحلل على القاعدة. القواعد غير المعروفة يتم تمثيلها باستخدام واجهة ICSSUnknownRule. |
| [ICSSRuleList](./icssrulelist/) | واجهة CSSRuleList توفر تجريد مجموعة مرتبة من قواعد CSS. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | واجهة CSSStyleDeclaration تمثل كتلة إعلان CSS واحدة. يمكن استخدام هذه الواجهة لتحديد خصائص النمط الحالية في الكتلة أو لتعيين خصائص النمط صراحةً داخل الكتلة. |
| [ICSSStyleRule](./icssstylerule/) | واجهة CSSStyleRule تمثل مجموعة قواعد واحدة في ورقة أنماط CSS. |
| [ICSSStyleSheet](./icssstylesheet/) | واجهة CSSStyleSheet هي واجهة ملموسة تُستخدم لتمثيل ورقة أنماط CSS، أي ورقة أنماط يكون نوع محتواها "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | واجهة CSSUnknownRule تمثل at-rule غير مدعومة من قبل هذا وكيل المستخدم. |
| [ICSSValueList](./icssvaluelist/) | الواجهة توفر تجريد مجموعة مرتبة من قيم CSS. |
| [IDocumentCSS](./idocumentcss/) | هذه الواجهة تمثل مستندًا مع عرض CSS. |
| [IDocumentStyle](./idocumentstyle/) | واجهة DocumentStyle توفر آلية يمكن من خلالها استرجاع أوراق الأنماط المدمجة في مستند. المتوقع هو أنه يمكن الحصول على مثال من واجهة DocumentStyle باستخدام طرق التحويل الخاصة بالربط على مثال من واجهة Document. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | معلومات النمط المضمنة المرتبطة بالعناصر تُعرض عبر سمة style. هذا يمثل محتويات سمة STYLE لعناصر HTML (أو العناصر في مخططات أو DTDs أخرى التي تستخدم سمة STYLE بنفس الطريقة). |
| [ILinkStyle](./ilinkstyle/) | توفر واجهة LinkStyle آلية يمكن من خلالها استرجاع ورقة الأنماط من العقدة المسؤولة عن ربطها بالمستند. يمكن الحصول على مثال من واجهة LinkStyle باستخدام طرق التحويل الخاصة بالربط على مثال لعقدة الربط (HTMLLinkElement، HTMLStyleElement أو ProcessingInstruction في DOM Level 2). |
| [IMediaList](./imedialist/) | توفر واجهة MediaList تجريدًا لمجموعة مرتبة من الوسائط، دون تعريف أو تقييد طريقة تنفيذ هذه المجموعة. القائمة الفارغة هي نفسها القائمة التي تحتوي على الوسيط "all". |
| [IStyleSheet](./istylesheet/) | واجهة StyleSheet هي الواجهة الأساسية المجردة لأي نوع من أوراق الأنماط. تمثل ورقة نمط واحدة مرتبطة بمستند منظم. |
| [IStyleSheetList](./istylesheetlist/) | توفر واجهة StyleSheetList تجريدًا لمجموعة مرتبة من أوراق الأنماط. |
| [IViewCSS](./iviewcss/) | تمثل هذه الواجهة عرض CSS. |
## التعداد

| التعداد | الوصف |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | يحدد وضع CSSEngine |
