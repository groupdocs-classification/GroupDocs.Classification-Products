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
      文本情感分析和文本分类是两种强大的技术，可用于从非结构化文本数据中提取有意义的见解，并在各行各业都有大量实际应用。 这些技术可应用于广泛的用例，从社交媒体监控到客户反馈分析，再到新闻文章分类，再到检测垃圾邮件等等。
      
      情感分析是识别一段文本的情感基调的过程。 情感分析的目标是从文本中提取主观信息，以了解作者的观点或情绪状态。 该技术可应用于社交媒体监控、客户反馈分析、品牌声誉管理等，以将反馈或提及分为正面、负面或中性类别。
      
      文本分类是将文本分类为预定义类或类别的过程。 该技术可用于组织大量文本文档或从文本数据流中过滤掉不相关的信息。 文本分类可以基于不同的标准，例如语义、情感或 IAB（互动广告局）类别。 基于 IAB 的分类用于根据 IAB 类别对文本进行分类。 这种方法通常用于广告中，以对内容进行分类以进行广告定位。 例如，软件开发人员可以使用基于 IAB 的分类将网站内容分类为不同的类别，例如艺术和娱乐、健康和健身或旅游。
      
      文档分类是文本分类的一个常见用例，它涉及根据文档的内容将文档组织成不同的类别。 这在法律、金融和医疗保健等各种行业中非常有用，在这些行业中需要组织和分析大量非结构化数据。 实现文档分类的一种方法是使用 GroupDocs.Classification，这是一个功能强大的文本分类库，支持多种文档格式，包括 PDF、DOC、DOCX、RTF 和 TXT。 我们的解决方案建立在机器学习算法之上，使其高度准确可靠，使您能够根据文本数据做出更明智的决策。 作为软件开发人员，您可以使用文本情感分析和文本分类来创建范围广泛的应用程序，例如跟踪品牌提及并按情感对其进行分类的社交媒体监控工具、按主题对文章进行分类的新闻聚合器、垃圾邮件过滤器 使用文本分类来识别和过滤垃圾邮件或从非结构化文本数据中提取其他有意义的见解，并构建为用户提供价值的应用程序。
      
      GroupDocs.Classification 的最佳功能之一是它的灵活性。 这意味着您可以使用几乎任何类型的文档对文本进行分类。 GroupDocs.Classification 的另一个重要特性是其用户友好的 API。 只需几行代码，您就可以将我们的库集成到您自己的应用程序中，并立即开始对文本进行分类。 我们的 API 易于使用且文档齐全，因此您可以立即启动并运行。 通过使用 GroupDocs.Classification 进行文档分类，企业可以通过自动化组织和分析文档的过程来节省时间和资源。 这可以带来更高效的工作流程、更好的决策制定，并最终改善业务成果。
       
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
          支持不同类型的分类，包括**情感分析**、**文档**和**IAB**分类。

      # feature loop
      - icon: "fas fa-eye"
        content: |
          使用 **IAB‑2**、**Documents**、**Sentiment** 或 **Sentiment3** 分类法执行原始文本分类

      # feature loop
      - icon: "fas fa-bolt"
        content: "情感分析功能，使企业能够分析英语、中文、西班牙语和德语文本的情感基调"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "IAB（互动广告局）功能，使企业能够根据 IAB 分类法对其内容进行分类"
        
      # feature loop
      - icon: "fas fa-copy"
        content: "文档分类功能，可检测文档是否为发票、信件、简历、纸张等。"

      # feature loop
      - icon: "fas fa-code"
        content: "广泛的文档格式支持，包括 PDF、DOC、DOCX、RTF 和 TXT 以及纯文本"
        
      # feature loop
      - icon: "fas fa-eye"
        content: "由于使用托管 C# 实现，GroupDocs.Classification 可用于任何 .NET 语言，如 C#、VB.NET 和 J#"
        
      # feature loop
      - icon: "fas fa-eye"
        content: "与任何类型的应用程序轻松集成，无论是 ASP.NET Web 应用程序还是 Windows 应用程序"

      # feature loop
      - icon: "fas fa-cloud"
        content: "提供 100% 工作示例和演示以快速了解支持的功能"
        
      # feature loop
      - icon: "fas fa-bolt"
        content: "先进的 ML 算法可确保分类结果的高精度和多线程支持以提高性能"
        
      # feature loop
      - icon: "fas fa-copy"
        content: "用户友好的 API，易于使用并与其他软件应用程序集成"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "通过产品论坛提供的无限免费技术支持"

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
