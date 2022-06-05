---
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Classification"
product_tag: "classification"
platform: ".NET"
platform_tag: "net"

head_title: "C# .NET 문서 및 텍스트 분류 및 감정 분석 API"
head_description: "C# .NET API를 사용한 문서 및 원시 텍스트 분류. IAB-2를 사용한 분류 및 문서 분류 및 분류를 사용한 소비자 감정 분석 Sentiment."

title: ".NET 텍스트 및 문서 분류 API"
description: "IAB-2, 문서 및 감정 분류 내에서 미리 정의된 태그 또는 범주를 사용하여 파일 및 텍스트 분류기 기능으로 .NET 애플리케이션을 강화합니다.."
button:
    enable: true

submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Classification for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
        product: "GroupDocs.Classification"
        platform: ".NET"

    middle:
        button:
            - link: "#overview"
              text: "개요"

            - link: "#features"
              text: "특징"

            - link: "#support"
              text: "지원하다"

            - link: "https://products.groupdocs.app/classification"
              text: "라이브 데모"

            - link: "https://purchase.groupdocs.com/pricing/classification/net"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/classification"
        link_learn: "https://docs.groupdocs.com/classification/net/"
        link_buy: "https://purchase.groupdocs.com"

overview:
    enable: true
    content: |
      .NET용 GroupDocs.Classification은 C#, ASP.NET 및 기타 .NET 기반 기술에서 강력한 텍스트 및 문서 분류/분류 응용 프로그램을 만드는 데 도움이 되는 직관적인 C# Netstandard 2.0 API입니다. API는 4가지 유형의 분류법을 지원하고 표준화된 텍스트 범주를 할당하기 위해 IAB-2를 사용하고 다양한 문서 유형에 대해 Aspose에서 개발한 문서 분류법을 사용하거나 감정 분석을 위해 Sentiment(및 Sentiment3)를 사용하여 고급 문서 및 텍스트 분류를 제공합니다. API는 텍스트, 문장, 단어까지 분석하고 PDF, Microsoft Word, OpenDocument, RTF 및 TXT를 포함한 다양한 산업 표준 문서 형식 분류를 지원합니다. 감정 분석(분류)은 언어 자동 감지로 영어, 중국어, 스페인어, 독일어를 지원합니다. API는 C#에서 세분화된 감정 분석에 사용할 수 있는 긍정 확률을 반환할 수 있습니다.  

      .NET용 GroupDocs.Classification은 자체 문서 처리/분류 엔진을 사용하며 시스템에 외부 도구를 설치할 필요가 없습니다. .NET 플랫폼을 대상으로 애플리케이션을 개발하고 .NET 프레임워크(.NET Core 포함)를 설치할 수 있는 모든 인기 있는 운영 체제(Windows, Linux, macOS)를 지원합니다.
    tabs:
      enable: true
      
      tab_one:
        description: |
          다음은 .NET용 GroupDocs.Classification의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 경로 및 스트림별 문서 분류
            * 원시 텍스트 분류
            * **IAB-2**, **Documents**, **Sentiment** 및 **Sentiment3** 분류가 지원됨
            * 여러 문서 형식 지원
      
      tab_two:
        description: |
          .NET용 GroupDocs.Classification [많은 인기 있는 문서 형식 지원](https://docs.groupdocs.com/classification/net/supported-document-formats/).

        left:
          enable: true
          table:
            - title: "마이크로 소프트 오피스"
              content: |
                * **단어**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF

        right:
          enable: true
          table:
            - title: "기타 형식"
              content: |
                * **고정 레이아웃**: PDF
                * **OpenDocument**: ODT, OTT
                * **텍스트**: TXT

      tab_three:
        description: |
          .NET용 GroupDocs.Classification은 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
        
        left:
          enable: true
          table:
            - icon: "fab fa-windows"
              title: "운영체제"
              content: |
                * 윈도우 10(x64)
                * 윈도우 데스크탑(x64)
                * 윈도우 서버(x64)
                * 윈도우 애저
                * 맥 OS X x64(10.12+)
                * 리눅스

            - icon: "fas fa-code"
              title: "지원되는 프레임워크"
              content: |
                * .NET Core 2.0 이상
                * .NET 프레임워크 4.7 이상

        right:
          enable: true
          table:
            - icon: "fas fa-box"
              title: "패키지 관리자"
              content: |
                * 누겟

            - icon: "fas fa-tools"
              title: "개발 환경"
              content: |
                * 마이크로소프트 비주얼 스튜디오
                * 자마린.안드로이드
                * 자마린.IOS
                * 자마린.맥
                * 모노디벨롭

features:
    enable: true
    title: "고급 텍스트 및 문서 분류 API 기능"

    feature:
      - icon: "fas fa-copy"
        content: |
          **IAB‑2**, **Documents**, **Sentiment** 또는 **Sentiment3** 분류를 사용하여 경로별로 문서 분류

      - icon: "fas fa-eye"
        content: |
          **IAB‑2**, **Documents**, **Sentiment** 또는 **Sentiment3** 분류를 사용하여 원시 텍스트 분류 수행

      - icon: "fas fa-bolt"
        content: "영어, 중국어, 스페인어, 독일어 감정 분류(분석)"
      
      - icon: "fas fa-file-powerpoint"
        content: "반환할 분류된 결과의 수를 선택하십시오."

      - icon: "fas fa-code"
        content: "PDF, 문서, OpenOffice 및 서식 있는 텍스트 문서 작업"

      - icon: "fas fa-cloud"
        content: "100% 작동 예제 및 데모가 제공되어 지원되는 기능을 빠르게 학습할 수 있습니다."

      - icon: "fas fa-remove-format"
        content: "제품 포럼을 통해 무제한 무료 기술 지원 제공"

    more_feature:
      - title: "정확한 문서 분류"
        content: |
          GroupDocs.Classification API는 다양한 문서 형식에 대한 분류를 지원합니다. 아래 C# 코드 예제는 최상의 결과 3개를 반환하여 문서 분류를 사용하여 현재 폴더에서 PDF 파일을 분류하는 방법을 보여줍니다.

          ```cs
          // 범용 분류기(IAB-2, Documents, Sentiment Analysis)를 초기화합니다.
          var classifier = new GroupDocs.Classification.Classifier();

          // 문서 분류로 pdf 파일을 분류하고 가장 가능성이 높은 3개의 카테고리를 반환합니다.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      - title: "정확한 텍스트 분류"
        content: |
          GroupDocs.Classification API는 텍스트 분류도 지원합니다. 텍스트 분류는 IAB-2, Documents, Sentiment 및 Sentiment3의 4가지 분류로 수행할 수 있습니다. 아래 C# 코드 예제에서는 최상의 결과를 반환하여 기본(IAB-2) 분류로 텍스트를 분류하는 방법을 보여줍니다.

          ```cs
          // 범용 분류기(IAB-2, Documents, Sentiment Analysis)를 초기화합니다.
          var classifier = new GroupDocs.Classification.Classifier();

          // IAB-2 분류법으로 텍스트를 분류하고 최상의 범주를 반환합니다.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      - title: "정확한 다국어 감정 분석"
        content: |
          .NET용 GroupDocs.Classification을 사용하면 영어, 중국어, 스페인어 및 독일어로 도메인 간 감정 분석(분류)을 수행할 수 있습니다. .NET용 GroupDocs.Classification은 적절한 언어를 자동으로 감지합니다. 감정 분석 API 사용 사례는 다음 C# 코드로 설명됩니다.

          ```cs
          // 교차 도메인 다국어 감정 분류기를 초기화합니다. 
          // SentimentClassifier는 영어, 중국어, 스페인어, 독일어로 다국어 분류를 지원합니다.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // 영어 텍스트의 감정 분석.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // 동일한 분류자 및 Sentiment3(Negative/Neutral/Positive) 분류법을 사용하여 중국어 텍스트의 감정 분석.
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

support:
    enable: true

solutions:
    enable: false
    title: "GroupDocs.Classification은 다른 인기 있는 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        - img_alt: "GroupDocs.Classification for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-java.png"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/java/"

back_to_top:
  enable: true
---
