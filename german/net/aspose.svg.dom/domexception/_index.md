---
title: "DOMException‑Klasse"
second_title: "Aspose.SVG für .NET API-Referenz"
description: "Aspose.Svg.Dom.DOMException Klasse. Das DOMException‑Interface stellt ein abnormalen Ereignis namens Ausnahme dar, das als Ergebnis des Aufrufs einer Methode oder des Zugriffs auf eine Eigenschaft einer Web‑API auftritt. So werden Fehlersituationen in Web‑APIs grundsätzlich beschrieben."
type: docs
weight: 2790
url: /de/net/aspose.svg.dom/domexception/
---
## DOMException class

Das DOMException-Interface repräsentiert ein abnormales Ereignis (eine Ausnahme), das als Ergebnis eines Methodenaufrufs oder des Zugriffs auf eine Eigenschaft einer Web-API auftritt. Dies ist im Wesentlichen die Art und Weise, wie Fehlbedingungen in Web-APIs beschrieben werden.

```csharp
public class DOMException : PlatformException
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | Initialisiert eine neue Instanz der `DOMException`‑Klasse. |
| [DOMException](domexception/#constructor_1)(*string, string*) | Initialisiert eine neue Instanz der `DOMException`‑Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Gibt einen Wert zurück, der eine der Fehlercode‑Konstanten enthält, oder 0, wenn keine zutrifft. Dieses Feld wird aus historischen Gründen verwendet. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Gibt eine Zeichenkette zurück, die eine Nachricht oder Beschreibung darstellt, die mit dem angegebenen Fehlernamen verknüpft ist. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Gibt eine Zeichenkette zurück, die einen der mit einem Fehlernamen verknüpften Zeichenketten enthält. |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | Der Vorgang wurde abgebrochen. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | Das Objekt kann nicht geklont werden. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | Wenn der angegebene Textbereich nicht in einen DOMString passt. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | Wenn ein beliebiger Knoten an einer Stelle eingefügt wird, an die er nicht gehört. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | Wenn Index oder Größe negativ ist oder den zulässigen Wert überschreitet. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | Wenn versucht wird, ein Attribut hinzuzufügen, das bereits an anderer Stelle verwendet wird. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | Wenn ein Parameter oder eine Operation vom zugrunde liegenden Objekt nicht unterstützt wird. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | Wenn ein ungültiges oder unzulässiges Zeichen angegeben wird, z. B. in einem XML‑Namen. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | Der Ausdruck hat einen Syntaxfehler oder ist anderweitig kein gültiger Ausdruck gemäß den Regeln des jeweiligen XPathEvaluator oder enthält spezialisierte Erweiterungsfunktionen oder Variablen, die von dieser Implementierung nicht unterstützt werden. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | Wenn versucht wird, den Typ des zugrunde liegenden Objekts zu ändern. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | Der bereitgestellte Knoten ist ungültig oder hat einen falschen Vorfahren für diesen Vorgang. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | Wenn versucht wird, ein Objekt zu verwenden, das nicht (oder nicht mehr) nutzbar ist. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | Wenn versucht wird, ein Objekt zu erstellen oder zu ändern, und dies in Bezug auf Namespaces inkorrekt ist. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | Ein Netzwerkfehler ist aufgetreten. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | Wenn versucht wird, einen Node in einem Kontext zu referenzieren, in dem er nicht existiert. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | Wenn die Implementierung den angeforderten Objekttyp oder die Operation nicht unterstützt. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | Wenn für einen Node Daten angegeben werden, der keine Daten unterstützt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | Wenn versucht wird, ein Objekt zu ändern, bei dem Änderungen nicht erlaubt sind. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | Das Kontingent wurde überschritten. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | Der Vorgang ist unsicher. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | Wenn eine ungültige oder unzulässige Zeichenkette angegeben wird. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | Der Vorgang hat ein Zeitlimit überschritten. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | Der Ausdruck kann nicht in den angegebenen Typ konvertiert werden. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | Wenn der Typ eines Objekts mit dem erwarteten Typ des mit dem Objekt verbundenen Parameters inkompatibel ist. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | Die angegebene URL stimmt nicht mit einer anderen URL überein. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | Wenn ein Aufruf einer Methode wie insertBefore oder removeChild den Node in Bezug auf \"partial validity\" ungültig machen würde, wird diese Ausnahme ausgelöst und der Vorgang nicht ausgeführt. Dieser Code wird in [DOM Level 3 Validation] verwendet. Weitere Informationen finden Sie in dieser Spezifikation. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Wenn ein Node in einem anderen Dokument verwendet wird als dem, das ihn erstellt hat (das ihn nicht unterstützt). |

### Siehe auch

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
