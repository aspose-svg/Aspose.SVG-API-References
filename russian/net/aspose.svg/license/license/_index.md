---
title: "Лицензия"
second_title: "Aspose.SVG для .NET справочник API"
description: "Конструктор License. Инициализирует новый экземпляр этого класса"
type: docs
weight: 10
url: /ru/net/aspose.svg/license/license/
---
## License constructor

Инициализирует новый экземпляр этого класса.

```csharp
public License()
```

## Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке основной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

файл jar компонента:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### См. также

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
