---
title: "License.SetLicense"
second_title: "Aspose.SVG for .NET API 参考"
description: "License SetLicense 方法。为组件授权"
type: docs
weight: 20
url: /zh/net/aspose.svg/license/setlicense/
---
## SetLicense(*string*) {#setlicense_1}

对组件进行授权。

```csharp
public void SetLicense(string licenseName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | String | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串切换到评估模式。 |

## 备注

尝试在以下位置查找许可证：

1. 明确路径。

2. 包含 Aspose 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明确路径。

2. 客户端调用程序集中的嵌入资源。

2. 包含 Aspose 组件 JAR 文件的文件夹。

3. 包含客户端调用 JAR 文件的文件夹。

## 示例

在此示例中，将尝试在包含组件的文件夹、调用程序集所在的文件夹、入口程序集所在的文件夹以及调用程序集的嵌入资源中，查找名为 MyLicense.lic 的许可证文件。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

组件 jar 文件：

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另请参阅

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)

---

## SetLicense(*Stream*) {#setlicense}

对组件进行授权。

```csharp
public void SetLicense(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | Stream | 包含许可证的流。 |

## 备注

使用此方法从流中加载许可证。

## 示例

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### 另请参阅

* class [License](../)
* namespace [Aspose.Svg](../../../aspose.svg/)
* assembly [Aspose.SVG](../../../)
