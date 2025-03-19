---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: zh

############################# Head ############################
head_title: "用于文档和文本分类以及情感分析的.NET API"
head_description: "强大的.NET库，使用IAB-2、文档和情感分类法进行文档和文本分类。支持多种文件格式和语言。"

############################# Header ############################
title: "文档和文本分类解决方案"
description: |
  使用我们的.NET API轻松地使用各种分类法对文档和文本进行分类。

  对多种文件格式和语言的内容进行情感分析和分类。

  只需几行代码即可将高级分类功能集成到您的.NET应用程序中。

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "选择您的平台"
  title: "平台独立性"
  description: "GroupDocs.Classification for .NET与以下操作系统和框架兼容："
  details_link_title: "了解更多"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification for .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0或更高版本  .NET Framework 4.7或更高版本
      
          # features loop
          - rows: "4"
            content: |
                    Windows Desktop (x64)  Windows Server (x64)  Windows Azure  Mac OS X x64 (10.12+)
      
          # features loop
          - rows: "3"
            content: |
                    Microsoft Visual Studio  JetBrains Rider  MonoDevelop
      
          # features loop
          - rows: "1"
            content: |
                    10+种文件格式

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Classification主要特性"
  description: "该解决方案帮助您使用各种分类法对文档和文本进行分类，执行情感分析，并将高级分类功能集成到您的.NET应用程序中。"

  items:
    # items loop
    - icon: "classify"
      title: "多种分类法"
      content: "使用IAB-2、文档和情感分类法进行分类。"

    # items loop
    - icon: "format"
      title: "广泛的格式支持"
      content: "处理各种文档格式，包括DOC、DOCX、PDF等。"

    # items loop
    - icon: "analyze"
      title: "情感分析"
      content: "对英文和中文文本进行情感分类。"

    # items loop
    - icon: "integrate"
      title: "易于集成"
      content: "只需几行代码即可集成分类功能。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "轻松分类文档"
  description: "GroupDocs.Classification代码示例"
  items:
    # code sample loop
    - title: "使用IAB-2分类法对PDF进行分类"
      content: |
       GroupDocs.Classification允许您使用IAB-2分类法轻松对PDF文档进行分类。只需指定文档路径、所需结果数量和分类法类型即可获得分类结果。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // 创建Classifier实例
            var classifier = new GroupDocs.Classification.Classifier();

            // 对文档进行分类
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // 打印最佳类别及其概率
            Console.WriteLine($"最佳类别：{response.BestClassName}，概率：{response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "支持10+种文件格式"
  description: "GroupDocs.Classification可处理各种流行的文档格式"

############################# Metrics ###############################
metrics:
  enable: true
  title: "深入的指标和洞察"
  description: "深入了解我们的详细指标，全面了解我们的性能和增长。"

  items:
    # items loop
    - number: "10+"
      title: "支持的格式"
      content: "我们支持10多种最广泛使用的文档格式。"

    # items loop
    - number: "3"
      title: "支持的分类法"
      content: "使用IAB-2、文档和情感分类法对内容进行分类。"

    # items loop
    - number: "2"
      title: "情感分析支持的语言"
      content: "对英文和中文进行情感分类。"

    # items loop
    - number: "4.7+"
      title: ".NET Framework支持"
      content: "兼容.NET Framework 4.7或更高版本和.NET Core 2.0或更高版本。"

############################# Actions ###############################
actions:
  enable: true
  title: "准备好开始了吗？"
  description: "在您的平台上免费试用GroupDocs.Classification功能。"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "常见问题"
  description: "关于GroupDocs.Classification的常见问题解答。"

  items:
    # items loop
    - question: "我可以使用GroupDocs.Classification对哪些类型的文档进行分类？"
      answer: "GroupDocs.Classification支持各种文档格式，包括Microsoft Word（DOC、DOCX、RTF）、OpenOffice（ODT）、PDF和纯文本（TXT）文件。"

    # items loop
    - question: "我可以使用GroupDocs.Classification进行情感分析吗？"
      answer: "是的，GroupDocs.Classification支持对英文和中文文本进行情感分析，允许您确定文档或文本片段的情感。"

    # items loop
    - question: "是否可以将GroupDocs.Classification集成到我现有的.NET应用程序中？"
      answer: "当然可以！GroupDocs.Classification提供了一个用户友好的API，只需几行代码就可以轻松集成到您的.NET应用程序中。它设计为与您现有的工作流程无缝协作。"

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---