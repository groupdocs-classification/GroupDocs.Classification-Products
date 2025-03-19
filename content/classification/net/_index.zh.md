---
############################# 静态 ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: zh
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# 下拉菜单 ############################
supported_platforms:
  items:
    # supported_platforms 循环
    - title: ".NET"
      tag: "net"

############################# 头部 ############################
head_title: ".NET 文本和文档分类 API"
head_description: "用于文本和文档分类的 C# .NET API,使用 IAB-2、文档和情感分类法。对 PDF、DOC、DOCX、RTF 和 TXT 等各种格式的内容进行分类。"

############################# 标题 ############################
title: ".NET 文本和文档分类 API"
description: "使用多种分类法在 .NET 应用程序中对文本和文档进行分类。"
words:
  for: "适用于"

actions:
  main: "通过 NuGet 下载试用版"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "准备开始了吗?"
  description: "免费试用 GroupDocs.Classification 功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "查看新功能"
  downloads: "下载"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "在 C# 中使用 IAB-2 分类法对 PDF 进行分类"
  more: "更多示例"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // 创建 Classifier 的实例
    var classifier = new GroupDocs.Classification.Classifier();

    // 使用 IAB-2 分类法对 PDF 文档进行分类
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // 打印最佳类别名称和概率
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# 概述 ############################
overview:
  enable: true
  title: "GroupDocs.Classification 概述"
  description: "使用各种分类法进行自动文本和文档分类的 .NET 解决方案。"
  features:
    # 特性循环
    - title: "使用 C# 对文本和文档进行分类"
      content: "使用 GroupDocs.Classification for .NET 轻松使用 IAB-2、文档和情感分类法对内容进行分类。"

    # 特性循环
    - title: "支持多种文件格式"
      content: "处理各种文档类型,包括 PDF、DOC、DOCX、RTF、TXT 等。"

    # 特性循环
    - title: "灵活的分类选项"
      content: "选择要返回的结果数量,并调整文档分类法的精确度/召回率平衡。"

############################# 平台 ############################
platforms:
  enable: true
  title: "平台独立性"
  description: "GroupDocs.Classification for .NET 支持以下操作系统、框架和包管理器"
  items:
    # 平台循环
    - title: "Amazon"
      image: "amazon"
    # 平台循环
    - title: "Docker"
      image: "docker"
    # 平台循环
    - title: "Windows"
      image: "windows"
    # 平台循环
    - title: "Linux"
      image: "linux"
    # 平台循环
    - title: "macOS"
      image: "finder"
    # 平台循环
    - title: ".NET"
      image: "net"
    # 平台循环
    - title: "NuGet"
      image: "nuget"

############################# 文件格式 ############################
formats:
  enable: true
  title: "支持的文件格式"
  description: |
    GroupDocs.Classification for .NET 支持以下 [文件格式](https://docs.groupdocs.com/classification/net/supported-document-formats/) 的操作。
  groups:
    # 组循环
    - color: "green"
      content: |
        ### Microsoft Office 格式
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # 组循环
    - color: "blue"
      content: |
        ### OpenDocument 和其他格式
        * **OpenOffice:** ODT, OTT
        * **固定布局:** PDF
        * **其他:** TXT

############################# 特性 ############################
features:
  enable: true
  title: "GroupDocs.Classification 特性"
  description: "使用高级分类法和选项对文本和文档进行分类。"

  items:
    # 特性循环
    - icon: "viewhtml"
      title: "多种分类法"
      content: "支持 IAB-2、文档和情感分类法,实现多样化分类。"

    # 特性循环
    - icon: "rasterize"
      title: "多语言支持"
      content: "可以对英语和中文进行情感分类。"

    # 特性循环
    - icon: "sourcecode"
      title: "可自定义结果"
      content: "指定要返回的分类结果数量。"

    # 特性循环
    - icon: "transform"
      title: "精确度控制"
      content: "调整文档分类法分类的精确度/召回率平衡。"

    # 特性循环
    - icon: "adjustment"
      title: "多种文件格式"
      content: "兼容各种文档格式,包括 PDF、DOC、DOCX、RTF 和 TXT。"

    # 特性循环
    - icon: "complex"
      title: "轻松集成"
      content: "无缝集成到任何 .NET 应用程序中,包括 ASP.NET 和 Windows 应用程序。"

############################# 代码示例 ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "GroupDocs.Classification for .NET 操作的一些典型用例"
  items:
    # 代码示例循环
    - title: "使用 IAB-2 分类法对文本进行分类"
      content: |
        此示例展示如何使用 IAB-2 分类法对原始文本进行分类:
        
        ```csharp {style=abap}
        // 创建分类请求
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "尝试文本分类"
        }, "3");

        // 获取分类结果
        var response = apiInstance.Classify(request);

        // 打印结果
        Console.WriteLine(response.ToString());
        ```
        
    # 代码示例循环
    - title: "文档的情感分析"
      content: |
        您可以使用情感分类法对文档进行情感分析:
        
        ```csharp {style=abap}
        // 创建 Classifier 的实例
        var classifier = new GroupDocs.Classification.Classifier();

        // 使用情感分类法对文档进行分类
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // 打印情感和概率
        Console.WriteLine($"情感: {response.BestClassName}");
        Console.WriteLine($"概率: {response.BestClassProbability}");
        ```

---
