---
title: Interface IWindow
second_title: Référence de l'API Aspose.SVG pour .NET
description: Aspose.Svg.Window.IWindow interface. Lobjet window représente une fenêtre contenant un document DOM.
type: docs
weight: 3820
url: /fr/net/aspose.svg.window/iwindow/
---
## IWindow interface

L'objet window représente une fenêtre contenant un document DOM.

```csharp
public interface IWindow : IDisposable, IDocumentView, IEventTarget, IGlobalEventHandlers, 
    IWindowEventHandlers, IWindowTimers
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.svg.window/iwindow/document/) { get; } | L'attribut document doit renvoyer l'objet Document le plus récent de l'objet Window. |
| [FrameElement](../../aspose.svg.window/iwindow/frameelement/) { get; } | L'objet frameElement d'un Document. |
| [Location](../../aspose.svg.window/iwindow/location/) { get; } | L'attribut location de l'interface Window doit renvoyer l'objet Location pour le document de cet objet Window. |
| [Name](../../aspose.svg.window/iwindow/name/) { get; set; } | L'attribut name de l'objet Window doit, lors de l'obtention, renvoyer le nom actuel du contexte de navigation et, lors de la définition, définir le nom du contexte de navigation sur la nouvelle valeur. |
| [Opener](../../aspose.svg.window/iwindow/opener/) { get; } | L'attribut IDL opener sur l'objet Window, lors de l'obtention, doit retourner l'objet WindowProxy du contexte de navigation à partir duquel le contexte de navigation courant a été créé (son contexte de navigation opener), s'il y en a un, s'il est toujours disponible, et si le contexte de navigation actuel n'a pas renié son ouvreur ; sinon, il doit retourner null. Au paramétrage, si la nouvelle valeur est nulle alors le contexte de navigation courant doit renier son ouvreur ; si la nouvelle valeur est autre chose, l'agent utilisateur doit appeler la méthode interne [[DefineOwnProperty]] de l'objet Window, en transmettant le nom de la propriété "opener" comme clé de propriété, et le Property Descriptor { [[Value]]: value , [[Writable]] : true, [[Enumerable]] : true, [[Configurable]] : true } comme descripteur de propriété, où value est la nouvelle valeur. |
| [Parent](../../aspose.svg.window/iwindow/parent/) { get; } | L'attribut IDL parent sur l'objet Window d'un Document dans un contexte de navigation b doit retourner l'objet WindowProxy du contexte de navigation parent, s'il y en a un (c'est-à-dire si b est un contexte de navigation enfant), ou l'objet WindowProxy du contexte de navigation contexte b lui-même, sinon (c'est-à-dire s'il s'agit d'un contexte de navigation de niveau supérieur ou d'un contexte de navigation imbriqué détaché). |
| [Self](../../aspose.svg.window/iwindow/self/) { get; } | Renvoie l'objet WindowProxy du contexte de navigation de l'objet Window. |
| [Top](../../aspose.svg.window/iwindow/top/) { get; } | L'attribut IDL supérieur de l'objet Window d'un Document dans un contexte de navigation b doit renvoyer l'objet WindowProxy de son contexte de navigation de niveau supérieur (qui serait son propre objet WindowProxy s'il s'agissait lui-même d'un contexte de navigation de niveau supérieur), si il en a un, ou sinon son propre objet WindowProxy (par exemple, s'il s'agissait d'un contexte de navigation imbriqué détaché). |
| [Window](../../aspose.svg.window/iwindow/window/) { get; } | Renvoie l'objet WindowProxy du contexte de navigation de l'objet Window. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Alert](../../aspose.svg.window/iwindow/alert/)(string) | Affiche une alerte modale avec le message donné et attend que l'utilisateur la rejette |
| [Confirm](../../aspose.svg.window/iwindow/confirm/)(string) | Affiche une invite modale OK/Annuler avec le message donné, attend que l'utilisateur le rejette et renvoie vrai si l'utilisateur clique sur OK et faux s'il clique sur Annuler. |
| [Prompt](../../aspose.svg.window/iwindow/prompt/)(string, string) | Affiche une invite de champ de texte modal avec le message donné, attend que l'utilisateur le rejette et renvoie la valeur que l'utilisateur a saisie. Si l'utilisateur annule l'invite, renvoie null à la place. Si le deuxième argument est présent, alors la valeur donnée est utilisée par défaut. |

### Voir également

* interface [IDocumentView](../../aspose.svg.dom.views/idocumentview/)
* interface [IEventTarget](../../aspose.svg.dom.events/ieventtarget/)
* interface [IGlobalEventHandlers](../../aspose.svg.dom/iglobaleventhandlers/)
* interface [IWindowEventHandlers](../iwindoweventhandlers/)
* interface [IWindowTimers](../iwindowtimers/)
* espace de noms [Aspose.Svg.Window](../../aspose.svg.window/)
* Assemblée [Aspose.SVG](../../)


