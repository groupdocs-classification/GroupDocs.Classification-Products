---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: ja
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# Head ############################
head_title: "テキストおよびドキュメント分類のための.NET API"
head_description: "IAB-2、ドキュメント、およびセンチメントタクソノミーを使用してテキストおよびドキュメントを分類するためのC# .NET API。PDF、DOC、DOCX、RTF、TXTなど様々な形式のコンテンツを分類します。"

############################# Header ############################
title: ".NETテキストおよびドキュメント分類API"
description: "複数のタクソノミーを使用して.NETアプリケーションでテキストとドキュメントを分類します。"
words:
  for: "用"

actions:
  main: "NuGet経由でトライアル版をダウンロード"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "始める準備はできていますか？"
  description: "GroupDocs.Classificationの機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能をご覧ください"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "C#でIAB-2タクソノミーを使用してPDFを分類する"
  more: "その他の例"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Classifierのインスタンスを作成
    var classifier = new GroupDocs.Classification.Classifier();

    // IAB-2タクソノミーを使用してPDFドキュメントを分類
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // 最良のクラス名と確率を出力
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Classification概要"
  description: "様々なタクソノミーを使用した自動テキストおよびドキュメント分類のための.NETソリューション。"
  features:
    # feature loop
    - title: "C#でテキストとドキュメントを分類"
      content: "GroupDocs.Classification for .NETを使用して、IAB-2、ドキュメント、およびセンチメントタクソノミーでコンテンツを簡単に分類します。"

    # feature loop
    - title: "複数のファイル形式のサポート"
      content: "PDF、DOC、DOCX、RTF、TXTなど、様々なドキュメントタイプを処理します。"

    # feature loop
    - title: "柔軟な分類オプション"
      content: "返す結果の数を選択し、ドキュメントタクソノミーの精度/再現率のバランスを調整します。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム独立性"
  description: "GroupDocs.Classification for .NETは以下のオペレーティングシステム、フレームワーク、およびパッケージマネージャーをサポートしています"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: ".NET"
      image: "net"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "サポートされているファイル形式"
  description: |
    GroupDocs.Classification for .NETは以下の[ファイル形式](https://docs.groupdocs.com/classification/net/supported-document-formats/)での操作をサポートしています。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office形式
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### OpenDocumentおよびその他の形式
        * **OpenOffice:** ODT, OTT
        * **固定レイアウト:** PDF
        * **その他:** TXT

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Classificationの機能"
  description: "高度なタクソノミーとオプションを使用してテキストとドキュメントを分類します。"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "複数のタクソノミー"
      content: "多様な分類のためにIAB-2、ドキュメント、およびセンチメントタクソノミーをサポートします。"

    # feature loop
    - icon: "rasterize"
      title: "多言語サポート"
      content: "英語と中国語の両方でセンチメント分類を実行します。"

    # feature loop
    - icon: "sourcecode"
      title: "カスタマイズ可能な結果"
      content: "返す分類結果の数を指定します。"

    # feature loop
    - icon: "transform"
      title: "精度制御"
      content: "ドキュメントタクソノミー分類の精度/再現率のバランスを調整します。"

    # feature loop
    - icon: "adjustment"
      title: "複数のファイル形式"
      content: "PDF、DOC、DOCX、RTF、TXTなど、様々なドキュメント形式と互換性があります。"

    # feature loop
    - icon: "complex"
      title: "簡単な統合"
      content: "ASP.NETやWindowsアプリを含む任意の.NETアプリケーションにシームレスに統合します。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "GroupDocs.Classification for .NETの典型的な操作のいくつかの使用例"
  items:
    # code sample loop
    - title: "IAB-2タクソノミーを使用してテキストを分類"
      content: |
        この例は、IAB-2タクソノミーを使用して生のテキストを分類する方法を示しています：
        
        ```csharp {style=abap}
        // 分類リクエストを作成
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "テキスト分類を試す"
        }, "3");

        // 分類結果を取得
        var response = apiInstance.Classify(request);

        // 結果を出力
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "ドキュメントのセンチメント分析"
      content: |
        センチメントタクソノミーを使用してドキュメントのセンチメント分析を実行できます：
        
        ```csharp {style=abap}
        // Classifierのインスタンスを作成
        var classifier = new GroupDocs.Classification.Classifier();

        // センチメントタクソノミーを使用してドキュメントを分類
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // センチメントと確率を出力
        Console.WriteLine($"センチメント: {response.BestClassName}");
        Console.WriteLine($"確率: {response.BestClassProbability}");
        ```

---
