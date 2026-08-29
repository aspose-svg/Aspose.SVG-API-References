---
title: "Aspose.Svg.Dom.Css"
second_title: "Aspose.SVG voor .NET API‑referentie"
description: "De Aspose.Svg.Dom.Css namespace is voor alle CSS-gerelateerde manipulaties. Het concentreert zich rond CSS-eigenschapnaam‑waardeparen gespecificeerd door officiële CSS‑documenten."
type: docs
weight: 90
url: /nl/net/aspose.svg.dom.css/
---
De **Aspose.Svg.Dom.Css** naamruimte is voor alle CSS‑gerelateerde manipulaties. Ze richt zich op CSS‑eigenschapnaam‑waardeparen die in officiële CSS‑documenten zijn gespecificeerd.

## Klassen

| Klasse | Beschrijving |
| --- | --- |
| [Counter](./counter/) | De Counter interface wordt gebruikt om elke teller- of counters-functiewaarde te vertegenwoordigen. Deze interface weerspiegelt de waarden in de onderliggende stijl‑eigenschap. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | De CSSPrimitiveValue interface vertegenwoordigt een enkele CSS‑waarde. Deze interface kan worden gebruikt om de waarde van een specifieke stijl‑eigenschap die momenteel in een blok is ingesteld te bepalen, of om een specifieke stijl‑eigenschap expliciet binnen het blok in te stellen. Een instantie van deze interface kan worden verkregen via de getPropertyCSSValue‑methode van de CSSStyleDeclaration interface. Een CSSPrimitiveValue‑object komt alleen voor in de context van een CSS‑eigenschap. |
| [CSSValue](./cssvalue/) | Vertegenwoordigt een eenvoudige of een complexe waarde. Een CSSValue‑object komt alleen voor in de context van een CSS‑eigenschap. |
| [CSSValueList](./cssvaluelist/) | De CSSValueList interface biedt de abstractie van een geordende collectie van CSS‑waarden. |
| [Rect](./rect/) | De Rect interface wordt gebruikt om elke rect‑waarde te vertegenwoordigen. Deze interface weerspiegelt de waarden in de onderliggende stijl‑eigenschap. Daarom wijzigen aanpassingen aan de CSSPrimitiveValue‑objecten de stijl‑eigenschap. |
| [RGBColor](./rgbcolor/) | De RGBColor interface wordt gebruikt om elke RGB‑kleurwaarde te vertegenwoordigen. Deze interface weerspiegelt de waarden in de onderliggende stijl‑eigenschap. Daarom wijzigen aanpassingen aan de CSSPrimitiveValue‑objecten de stijl‑eigenschap. |
## Interfaces

| Interface | Beschrijving |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Biedt een interface voor manipulatie van CSS2‑eigenschappen in de context van een bepaald HTML‑element. |
| [ICSSCharsetRule](./icsscharsetrule/) | De CSSCharsetRule interface vertegenwoordigt een @charset‑regel in een CSS‑stylesheet. De waarde van het encoding‑attribuut heeft geen invloed op de codering van tekstgegevens in de DOM‑objecten; deze codering is altijd UTF-16. Nadat een stylesheet is geladen, is de waarde van het encoding‑attribuut gelijk aan de waarde die in de @charset‑regel is gevonden. Als er geen @charset in het oorspronkelijke document stond, wordt er geen CSSCharsetRule aangemaakt. De waarde van het encoding‑attribuut kan ook worden gebruikt als hint voor de codering die bij het serialiseren van de stylesheet wordt gebruikt. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | De @counter-style‑regel stelt auteurs in staat om een aangepaste tellerstijl te definiëren. |
| [ICSSFontFaceRule](./icssfontfacerule/) | De CSSFontFaceRule interface vertegenwoordigt een @font-face‑regel in een CSS‑stylesheet. De @font-face‑regel wordt gebruikt om een set van font‑beschrijvingen vast te houden. |
| [ICSSImportRule](./icssimportrule/) | De CSSImportRule interface vertegenwoordigt een @import‑regel binnen een CSS‑stylesheet. De @import‑regel wordt gebruikt om stijlregels van andere stylesheets te importeren. |
| [ICSSKeyframeRule](./icsskeyframerule/) | De CSSKeyframeRule interface vertegenwoordigt de stijlregel voor een enkele key. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | De CSSKeyframesRule interface vertegenwoordigt een volledige set van keyframes voor een enkele animatie. |
| [ICSSMarginRule](./icssmarginrule/) | De CSSMarginRule interface vertegenwoordigt een margin-at-rule. |
| [ICSSMediaRule](./icssmediarule/) | De CSSMediaRule interface vertegenwoordigt een @media-regel in een CSS-stylesheet. Een @media-regel kan worden gebruikt om stijlregels voor specifieke mediatypen af te bakenen. |
| [ICSSPageRule](./icsspagerule/) | De CSSPageRule interface vertegenwoordigt een @page-regel binnen een CSS-stylesheet. De @page-regel wordt gebruikt om de afmetingen, oriëntatie, marges, enz. van een pagina‑box voor paginagestuurde media te specificeren. |
| [ICSSRule](./icssrule/) | De CSSRule interface is de abstracte basisinterface voor elk type CSS‑statement. Dit omvat zowel regelsets als at-rules. Van een implementatie wordt verwacht alle regels die in een CSS-stylesheet zijn gespecificeerd te behouden, zelfs als de regel niet door de parser wordt herkend. Niet-herkende regels worden weergegeven met behulp van de ICSSUnknownRule interface. |
| [ICSSRuleList](./icssrulelist/) | De CSSRuleList interface biedt de abstractie van een geordende collectie van CSS‑regels. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | De CSSStyleDeclaration interface vertegenwoordigt een enkel CSS-declaratieblok. Deze interface kan worden gebruikt om de stijl‑eigenschappen die momenteel in een blok zijn ingesteld te bepalen of om stijl‑eigenschappen expliciet binnen het blok in te stellen. |
| [ICSSStyleRule](./icssstylerule/) | De CSSStyleRule interface vertegenwoordigt een enkele regelset in een CSS-stylesheet. |
| [ICSSStyleSheet](./icssstylesheet/) | De CSSStyleSheet interface is een concrete interface die wordt gebruikt om een CSS-stylesheet te vertegenwoordigen, d.w.z. een stylesheet waarvan het content‑type "text/css" is. |
| [ICSSUnknownRule](./icssunknownrule/) | De CSSUnknownRule interface vertegenwoordigt een at-rule die niet door deze user agent wordt ondersteund. |
| [ICSSValueList](./icssvaluelist/) | De interface biedt de abstractie van een geordende collectie van CSS‑waarden. |
| [IDocumentCSS](./idocumentcss/) | Deze interface vertegenwoordigt een document met een CSS‑view. |
| [IDocumentStyle](./idocumentstyle/) | De DocumentStyle interface biedt een mechanisme waarmee de stylesheets die in een document zijn ingebed, kunnen worden opgehaald. De verwachting is dat een instantie van de DocumentStyle interface kan worden verkregen door binding‑specifieke cast‑methoden te gebruiken op een instantie van de Document interface. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inline‑stijl‑informatie die aan elementen is gekoppeld, wordt blootgesteld via het style‑attribuut. Dit vertegenwoordigt de inhoud van het STYLE‑attribuut voor HTML‑elementen (of elementen in andere schema's of DTD's die het STYLE‑attribuut op dezelfde manier gebruiken). |
| [ILinkStyle](./ilinkstyle/) | De LinkStyle interface biedt een mechanisme waarmee een stylesheet kan worden opgehaald van het knooppunt dat verantwoordelijk is voor het koppelen ervan aan een document. Een instantie van de LinkStyle interface kan worden verkregen met binding‑specifieke cast‑methoden op een instantie van een koppelingsknooppunt (HTMLLinkElement, HTMLStyleElement of ProcessingInstruction in DOM Level 2). |
| [IMediaList](./imedialist/) | De MediaList interface biedt de abstractie van een geordende collectie van media, zonder te definiëren of te beperken hoe deze collectie wordt geïmplementeerd. Een lege lijst is hetzelfde als een lijst die het medium "all" bevat. |
| [IStyleSheet](./istylesheet/) | De StyleSheet interface is de abstracte basisinterface voor elk type stylesheet. Het vertegenwoordigt een enkele stylesheet die is gekoppeld aan een gestructureerd document. |
| [IStyleSheetList](./istylesheetlist/) | De StyleSheetList interface biedt de abstractie van een geordende collectie van stylesheets. |
| [IViewCSS](./iviewcss/) | Deze interface vertegenwoordigt een CSS‑view. |
## Enumeratie

| Enumeratie | Beschrijving |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Specificeert CSSEngine-modus |
