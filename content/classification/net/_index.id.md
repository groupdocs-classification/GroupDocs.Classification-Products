---
layout: "product"
date: 2022-07-07T12:44:18+03:00
draft: false

product: "Classification"
product_tag: "classification"
platform: ".NET"
platform_tag: "net"

head_title: "C# .NET Dokumen & Klasifikasi Teks dan Analisis Sentimen API"
head_description: "Klasifikasi dokumen dan teks mentah dengan c# .NET API. Kategorisasi dengan taksonomi IAB-2 dan Dokumen dan analisis sentimen konsumen dengan Sentimen taksonomi."

title: ".API Klasifikasi Teks & Dokumen .NET"
description: "Berdayakan aplikasi .NET Anda dengan kemampuan Pengklasifikasi File & Teks menggunakan tag atau kategori yang telah ditentukan sebelumnya dalam taksonomi IAB-2, Dokumen, dan Sentimen."
button:
    enable: true

submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Classification for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-net.png"
        product: "GroupDocs.Classification"
        platform: ".NET"

    middle:
        button:
            - link: "#overview"
              text: "Ringkasan"

            - link: "#features"
              text: "Fitur"

            - link: "#support"
              text: "Mendukung"

            - link: "https://products.groupdocs.app/classification"
              text: "Demo Langsung"

            - link: "https://purchase.groupdocs.com/pricing/classification/net"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/classification"
        link_learn: "https://docs.groupdocs.com/classification/net/"
        link_buy: "https://purchase.groupdocs.com"

overview:
    enable: true
    content: |
      GroupDocs.Classification for .NET adalah C# Netstandard 2.0 API intuitif yang membantu Anda membuat aplikasi klasifikasi/kategorisasi teks dan dokumen yang kuat di C#, ASP.NET, dan teknologi berbasis .NET lainnya. API mendukung empat jenis taksonomi yang berbeda dan menawarkan klasifikasi dokumen dan teks tingkat lanjut dengan menggunakan IAB-2 untuk menetapkan kategori teks standar, Taksonomi dokumen yang dikembangkan oleh Aspose untuk berbagai jenis dokumen, atau Sentimen (dan Sentimen3) untuk analisis sentimen. API menganalisis teks, kalimat, bahkan kata-kata dan mendukung klasifikasi berbagai format dokumen standar industri termasuk PDF, Microsoft Word, OpenDocument, RTF, dan TXT. Analisis sentimen (klasifikasi) mendukung bahasa Inggris, Cina, Spanyol, dan Jerman dengan deteksi otomatis bahasa. API dapat mengembalikan probabilitas positif yang dapat digunakan untuk analisis sentimen berbutir halus di C#.  

      GroupDocs.Classification untuk .NET menggunakan mesin pengolah/klasifikasi dokumennya sendiri dan tidak memerlukan alat eksternal apa pun untuk diinstal pada sistem. Ini menargetkan platform .NET untuk mengembangkan aplikasi dan mendukung semua sistem operasi populer (Windows, Linux, macOS) di mana kerangka kerja .NET (termasuk .NET Core) dapat diinstal.
    tabs:
      enable: true
      
      tab_one:
        description: |
          Berikut ini adalah ikhtisar GroupDocs.Classification untuk .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Ringkasan"
          content: |
            * Klasifikasi dokumen berdasarkan jalur dan aliran
            * Klasifikasikan teks mentah
            * **IAB-2**, **Dokumen**, **Sentimen**, dan **Sentiment3** didukung taksonomi
            * Mendukung berbagai format dokumen
      
      tab_two:
        description: |
          GroupDocs.Classification untuk .NET [mendukung sejumlah format dokumen populer](https://docs.groupdocs.com/classification/net/supported-document-formats/).

        left:
          enable: true
          table:
            - title: "Microsoft Office"
              content: |
                * **Kata**: DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF

        right:
          enable: true
          table:
            - title: "Format lainnya"
              content: |
                * **Tata Letak Tetap**: PDF
                * **OpenDocument**: ODT, OTT
                * **Teks**: TXT

      tab_three:
        description: |
          GroupDocs.Classification untuk .NET mendukung Sistem Operasi, Kerangka & Manajer Paket berikut:
        
        left:
          enable: true
          table:
            - icon: "fab fa-windows"
              title: "Sistem operasi"
              content: |
                * Jendela 10 (x64)
                * Desktop Windows (x64)
                * Windows Server (x64)
                * Windows Azure
                * Mac OS X x64 (10.12+)
                * Linux

            - icon: "fas fa-code"
              title: "Kerangka yang Didukung"
              content: |
                * .NET Core 2.0 atau lebih baru
                * .NET Framework 4.7 atau lebih tinggi

        right:
          enable: true
          table:
            - icon: "fas fa-box"
              title: "Manajer Paket"
              content: |
                * NuGet

            - icon: "fas fa-tools"
              title: "Lingkungan Pengembangan"
              content: |
                * Microsoft Visual Studio
                * Xamarin.Android
                * Xamarin.IOS
                * Xamarin.Mac
                * MonoDevelop

features:
    enable: true
    title: "Fitur API Klasifikasi Teks & Dokumen Tingkat Lanjut"

    feature:
      - icon: "fas fa-copy"
        content: |
          Klasifikasikan dokumen berdasarkan jalur menggunakan taksonomi **IAB‑2**, **Documents**, **Sentiment**, atau **Sentiment3**

      - icon: "fas fa-eye"
        content: |
          Melakukan Klasifikasi Teks Mentah dengan taksonomi **IAB‑2**, **Documents**, **Sentiment**, atau **Sentiment3**

      - icon: "fas fa-bolt"
        content: "Klasifikasi Sentimen (Analisis) untuk bahasa Inggris, Cina, Spanyol, dan Jerman"
      
      - icon: "fas fa-file-powerpoint"
        content: "Pilih jumlah hasil rahasia untuk dikembalikan"

      - icon: "fas fa-code"
        content: "Bekerja dengan dokumen PDF, Docs, OpenOffice dan Rich Text"

      - icon: "fas fa-cloud"
        content: "100% Contoh Kerja & Demo Diberikan untuk Mempelajari Fitur yang Didukung dengan Cepat"

      - icon: "fas fa-remove-format"
        content: "Dukungan Teknis Gratis Tanpa Batas yang Disediakan melalui Forum Produk"

    more_feature:
      - title: "Klasifikasi Dokumen yang Tepat"
        content: |
          GroupDocs.Classification API mendukung klasifikasi untuk berbagai format dokumen. Contoh kode C# di bawah ini menunjukkan cara mengklasifikasikan file PDF dari folder saat ini dengan taksonomi Dokumen dengan mengembalikan 3 hasil terbaik.

          ```cs
          // Inisialisasi pengklasifikasi tujuan umum (IAB-2, Dokumen, Analisis Sentimen).
          var classifier = new GroupDocs.Classification.Classifier();

          // Klasifikasikan file pdf dengan taksonomi Dokumen dan kembalikan 3 kategori yang paling mungkin.
          var response = classifier.Classify("document.pdf", ".", 3, Taxonomy.Documents);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```
      - title: "Klasifikasi Teks Tepat"
        content: |
          GroupDocs.Classification API juga mendukung klasifikasi teks. Klasifikasi teks dapat dilakukan dengan 4 taksonomi yang berbeda: IAB-2, Documents, Sentiment, dan Sentiment3. Contoh kode C# di bawah ini menunjukkan cara mengklasifikasikan teks dengan taksonomi default (IAB-2) dengan mengembalikan hasil terbaik.

          ```cs
          // Inisialisasi pengklasifikasi tujuan umum (IAB-2, Dokumen, Analisis Sentimen).
          var classifier = new GroupDocs.Classification.Classifier();

          // Mengklasifikasikan teks dengan taksonomi IAB-2 dan mengembalikan kategori terbaik.
          var response = classifier.Classify("Classify text using the default IAB-2 taxonomy");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

      - title: "Analisis Sentimen Multibahasa yang Tepat"
        content: |
          GroupDocs.Classification untuk .NET memungkinkan untuk melakukan Analisis Sentimen (Klasifikasi) lintas domain dalam bahasa Inggris, Cina, Spanyol, dan Jerman. GroupDocs.Classification untuk .NET akan mendeteksi bahasa yang sesuai secara otomatis. Kasus penggunaan API analisis sentimen diilustrasikan oleh kode C# berikut:

          ```cs
          // Inisialisasi pengklasifikasi sentimen multibahasa lintas domain. 
          // SentimentClassifier mendukung klasifikasi multibahasa dengan bahasa Inggris, Cina, Spanyol, dan Jerman.
          var classifier = new GroupDocs.Classification.SentimentClassifier();

          // Analisis sentimen dari teks bahasa Inggris.
          var response = classifier.Classify("Experience is simply the name we give our mistakes");
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");

          // Analisis sentimen dari teks Cina dengan pengklasifikasi dan taksonomi Sentimen3 yang sama (Negatif/Netral/Positif).
          response = classifier.Classify("熟能生巧", taxonomy: Taxonomy.Sentiment3);
          Console.WriteLine($"{response.BestClassName}: {response.BestClassProbability}");
          ```

support:
    enable: true

solutions:
    enable: false
    title: "GroupDocs.Classification menawarkan API tampilan dokumen untuk lingkungan pengembangan populer lainnya"

    solution:
        - img_alt: "GroupDocs.Classification for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-classification-java.png"
          product: "GroupDocs.Classification"
          platform: "Java"
          link: "/classification/java/"

back_to_top:
  enable: true
---
