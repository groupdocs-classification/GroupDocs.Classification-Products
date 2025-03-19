---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: vi
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
head_title: "API .NET cho Phân loại Văn bản và Tài liệu"
head_description: "API C# .NET để phân loại văn bản và tài liệu sử dụng các phân loại IAB-2, Tài liệu và Cảm xúc. Phân loại nội dung ở nhiều định dạng khác nhau bao gồm PDF, DOC, DOCX, RTF và TXT."

############################# Header ############################
title: "API Phân loại Văn bản và Tài liệu .NET"
description: "Phân loại văn bản và tài liệu trong các ứng dụng .NET bằng cách sử dụng nhiều phân loại."
words:
  for: "cho"

actions:
  main: "Tải bản dùng thử qua NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Sẵn sàng bắt đầu?"
  description: "Dùng thử các tính năng của GroupDocs.Classification miễn phí hoặc yêu cầu giấy phép"

release:
  title: "Phiên bản {0} đã phát hành"
  notes: "Xem có gì mới"
  downloads: "Tải xuống"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Phân loại PDF với Phân loại IAB-2 trong C#"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Tạo một thể hiện của Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Phân loại một tài liệu PDF sử dụng phân loại IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // In ra tên lớp tốt nhất và xác suất
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Tổng quan về GroupDocs.Classification"
  description: "Giải pháp .NET để phân loại văn bản và tài liệu tự động sử dụng nhiều phân loại khác nhau."
  features:
    # feature loop
    - title: "Phân loại Văn bản và Tài liệu với C#"
      content: "Dễ dàng phân loại nội dung sử dụng các phân loại IAB-2, Tài liệu và Cảm xúc với GroupDocs.Classification cho .NET."

    # feature loop
    - title: "Hỗ trợ Nhiều Định dạng Tệp"
      content: "Xử lý nhiều loại tài liệu khác nhau bao gồm PDF, DOC, DOCX, RTF, TXT và nhiều hơn nữa."

    # feature loop
    - title: "Tùy chọn Phân loại Linh hoạt"
      content: "Chọn số lượng kết quả trả về và điều chỉnh cân bằng độ chính xác/thu hồi cho phân loại Tài liệu."

############################# Platforms ############################
platforms:
  enable: true
  title: "Độc lập nền tảng"
  description: "GroupDocs.Classification cho .NET hỗ trợ các hệ điều hành, framework và trình quản lý gói sau"
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
  title: "Các định dạng tệp được hỗ trợ"
  description: |
    GroupDocs.Classification cho .NET hỗ trợ các thao tác với [các định dạng tệp](https://docs.groupdocs.com/classification/net/supported-document-formats/) sau.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Định dạng Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Định dạng OpenDocument & Khác
        * **OpenOffice:** ODT, OTT
        * **Bố cục cố định:** PDF
        * **Khác:** TXT

############################# Features ############################
features:
  enable: true
  title: "Tính năng của GroupDocs.Classification"
  description: "Phân loại văn bản và tài liệu sử dụng các phân loại và tùy chọn nâng cao."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Nhiều Phân loại"
      content: "Hỗ trợ các phân loại IAB-2, Tài liệu và Cảm xúc để phân loại đa dạng."

    # feature loop
    - icon: "rasterize"
      title: "Hỗ trợ Đa Ngôn ngữ"
      content: "Thực hiện phân loại cảm xúc bằng cả tiếng Anh và tiếng Trung."

    # feature loop
    - icon: "sourcecode"
      title: "Kết quả Tùy chỉnh"
      content: "Chỉ định số lượng kết quả phân loại để trả về."

    # feature loop
    - icon: "transform"
      title: "Kiểm soát Độ chính xác"
      content: "Điều chỉnh cân bằng độ chính xác/thu hồi cho phân loại Tài liệu."

    # feature loop
    - icon: "adjustment"
      title: "Nhiều Định dạng Tệp"
      content: "Tương thích với nhiều định dạng tài liệu khác nhau bao gồm PDF, DOC, DOCX, RTF và TXT."

    # feature loop
    - icon: "complex"
      title: "Tích hợp Dễ dàng"
      content: "Tích hợp liền mạch với bất kỳ ứng dụng .NET nào, bao gồm ASP.NET và ứng dụng Windows."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã"
  description: "Một số trường hợp sử dụng điển hình của các thao tác GroupDocs.Classification cho .NET"
  items:
    # code sample loop
    - title: "Phân loại Văn bản sử dụng Phân loại IAB-2"
      content: |
        Ví dụ này cho thấy cách phân loại văn bản thô sử dụng phân loại IAB-2:
        
        ```csharp {style=abap}
        // Tạo một yêu cầu phân loại
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Thử phân loại Văn bản"
        }, "3");

        // Nhận kết quả phân loại
        var response = apiInstance.Classify(request);

        // In kết quả
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Phân tích Cảm xúc của một Tài liệu"
      content: |
        Bạn có thể thực hiện phân tích cảm xúc trên tài liệu sử dụng phân loại Cảm xúc:
        
        ```csharp {style=abap}
        // Tạo một thể hiện của Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Phân loại một tài liệu sử dụng phân loại Cảm xúc
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // In ra cảm xúc và xác suất
        Console.WriteLine($"Cảm xúc: {response.BestClassName}");
        Console.WriteLine($"Xác suất: {response.BestClassProbability}");
        ```

---
