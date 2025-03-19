---
############################# استاتیک ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: fa
product: "Classification"
product_tag: "classification"
platform: "Net"
platform_tag: "net"

############################# کشویی ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"

############################# سرصفحه ############################
head_title: "API دات‌نت برای طبقه‌بندی متن و اسناد"
head_description: "API دات‌نت برای طبقه‌بندی متن و اسناد با استفاده از طبقه‌بندی‌های IAB-2، سند و احساسات. طبقه‌بندی محتوا در فرمت‌های مختلف از جمله PDF، DOC، DOCX، RTF و TXT."

############################# هدر ############################
title: "API طبقه‌بندی متن و اسناد دات‌نت"
description: "طبقه‌بندی متن‌ها و اسناد در برنامه‌های دات‌نت با استفاده از چندین طبقه‌بندی."
words:
  for: "برای"

actions:
  main: "دانلود نسخه آزمایشی از طریق NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "مجوزدهی"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "آماده شروع هستید؟"
  description: "ویژگی‌های GroupDocs.Classification را به صورت رایگان امتحان کنید یا درخواست مجوز دهید."

release:
  title: "نسخه {0} منتشر شد"
  notes: "مشاهده تغییرات جدید"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "طبقه‌بندی PDF با طبقه‌بندی IAB-2 در C#"
  more: "مثال‌های بیشتر"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```
    // ایجاد یک نمونه از Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // طبقه‌بندی یک سند PDF با استفاده از طبقه‌بندی IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // چاپ بهترین نام کلاس و احتمال آن
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# مرور کلی ############################
overview:
  enable: true
  title: "مروری بر GroupDocs.Classification"
  description: "راه‌حل دات‌نت برای طبقه‌بندی خودکار متن و اسناد با استفاده از طبقه‌بندی‌های مختلف."
  features:
    # feature loop
    - title: "طبقه‌بندی متن و اسناد با C#"
      content: "به راحتی محتوا را با استفاده از طبقه‌بندی‌های IAB-2، سند و احساسات با GroupDocs.Classification برای دات‌نت طبقه‌بندی کنید."

    # feature loop
    - title: "پشتیبانی از فرمت‌های مختلف فایل"
      content: "انواع مختلف اسناد از جمله PDF، DOC، DOCX، RTF، TXT و موارد دیگر را پردازش کنید."

    # feature loop
    - title: "گزینه‌های انعطاف‌پذیر برای طبقه‌بندی"
      content: "تعداد نتایج بازگشتی را انتخاب کنید و تعادل دقت/بازیابی را برای طبقه‌بندی اسناد تنظیم کنید."

############################# پلتفرم‌ها ############################
platforms:
  enable: true
  title: "استقلال پلتفرم"
  description: "GroupDocs.Classification برای دات‌نت از سیستم‌عامل‌ها، فریمورک‌ها و مدیرهای بسته زیر پشتیبانی می‌کند:"
  items:
    # platform loop
    - title: "آمازون"
      image: "amazon"
    # platform loop
    - title: "داکر"
      image: "docker"
    # platform loop
    - title: "ویندوز"
      image: "windows"
    # platform loop
    - title: "لینوکس"
      image: "linux"
    # platform loop
    - title: "مک او اس"
      image: "finder"
    # platform loop
    - title: ".NET"
      image: "net"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# فرمت‌های فایل ############################
formats:
  enable: true
  title: "فرمت‌های پشتیبانی‌شده فایل‌ها"
  description: |
    GroupDocs.Classification برای دات‌نت عملیات‌هایی را با فرمت‌های [فایل پشتیبانی‌شده](https://docs.groupdocs.com/classification/net/supported-document-formats/) زیر انجام می‌دهد.
  groups:
    # group loop
    - color: "green"
      content: |
        ### فرمت‌های مایکروسافت آفیس
        * **ورد:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### فرمت‌های OpenDocument و دیگر فرمت‌ها
        * **OpenOffice:** ODT, OTT
        * **فرمت ثابت:** PDF
        * **دیگر:** TXT

############################# ویژگی‌ها ############################
features:
  enable: true
  title: "ویژگی‌های GroupDocs.Classification"
  description: "طبقه‌بندی متن و اسناد با استفاده از طبقه‌بندی‌ها و گزینه‌های پیشرفته."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "طبقه‌بندی‌های متعدد"
      content: "پشتیبانی از طبقه‌بندی‌های IAB-2، سند و احساسات برای طبقه‌بندی متنوع."

    # feature loop
    - icon: "rasterize"
      title: "پشتیبانی از چند زبان"
      content: "طبقه‌بندی احساسات را به زبان انگلیسی و چینی انجام دهید."

    # feature loop
    - icon: "sourcecode"
      title: "نتایج قابل تنظیم"
      content: "تعداد نتایج بازگشتی برای طبقه‌بندی را مشخص کنید."

    # feature loop
    - icon: "transform"
      title: "کنترل دقت"
      content: "تعادل دقت/بازیابی را برای طبقه‌بندی اسناد تنظیم کنید."

    # feature loop
    - icon: "adjustment"
      title: "فرمت‌های متعدد فایل‌ها "
      content: "**سازگار با فرمت‌هایی مانند PDF، DOC، DOCX، RTF و TXT.**"

    # feature loop
    - icon: "complex" 
      title: "ادغام آسان" 
      content: "به راحتی در هر برنامه دات‌نت مانند ASP.NET یا برنامه ویندوز ادغام می‌شود."

############################# نمونه کد ############################
code_samples:
  enable: true
  title: "نمونه کدها"
  description: ".برخی موارد استفاده معمول از عملیات GroupDocs.Classification برای .NET."
  items:
    # code sample loop
    - title: ".دسته‌بندی متن با استفاده از طبقه‌بندی IAB-2."
      content: | 
        این مثال نحوه دسته بندی متن خام را با استفاده از طبقه بندی نشان می دهد:
        ```csharp {style=abap}
        // Create a classification request
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Try Text classification"
        }, "3");

        // Get classification results
        var response = apiInstance.Classify(request);

        // Print the results
        Console.WriteLine(response.ToString());
        ```
---