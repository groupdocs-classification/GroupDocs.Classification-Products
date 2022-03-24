---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Classification"
product_tag: "classification"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "C# .NET 文档和文本分类和情感分析 API"
head_description: "使用 c# .NET API 进行文档和原始文本分类。使用 IAB-2 和文档分类法进行分类和使用分类法进行消费者情绪分析 Sentiment."

############################# Header ############################
title: ".NET 文本和文档分类 API"
description: "使用 IAB-2、文档和情感分类法中的预定义标签或类别，为您的 .NET 应用程序提供文件和文本分类器功能."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Classification for .NET"
        image: "/border/groupdocs-classification-net.svg"
        product: "GroupDocs.Classification"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "概述"

            # button loop
            - link: "#features"
              text: "特征"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/classification"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/classification/net"
              text: "价钱"

    right:
        link_download: "https://downloads.groupdocs.com/classification"
        link_learn: "https://docs.groupdocs.com/classification/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: |
      GroupDocs.Classification for .NET 是一个直观的 C# Netstandard 2.0 API，可帮助您使用 C#、ASP.NET 和其他基于 .NET 的技术创建功能强大的文本和文档分类/分类应用程序。 API 支持四种不同类型的分类法，并通过使用 IAB-2 分配标准化文本类别、Aspose 为不同文档类型开发的文档分类法或用于情感分析的 Sentiment（和 Sentiment3）提供高级文档和文本分类。 API 分析文本、句子甚至单词，并支持对各种行业标准文档格式进行分类，包括 PDF、Microsoft Word、OpenDocument、RTF 和 TXT。情感分析（分类）支持英语、汉语、西班牙语和德语语言自动检测。 API 可以返回积极性概率，可用于 C# 中的细粒度情感分析。

      GroupDocs.Classification for .NET 使用自己的文档处理/分类引擎，不需要在系统上安装任何外部工具。它以 .NET 平台为目标开发应用程序，并支持所有可以安装 .NET 框架（包括 .NET Core）的流行操作系统（Windows、Linux、macOS）。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 .NET 的 GroupDocs.Classification 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 按路径和流分类的文档
            * 对原始文本进行分类
            * **IAB-2**, **Documents**, **Sentiment**, and **Sentiment3** taxonomies supported
            * 支持多种文档格式
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Classification for .NET [支持多种流行的文档格式](https://docs.groupdocs.com/classification/net/supported-document-formats/)。

        left:
          enable: true
          table:
            # table loop
            - title: "微软办公软件"
              content: |
                * **Word**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF

        right:
          enable: true
          table:
            # table loop
            - title: "其他格式"
              content: |
                * **Fixed Layout**: PDF
                * **OpenDocument**: ODT, OTT
                * **Text**: TXT

      ## TAB THREE ##
      tab_three:
        description: |
         GroupDocs.Classification for .NET 支持以下框架和s：
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系统"
              content: |
                * Windows 10 (x64)
                * Windows Desktop (x64)
                * Windows Server (x64)
                * Windows Azure
                * Mac OS X x64 (10.12+)
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * .NET Core 2.0 or later
                * .NET Framework 4.7 or higher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "包管理器"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "开发环境"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

############################# 特征 ############################
features:
    enable: true
    title: "高级文本和文档分类 API 功能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: |
          使用 **IAB‑2**、**Documents**、**Sentiment** 或 **Sentiment3** 分类法按路径对文档进行分类

      # feature loop
      - icon: "fas fa-eye"
        content: |
          使用 **IAB‑2**、**Documents**、**Sentiment** 或 **Sentiment3** 分类法执行原始文本分类

      # feature loop
      - icon: "fas fa-bolt"
        content: "英语、汉语、西班牙语和德语的情绪分类（分析）"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "选择要返回的分类结果的数量"

      # feature loop
      - icon: "fas fa-code"
        content: "处理 PDF、Docs、OpenOffice 和 Rich Text 文档"

      # feature loop
      - icon: "fas fa-cloud"
        content: "提供 100% 工作示例和演示，以快速了解支持的功能"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "通过产品论坛提供无限制的免费技术支持"

    more_feature:
      # more_feature_loop
      - title: "精确的文件分类"
        content: |
          GroupDocs.Classification API 支持多种文档格式的分类。下面的 C# 代码示例显示了如何通过返回 3 个最佳结果来使用 Documents 分类对当前文件夹中的 PDF 文件进行分类。

          ```cs
          // 初始化通用分类器（IAB-2、文档、情感分析
          var classifier = new GroupDocs.Classification.Classifier();

          // 使用 Documents taxonomy 对 pdf 文件进行分类并返回 3 个最可能的类别
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      # more_feature_loop
      - title: "精确的文本分类"
        content: |
          GroupDocs.Classification API 也支持文本分类。可以使用 4 种不同的分类法执行文本分类：IAB-2、Documents、Sentiment 和 Sentiment3。下面的 C# 代码示例显示了如何通过返回最佳结果来使用默认 (IAB-2) 分类法对文本进行分类。

          ```cs
          // 初始化通用分类器（IAB-2、文档、情感分析）
          var classifier = new GroupDocs.Classification.Classifier();

          // 使用 IAB-2 分类法对文本进行分类并返回最佳类别
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      # more_feature_loop
      - title: "精确的多语言情感分析"
        content: |
          GroupDocs.Classification for .NET 允许以英语、中文、西班牙语和德语执行跨域情感分析（分类）。 GroupDocs.Classification for .NET 将自动检测正确的语言。以下 C# 代码说明了情感分析 API 用例：

          ```cs
          // 初始化跨域多语言情感分类器
          // SentimentClassifier 支持英语、汉语、西班牙语和德语的多语言分类
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // 英文文本的情感分析
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // 具有相同分类器和 Sentiment3 (Negative / Neutral / Positive) 分类法的中文文本的情感分析
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: false
    title: "GroupDocs.Classification 为其他流行的开发环境提供文档查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Classification for Java"
          image: "/border/groupdocs-classification-java.svg"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
