---
title: "DOMException klasse"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "Aspose.Svg.Dom.DOMException klasse. De DOMException-interface vertegenwoordigt een abnormale gebeurtenis die een uitzondering wordt genoemd en optreedt als gevolg van het aanroepen van een methode of het benaderen van een eigenschap van een web‑API. Dit is in wezen hoe foutcondities worden beschreven in web‑API's."
type: docs
weight: 2790
url: /nl/net/aspose.svg.dom/domexception/
---
## DOMException class

De DOMException interface vertegenwoordigt een abnormale gebeurtenis (een uitzondering genoemd) die optreedt als gevolg van het aanroepen van een methode of het benaderen van een eigenschap van een web-API. Dit is in wezen hoe foutcondities worden beschreven in web-API's.

```csharp
public class DOMException : PlatformException
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DOMException](domexception/#constructor)(*string*) | Initialiseert een nieuw exemplaar van de `DOMException` klasse. |
| [DOMException](domexception/#constructor_1)(*string, string*) | Initialiseert een nieuw exemplaar van de `DOMException` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Code](../../aspose.svg.dom/domexception/code/) { get; } | Retourneert een waarde die een van de foutcode‑constanten bevat, of 0 als geen overeenkomt. Dit veld wordt om historische redenen gebruikt. |
| virtual [Data](../../system/exception/data/) { get; } |  |
| virtual [HelpLink](../../system/exception/helplink/) { get; set; } |  |
| [HResult](../../system/exception/hresult/) { get; set; } |  |
| [InnerException](../../system/exception/innerexception/) { get; } |  |
| override [Message](../../aspose.svg.dom/domexception/message/) { get; } | Retourneert een tekenreeks die een bericht of beschrijving weergeeft die bij de opgegeven foutnaam hoort. |
| [Name](../../aspose.svg.dom/domexception/name/) { get; } | Retourneert een tekenreeks die een van de tekenreeksen bevat die aan een foutnaam zijn gekoppeld. |
| virtual [Source](../../system/exception/source/) { get; set; } |  |
| virtual [StackTrace](../../system/exception/stacktrace/) { get; } |  |
| [TargetSite](../../system/exception/targetsite/) { get; } |  |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [ABORT_ERR](../../aspose.svg.dom/domexception/abort_err/) | De bewerking werd afgebroken. |
| const [DATA_CLONE_ERR](../../aspose.svg.dom/domexception/data_clone_err/) | Het object kan niet worden gekloond. |
| const [DOMSTRING_SIZE_ERR](../../aspose.svg.dom/domexception/domstring_size_err/) | Als het opgegeven tekstbereik niet in een DOMString past. |
| const [HIERARCHY_REQUEST_ERR](../../aspose.svg.dom/domexception/hierarchy_request_err/) | Als een Node ergens wordt ingevoegd waar deze niet thuishoort. |
| const [INDEX_SIZE_ERR](../../aspose.svg.dom/domexception/index_size_err/) | Als index of grootte negatief is, of groter dan de toegestane waarde. |
| const [INUSE_ATTRIBUTE_ERR](../../aspose.svg.dom/domexception/inuse_attribute_err/) | Als geprobeerd wordt een attribuut toe te voegen dat elders al in gebruik is. |
| const [INVALID_ACCESS_ERR](../../aspose.svg.dom/domexception/invalid_access_err/) | Als een parameter of bewerking niet wordt ondersteund door het onderliggende object. |
| const [INVALID_CHARACTER_ERR](../../aspose.svg.dom/domexception/invalid_character_err/) | Als een ongeldig of illegaal teken wordt opgegeven, bijvoorbeeld in een XML‑naam. |
| const [INVALID_EXPRESSION_ERR](../../aspose.svg.dom/domexception/invalid_expression_err/) | De expressie bevat een syntaxisfout of is anderszins geen geldige expressie volgens de regels van de specifieke XPathEvaluator, of bevat gespecialiseerde extensiefuncties of variabelen die niet door deze implementatie worden ondersteund. |
| const [INVALID_MODIFICATION_ERR](../../aspose.svg.dom/domexception/invalid_modification_err/) | Als geprobeerd wordt het type van het onderliggende object te wijzigen. |
| const [INVALID_NODE_TYPE_ERR](../../aspose.svg.dom/domexception/invalid_node_type_err/) | De opgegeven node is onjuist of heeft een onjuiste ouder voor deze bewerking. |
| const [INVALID_STATE_ERR](../../aspose.svg.dom/domexception/invalid_state_err/) | Als geprobeerd wordt een object te gebruiken dat niet, of niet langer, bruikbaar is. |
| const [NAMESPACE_ERR](../../aspose.svg.dom/domexception/namespace_err/) | Als geprobeerd wordt een object te maken of te wijzigen op een manier die onjuist is met betrekking tot namespaces. |
| const [NETWORK_ERR](../../aspose.svg.dom/domexception/network_err/) | Er trad een netwerkfout op. |
| const [NOT_FOUND_ERR](../../aspose.svg.dom/domexception/not_found_err/) | Als geprobeerd wordt een Node te refereren in een context waar deze niet bestaat. |
| const [NOT_SUPPORTED_ERR](../../aspose.svg.dom/domexception/not_supported_err/) | Als de implementatie het gevraagde type object of bewerking niet ondersteunt. |
| const [NO_DATA_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_data_allowed_err/) | Als gegevens worden opgegeven voor een Node die geen gegevens ondersteunt. |
| const [NO_MODIFICATION_ALLOWED_ERR](../../aspose.svg.dom/domexception/no_modification_allowed_err/) | Als geprobeerd wordt een object te wijzigen waar wijzigingen niet zijn toegestaan. |
| const [QUOTA_EXCEEDED_ERR](../../aspose.svg.dom/domexception/quota_exceeded_err/) | Het quotum is overschreden. |
| const [SECURITY_ERR](../../aspose.svg.dom/domexception/security_err/) | De bewerking is onveilig. |
| const [SYNTAX_ERR](../../aspose.svg.dom/domexception/syntax_err/) | Als een ongeldige of illegale tekenreeks is opgegeven. |
| const [TIMEOUT_ERR](../../aspose.svg.dom/domexception/timeout_err/) | De bewerking heeft een time‑out. |
| const [TYPE_ERR](../../aspose.svg.dom/domexception/type_err/) | De expressie kan niet worden geconverteerd om het opgegeven type te retourneren. |
| const [TYPE_MISMATCH_ERR](../../aspose.svg.dom/domexception/type_mismatch_err/) | Als het type van een object niet compatibel is met het verwachte type van de parameter die aan het object is gekoppeld. |
| const [URL_MISMATCH_ERR](../../aspose.svg.dom/domexception/url_mismatch_err/) | De opgegeven URL komt niet overeen met een andere URL. |
| const [VALIDATION_ERR](../../aspose.svg.dom/domexception/validation_err/) | Als een aanroep van een methode zoals insertBefore of removeChild de Node ongeldig zou maken met betrekking tot "partial validity", wordt deze uitzondering opgegooid en wordt de bewerking niet uitgevoerd. Deze code wordt gebruikt in [DOM Level 3 Validation]. Raadpleeg deze specificatie voor meer informatie. |
| const [WRONG_DOCUMENT_ERR](../../aspose.svg.dom/domexception/wrong_document_err/) | Als een Node wordt gebruikt in een ander document dan het document dat het heeft aangemaakt (dat het niet ondersteunt). |

### Zie ook

* class [PlatformException](../../aspose.svg/platformexception/)
* namespace [Aspose.Svg.Dom](../../aspose.svg.dom/)
* assembly [Aspose.SVG](../../)
