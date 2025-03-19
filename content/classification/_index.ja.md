---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: ja

############################# Head ############################
head_title: "ドキュメントとテキスト分類および感情分析のための.NET API"
head_description: "IAB-2、ドキュメント、感情分類法を使用したドキュメントとテキスト分類のための強力な.NETライブラリ。複数のファイル形式と言語をサポートします。"

############################# Header ############################
title: "ドキュメントとテキスト分類ソリューション"
description: |
  当社の.NET APIを使用して、様々な分類法でドキュメントとテキストを簡単に分類できます。

  感情分析を実行し、複数のファイル形式と言語にわたってコンテンツを分類します。

  わずか数行のコードで、高度な分類機能を.NETアプリケーションに統合できます。

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "プラットフォームを選択"
  title: "プラットフォーム独立性"
  description: "GroupDocs.Classification for .NETは、以下のオペレーティングシステムとフレームワークと互換性があります："
  details_link_title: "詳細を見る"

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
                    .NET Core 2.0以降  .NET Framework 4.7以上
      
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
                    10以上のファイル形式

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Classificationの主な機能"
  description: "このソリューションは、様々な分類法を使用してドキュメントとテキストを分類し、感情分析を実行し、高度な分類機能を.NETアプリケーションに統合するのに役立ちます。"

  items:
    # items loop
    - icon: "classify"
      title: "複数の分類法"
      content: "IAB-2、ドキュメント、感情分類法を使用して分類します。"

    # items loop
    - icon: "format"
      title: "幅広い形式サポート"
      content: "DOC、DOCX、PDFなど、様々なドキュメント形式を処理します。"

    # items loop
    - icon: "analyze"
      title: "感情分析"
      content: "英語と中国語のテキストの感情分類を実行します。"

    # items loop
    - icon: "integrate"
      title: "簡単な統合"
      content: "わずか数行のコードで分類機能を統合します。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "簡単にドキュメントを分類"
  description: "GroupDocs.Classificationのコード例"
  items:
    # code sample loop
    - title: "IAB-2分類法でPDFを分類"
      content: |
       GroupDocs.Classificationを使用すると、IAB-2分類法を使用してPDFドキュメントを簡単に分類できます。ドキュメントのパス、希望する結果の数、分類法の種類を指定するだけで、分類結果を取得できます。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```
            // Classifierのインスタンスを作成
            var classifier = new GroupDocs.Classification.Classifier();

            // ドキュメントを分類
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // 最適なクラスとその確率を出力
            Console.WriteLine($"最適なクラス: {response.BestClassName}, 確率: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "10以上のファイル形式をサポート"
  description: "GroupDocs.Classificationは、様々な一般的なドキュメント形式で動作します"

############################# Metrics ###############################
metrics:
  enable: true
  title: "詳細な指標とインサイト"
  description: "当社のパフォーマンスと成長を包括的に把握するために、詳細な指標をご覧ください。"

  items:
    # items loop
    - number: "10+"
      title: "サポートされる形式"
      content: "最も広く使用されている10以上のドキュメント形式をサポートしています。"

    # items loop
    - number: "3"
      title: "サポートされる分類法"
      content: "IAB-2、ドキュメント、感情分類法を使用してコンテンツを分類します。"

    # items loop
    - number: "2"
      title: "感情分析の言語"
      content: "英語と中国語で感情分類を実行します。"

    # items loop
    - number: "4.7+"
      title: ".NET Frameworkサポート"
      content: ".NET Framework 4.7以上および.NET Core 2.0以降と互換性があります。"

############################# Actions ###############################
actions:
  enable: true
  title: "始める準備はできましたか？"
  description: "お使いのプラットフォームでGroupDocs.Classificationの機能を無料でお試しください。"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "よくある質問"
  description: "GroupDocs.Classificationに関する一般的な質問への回答。"

  items:
    # items loop
    - question: "GroupDocs.Classificationでどのような種類のドキュメントを分類できますか？"
      answer: "GroupDocs.Classificationは、Microsoft Word（DOC、DOCX、RTF）、OpenOffice（ODT）、PDF、プレーンテキスト（TXT）ファイルなど、様々なドキュメント形式をサポートしています。"

    # items loop
    - question: "GroupDocs.Classificationを感情分析に使用できますか？"
      answer: "はい、GroupDocs.Classificationは英語と中国語のテキストの感情分析をサポートしており、ドキュメントやテキスト断片の感情を判断することができます。"

    # items loop
    - question: "既存の.NETアプリケーションにGroupDocs.Classificationを統合することは可能ですか？"
      answer: "もちろんです！GroupDocs.Classificationは、わずか数行のコードで.NETアプリケーションに簡単に統合できるユーザーフレンドリーなAPIを提供しています。既存のワークフローとシームレスに連携するように設計されています。"

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
