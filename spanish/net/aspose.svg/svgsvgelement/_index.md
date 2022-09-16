---
title: SVGSVGElement
second_title: Referencia de API de Aspose.SVG para .NET
description: Una definición de interfaz clave es la interfaz SVGSVGElement que es la interfaz que corresponde al elemento svg. Esta interfaz contiene varios métodos de utilidad misceláneos de uso común como operaciones matriciales y la capacidad de controlar el tiempo de redibujado en dispositivos de representación visual.
type: docs
weight: 3390
url: /es/net/aspose.svg/svgsvgelement/
---
## SVGSVGElement class

Una definición de interfaz clave es la interfaz SVGSVGElement, que es la interfaz que corresponde al elemento 'svg'. Esta interfaz contiene varios métodos de utilidad misceláneos de uso común, como operaciones matriciales y la capacidad de controlar el tiempo de redibujado en dispositivos de representación visual.

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [Attributes](../../aspose.svg.dom/element/attributes) { get; } | Un NamedNodeMap que contiene los atributos de este nodo (si es un Elemento) o nulo en caso contrario. |
| virtual [BaseURI](../../aspose.svg.dom/node/baseuri) { get; } | El URI base absoluto de este nodo o nulo si la implementación no pudo obtener un URI absoluto. |
| [ChildElementCount](../../aspose.svg.dom/element/childelementcount) { get; } | Devuelve el número actual de nodos de elementos que son hijos de este elemento. 0 si este elemento no tiene nodos secundarios que sean de nodeType 1. |
| [ChildNodes](../../aspose.svg.dom/node/childnodes) { get; } | Una lista de nodos que contiene todos los elementos secundarios de este nodo. Si no hay hijos, esta es una lista de nodos que no contiene nodos.. |
| [Children](../../aspose.svg.dom/element/children) { get; } | Devuelve los elementos secundarios del elemento actual. |
| [ClassList](../../aspose.svg.dom/element/classlist) { get; } | Devuelve una DOMTokenList en vivo que contiene los tokens recibidos al analizar el atributo "clase". |
| [ClassName](../../aspose.svg/svgelement/classname) { get; } | Corresponde al atributo 'clase' en el elemento dado. |
| [ClassName](../../aspose.svg.dom/element/classname) { get; set; } | El atributo de clase del elemento. Este atributo se ha renombrado debido debido a conflictos con la palabra clave "clase" expuesta por muchos idiomas. Ver la definición del atributo de clase en HTML 4.01. |
| [CurrentScale](../../aspose.svg/svgsvgelement/currentscale) { get; set; } | En un elemento svg más externo, este atributo indica el factor de escala actual en relación con la vista inicial para tener en cuenta las operaciones de ampliación y panorámica del usuario, como se describe en Ampliación y panorámica. Los atributos DOM currentScale y currentTranslate son equivalentes a la matriz 2x3 [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. Si la "ampliación" está habilitada (es decir, zoomAndPan="magnificar"), el efecto es como si se colocara una transformación adicional en el nivel más externo del fragmento del documento SVG (es decir, fuera del elemento svg más externo). Cuando se accede en un elemento 'svg' que no es un elemento svg más externo, no está definido qué comportamiento tiene este atributo. |
| [CurrentTranslate](../../aspose.svg/svgsvgelement/currenttranslate) { get; } | En un elemento svg más externo, el factor de traducción correspondiente que tiene en cuenta la "ampliación" del usuario. Cuando se accede a un elemento 'svg' que no es un elemento svg más externo, no está definido qué comportamiento tiene este atributo. |
| [FarthestViewportElement](../../aspose.svg/svggraphicselement/farthestviewportelement) { get; } | El elemento 'svg' del ancestro más lejano. Nulo si el elemento actual es el elemento svg más externo. |
| [FirstChild](../../aspose.svg.dom/node/firstchild) { get; } | El primer hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [FirstElementChild](../../aspose.svg.dom/element/firstelementchild) { get; } | Devuelve el primer nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [Height](../../aspose.svg/svgsvgelement/height) { get; } | Corresponde al atributo 'altura' en el elemento 'svg' dado. |
| [Id](../../aspose.svg/svgelement/id) { get; set; } | El valor del atributo 'id' en el elemento dado, o la cadena vacía si 'id' no está presente. |
| [InnerHTML](../../aspose.svg.dom/element/innerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el contenido del elemento. Se puede configurar para reemplazar el contenido del elemento con nodos analizados de la cadena dada. |
| [LastChild](../../aspose.svg.dom/node/lastchild) { get; } | El último hijo de este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [LastElementChild](../../aspose.svg.dom/element/lastelementchild) { get; } | Devuelve el último nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| override [LocalName](../../aspose.svg.dom/element/localname) { get; } | Devuelve la parte local del nombre calificado de este nodo. Para los nodos de cualquier tipo que no sean ELEMENT_NODE y ATTRIBUTE_NODE y los nodos creados con un método DOM Nivel 1, como Document.createElement(), esto siempre es nulo. |
| override [NamespaceURI](../../aspose.svg.dom/element/namespaceuri) { get; } | El URI del espacio de nombres de este nodo, o nulo si no se especifica. |
| [NearestViewportElement](../../aspose.svg/svggraphicselement/nearestviewportelement) { get; } | El elemento que estableció la ventana gráfica actual. A menudo, el elemento 'svg' del ancestro más cercano. Nulo si el elemento actual es el elemento svg más externo. |
| [NextElementSibling](../../aspose.svg.dom/element/nextelementsibling) { get; } | Devuelve el siguiente nodo de elemento hermano de este elemento. nulo si este elemento no tiene nodos hermanos del elemento que vienen después de este en el árbol del documento. |
| [NextSibling](../../aspose.svg.dom/node/nextsibling) { get; } | El nodo que sigue inmediatamente a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| override [NodeName](../../aspose.svg.dom/element/nodename) { get; } | El nombre de este nodo, dependiendo de su tipo. |
| override [NodeType](../../aspose.svg.dom/element/nodetype) { get; } | Un código que representa el tipo del objeto subyacente. |
| virtual [NodeValue](../../aspose.svg.dom/node/nodevalue) { get; set; } | El valor de este nodo, según su tipo. |
| [OuterHTML](../../aspose.svg.dom/element/outerhtml) { get; set; } | Devuelve un fragmento de HTML o XML que representa el elemento y su contenido. Se puede configurar para reemplazar el elemento con nodos analizados de la cadena dada. |
| virtual [OwnerDocument](../../aspose.svg.dom/node/ownerdocument) { get; } | El objeto Documento asociado con este nodo. Este es también el objeto Documento utilizado para crear nuevos nodos. Cuando este nodo es un Documento o un Tipo de documento que aún no se usa con ningún Documento, es nulo. |
| [OwnerSVGElement](../../aspose.svg/svgelement/ownersvgelement) { get; } | El elemento 'svg' del ancestro más cercano. Nulo si el elemento dado es el elemento svg más externo. |
| [ParentElement](../../aspose.svg.dom/node/parentelement) { get; } | Obtiene el padre[`Element`](../../aspose.svg.dom/element) de este nodo. |
| [ParentNode](../../aspose.svg.dom/node/parentnode) { get; } | El padre de este nodo. Todos los nodos, excepto Attr, Document, DocumentFragment, Entity y Notation pueden tener un padre. Sin embargo, si se acaba de crear un nodo y aún no se ha agregado al árbol, o si se ha eliminado del árbol, este es nulo. |
| override [Prefix](../../aspose.svg.dom/element/prefix) { get; } | El prefijo del espacio de nombres de este nodo, o nulo si no se especifica. Cuando se define como nulo, configurarlo no tiene efecto |
| [PreserveAspectRatio](../../aspose.svg/svgsvgelement/preserveaspectratio) { get; } | Corresponde al atributo 'preserveAspectRatio' en el elemento dado. |
| [PreviousElementSibling](../../aspose.svg.dom/element/previouselementsibling) { get; } | Devuelve el nodo de elemento hermano anterior de este elemento. nulo si este elemento no tiene nodos hermanos que estén antes de este en el árbol del documento. |
| [PreviousSibling](../../aspose.svg.dom/node/previoussibling) { get; } | El nodo inmediatamente anterior a este nodo. Si no existe tal nodo, esto devuelve nulo. |
| [RequiredExtensions](../../aspose.svg/svggraphicselement/requiredextensions) { get; } | Corresponde al atributo 'extensiones requeridas' en el elemento dado. |
| [RequiredFeatures](../../aspose.svg/svggraphicselement/requiredfeatures) { get; } | Corresponde al atributo 'requiredFeatures' en el elemento dado. |
| [SchemaTypeInfo](../../aspose.svg.dom/element/schematypeinfo) { get; } | La información de tipo asociada con este elemento. |
| [ShadowRoot](../../aspose.svg.dom/element/shadowroot) { get; } | Devuelve shadowRoot almacenado en este elemento o nulo si está cerrado. |
| [Style](../../aspose.svg/svgelement/style) { get; } | Corresponde al atributo 'estilo' en el elemento dado. Si la aplicación de usuario no admite estilos con CSS, este atributo siempre debe tener el valor null. |
| [SystemLanguage](../../aspose.svg/svggraphicselement/systemlanguage) { get; } | Corresponde al atributo 'systemLanguage' en el elemento dado. |
| [TagName](../../aspose.svg.dom/element/tagname) { get; } | El nombre del elemento. |
| override [TextContent](../../aspose.svg.dom/element/textcontent) { get; set; } | Este atributo devuelve el contenido de texto de este nodo y sus descendientes. Cuando se define como nulo, establecerlo no tiene ningún efecto. En la configuración, se eliminan todos los posibles elementos secundarios que este nodo pueda tener y, si la nueva cadena no está vacía o es nula, se reemplaza por un solo nodo de texto que contiene la cadena en la que se establece este atributo. |
| [Transform](../../aspose.svg/svggraphicselement/transform) { get; } | Corresponde al atributo 'transformar' en el elemento dado. |
| [ViewBox](../../aspose.svg/svgsvgelement/viewbox) { get; } | Corresponde al atributo 'viewBox' en el elemento dado. |
| [ViewportElement](../../aspose.svg/svgelement/viewportelement) { get; } | El elemento que estableció la ventana gráfica actual. A menudo, el elemento 'svg' del ancestro más cercano. Nulo si el elemento dado es el elemento svg más externo. |
| [Width](../../aspose.svg/svgsvgelement/width) { get; } | Corresponde al atributo 'ancho' en el elemento 'svg' dado. |
| [X](../../aspose.svg/svgsvgelement/x) { get; } | Corresponde al atributo 'x' en el elemento 'svg' dado. |
| [Y](../../aspose.svg/svgsvgelement/y) { get; } | Corresponde al atributo 'y' en el elemento 'svg' dado. |
| [ZoomAndPan](../../aspose.svg/svgsvgelement/zoomandpan) { get; set; } | Corresponde al atributo 'zoomAndPan' en el elemento dado. El valor debe ser una de las constantes SVG_ZOOMANDPAN_* definidas en esta interfaz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.svg.dom/eventtarget/addeventlistener)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AnimationsPaused](../../aspose.svg/svgsvgelement/animationspaused)() | Devuelve verdadero si este fragmento de documento SVG está en estado de pausa. |
| [AppendChild](../../aspose.svg.dom/node/appendchild)(Node) | Agrega el nodo newChild al final de la lista de hijos de este nodo. Si newChild ya está en el árbol, primero se elimina. |
| [AttachShadow](../../aspose.svg.dom/element/attachshadow)(ShadowRootMode) | Crea shadow root y lo adjunta al elemento actual. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)() | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CloneNode](../../aspose.svg.dom/node/clonenode)(bool) | Devuelve un duplicado de este nodo, es decir, sirve como constructor de copia genérico para nodos. El nodo duplicado no tiene padre (parentNode es nulo) y no tiene datos de usuario. |
| [CreateEvent](../../aspose.svg/svgsvgelement/createevent)(string) | Crea un[`Event`](../../aspose.svg.dom.events/event) de un tipo soportado por la implementación. |
| [CreateSVGAngle](../../aspose.svg/svgsvgelement/createsvgangle)() | Crea un objeto SVGAngle fuera de cualquier árbol de documentos. El objeto se inicializa con el valor 0 grados (sin unidades). |
| [CreateSVGLength](../../aspose.svg/svgsvgelement/createsvglength)() | Crea un objeto SVGLength fuera de cualquier árbol de documentos. El objeto se inicializa con el valor de 0 unidades de usuario. |
| [CreateSVGMatrix](../../aspose.svg/svgsvgelement/createsvgmatrix)() | Crea un objeto SVGMatrix fuera de cualquier árbol de documentos. El objeto se inicializa en la matriz de identidad. |
| [CreateSVGNumber](../../aspose.svg/svgsvgelement/createsvgnumber)() | Crea un objeto SVGNumber fuera de cualquier árbol de documentos. El objeto se inicializa con un valor de cero. |
| [CreateSVGPoint](../../aspose.svg/svgsvgelement/createsvgpoint)() | Crea un objeto SVGPoint fuera de cualquier árbol de documentos. El objeto se inicializa en el punto (0,0) en el sistema de coordenadas del usuario. |
| [CreateSVGRect](../../aspose.svg/svgsvgelement/createsvgrect)() | Crea un objeto SVGRect fuera de cualquier árbol de documentos. El objeto se inicializa de modo que todos los valores se establezcan en 0 unidades de usuario. |
| [CreateSVGTransform](../../aspose.svg/svgsvgelement/createsvgtransform)() | Crea un objeto SVGTransform fuera de cualquier árbol de documentos. El objeto se inicializa en una transformación de matriz de identidad (SVG_TRANSFORM_MATRIX). |
| [CreateSVGTransformFromMatrix](../../aspose.svg/svgsvgelement/createsvgtransformfrommatrix)(SVGMatrix) | Crea un objeto SVGTransform fuera de cualquier árbol de documentos. El objeto se inicializa en la transformación de matriz dada (es decir, SVG_TRANSFORM_MATRIX). Los valores de la matriz de parámetros se copian, el parámetro de matriz no se adopta como SVGTransform::matrix. |
| [DispatchEvent](../../aspose.svg.dom/eventtarget/dispatchevent)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.svg.dom/eventtarget/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| [GetAttribute](../../aspose.svg.dom/element/getattribute)(string) | Recupera un valor de atributo por nombre. |
| [GetAttributeNode](../../aspose.svg.dom/element/getattributenode)(string) | Recupera un nodo de atributo por nombre. |
| [GetAttributeNodeNS](../../aspose.svg.dom/element/getattributenodens)(string, string) | Recupera un nodo Attr por nombre local y URI de espacio de nombres. |
| [GetAttributeNS](../../aspose.svg.dom/element/getattributens)(string, string) | Recupera un valor de atributo por nombre local y URI de espacio de nombres. |
| [GetBBox](../../aspose.svg/svggraphicselement/getbbox)() | Devuelve el cuadro delimitador estrecho en el espacio de usuario actual (es decir, después de la aplicación del atributo 'transformar', si lo hay) en la geometría de todos los elementos gráficos contenidos, excepto los efectos de trazo, recorte, enmascaramiento y filtro). Tenga en cuenta que getBBox debe devolver el cuadro delimitador real en el momento en que se llamó al método, incluso en caso de que el elemento aún no se haya representado. |
| [GetCTM](../../aspose.svg/svggraphicselement/getctm)() | Devuelve la matriz de transformación de las unidades de usuario actuales (es decir, después de la aplicación del atributo 'transformar', si corresponde) al sistema de coordenadas de la ventana gráfica para el ViewportElement más cercano. |
| [GetCurrentTime](../../aspose.svg/svgsvgelement/getcurrenttime)() | Devuelve la hora actual en segundos relativa a la hora de inicio del fragmento de documento SVG actual. Si se llama a getCurrentTime antes de que comience la línea de tiempo del documento (por ejemplo, mediante un script que se ejecuta en un elemento 'script' antes de que se envíe el evento SVGLoad del documento), se devuelve 0. |
| [GetElementById](../../aspose.svg/svgsvgelement/getelementbyid)(string) | Busca en este fragmento de documento SVG (es decir, la búsqueda está restringida a un subconjunto del árbol del documento) para un elemento cuyo id está dado por elementId. Si se encuentra un elemento, se devuelve ese elemento. Si no existe tal elemento, devuelve nulo. El comportamiento no está definido si más de un elemento tiene este id. |
| [GetElementsByClassName](../../aspose.svg.dom/element/getelementsbyclassname)(string) | Devuelve un objeto NodeList activo que contiene todos los elementos del documento que tienen todas las clases especificadas en el argumento. http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.svg.dom/element/getelementsbytagname)(string) | Devuelve una lista de nodos de todos los elementos descendientes con un nombre de etiqueta determinado, en el orden del documento. |
| [GetElementsByTagNameNS](../../aspose.svg.dom/element/getelementsbytagnamens)(string, string) | Devuelve una lista de nodos de todos los elementos descendientes con un nombre local determinado y un URI de espacio de nombres en el orden del documento. |
| virtual [GetPlatformType](../../aspose.svg.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [GetScreenCTM](../../aspose.svg/svggraphicselement/getscreenctm)() | Devuelve la matriz de transformación de las unidades de usuario actuales (es decir, después de la aplicación del atributo 'transformar', si corresponde) al aviso del agente de usuario principal de un "píxel". Para dispositivos de visualización, idealmente esto representa un píxel de pantalla física. Para otros dispositivos o entornos en los que no se conocen los tamaños de píxeles físicos, se puede usar un algoritmo similar a la definición CSS2 de un "píxel". Tenga en cuenta que se devuelve un valor nulo si este elemento no está vinculado al árbol del documento. Este método se habría llamado más acertadamente como getClientCTM, pero el nombre getScreenCTM se mantiene por razones históricas. |
| [HasAttribute](../../aspose.svg.dom/element/hasattribute)(string) | Devuelve verdadero cuando se especifica un atributo con un nombre determinado en este elemento o tiene un valor predeterminado; de lo contrario, devuelve falso. |
| [HasAttributeNS](../../aspose.svg.dom/element/hasattributens)(string, string) | Devuelve verdadero cuando se especifica un atributo con un nombre local determinado y un URI de espacio de nombres en este elemento o tiene un valor predeterminado; de lo contrario, devuelve falso. |
| override [HasAttributes](../../aspose.svg.dom/element/hasattributes)() | Devuelve si este nodo (si es un elemento) tiene algún atributo |
| [HasChildNodes](../../aspose.svg.dom/node/haschildnodes)() | Devuelve si este nodo tiene hijos. |
| [InsertBefore](../../aspose.svg.dom/node/insertbefore)(Node, Node) | Inserta el nodo antes del nodo secundario existente. Si hijo es nulo, inserte el nodo al final de la lista de hijos. Si hijo es un objeto DocumentFragment, todos sus hijos se insertan, en el mismo orden, antes de hijo. Si el niño ya está en el árbol, primero se elimina. |
| [IsDefaultNamespace](../../aspose.svg.dom/node/isdefaultnamespace)(string) | Este método comprueba si el namespaceURI especificado es el espacio de nombres predeterminado o no. |
| [IsEqualNode](../../aspose.svg.dom/node/isequalnode)(Node) | Comprueba si dos nodos son iguales. Este método comprueba la igualdad de los nodos, no la uniformidad (es decir, si los dos nodos son referencias al mismo objeto) que se puede probar con Node.isSameNode(). Todos los nodos que son iguales también serán iguales, aunque lo contrario puede no ser cierto. |
| [IsSameNode](../../aspose.svg.dom/node/issamenode)(Node) | Devuelve si este nodo es el mismo nodo que el dado. Este método proporciona una forma de determinar si dos referencias de nodo devueltas por la implementación hacen referencia al mismo objeto. Cuando dos referencias de Nodo son referencias al mismo objeto, incluso a través de un proxy, las referencias se pueden usar de manera completamente intercambiable, de modo que todos los atributos tengan los mismos valores y llamar al mismo método DOM en cualquiera de las referencias siempre tiene exactamente el mismo efecto. |
| [LookupNamespaceURI](../../aspose.svg.dom/node/lookupnamespaceuri)(string) | Busque el URI del espacio de nombres asociado al prefijo dado, a partir de este nodo. |
| [LookupPrefix](../../aspose.svg.dom/node/lookupprefix)(string) | Busque el prefijo asociado al URI del espacio de nombres dado, a partir de este nodo. Este método ignora las declaraciones de espacios de nombres predeterminados. Consulte Búsqueda de prefijo de espacio de nombres para obtener detalles sobre el algoritmo utilizado por este método. |
| [Normalize](../../aspose.svg.dom/node/normalize)() | Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes. |
| [PauseAnimations](../../aspose.svg/svgsvgelement/pauseanimations)() | Suspende (es decir, hace una pausa) todas las animaciones actualmente en ejecución que están definidas dentro del fragmento de documento SVG correspondiente a este elemento 'svg', lo que hace que el reloj de animación correspondiente a este fragmento de documento se detenga hasta que se restablezca la pausa. |
| [QuerySelector](../../aspose.svg.dom/element/queryselector)(string) | Devuelve el primer Elemento del documento, que coincide con selector |
| [QuerySelectorAll](../../aspose.svg.dom/element/queryselectorall)(string) | Devuelve una lista de nodos de todos los elementos en el documento, que coinciden con selector |
| [Remove](../../aspose.svg.dom/element/remove)() | Elimina esta instancia. |
| [RemoveAttribute](../../aspose.svg.dom/element/removeattribute)(string) | Elimina un atributo por nombre. |
| [RemoveAttributeNode](../../aspose.svg.dom/element/removeattributenode)(Attr) | Elimina el nodo de atributo especificado. |
| [RemoveAttributeNS](../../aspose.svg.dom/element/removeattributens)(string, string) | Elimina un atributo por nombre local y URI de espacio de nombres. |
| [RemoveChild](../../aspose.svg.dom/node/removechild)(Node) | Elimina el nodo hijo indicado por oldChild de la lista de hijos y lo devuelve. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.svg.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.svg.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.svg.dom/eventtarget/removeeventlistener)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.svg.dom.events/ieventlistener) se elimina de un[`EventTarget`](../../aspose.svg.dom/eventtarget) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [ReplaceChild](../../aspose.svg.dom/node/replacechild)(Node, Node) | Reemplaza el nodo secundario oldChild con newChild en la lista de elementos secundarios y devuelve el nodo oldChild. Si newChild es un objeto DocumentFragment, oldChild se reemplaza por todos los hijos de DocumentFragment, que se insertan en el mismo orden. Si newChild ya está en el árbol, primero se elimina. |
| [SetAttribute](../../aspose.svg.dom/element/setattribute)(string, string) | Agrega un nuevo atributo. Si un atributo con ese nombre ya está presente en el elemento, su valor se cambia para ser el del valor parámetro |
| [SetAttributeNode](../../aspose.svg.dom/element/setattributenode)(Attr) | Agrega un nuevo nodo de atributo. Si un atributo con ese nombre (nodeName) ya está presente en el elemento, se reemplaza por el nuevo. |
| [SetAttributeNodeNS](../../aspose.svg.dom/element/setattributenodens)(Attr) | Agrega un nuevo atributo. Si un atributo con ese nombre local y esa URI de espacio de nombres ya está presente en el elemento, se reemplaza por el nuevo. |
| [SetAttributeNS](../../aspose.svg.dom/element/setattributens)(string, string, string) | Agrega un nuevo atributo. Si un atributo con el mismo nombre local y URI de espacio de nombres ya está presente en el elemento, su prefijo se cambia para que sea la parte del prefijo del nombre calificado y su valor se cambia para que sea el parámetro de valor. |
| [SetCurrentTime](../../aspose.svg/svgsvgelement/setcurrenttime)(float) | Ajusta el reloj para este fragmento de documento SVG, estableciendo una nueva hora actual. Si se llama a setCurrentTime antes de que comience la línea de tiempo del documento (por ejemplo, mediante la ejecución de un script en un elemento 'script' antes de que se envíe el evento SVGLoad del documento), el valor de segundos en la última invocación del método proporciona el tiempo que el documento buscará una vez que la línea de tiempo del documento haya comenzado. |
| [SetIdAttribute](../../aspose.svg.dom/element/setidattribute)(string, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| [SetIdAttributeNode](../../aspose.svg.dom/element/setidattributenode)(Attr, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| [SetIdAttributeNS](../../aspose.svg.dom/element/setidattributens)(string, string, bool) | Si el parámetro isId es verdadero, este método declara que el atributo especificado es un atributo de ID determinado por el usuario. |
| override [ToString](../../aspose.svg.dom/node/tostring)() | Devuelve unString que representa esta instancia. |
| [UnpauseAnimations](../../aspose.svg/svgsvgelement/unpauseanimations)() | Reactiva la suspensión (es decir, reanuda) las animaciones que se están ejecutando actualmente y que están definidas en el fragmento del documento SVG, lo que hace que el reloj de la animación continúe desde el momento en que se suspendió. |

### Ver también

* class [SVGGraphicsElement](../svggraphicselement)
* interface [ISVGFitToViewBox](../isvgfittoviewbox)
* interface [IDocumentEvent](../../aspose.svg.dom.events/idocumentevent)
* interface [IViewCSS](../../aspose.svg.dom.css/iviewcss)
* interface [IDocumentCSS](../../aspose.svg.dom.css/idocumentcss)
* interface [ISVGZoomAndPan](../isvgzoomandpan)
* espacio de nombres [Aspose.Svg](../../aspose.svg)
* asamblea [Aspose.SVG](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.SVG.dll -->
