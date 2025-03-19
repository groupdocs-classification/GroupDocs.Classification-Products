---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: ko
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
head_title: "텍스트 및 문서 분류를 위한 .NET API"
head_description: "IAB-2, 문서 및 감성 분류법을 사용하여 텍스트와 문서를 분류하는 C# .NET API. PDF, DOC, DOCX, RTF 및 TXT를 포함한 다양한 형식의 콘텐츠를 분류합니다."

############################# Header ############################
title: ".NET 텍스트 및 문서 분류 API"
description: "다양한 분류법을 사용하여 .NET 애플리케이션에서 텍스트와 문서를 분류하세요."
words:
  for: "for"

actions:
  main: "NuGet을 통해 평가판 다운로드"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "라이선싱"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Classification 기능을 무료로 사용해보거나 라이선스를 요청하세요"

release:
  title: "버전 {0} 출시"
  notes: "새로운 기능 보기"
  downloads: "다운로드"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "C#에서 IAB-2 분류법으로 PDF 분류하기"
  more: "더 많은 예제"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Classifier 인스턴스 생성
    var classifier = new GroupDocs.Classification.Classifier();

    // IAB-2 분류법을 사용하여 PDF 문서 분류
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // 최상의 클래스 이름과 확률 출력
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Classification 개요"
  description: "다양한 분류법을 사용한 자동화된 텍스트 및 문서 분류를 위한 .NET 솔루션."
  features:
    # feature loop
    - title: "C#으로 텍스트 및 문서 분류"
      content: "GroupDocs.Classification for .NET을 사용하여 IAB-2, 문서 및 감성 분류법으로 콘텐츠를 쉽게 분류하세요."

    # feature loop
    - title: "다양한 파일 형식 지원"
      content: "PDF, DOC, DOCX, RTF, TXT 등 다양한 문서 유형을 처리합니다."

    # feature loop
    - title: "유연한 분류 옵션"
      content: "반환할 결과 수를 선택하고 문서 분류법에 대한 정밀도/재현율 균형을 조정하세요."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Classification for .NET은 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다"
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
  title: "지원되는 파일 형식"
  description: |
    GroupDocs.Classification for .NET은 다음 [파일 형식](https://docs.groupdocs.com/classification/net/supported-document-formats/)으로 작업을 지원합니다.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office 형식
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### OpenDocument 및 기타 형식
        * **OpenOffice:** ODT, OTT
        * **고정 레이아웃:** PDF
        * **기타:** TXT

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Classification 기능"
  description: "고급 분류법과 옵션을 사용하여 텍스트와 문서를 분류합니다."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "다양한 분류법"
      content: "다양한 분류를 위해 IAB-2, 문서 및 감성 분류법을 지원합니다."

    # feature loop
    - icon: "rasterize"
      title: "다국어 지원"
      content: "영어와 중국어로 감성 분류를 수행합니다."

    # feature loop
    - icon: "sourcecode"
      title: "맞춤형 결과"
      content: "반환할 분류 결과 수를 지정합니다."

    # feature loop
    - icon: "transform"
      title: "정밀도 제어"
      content: "문서 분류법 분류에 대한 정밀도/재현율 균형을 조정합니다."

    # feature loop
    - icon: "adjustment"
      title: "다양한 파일 형식"
      content: "PDF, DOC, DOCX, RTF 및 TXT를 포함한 다양한 문서 형식과 호환됩니다."

    # feature loop
    - icon: "complex"
      title: "쉬운 통합"
      content: "ASP.NET 및 Windows 앱을 포함한 모든 .NET 애플리케이션과 원활하게 통합됩니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "일반적인 GroupDocs.Classification for .NET 작업의 일부 사용 사례"
  items:
    # code sample loop
    - title: "IAB-2 분류법을 사용하여 텍스트 분류"
      content: |
        이 예제는 IAB-2 분류법을 사용하여 원시 텍스트를 분류하는 방법을 보여줍니다:
        
        ```csharp {style=abap}
        // 분류 요청 생성
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "텍스트 분류 시도"
        }, "3");

        // 분류 결과 가져오기
        var response = apiInstance.Classify(request);

        // 결과 출력
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "문서의 감성 분석"
      content: |
        감성 분류법을 사용하여 문서에 대한 감성 분석을 수행할 수 있습니다:
        
        ```csharp {style=abap}
        // Classifier 인스턴스 생성
        var classifier = new GroupDocs.Classification.Classifier();

        // 감성 분류법을 사용하여 문서 분류
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // 감성과 확률 출력
        Console.WriteLine($"감성: {response.BestClassName}");
        Console.WriteLine($"확률: {response.BestClassProbability}");
        ```

---