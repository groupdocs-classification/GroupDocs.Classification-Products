---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: ko

############################# Head ############################
head_title: "문서 및 텍스트 분류와 감정 분석을 위한 .NET API"
head_description: "IAB-2, 문서 및 감정 분류법을 사용하여 문서와 텍스트를 분류하는 강력한 .NET 라이브러리. 다양한 파일 형식과 언어를 지원합니다."

############################# Header ############################
title: "문서 및 텍스트 분류 솔루션"
description: |
  .NET API를 사용하여 다양한 분류법으로 문서와 텍스트를 쉽게 분류할 수 있습니다.

  여러 파일 형식과 언어에 걸쳐 감정 분석을 수행하고 콘텐츠를 분류합니다.

  몇 줄의 코드만으로 고급 분류 기능을 .NET 애플리케이션에 통합할 수 있습니다.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "플랫폼 선택"
  title: "플랫폼 독립성"
  description: "GroupDocs.Classification for .NET은 다음 운영 체제 및 프레임워크와 호환됩니다:"
  details_link_title: "자세히 알아보기"

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
                    .NET Core 2.0 이상  .NET Framework 4.7 이상
      
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
                    10개 이상의 파일 형식

############################# Features ###############################
features:
  enable: true
  title: "GroupDocs.Classification 주요 기능"
  description: "이 솔루션은 다양한 분류법을 사용하여 문서와 텍스트를 분류하고, 감정 분석을 수행하며, 고급 분류 기능을 .NET 애플리케이션에 통합하는 데 도움을 줍니다."

  items:
    # items loop
    - icon: "classify"
      title: "다양한 분류법"
      content: "IAB-2, 문서 및 감정 분류법을 사용하여 분류합니다."

    # items loop
    - icon: "format"
      title: "광범위한 형식 지원"
      content: "DOC, DOCX, PDF 등 다양한 문서 형식을 처리합니다."

    # items loop
    - icon: "analyze"
      title: "감정 분석"
      content: "영어와 중국어 텍스트에 대한 감정 분류를 수행합니다."

    # items loop
    - icon: "integrate"
      title: "쉬운 통합"
      content: "몇 줄의 코드만으로 분류 기능을 통합할 수 있습니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "쉽게 문서 분류하기"
  description: "GroupDocs.Classification 코드 예제"
  items:
    # code sample loop
    - title: "IAB-2 분류법으로 PDF 분류하기"
      content: |
       GroupDocs.Classification을 사용하면 IAB-2 분류법으로 PDF 문서를 쉽게 분류할 수 있습니다. 문서 경로, 원하는 결과 수, 분류법 유형을 지정하기만 하면 분류 결과를 얻을 수 있습니다.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Classifier 인스턴스 생성
            var classifier = new GroupDocs.Classification.Classifier();

            // 문서 분류
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // 최상의 클래스와 확률 출력
            Console.WriteLine($"최상의 클래스: {response.BestClassName}, 확률: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "10개 이상의 파일 형식 지원"
  description: "GroupDocs.Classification은 다양한 인기 있는 문서 형식과 작동합니다"

############################# Metrics ###############################
metrics:
  enable: true
  title: "심층적인 지표 및 인사이트"
  description: "우리의 성과와 성장에 대한 포괄적인 view를 위해 상세한 지표를 살펴보세요."

  items:
    # items loop
    - number: "10+"
      title: "지원되는 형식"
      content: "가장 널리 사용되는 문서 형식 10개 이상을 지원합니다."

    # items loop
    - number: "3"
      title: "지원되는 분류법"
      content: "IAB-2, 문서 및 감정 분류법을 사용하여 콘텐츠를 분류합니다."

    # items loop
    - number: "2"
      title: "감정 분석 지원 언어"
      content: "영어와 중국어로 감정 분류를 수행합니다."

    # items loop
    - number: "4.7+"
      title: ".NET Framework 지원"
      content: ".NET Framework 4.7 이상 및 .NET Core 2.0 이상과 호환됩니다."

############################# Actions ###############################
actions:
  enable: true
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Classification 기능을 무료로 플랫폼에서 사용해 보세요."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "자주 묻는 질문"
  description: "GroupDocs.Classification에 대한 일반적인 질문에 대한 답변입니다."

  items:
    # items loop
    - question: "GroupDocs.Classification으로 어떤 종류의 문서를 분류할 수 있나요?"
      answer: "GroupDocs.Classification은 Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF, 일반 텍스트 (TXT) 파일을 포함한 다양한 문서 형식을 지원합니다."

    # items loop
    - question: "GroupDocs.Classification을 감정 분석에 사용할 수 있나요?"
      answer: "네, GroupDocs.Classification은 영어와 중국어 텍스트 모두에 대한 감정 분석을 지원하여 문서나 텍스트 스니펫의 감정을 결정할 수 있습니다."

    # items loop
    - question: "GroupDocs.Classification을 기존 .NET 애플리케이션에 통합할 수 있나요?"
      answer: "물론입니다! GroupDocs.Classification은 몇 줄의 코드만으로 .NET 애플리케이션에 쉽게 통합할 수 있는 사용자 친화적인 API를 제공합니다. 기존 워크플로우와 원활하게 작동하도록 설계되었습니다."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
