---
############################# Static ############################
layout: "landing"
date: 2025-03-17T22:16:00
draft: false

lang: id
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
head_title: "API .NET untuk Klasifikasi Teks dan Dokumen"
head_description: "API C# .NET untuk klasifikasi teks dan dokumen menggunakan taksonomi IAB-2, Dokumen, dan Sentimen. Klasifikasikan konten dalam berbagai format termasuk PDF, DOC, DOCX, RTF, dan TXT."

############################# Header ############################
title: "API Klasifikasi Teks dan Dokumen .NET"
description: "Klasifikasikan teks dan dokumen dalam aplikasi .NET menggunakan beberapa taksonomi."
words:
  for: "untuk"

actions:
  main: "Unduh Uji Coba melalui NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Classification"
  alt: "Lisensi"
  alt_link: "https://purchase.groupdocs.com/pricing/classification/net/"
  title: "Siap untuk Memulai?"
  description: "Coba fitur GroupDocs.Classification secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"
  link: "https://releases.groupdocs.com/classification/net/"

code:
  title: "Klasifikasikan PDF dengan Taksonomi IAB-2 di C#"
  more: "Contoh lainnya"
  more_link: "https://github.com/groupdocs-classification/GroupDocs.Classification-for-.NET"
  install: "dotnet add package GroupDocs.Classification"
  content: |
    ```csharp {style=abap}   
    // Buat instance Classifier
    var classifier = new GroupDocs.Classification.Classifier();

    // Klasifikasikan dokumen PDF menggunakan taksonomi IAB-2
    var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Iab2);

    // Cetak nama kelas terbaik dan probabilitasnya
    Console.WriteLine(response.BestClassName);
    Console.WriteLine(response.BestClassProbability);
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Ikhtisar GroupDocs.Classification"
  description: "Solusi .NET untuk klasifikasi teks dan dokumen otomatis menggunakan berbagai taksonomi."
  features:
    # feature loop
    - title: "Klasifikasikan Teks dan Dokumen dengan C#"
      content: "Klasifikasikan konten dengan mudah menggunakan taksonomi IAB-2, Dokumen, dan Sentimen dengan GroupDocs.Classification untuk .NET."

    # feature loop
    - title: "Dukungan untuk Berbagai Format File"
      content: "Proses berbagai jenis dokumen termasuk PDF, DOC, DOCX, RTF, TXT, dan lainnya."

    # feature loop
    - title: "Opsi Klasifikasi yang Fleksibel"
      content: "Pilih jumlah hasil yang akan dikembalikan dan sesuaikan keseimbangan presisi/recall untuk taksonomi Dokumen."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi platform"
  description: "GroupDocs.Classification untuk .NET mendukung sistem operasi, framework, dan manajer paket berikut"
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
  title: "Format file yang didukung"
  description: |
    GroupDocs.Classification untuk .NET mendukung operasi dengan [format file](https://docs.groupdocs.com/classification/net/supported-document-formats/) berikut.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Format Microsoft Office
        * **Word:** DOC, DOCM, DOCX, DOT, DOTM, DOTX, RTF
    # group loop
    - color: "blue"
      content: |
        ### Format OpenDocument & Lainnya
        * **OpenOffice:** ODT, OTT
        * **Tata Letak Tetap:** PDF
        * **Lainnya:** TXT

############################# Features ############################
features:
  enable: true
  title: "Fitur GroupDocs.Classification"
  description: "Klasifikasikan teks dan dokumen menggunakan taksonomi dan opsi lanjutan."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Beberapa Taksonomi"
      content: "Mendukung taksonomi IAB-2, Dokumen, dan Sentimen untuk klasifikasi yang serbaguna."

    # feature loop
    - icon: "rasterize"
      title: "Dukungan Multi-Bahasa"
      content: "Lakukan klasifikasi sentimen dalam bahasa Inggris dan Cina."

    # feature loop
    - icon: "sourcecode"
      title: "Hasil yang Dapat Disesuaikan"
      content: "Tentukan jumlah hasil klasifikasi yang akan dikembalikan."

    # feature loop
    - icon: "transform"
      title: "Kontrol Presisi"
      content: "Sesuaikan keseimbangan presisi/recall untuk klasifikasi taksonomi Dokumen."

    # feature loop
    - icon: "adjustment"
      title: "Berbagai Format File"
      content: "Kompatibel dengan berbagai format dokumen termasuk PDF, DOC, DOCX, RTF, dan TXT."

    # feature loop
    - icon: "complex"
      title: "Integrasi Mudah"
      content: "Integrasikan dengan mulus ke dalam aplikasi .NET apa pun, termasuk ASP.NET dan aplikasi Windows."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Classification untuk .NET yang umum"
  items:
    # code sample loop
    - title: "Klasifikasikan Teks menggunakan Taksonomi IAB-2"
      content: |
        Contoh ini menunjukkan cara mengklasifikasikan teks mentah menggunakan taksonomi IAB-2:
        
        ```csharp {style=abap}
        // Buat permintaan klasifikasi
        var request = new ClassifyRequest(new BaseRequest()
        {
            Description = "Coba klasifikasi Teks"
        }, "3");

        // Dapatkan hasil klasifikasi
        var response = apiInstance.Classify(request);

        // Cetak hasilnya
        Console.WriteLine(response.ToString());
        ```
        
    # code sample loop
    - title: "Analisis Sentimen Dokumen"
      content: |
        Anda dapat melakukan analisis sentimen pada dokumen menggunakan taksonomi Sentimen:
        
        ```csharp {style=abap}
        // Buat instance Classifier
        var classifier = new GroupDocs.Classification.Classifier();

        // Klasifikasikan dokumen menggunakan taksonomi Sentimen
        var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Sentiment);

        // Cetak sentimen dan probabilitasnya
        Console.WriteLine($"Sentimen: {response.BestClassName}");
        Console.WriteLine($"Probabilitas: {response.BestClassProbability}");
        ```

---