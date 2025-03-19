---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "طبقه‌بندی"
product_tag: "classification"

lang: fa

############################# Head ############################
head_title: "API .NET برای طبقه‌بندی اسناد و متن و تحلیل احساسات"
head_description: "کتابخانه قدرتمند .NET برای طبقه‌بندی اسناد و متن با استفاده از طبقه‌بندی‌های IAB-2، اسناد و احساسات. پشتیبانی از فرمت‌های متعدد فایل و زبان‌ها."

############################# Header ############################
title: "راه‌حل طبقه‌بندی اسناد و متن"
description: |
  به راحتی اسناد و متن را با استفاده از طبقه‌بندی‌های مختلف با API .NET ما طبقه‌بندی کنید.

  تحلیل احساسات را انجام دهید و محتوا را در فرمت‌های مختلف فایل و زبان‌ها دسته‌بندی کنید.

  قابلیت‌های پیشرفته طبقه‌بندی را با چند خط کد در برنامه‌های .NET خود ادغام کنید.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "پلتفرم خود را انتخاب کنید"
  title: "استقلال پلتفرم"
  description: "GroupDocs.Classification برای .NET با سیستم‌عامل‌ها و چارچوب‌های زیر سازگار است:"
  details_link_title: "بیشتر بدانید"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification برای .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 یا بالاتر  .NET Framework 4.7 یا بالاتر
      
          # features loop
          - rows: "4"
            content: |
                    ویندوز دسکتاپ (x64)  ویندوز سرور (x64)  ویندوز آزور  مک او اس ایکس x64 (10.12+)
      
          # features loop
          - rows: "3"
            content: |
                    مایکروسافت ویژوال استودیو  جت‌برینز رایدر  مونودولوپ
      
          # features loop
          - rows: "1"
            content: |
                    بیش از 10 فرمت فایل

############################# Features ###############################
features:
  enable: true
  title: "ویژگی‌های کلیدی GroupDocs.Classification"
  description: "این راه‌حل به شما کمک می‌کند تا اسناد و متن را با استفاده از طبقه‌بندی‌های مختلف طبقه‌بندی کنید، تحلیل احساسات را انجام دهید و قابلیت‌های پیشرفته طبقه‌بندی را در برنامه‌های .NET خود ادغام کنید."

  items:
    # items loop
    - icon: "classify"
      title: "طبقه‌بندی‌های متعدد"
      content: "طبقه‌بندی با استفاده از طبقه‌بندی‌های IAB-2، اسناد و احساسات."

    # items loop
    - icon: "format"
      title: "پشتیبانی از فرمت‌های گسترده"
      content: "پردازش فرمت‌های مختلف اسناد از جمله DOC، DOCX، PDF و غیره."

    # items loop
    - icon: "analyze"
      title: "تحلیل احساسات"
      content: "انجام طبقه‌بندی احساسات برای متن انگلیسی و چینی."

    # items loop
    - icon: "integrate"
      title: "ادغام آسان"
      content: "ادغام قابلیت‌های طبقه‌بندی با چند خط کد."

############################# Code samples ############################
code_samples:
  enable: true
  title: "طبقه‌بندی اسناد به راحتی"
  description: "نمونه‌های کد GroupDocs.Classification"
  items:
    # code sample loop
    - title: "طبقه‌بندی PDF با طبقه‌بندی IAB-2"
      content: |
       GroupDocs.Classification به شما امکان می‌دهد به راحتی اسناد PDF را با استفاده از طبقه‌بندی IAB-2 طبقه‌بندی کنید. کافی است مسیر سند، تعداد نتایج مورد نظر و نوع طبقه‌بندی را مشخص کنید تا نتایج طبقه‌بندی را دریافت کنید.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // ایجاد یک نمونه از Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // طبقه‌بندی سند
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // چاپ بهترین کلاس و احتمال آن
            Console.WriteLine($"بهترین کلاس: {response.BestClassName}، احتمال: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "پشتیبانی از بیش از 10 فرمت فایل"
  description: "GroupDocs.Classification با فرمت‌های مختلف اسناد محبوب کار می‌کند"

############################# Metrics ###############################
metrics:
  enable: true
  title: "معیارها و بینش‌های عمیق"
  description: "در معیارهای دقیق ما غوطه‌ور شوید تا دیدگاه جامعی از عملکرد و رشد ما داشته باشید."

  items:
    # items loop
    - number: "+10"
      title: "فرمت‌های پشتیبانی شده"
      content: "ما بیش از 10 فرمت پرکاربرد اسناد را پشتیبانی می‌کنیم."

    # items loop
    - number: "3"
      title: "طبقه‌بندی‌های پشتیبانی شده"
      content: "طبقه‌بندی محتوا با استفاده از طبقه‌بندی‌های IAB-2، اسناد و احساسات."

    # items loop
    - number: "2"
      title: "زبان‌های تحلیل احساسات"
      content: "انجام طبقه‌بندی احساسات به زبان‌های انگلیسی و چینی."

    # items loop
    - number: "+4.7"
      title: "پشتیبانی از .NET Framework"
      content: "سازگار با .NET Framework 4.7 یا بالاتر و .NET Core 2.0 یا بالاتر."

############################# Actions ###############################
actions:
  enable: true
  title: "آماده شروع هستید؟"
  description: "ویژگی‌های GroupDocs.Classification را به صورت رایگان در پلتفرم خود امتحان کنید."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "سؤالات متداول"
  description: "پاسخ به سؤالات رایج درباره GroupDocs.Classification."

  items:
    # items loop
    - question: "چه نوع اسنادی را می‌توانم با GroupDocs.Classification طبقه‌بندی کنم؟"
      answer: "GroupDocs.Classification از فرمت‌های مختلف اسناد از جمله Microsoft Word (DOC، DOCX، RTF)، OpenOffice (ODT)، PDF و فایل‌های متنی ساده (TXT) پشتیبانی می‌کند."

    # items loop
    - question: "آیا می‌توانم از GroupDocs.Classification برای تحلیل احساسات استفاده کنم؟"
      answer: "بله، GroupDocs.Classification از تحلیل احساسات برای متن انگلیسی و چینی پشتیبانی می‌کند و به شما امکان می‌دهد احساسات اسناد یا قطعات متنی را تعیین کنید."

    # items loop
    - question: "آیا امکان ادغام GroupDocs.Classification در برنامه .NET موجود من وجود دارد؟"
      answer: "قطعاً! GroupDocs.Classification یک API کاربرپسند ارائه می‌دهد که می‌تواند به راحتی با چند خط کد در برنامه‌های .NET شما ادغام شود. این برنامه طراحی شده است تا به طور یکپارچه با جریان‌های کاری موجود شما کار کند."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
