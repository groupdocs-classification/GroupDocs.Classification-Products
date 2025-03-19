---
############################# Tĩnh ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Phân loại"
product_tag: "phan-loai"

lang: vi

############################# Đầu trang ############################
head_title: ".NET API để Phân loại Tài liệu & Văn bản và Phân tích Cảm xúc"
head_description: "Thư viện .NET mạnh mẽ để phân loại tài liệu và văn bản sử dụng các phân loại IAB-2, Tài liệu và Cảm xúc. Hỗ trợ nhiều định dạng tệp và ngôn ngữ."

############################# Tiêu đề ############################
title: "Giải pháp Phân loại Tài liệu & Văn bản"
description: |
  Dễ dàng phân loại tài liệu và văn bản bằng các phân loại khác nhau với API .NET của chúng tôi.

  Thực hiện phân tích cảm xúc và phân loại nội dung trên nhiều định dạng tệp và ngôn ngữ.

  Tích hợp các khả năng phân loại nâng cao vào ứng dụng .NET của bạn chỉ với vài dòng mã.

############################# Nền tảng được hỗ trợ ###############################
supported_platforms:
  enable: true
  head_title: "Chọn nền tảng của bạn"
  title: "Độc lập nền tảng"
  description: "GroupDocs.Classification for .NET tương thích với các hệ điều hành và khung công tác sau:"
  details_link_title: "Tìm hiểu thêm"

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
                    .NET Core 2.0 hoặc mới hơn  .NET Framework 4.7 hoặc cao hơn
      
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
                    Hơn 10 định dạng tệp

############################# Tính năng ###############################
features:
  enable: true
  title: "Các tính năng chính của GroupDocs.Classification"
  description: "Giải pháp này giúp bạn phân loại tài liệu và văn bản bằng các phân loại khác nhau, thực hiện phân tích cảm xúc và tích hợp các khả năng phân loại nâng cao vào ứng dụng .NET của bạn."

  items:
    # items loop
    - icon: "classify"
      title: "Nhiều hệ thống phân loại"
      content: "Phân loại sử dụng các hệ thống IAB-2, Tài liệu và Cảm xúc."

    # items loop
    - icon: "format"
      title: "Hỗ trợ nhiều định dạng"
      content: "Xử lý nhiều định dạng tài liệu bao gồm DOC, DOCX, PDF, v.v."

    # items loop
    - icon: "analyze"
      title: "Phân tích cảm xúc"
      content: "Thực hiện phân loại cảm xúc cho văn bản tiếng Anh và tiếng Trung."

    # items loop
    - icon: "integrate"
      title: "Tích hợp dễ dàng"
      content: "Tích hợp khả năng phân loại chỉ với vài dòng mã."

############################# Mẫu mã ############################
code_samples:
  enable: true
  title: "Phân loại tài liệu dễ dàng"
  description: "Ví dụ mã GroupDocs.Classification"
  items:
    # code sample loop
    - title: "Phân loại PDF với Hệ thống IAB-2"
      content: |
       GroupDocs.Classification cho phép bạn dễ dàng phân loại tài liệu PDF sử dụng hệ thống IAB-2. Chỉ cần chỉ định đường dẫn tài liệu, số lượng kết quả mong muốn và kiểu hệ thống để nhận kết quả phân loại.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```
            // Tạo một phiên bản của Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // Phân loại tài liệu
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // In ra lớp tốt nhất và xác suất của nó
            Console.WriteLine($"Lớp tốt nhất: {response.BestClassName}, Xác suất: {response.BestClassProbability}");
            ```

############################# Định dạng được hỗ trợ ###############################
formats:
  enable: true
  title: "Hỗ trợ hơn 10 định dạng tệp"
  description: "GroupDocs.Classification hoạt động với nhiều định dạng tài liệu phổ biến"

############################# Chỉ số ###############################
metrics:
  enable: true
  title: "Chỉ số chi tiết và thông tin chuyên sâu"
  description: "Khám phá các chỉ số chi tiết của chúng tôi để có cái nhìn toàn diện về hiệu suất và sự phát triển của chúng tôi."

  items:
    # items loop
    - number: "10+"
      title: "Định dạng được hỗ trợ"
      content: "Chúng tôi hỗ trợ hơn 10 định dạng tài liệu được sử dụng rộng rãi nhất."

    # items loop
    - number: "3"
      title: "Hệ thống Phân loại được hỗ trợ"
      content: "Phân loại nội dung sử dụng các hệ thống IAB-2, Tài liệu, và Cảm xúc."

    # items loop
    - number: "2"
      title: "Ngôn ngữ cho Phân tích Cảm xúc"
      content: "Thực hiện phân tích cảm xúc bằng tiếng Anh và tiếng Trung."

    # items loop
    - number: "4.7+"
      title: ".NET Framework Support"
      content: "Compatible with .NET Framework 4.7 or higher and .NET Core 2.0 or later."

############################# Hành động ###############################
actions:
  enable: true
  title: "Sẵn sàng bắt đầu?"
  description: "Dùng thử các tính năng của GroupDocs.Classification miễn phí trên nền tảng của bạn."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# Câu hỏi thường gặp ###############################
faq:
  enable: true
  title: "Câu hỏi thường gặp"
  description: "Câu trả lời cho các câu hỏi phổ biến về GroupDocs.Classification."

  items:
    # items loop
    - question: "Tôi có thể phân loại những loại tài liệu nào với GroupDocs.Classification?"
      answer: "GroupDocs.Classification hỗ trợ nhiều định dạng tài liệu khác nhau bao gồm Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF và các tệp văn bản thuần túy (TXT)."

    # items loop
    - question: "Tôi có thể sử dụng GroupDocs.Classification cho phân tích cảm xúc không?"
      answer: "Có, GroupDocs.Classification hỗ trợ phân tích cảm xúc cho cả văn bản tiếng Anh và tiếng Trung, cho phép bạn xác định cảm xúc của tài liệu hoặc đoạn văn bản."

    # items loop
    - question: "Có thể tích hợp GroupDocs.Classification vào ứng dụng .NET hiện có của tôi không?"
      answer: "Hoàn toàn có thể! GroupDocs.Classification cung cấp API thân thiện với người dùng có thể dễ dàng tích hợp vào ứng dụng .NET của bạn chỉ với vài dòng mã. Nó được thiết kế để hoạt động liền mạch với quy trình làm việc hiện có của bạn."

---