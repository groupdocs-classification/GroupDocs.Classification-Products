---
############################# Static ############################
layout: "family"
date:  2025-03-17T15:57:00
draft: false

product: "Classification"
product_tag: "classification"

lang: id

############################# Head ############################
head_title: "API .NET untuk Klasifikasi Dokumen & Teks dan Analisis Sentimen"
head_description: "Pustaka .NET yang kuat untuk klasifikasi dokumen dan teks menggunakan taksonomi IAB-2, Dokumen, dan Sentimen. Mendukung berbagai format file dan bahasa."

############################# Header ############################
title: "Solusi Klasifikasi Dokumen & Teks"
description: |
  Klasifikasikan dokumen dan teks dengan mudah menggunakan berbagai taksonomi dengan API .NET kami.

  Lakukan analisis sentimen dan kategorisasi konten di berbagai format file dan bahasa.

  Integrasikan kemampuan klasifikasi canggih ke dalam aplikasi .NET Anda hanya dengan beberapa baris kode.

############################# Supported Platforms ###############################
supported_platforms:
  enable: true
  head_title: "Pilih platform Anda"
  title: "Independensi platform"
  description: "GroupDocs.Classification untuk .NET kompatibel dengan sistem operasi dan framework berikut:"
  details_link_title: "Pelajari lebih lanjut"

  items:
    # items loop
    - title: ".NET"
      description: GroupDocs.Classification untuk .NET
      color: "blue"
      tag: "net"
      link: "/classification/net/"
      features_link: "https://docs.groupdocs.com/classification/net/system-requirements/"
      features:
          # features loop
          - rows: "3"
            content: |
                    .NET Core 2.0 atau lebih baru  .NET Framework 4.7 atau lebih tinggi
      
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
                    10+ format file

############################# Features ###############################
features:
  enable: true
  title: "Fitur utama GroupDocs.Classification"
  description: "Solusi ini membantu Anda mengklasifikasikan dokumen dan teks menggunakan berbagai taksonomi, melakukan analisis sentimen, dan mengintegrasikan kemampuan klasifikasi canggih ke dalam aplikasi .NET Anda."

  items:
    # items loop
    - icon: "classify"
      title: "Beberapa taksonomi"
      content: "Klasifikasikan menggunakan taksonomi IAB-2, Dokumen, dan Sentimen."

    # items loop
    - icon: "format"
      title: "Dukungan format yang luas"
      content: "Proses berbagai format dokumen termasuk DOC, DOCX, PDF, dan lainnya."

    # items loop
    - icon: "analyze"
      title: "Analisis sentimen"
      content: "Lakukan klasifikasi sentimen untuk teks bahasa Inggris dan Cina."

    # items loop
    - icon: "integrate"
      title: "Integrasi mudah"
      content: "Integrasikan kemampuan klasifikasi hanya dengan beberapa baris kode."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Klasifikasikan dokumen dengan mudah"
  description: "Contoh kode GroupDocs.Classification"
  items:
    # code sample loop
    - title: "Klasifikasikan PDF dengan Taksonomi IAB-2"
      content: |
       GroupDocs.Classification memungkinkan Anda dengan mudah mengklasifikasikan dokumen PDF menggunakan taksonomi IAB-2. Cukup tentukan jalur dokumen, jumlah hasil yang diinginkan, dan jenis taksonomi untuk mendapatkan hasil klasifikasi.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp
            // Buat instance Classifier
            var classifier = new GroupDocs.Classification.Classifier();

            // Klasifikasikan dokumen
            var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

            // Cetak kelas terbaik dan probabilitasnya
            Console.WriteLine($"Kelas terbaik: {response.BestClassName}, Probabilitas: {response.BestClassProbability}");
            ```

############################# Supported Formats ###############################
formats:
  enable: true
  title: "Mendukung 10+ format file"
  description: "GroupDocs.Classification bekerja dengan berbagai format dokumen populer"

############################# Metrics ###############################
metrics:
  enable: true
  title: "Metrik dan wawasan mendalam"
  description: "Selami metrik terperinci kami untuk pandangan komprehensif tentang kinerja dan pertumbuhan kami."

  items:
    # items loop
    - number: "10+"
      title: "Format yang Didukung"
      content: "Kami mendukung lebih dari 10 format dokumen yang paling banyak digunakan."

    # items loop
    - number: "3"
      title: "Taksonomi yang Didukung"
      content: "Klasifikasikan konten menggunakan taksonomi IAB-2, Dokumen, dan Sentimen."

    # items loop
    - number: "2"
      title: "Bahasa untuk Analisis Sentimen"
      content: "Lakukan klasifikasi sentimen dalam bahasa Inggris dan Cina."

    # items loop
    - number: "4.7+"
      title: "Dukungan .NET Framework"
      content: "Kompatibel dengan .NET Framework 4.7 atau lebih tinggi dan .NET Core 2.0 atau lebih baru."

############################# Actions ###############################
actions:
  enable: true
  title: "Siap untuk Memulai?"
  description: "Coba fitur GroupDocs.Classification secara gratis di platform Anda."

  items:
    # items loop
    - title: ".NET"
      color: "blue"
      link: "/classification/net/"

############################# FAQ ###############################
faq:
  enable: true
  title: "Pertanyaan yang Sering Diajukan"
  description: "Jawaban untuk pertanyaan umum tentang GroupDocs.Classification."

  items:
    # items loop
    - question: "Jenis dokumen apa yang dapat saya klasifikasikan dengan GroupDocs.Classification?"
      answer: "GroupDocs.Classification mendukung berbagai format dokumen termasuk Microsoft Word (DOC, DOCX, RTF), OpenOffice (ODT), PDF, dan file teks biasa (TXT)."

    # items loop
    - question: "Bisakah saya menggunakan GroupDocs.Classification untuk analisis sentimen?"
      answer: "Ya, GroupDocs.Classification mendukung analisis sentimen untuk teks bahasa Inggris dan Cina, memungkinkan Anda menentukan sentimen dokumen atau cuplikan teks."

    # items loop
    - question: "Apakah mungkin untuk mengintegrasikan GroupDocs.Classification ke dalam aplikasi .NET yang sudah ada?"
      answer: "Tentu saja! GroupDocs.Classification menawarkan API yang ramah pengguna yang dapat dengan mudah diintegrasikan ke dalam aplikasi .NET Anda hanya dengan beberapa baris kode. Dirancang untuk bekerja secara mulus dengan alur kerja yang sudah ada."

############################# Cloud Links ###############################
cloud_links:
  enable: false

############################# App links ###############################
app_links:
  enable: false
---
