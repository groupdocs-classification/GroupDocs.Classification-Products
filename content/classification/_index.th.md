---
############################# Static ############################
layout: "family"
date: 2025-03-17T15:57:00
draft: false

product: "การจำแนกประเภท"
product_tag: "classification"

lang: th

############################# Head ############################
head_title: "API .NET สำหรับการจำแนกประเภทเอกสารและข้อความ และการวิเคราะห์ความรู้สึก"
head_description: "ไลบรารี .NET ที่ทรงพลังสำหรับการจำแนกประเภทเอกสารและข้อความโดยใช้ระบบอนุกรมวิธาน IAB-2, เอกสาร และความรู้สึก รองรับหลายรูปแบบไฟล์และภาษา"

############################# Header ############################
title: "โซลูชันการจำแนกประเภทเอกสารและข้อความ"
description: |
  จำแนกประเภทเอกสารและข้อความได้อย่างง่ายดายโดยใช้ระบบอนุกรมวิธานต่างๆ ด้วย API .NET ของเรา

  ทำการวิเคราะห์ความรู้สึกและจัดหมวดหมู่เนื้อหาในหลายรูปแบบไฟล์และภาษา

  รวมความสามารถในการจำแนกประเภทขั้นสูงเข้ากับแอปพลิเคชัน .NET ของคุณด้วยโค้ดเพียงไม่กี่บรรทัด

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "เลือกแพลตฟอร์มของคุณ"
  title: "ความเป็นอิสระของแพลตฟอร์ม"
  description: "GroupDocs.Classification สำหรับ .NET เข้ากันได้กับระบบปฏิบัติการและเฟรมเวิร์กต่อไปนี้:"
  details_link_title: "เรียนรู้เพิ่มเติม"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification สำหรับ .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 หรือใหม่กว่า  .NET Framework 4.7 หรือสูงกว่า
      
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
                    รูปแบบไฟล์มากกว่า 10 รูปแบบ

############################# Features ###############################
features:
  enable: true
  title: "คุณสมบัติหลักของ GroupDocs.Classification"
  description: "โซลูชันนี้ช่วยให้คุณจำแนกประเภทเอกสารและข้อความโดยใช้ระบบอนุกรมวิธานต่างๆ ทำการวิเคราะห์ความรู้สึก และรวมความสามารถในการจำแนกประเภทขั้นสูงเข้ากับแอปพลิเคชัน .NET ของคุณ"

  items:
    # items loop
    - icon: "classify"
      title: "หลายระบบอนุกรมวิธาน"
      content: "จำแนกประเภทโดยใช้ระบบอนุกรมวิธาน IAB-2, เอกสาร และความรู้สึก"

    # items loop
    - icon: "format"
      title: "รองรับรูปแบบที่หลากหลาย"
      content: "ประมวลผลรูปแบบเอกสารต่างๆ รวมถึง DOC, DOCX, PDF และอื่นๆ"

    # items loop
    - icon: "analyze"
      title: "การวิเคราะห์ความรู้สึก"
      content: "ทำการจำแนกประเภทความรู้สึกสำหรับข้อความภาษาอังกฤษและจีน"

    # items loop
    - icon: "integrate"
      title: "การรวมเข้าด้วยกันอย่างง่ายดาย"
      content: "รวมความสามารถในการจำแนกประเภทด้วยโค้ดเพียงไม่กี่บรรทัด"

############################# Code samples ############################
code_samples:
  enable: true
  title: "จำแนกประเภทเอกสารได้อย่างง่ายดาย"
  description: "ตัวอย่างโค้ด GroupDocs.Classification"
  items:
    # code sample loop
    - title: "จำแนกประเภท PDF ด้วยระบบอนุกรมวิธาน IAB-2"
      content: |
       GroupDocs.Classification ช่วยให้คุณจำแนกประเภทเอกสาร PDF ได้อย่างง่ายดายโดยใช้ระบบอนุกรมวิธาน IAB-2 เพียงระบุเส้นทางเอกสาร จำนวนผลลัพธ์ที่ต้องการ และประเภทของระบบอนุกรมวิธานเพื่อรับผลการจำแนกประเภท
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // สร้างอินสแตนซ์ของ Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // จำแนกประเภทเอกสาร
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // พิมพ์คลาสที่ดีที่สุดและความน่าจะเป็น
            Console.WriteLine($"คลาสที่ดีที่สุด: {response.BestClassName}, ความน่าจะเป็น: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "รองรับรูปแบบไฟล์มากกว่า 10 รูปแบบ"
  description: "GroupDocs.Classification ทำงานกับรูปแบบเอกสารยอดนิยมต่างๆ"

############################# Metrics ###############################
metrics:
  enable: true
  title: "ข้อมูลเชิงลึกและเมตริกอย่างละเอียด"
  description: "เจาะลึกเมตริกอย่างละเอียดของเราเพื่อดูภาพรวมที่ครอบคลุมของประสิทธิภาพและการเติบโตของเรา"

  items:
    # items loop
    - number: "10+"
      title: "รูปแบบที่รองรับ"
      content: "เรารองรับรูปแบบเอกสารที่ใช้กันอย่างแพร่หลายมากกว่า 10 รูปแบบ"

    # items loop
    - number: "3"
      title: "ระบบอนุกรมวิธานที่รองรับ"
      content: "จำแนกประเภทเนื้อหาโดยใช้ระบบอนุกรมวิธาน IAB-2, เอกสาร และความรู้สึก"

    # items loop
    - number: "2"
      title: "ภาษาสำหรับการวิเคราะห์ความรู้สึก"
      content: "ทำการจำแนกประเภทความรู้สึกในภาษาอังกฤษและจีน"

    # items loop
    - number: "4.7+"
      title: "การรองรับ .NET Framework"
      content: "เข้ากันได้กับ .NET Framework 4.7 หรือสูงกว่า และ .NET Core 2.0 หรือใหม่กว่า"

############################# Actions ###############################
actions:
  enable: true
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติของ GroupDocs.Classification ฟรีบนแพลตฟอร์มของคุณ"

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "คำถามที่พบบ่อย"
  description: "คำตอบสำหรับคำถามทั่วไปเกี่ยวกับ GroupDocs.Classification"

  items:
    # items loop
    - question: "ฉันสามารถจำแนกประเภทเอกสารประเภทใดได้บ้างด้วย GroupDocs.Classification?"
      answer: "GroupDocs.Classification รองรับรูปแบบเอกสารต่างๆ รวมถึง Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF และไฟล์ข้อความธรรมดา (TXT)"

    # items loop
    - question: "ฉันสามารถใช้ GroupDocs.Classification สำหรับการวิเคราะห์ความรู้สึกได้หรือไม่?"
      answer: "ได้ GroupDocs.Classification รองรับการวิเคราะห์ความรู้สึกสำหรับข้อความภาษาอังกฤษและจีน ช่วยให้คุณสามารถกำหนดความรู้สึกของเอกสารหรือข้อความสั้นๆ ได้"

    # items loop
    - question: "เป็นไปได้หรือไม่ที่จะรวม GroupDocs.Classification เข้ากับแอปพลิเคชัน .NET ที่มีอยู่ของฉัน?"
      answer: "แน่นอน! GroupDocs.Classification มี API ที่ใช้งานง่ายซึ่งสามารถรวมเข้ากับแอปพลิเคชัน .NET ของคุณได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด ออกแบบมาเพื่อทำงานร่วมกับเวิร์กโฟลว์ที่มีอยู่ของคุณได้อย่างราบรื่น"

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
