---
title: "SVGDocument.Save"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Save في SVGDocument. تحفظ المستند إلى ملف محلي محدد بواسطة url. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور يُنشأ اسمه كـ output_file_name _files. إذا انتهى url المحدد بـ .svgz سيتم حفظ المستند كملف SVGZ مضغوط"
type: docs
weight: 90
url: /ar/net/aspose.svg/svgdocument/save/
---
## Save(*[Url](../../url/)*) {#save_4}

يحفظ المستند إلى ملف محلي محدد بـ `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". إذا انتهى `url` المحدد بـ ".svgz"، سيتم حفظ المستند كملف SVGZ مضغوط.

```csharp
public void Save(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | URL محلي لملف الإخراج. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `url` المحدد ليس عنوان URL ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../url/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string*) {#save_8}

يحفظ المستند إلى ملف محلي محدد بالمسار `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، يُنشأ اسمه كالتالي: output_file_name + \"_files\". إذا انتهى `url` المحدد بـ ".svgz"، سيتم حفظ المستند كملف SVGZ مضغوط.

```csharp
public void Save(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار محلي لملف الإخراج. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)*) {#save}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |

### انظر أيضًا

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_9}

يحفظ المستند إلى ملف محلي محدد بواسطة `path`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيتم إنشاء اسمه كالتالي: output_file_name + "_files".

```csharp
public void Save(string path, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار محلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | التنسيق الذي يُحفظ به المستند. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرفع إذا كان `path` المحدد ليس مسار ملف محلي صالح. |
| ArgumentOutOfRangeException | يُرفع عندما تكون قيمة *saveFormat* المحددة غير معروفة من قبل التنفيذ الحالي. |

### انظر أيضًا

* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_1}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveFormat | SVGSaveFormat | التنسيق الذي يُحفظ به المستند. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يُرفع عندما تكون قيمة *saveFormat* المحددة غير معروفة من قبل التنفيذ الحالي. |

### انظر أيضًا

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_10}

يحفظ المستند كملف `.svg` إلى المسار المحلي المحدد بواسطة *path*. يتم كتابة أي موارد خارجية إلى مجلد شقيق يُسمى `{output_file_name}_files`.

```csharp
public void Save(string path, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار المطلق أو النسبي للملف `.svg` المستهدف. |
| saveOptions | SVGSaveOptions | الخيارات التي تتحكم في تسلسل plain-SVG. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى إذا *path* ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_2}

يحفظ محتوى المستند والموارد باستخدام [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/). |
| saveOptions | SVGSaveOptions | خيارات حفظ SVG. |

### انظر أيضًا

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)*) {#save_5}

يحفظ المستند إلى ملف محلي محدد بـ `url`. سيتم حفظ جميع الموارد المستخدمة في هذا المستند في مجلد مجاور، سيكون اسمه مُنشأ كالتالي: output_file_name + "_files".

```csharp
public void Save(Url url, SVGSaveFormat saveFormat)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | URL محلي لملف الإخراج. |
| saveFormat | SVGSaveFormat | التنسيق الذي يُحفظ به المستند. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى عندما *url* لا يمثل موقع ملف محلي صالح (مثال: يكون null أو نسبيًا أو يشير إلى مخطط غير ملف). |
| ArgumentOutOfRangeException | يُرمى عندما لا يتم التعرف على قيمة *saveFormat* المقدمة من قبل التنفيذ الحالي. |

### انظر أيضًا

* class [Url](../../url/)
* enum [SVGSaveFormat](../../../aspose.svg.saving/svgsaveformat/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)*) {#save_6}

يحفظ المستند كملف `.svg` إلى *url*. يتم وضع جميع الموارد الخارجية في مجلد شقيق يُسمى `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | المسار المحلي للملف `.svg` المستهدف. |
| saveOptions | SVGSaveOptions | الخيارات التي تتحكم في تسلسل plain-SVG. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى إذا *url* ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../url/)
* class [SVGSaveOptions](../../../aspose.svg.saving/svgsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[Url](../../url/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_7}

يحفظ المستند كملف `.svgz` مضغوط إلى *url*. يتم وضع جميع الموارد الخارجية في مجلد شقيق يُسمى `{output_file_name}_files`.

```csharp
public void Save(Url url, SVGZSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | المسار المحلي للملف `.svgz` المستهدف. |
| saveOptions | SVGZSaveOptions | الخيارات التي تتحكم في تسلسل SVGZ. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى إذا *url* ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [Url](../../url/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*[ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/), [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_3}

يحفظ محتوى المستند والموارد المرتبطة باستخدام [`ResourceHandler`](../../../aspose.svg.saving.resourcehandlers/resourcehandler/).

```csharp
public void Save(ResourceHandler resourceHandler, SVGZSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| resourceHandler | ResourceHandler | معالج الموارد لإدارة موارد المستند، مثل نظام الملفات أو التخزين القائم على الذاكرة. |
| saveOptions | SVGZSaveOptions | الخيارات التي تحدد معلمات حفظ إضافية، مثل تفضيلات التحويل إلى متجهات. |

### انظر أيضًا

* class [ResourceHandler](../../../aspose.svg.saving.resourcehandlers/resourcehandler/)
* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## Save(*string, [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)*) {#save_11}

يحفظ المستند كملف `.svgz` مضغوط إلى المسار المحلي المحدد بواسطة *path*. يتم كتابة أي موارد خارجية إلى مجلد شقيق يُسمى `{output_file_name}_files`.

```csharp
public void Save(string path, SVGZSaveOptions saveOptions)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار المطلق أو النسبي للملف `.svgz` المستهدف. |
| saveOptions | SVGZSaveOptions | الخيارات التي تتحكم في تسلسل SVGZ. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُرمى إذا *path* ليس مسار ملف محلي صالح. |

### انظر أيضًا

* class [SVGZSaveOptions](../../../aspose.svg.saving/svgzsaveoptions/)
* class [SVGDocument](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
