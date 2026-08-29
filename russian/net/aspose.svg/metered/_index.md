---
title: "Класс Metered"
second_title: "Aspose.SVG для .NET справочник API"
description: "Класс Aspose.Svg.Metered. Предоставляет методы для установки метрированного ключа."
type: docs
weight: 4270
url: /ru/net/aspose.svg/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../aspose.svg/metered/setmeteredkey/)(*string, string*) | Устанавливает публичный и приватный метрированный ключ. Если вы приобретаете метрированную лицензию, при запуске приложения следует вызвать этот API; обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и проходит более 24 часов, лицензия будет переключена в режим оценки. Чтобы избежать этого, регулярно проверяйте статус лицензии; если он находится в режиме оценки, вызовите этот API снова. |
| static [GetConsumptionCredit](../../aspose.svg/metered/getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../aspose.svg/metered/getconsumptionquantity/)() | Получает размер файла потребления |
| static [IsMeteredLicensed](../../aspose.svg/metered/ismeteredlicensed/)() | Проверьте, лицензировано ли metered |

## Примеры

В этом примере будет предпринята попытка установить публичный и приватный ключ metered

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### См. также

* namespace [Aspose.Svg](../../aspose.svg/)
* assembly [Aspose.SVG](../../)
