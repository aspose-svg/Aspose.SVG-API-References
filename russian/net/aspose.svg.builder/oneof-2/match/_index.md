---
title: "OneOf-2.Match"
second_title: "Aspose.SVG для .NET справочник API"
description: "Метод Match класса OneOf. Выполняет одну из предоставленных функций в зависимости от базового типа значения"
type: docs
weight: 20
url: /ru/net/aspose.svg.builder/oneof-2/match/
---
## OneOf<T1,T2>.Match<TResult> method

Выполняет одну из предоставленных функций в зависимости от базового типа значения.

```csharp
public TResult Match<TResult>(Func<T1, TResult> func1, Func<T2, TResult> func2)
```

| Параметр | Описание |
| --- | --- |
| TResult | Тип возвращаемого значения функций. |
| func1 | Функция, которую следует выполнить, если значение имеет тип T1. |
| func2 | Функция, которую следует выполнить, если значение имеет тип T2. |

### Возвращаемое значение

Результат выполненной функции.

### См. также

* class [OneOf&lt;T1,T2&gt;](../)
* namespace [Aspose.Svg.Builder](../../../aspose.svg.builder/)
* assembly [Aspose.SVG](../../../)
