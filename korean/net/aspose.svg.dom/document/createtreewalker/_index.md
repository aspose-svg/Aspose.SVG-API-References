---
title: Document.CreateTreeWalker
second_title: .NET API 참조용 Aspose.SVG
description: Document 방법. 지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다.
type: docs
weight: 940
url: /ko/net/aspose.svg.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | the TreeWalker의 루트 역할을 할 노드입니다. 이 값을 설정할 때 whatToShow 플래그 및 the NodeFilter는 고려되지 않습니다. 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 표시 여부에 관계없이 이 노드로 초기화됩니다. The 루트는 parentNode 및 nextNode와 같이 문서 구조에서 위쪽을 찾는 traversal 메서드의 중지점 역할을 합니다. 루트 must 는 null이 아니어야 합니다. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* 네임스페이스 [Aspose.Svg.Dom](../../document/)
* 집회 [Aspose.SVG](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | the TreeWalker의 루트 역할을 할 노드입니다. 이 값을 설정할 때 whatToShow 플래그 및 the NodeFilter는 고려되지 않습니다. 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 표시 여부에 관계없이 이 노드로 초기화됩니다. The 루트는 parentNode 및 nextNode와 같이 문서 구조에서 위쪽을 찾는 traversal 메서드의 중지점 역할을 합니다. 루트 must 는 null이 아니어야 합니다. |
| whatToShow | Int64 | 플래그는 tree-walker가 제공하는 트리의 논리적 보기에 나타날 수 있는 노드 유형을 지정합니다. possible SHOW_ 값 집합에 대해서는 NodeFilter의 설명을 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* 네임스페이스 [Aspose.Svg.Dom](../../document/)
* 집회 [Aspose.SVG](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

지정한 노드 에 뿌리를 둔 하위 트리에 새 TreeWalker를 만듭니다.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| root | Node | the TreeWalker의 루트 역할을 할 노드입니다. 이 값을 설정할 때 whatToShow 플래그 및 the NodeFilter는 고려되지 않습니다. 모든 노드 유형이 루트로 허용됩니다. TreeWalker의 currentNode는 표시 여부에 관계없이 이 노드로 초기화됩니다. The 루트는 parentNode 및 nextNode와 같이 문서 구조에서 위쪽을 찾는 traversal 메서드의 중지점 역할을 합니다. 루트 must 는 null이 아니어야 합니다. |
| whatToShow | Int64 | 플래그는 tree-walker가 제공하는 트리의 논리적 보기에 나타날 수 있는 노드 유형을 지정합니다. possible SHOW_ 값 집합에 대해서는 NodeFilter의 설명을 참조하십시오. 이러한 플래그는 OR을 사용하여 결합할 수 있습니다. |
| filter | INodeFilter | this TreeWalker와 함께 사용할 NodeFilter 또는 필터가 없음을 나타내는 null입니다. |

### 반환 값

새로 생성된 TreeWalker.

### 예외

| 예외 | 상태 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: 지정된 루트가 null인 경우 발생합니다. |

### 또한보십시오

* interface [ITreeWalker](../../../aspose.svg.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.svg.dom.traversal/inodefilter/)
* class [Document](../)
* 네임스페이스 [Aspose.Svg.Dom](../../document/)
* 집회 [Aspose.SVG](../../../)


