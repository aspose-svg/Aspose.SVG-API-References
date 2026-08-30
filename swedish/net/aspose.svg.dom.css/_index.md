---
title: "Aspose.Svg.Dom.Css"
second_title: "Aspose.SVG för .NET API-referens"
description: "Aspose.Svg.Dom.Css-namnutrymmet är för alla CSS-relaterade manipulationer. Det fokuserar på CSS-egenskapsnamn‑värde-par som specificeras av CSS-officiella dokument."
type: docs
weight: 90
url: /sv/net/aspose.svg.dom.css/
---
Namnrummet **Aspose.Svg.Dom.Css** är för all CSS‑relaterad manipulation. Det fokuserar på CSS‑egenskaps‑namn‑värde‑par som specificeras i officiella CSS‑dokument.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Counter](./counter/) | Counter-gränssnittet används för att representera ett räknare‑ eller counters‑funktionsvärde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue-gränssnittet representerar ett enskilt CSS‑värde. Detta gränssnitt kan användas för att bestämma värdet på en specifik stil‑egenskap som för närvarande är satt i ett block eller för att explicit sätta en specifik stil‑egenskap inom blocket. En instans av detta gränssnitt kan erhållas via getPropertyCSSValue‑metoden i CSSStyleDeclaration‑gränssnittet. Ett CSSPrimitiveValue‑objekt förekommer endast i samband med en CSS‑egenskap. |
| [CSSValue](./cssvalue/) | Representerar ett enkelt eller komplext värde. Ett CSSValue‑objekt förekommer endast i samband med en CSS‑egenskap. |
| [CSSValueList](./cssvaluelist/) | CSSValueList-gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [Rect](./rect/) | Rect-gränssnittet används för att representera vilket som helst rektangelvärde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. Därför ändrar modifieringar av CSSPrimitiveValue‑objekten stil‑egenskapen. |
| [RGBColor](./rgbcolor/) | RGBColor-gränssnittet används för att representera vilket som helst RGB‑färgvärde. Detta gränssnitt speglar värdena i den underliggande stil‑egenskapen. Därför ändrar modifieringar av CSSPrimitiveValue‑objekten stil‑egenskapen. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | Tillhandahåller ett gränssnitt för manipulation av CSS2‑egenskapsvärden i samband med ett visst HTML‑element. |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule-gränssnittet representerar en @charset‑regel i ett CSS‑formatark. Värdet på kodningsattributet påverkar inte kodningen av textdata i DOM‑objekten; denna kodning är alltid UTF-16. Efter att ett formatark har lästs in är värdet på kodningsattributet det värde som finns i @charset‑regeln. Om det inte fanns någon @charset i originaldokumentet skapas inget CSSCharsetRule. Värdet på kodningsattributet kan även användas som en ledtråd för den kodning som används vid serialisering av formatarket. |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style‑regeln låter författare definiera en anpassad räknarstil. |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule-gränssnittet representerar en @font-face-regel i en CSS-stilmall. @font-face-regeln används för att hålla en uppsättning teckensnittsbeskrivningar. |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule-gränssnittet representerar en @import-regel i en CSS-stilmall. @import-regeln används för att importera stilregler från andra stilmallar. |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule-gränssnittet representerar stilregeln för en enskild nyckel. |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule-gränssnittet representerar en komplett uppsättning nyckelbilder för en enskild animation. |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule-gränssnittet representerar en marginal‑at‑regel. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule-gränssnittet representerar en @media-regel i en CSS-stilmall. En @media-regel kan användas för att avgränsa stilregler för specifika mediatyper. |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule-gränssnittet representerar en @page-regel i en CSS-stilmall. @page-regeln används för att ange dimensioner, orientering, marginaler osv. för en sidlåda för sidindelat media. |
| [ICSSRule](./icssrule/) | CSSRule-gränssnittet är det abstrakta basgränssnittet för alla typer av CSS‑uttalanden. Detta inkluderar både regeluppsättningar och at‑regler. En implementation förväntas bevara alla regler som specificerats i en CSS-stilmall, även om regeln inte känns igen av parsern. Oidentifierade regler representeras med ICSSUnknownRule‑gränssnittet. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑regler. |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration‑gränssnittet representerar ett enskilt CSS‑deklarationsblock. Detta gränssnitt kan användas för att avgöra vilka stilegenskaper som för närvarande är satta i ett block eller för att explicit sätta stilegenskaper i blocket. |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule‑gränssnittet representerar en enskild regeluppsättning i en CSS-stilmall. |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet‑gränssnittet är ett konkret gränssnitt som används för att representera en CSS‑stilmall, d.v.s. en stilmall vars innehållstyp är "text/css". |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule‑gränssnittet representerar en at‑regel som inte stöds av denna användaragenter. |
| [ICSSValueList](./icssvaluelist/) | Gränssnittet tillhandahåller abstraktionen av en ordnad samling av CSS‑värden. |
| [IDocumentCSS](./idocumentcss/) | Detta gränssnitt representerar ett dokument med en CSS‑vy. |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle‑gränssnittet tillhandahåller en mekanism för att hämta de stilmallar som är inbäddade i ett dokument. Förväntningen är att en instans av DocumentStyle‑gränssnittet kan erhållas genom att använda bindningsspecifika cast‑metoder på en instans av Document‑gränssnittet. |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | Inbäddad stilinformation som är knuten till element exponeras via style‑attributet. Detta representerar innehållet i STYLE‑attributet för HTML‑element (eller element i andra scheman eller DTD:er som använder STYLE‑attributet på samma sätt). |
| [ILinkStyle](./ilinkstyle/) | LinkStyle‑gränssnittet tillhandahåller en mekanism för att hämta en stilmall från den nod som ansvarar för att länka in den i ett dokument. En instans av LinkStyle‑gränssnittet kan erhållas med bindnings‑specifika cast‑metoder på en instans av en länknod (HTMLLinkElement, HTMLStyleElement eller ProcessingInstruction i DOM Level 2). |
| [IMediaList](./imedialist/) | MediaList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av media, utan att definiera eller begränsa hur samlingen implementeras. En tom lista är densamma som en lista som innehåller mediet "all". |
| [IStyleSheet](./istylesheet/) | StyleSheet‑gränssnittet är det abstrakta basgränssnittet för alla typer av stilmallar. Det representerar en enskild stilmall som är associerad med ett strukturerat dokument. |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList‑gränssnittet tillhandahåller abstraktionen av en ordnad samling av stilmallar. |
| [IViewCSS](./iviewcss/) | Detta gränssnitt representerar en CSS‑vy. |
## Uppräkning

| Uppräkning | Beskrivning |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | Anger CSSEngine‑läge |
