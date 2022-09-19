---
title: ProcessingInstruction
second_title: Référence de l'API Aspose.SVG pour .NET
description: Le ProcessingInstruction représente une instruction de traitement utilisée en XML comme moyen de conserver des informations spécifiques au processeur dans le texte du document.
type: docs
weight: 1170
url: /fr/net/aspose.svg.dom/processinginstruction/
---
## ProcessingInstruction class

Le ProcessingInstruction représente une "instruction de traitement", utilisée en XML comme moyen de conserver des informations spécifiques au processeur dans le texte du document.

```csharp
public class ProcessingInstruction : CharacterData
```

## Propriétés

| Nom | La description |
| --- | --- |
| virtual [Attributes](../../aspose.svg.dom/node/attributes) { get; } | Un NamedNodeMap contenant les attributs de ce nœud (si c'est un Element) ou null sinon. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri) { get; } | L'URI de base absolu de ce nœud ou null si l'implémentation n'a pas pu obtenir d'URI absolu. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | Une NodeList qui contient tous les enfants de ce nœud. S'il n'y a pas d'enfants, il s'agit d'une NodeList ne contenant aucun nœud.. |
| virtual [Data](../../aspose.svg.dom/characterdata/data) { get; set; } | Les données de caractères du nœud qui implémente cette interface. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | Le premier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | Le dernier enfant de ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [Length](../../aspose.svg.dom/characterdata/length) { get; } | Le nombre d'unités 16 bits disponibles via les données et la méthode substringData ci-dessous. Cela peut avoir la valeur zéro, c'est-à-dire que les nœuds CharacterData peuvent être vides. |
| virtual [LocalName](../../aspose.svg.dom/node/localname) { get; } | Renvoie la partie locale du nom qualifié de ce nœud. Pour les nœuds de tout type autre que ELEMENT_NODE et ATTRIBUTE_NODE et les nœuds créés avec une méthode DOM Niveau 1, comme Document.createElement(), c'est toujours null. |
| virtual [NamespaceURI](../../aspose.svg.dom/node/namespaceuri) { get; } | L'URI de l'espace de noms de ce nœud, ou null s'il n'est pas spécifié. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | Le nœud suivant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| override [NodeName](../../aspose.svg.dom/processinginstruction/nodename) { get; } | Le nom de ce nœud, en fonction de son type. |
| override [NodeType](../../aspose.svg.dom/processinginstruction/nodetype) { get; } | Un code représentant le type de l'objet sous-jacent. |
| override [NodeValue](../../aspose.svg.dom/processinginstruction/nodevalue) { get; set; } | La valeur de ce nœud, en fonction de son type. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument) { get; } | L'objet Document associé à ce nœud. Il s'agit également de l'objet Document utilisé pour créer de nouveaux nœuds. Lorsque ce nœud est un Document ou un DocumentType qui n'est pas encore utilisé avec un Document, c'est null. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | Obtient le parent[`Element`](../element) de ce nœud. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | Le parent de ce nœud. Tous les nœuds, à l'exception de Attr, Document, DocumentFragment, Entity et Notation peuvent avoir un parent. Cependant, si un nœud vient d'être créé et n'a pas encore été ajouté à l'arbre, ou s'il a été supprimé de l'arbre, c'est null. |
| virtual [Prefix](../../aspose.svg.dom/node/prefix) { get; set; } | Le préfixe d'espace de noms de ce nœud, ou null s'il n'est pas spécifié. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | Le nœud précédant immédiatement ce nœud. S'il n'y a pas de tel nœud, cela renvoie null. |
| [Target](../../aspose.svg.dom/processinginstruction/target) { get; } | La cible de cette instruction de traitement. |
| override [TextContent](../../aspose.svg.dom/processinginstruction/textcontent) { get; set; } | Cet attribut renvoie le contenu textuel de ce nœud et de ses descendants. Lorsqu'il est défini comme étant nul, sa définition n'a aucun effet. Lors de la définition, tous les enfants possibles que ce nœud peut avoir sont supprimés et, si la nouvelle chaîne n'est pas vide ou nulle, remplacés par un seul nœud de texte contenant la chaîne à laquelle cet attribut est défini. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Cette méthode permet l'enregistrement des écouteurs d'événement sur la cible de l'événement. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | Ajoute le nœud newChild à la fin de la liste des enfants de ce nœud. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| virtual [AppendData](../../aspose.svg.dom/characterdata/appenddata)(string) | Ajoutez la chaîne à la fin des données de caractères du nœud. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)() | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)(bool) | Renvoie un doublon de ce nœud, c'est-à-dire qu'il sert de constructeur de copie générique pour les nœuds. Le nœud dupliqué n'a pas de parent (parentNode est nul) et pas de données utilisateur. |
| virtual [DeleteData](../../aspose.svg.dom/characterdata/deletedata)(int, int) | Supprimer une plage d'unités 16 bits du nœud. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Cette méthode permet de répartir les événements dans le modèle d'événement des implémentations. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Effectue des tâches définies par l'application associées à la libération, à la libération ou à la réinitialisation des ressources non gérées. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| virtual [HasAttributes](../../aspose.svg.dom/node/hasattributes)() | Renvoie si ce nœud (s'il s'agit d'un élément) a des attributs |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | Renvoie si ce nœud a des enfants. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | Insère le nœud avant le nœud enfant existant. Si enfant est nul, insère le nœud à la fin de la liste des enfants. Si enfant est un objet DocumentFragment, tous ses enfants sont insérés, dans le même ordre, avant enfant. Si l'enfant est déjà dans l'arborescence, il est d'abord supprimé. |
| virtual [InsertData](../../aspose.svg.dom/characterdata/insertdata)(int, string) | Insérer une chaîne à l'offset d'unité de 16 bits spécifié. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | Cette méthode vérifie si le namespaceURI spécifié est l'espace de noms par défaut ou non. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | Teste si deux nœuds sont égaux. Cette méthode teste l'égalité des nœuds, pas la similitude (c'est-à-dire si les deux nœuds sont des références au même objet) qui peut être testée avec Node.isSameNode(). Tous les nœuds identiques seront également égaux, bien que l'inverse puisse ne pas être vrai. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | Renvoie si ce nœud est le même nœud que celui donné. Cette méthode permet de déterminer si deux références de nœud renvoyées par l'implémentation font référence au même objet. Lorsque deux références de nœud sont des références au même objet, même via un proxy, les références peuvent être utilisées de manière complètement interchangeable, de sorte que tous les attributs ont les mêmes valeurs et que l'appel de la même méthode DOM sur l'une ou l'autre des références a toujours exactement le même effet. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | Recherchez l'URI de l'espace de noms associé au préfixe donné, à partir de ce nœud. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | Recherchez le préfixe associé à l'URI de l'espace de noms donné, à partir de ce nœud. Les déclarations d'espace de noms par défaut sont ignorées par cette méthode. Voir Recherche de préfixe d'espace de noms pour plus de détails sur l'algorithme utilisé par cette méthode. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | Met tous les nœuds de texte dans toute la profondeur de la sous-arborescence sous ce nœud, y compris les nœuds d'attribut, dans une forme "normale" où seule la structure (par exemple, les éléments, les commentaires, les instructions de traitement, les sections CDATA et les références d'entité) sépare le texte nœuds, c'est-à-dire qu'il n'y a ni nœuds Text adjacents ni nœuds Text vides. Cela peut être utilisé pour s'assurer que la vue DOM d'un document est la même que s'il avait été enregistré et rechargé, et est utile lorsque des opérations (telles que les recherches XPointer [XPointer]) qui dépendent d'une arborescence de document particulière doivent être utilisé. Si le paramètre "normalize-characters" de l'objet DOMConfiguration attaché au Node.ownerDocument est vrai, cette méthode normalisera également complètement les caractères des nœuds Text. |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | Supprime le nœud enfant indiqué par oldChild de la liste des enfants et le renvoie. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Cette méthode permet de supprimer les écouteurs d'événement de la cible de l'événement. Si un[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) est retiré d'un[`EventTarget`](../eventtarget) pendant qu'il traite un événement, il ne sera pas déclenché par les actions en cours. Les écouteurs d'événement ne peuvent jamais être invoqués après avoir été supprimés. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | Remplace le nœud enfant oldChild par newChild dans la liste des enfants et renvoie le nœud oldChild. Si newChild est un objet DocumentFragment, oldChild est remplacé par tous les enfants DocumentFragment, qui sont insérés dans le même ordre. Si le newChild est déjà dans l'arborescence, il est d'abord supprimé. |
| virtual [ReplaceData](../../aspose.svg.dom/characterdata/replacedata)(int, int, string) | Remplacez les caractères commençant au décalage d'unité de 16 bits spécifié par la chaîne spécifiée. |
| virtual [SubstringData](../../aspose.svg.dom/characterdata/substringdata)(int, int) | Extrait une plage de données du nœud. |
| override [ToString](../../aspose.svg.dom/characterdata/tostring)() | Renvoie unString qui représente cette instance. |

### Voir également

* class [CharacterData](../characterdata)
* espace de noms [Aspose.Svg.Dom](../../aspose.svg.dom)
* Assemblée [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
