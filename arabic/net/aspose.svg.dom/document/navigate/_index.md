---
title: "Document.Navigate"
second_title: "مرجع API لـ Aspose.SVG لـ .NET"
description: "طريقة Document Navigate. تُحمّل المستند من عنوان URL المحدد (Uniform Resource Locator) إلى النسخة الحالية مع استبدال المحتوى السابق"
type: docs
weight: 1010
url: /ar/net/aspose.svg.dom/document/navigate/
---
## Navigate(*string*) {#navigate_8}

يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string address)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | String | عنوان المستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/)*) {#navigate_2}

يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(Url url)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | عنوان URL للمستند. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string*) {#navigate_11}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string content, string baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | String | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/)*) {#navigate_9}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | String | محتوى المستند. |
| baseUri | عنوان URL | عنوان URI الأساسي لحل الموارد النسبية. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string*) {#navigate_6}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```csharp
public void Navigate(Stream content, string baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/)*) {#navigate_4}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```csharp
public void Navigate(Stream content, Url baseUri)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى المستند. |
| baseUri | عنوان URL | عنوان URI الأساسي لحل الموارد النسبية. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/)*) {#navigate}

يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(RequestMessage request)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| request | RequestMessage | كائن الطلب الذي يُستخدم لتحميل محتوى المستند. |

### انظر أيضًا

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, CancellationToken*) {#navigate_13}

يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string address, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العنوان | String | عنوان المستند. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_3}

يقوم بتحميل المستند من عنوان الموارد الموحد (URL) المحدد إلى النسخة الحالية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(Url url, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| url | عنوان URL | عنوان URL للمستند. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, string, CancellationToken*) {#navigate_12}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string content, string baseUri, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | String | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*string, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_10}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(string content, Url baseUri, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | String | محتوى المستند. |
| baseUri | عنوان URL | عنوان URI الأساسي لحل الموارد النسبية. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, string, CancellationToken*) {#navigate_7}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```csharp
public void Navigate(Stream content, string baseUri, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى المستند. |
| baseUri | String | عنوان URI الأساسي لحل الموارد النسبية. سيتم دمجه مع مسار الدليل الحالي لتكوين عنوان URL مطلق. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*Stream, [Url](../../../aspose.svg/url/), CancellationToken*) {#navigate_5}

يقوم بتحميل المستند من المحتوى المحدد باستخدام baseUri لحل الموارد النسبية، مستبدلًا المحتوى السابق. يبدأ تحميل المستند من الموضع الحالي في الدفق.

```csharp
public void Navigate(Stream content, Url baseUri, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| content | Stream | محتوى المستند. |
| baseUri | عنوان URL | عنوان URI الأساسي لحل الموارد النسبية. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |
| ArgumentNullException | `baseUri` هو `null`. |

### انظر أيضًا

* class [Url](../../../aspose.svg/url/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)

---

## Navigate(*[RequestMessage](../../../aspose.svg.net/requestmessage/), CancellationToken*) {#navigate_1}

يقوم بتحميل المستند بناءً على كائن الطلب المحدد، مستبدلًا المحتوى السابق.

```csharp
public void Navigate(RequestMessage request, CancellationToken cancellationToken)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| request | RequestMessage | كائن الطلب الذي يُستخدم لتحميل محتوى المستند. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| OperationCanceledException | تم إلغاء العملية. |

### انظر أيضًا

* class [RequestMessage](../../../aspose.svg.net/requestmessage/)
* class [Document](../)
* namespace [Aspose.Svg.Dom](../../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../../)
