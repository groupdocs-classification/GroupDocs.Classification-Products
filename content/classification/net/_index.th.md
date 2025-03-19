---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: th
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
head_title: "API .NET สำหรับการจำแนกประเภทข้อความและเอกสาร"
head_description: "API C# .NET สำหรับการจำแนกประเภทข้อความและเอกสารโดยใช้ระบบการจัดหมวดหมู่ IAB-2, เอกสาร และความรู้สึก จำแนกประเภทเนื้อหาในรูปแบบต่างๆ รวมถึง PDF, DOC, DOCX, RTF และ TXT"

############################# Header ############################
title: "API การจำแนกประเภทข้อความและเอกสาร .NET"
description: "จำแนกประเภทข้อความและเอกสารในแอปพลิเคชัน .NET โดยใช้ระบบการจัดหมวดหมู่หลายประเภท"
words:
  for: "สำหรับ"

actions:
  main: "ดาวน์โหลดทดลองใช้ผ่าน NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "การอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติของ GroupDocs.Classification ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เผยแพร่แล้ว"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "จำแนกประเภท PDF ด้วยระบบการจัดหมวดหมู่ IAB-2 ใน C#"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // สร้างอินสแตนซ์ของ Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // จำแนกประเภทเอกสาร PDF โดยใช้ระบบการจัดหมวดหมู่ IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // พิมพ์ชื่อคลาสที่ดีที่สุดและความน่าจะเป็น
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "ภาพรวมของ GroupDocs.Classification"
  description: "โซลูชัน .NET สำหรับการจำแนกประเภทข้อความและเอกสารอัตโนมัติโดยใช้ระบบการจัดหมวดหมู่ต่างๆ"
  features:
    # feature loop
    - title: "จำแนกประเภทข้อความและเอกสารด้วย C#"
      content: "จำแนกประเภทเนื้อหาได้อย่างง่ายดายโดยใช้ระบบการจัดหมวดหมู่ IAB-2, เอกสาร และความรู้สึกด้วย GroupDocs.Classification สำหรับ .NET"

    # feature loop
    - title: "รองรับรูปแบบไฟล์หลายประเภท"
      content: "ประมวลผลประเภทเอกสารต่างๆ รวมถึง PDF, DOC, DOCX, RTF, TXT และอื่นๆ"

    # feature loop
    - title: "ตัวเลือกการจำแนกประเภทที่ยืดหยุ่น"
      content: "เลือกจำนวนผลลัพธ์ที่จะส่งคืนและปรับความสมดุลระหว่างความแม่นยำ/การเรียกคืนสำหรับระบบการจัดหมวดหมู่เอกสาร"

############################# Platforms ############################
platforms:
  enable: true
  title: "ความเป็นอิสระของแพลตฟอร์ม"
  description: "GroupDocs.Classification สำหรับ .NET รองรับระบบปฏิบัติการ, เฟรมเวิร์ก และตัวจัดการแพ็คเกจต่อไปนี้"
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
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Classification สำหรับ .NET รองรับการทำงานกับ [รูปแบบไฟล์](https://docs.groupdocs.com/classification/net/supported-document-formats/) ต่อไปนี้
  groups:
    # group loop
    - color: "green"
      content: |
        ### รูปแบบ Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### รูปแบบ OpenDocument และอื่นๆ
        * **OpenOffice:** ODT, OTT
        * **เค้าโครงคงที่:** PDF
        * **อื่นๆ:** TXT

############################# Features ############################
features:
  enable: true
  title: "คุณสมบัติของ GroupDocs.Classification"
  description: "จำแนกประเภทข้อความและเอกสารโดยใช้ระบบการจัดหมวดหมู่และตัวเลือกขั้นสูง"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "ระบบการจัดหมวดหมู่หลายประเภท"
      content: "รองรับระบบการจัดหมวดหมู่ IAB-2, เอกสาร และความรู้สึกสำหรับการจำแนกประเภทที่หลากหลาย"

    # feature loop
    - icon: "rasterize"
      title: "รองรับหลายภาษา"
      content: "ทำการจำแนกประเภทความรู้สึกได้ทั้งภาษาอังกฤษและภาษาจีน"

    # feature loop
    - icon: "sourcecode"
      title: "ผลลัพธ์ที่ปรับแต่งได้"
      content: "ระบุจำนวนผลลัพธ์การจำแนกประเภทที่จะส่งคืน"

    # feature loop
    - icon: "transform"
      title: "การควบคุมความแม่นยำ"
      content: "ปรับความสมดุลระหว่างความแม่นยำ/การเรียกคืนสำหรับการจำแนกประเภทระบบการจัดหมวดหมู่เอกสาร"

    # feature loop
    - icon: "adjustment"
      title: "รูปแบบไฟล์หลายประเภท"
      content: "เข้ากันได้กับรูปแบบเอกสารต่างๆ รวมถึง PDF, DOC, DOCX, RTF และ TXT"

    # feature loop
    - icon: "complex"
      title: "การผสานรวมที่ง่าย"
      content: "ผสานรวมเข้ากับแอปพลิเคชัน .NET ใดๆ ได้อย่างราบรื่น รวมถึง ASP.NET และแอป Windows"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างโค้ด"
  description: "กรณีการใช้งานบางอย่างของการดำเนินการ GroupDocs.Classification ทั่วไปสำหรับ .NET"
  items:
    # code sample loop
    - title: "จำแนกประเภทข้อความโดยใช้ระบบการจัดหมวดหมู่ IAB-2"
      content: |
        ตัวอย่างนี้แสดงวิธีการจำแนกประเภทข้อความดิบโดยใช้ระบบการจัดหมวดหมู่ IAB-2:
        
        ```csharp {style=abap}
        // สร้างคำขอการจำแนกประเภท
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "ลองการจำแนกประเภทข้อความ"
        }, "3");

        // รับผลลัพธ์การจำแนกประเภท
        var response = apiInstance.Classify(request);

        // พิมพ์ผลลัพธ์
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "การวิเคราะห์ความรู้สึกของเอกสาร"
      content: |
        คุณสามารถทำการวิเคราะห์ความรู้สึกบนเอกสารโดยใช้ระบบการจัดหมวดหมู่ความรู้สึก:
        
        ```csharp {style=abap}
        // สร้างอินสแตนซ์ของ Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // จำแนกประเภทเอกสารโดยใช้ระบบการจัดหมวดหมู่ความรู้สึก
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // พิมพ์ความรู้สึกและความน่าจะเป็น
        Console.WriteLine($"ความรู้สึก: {response.BestClassName}");
        Console.WriteLine($"ความน่าจะเป็น: {response.BestClassProbability}");
        ```

---
