# TaskPro QA Project

Manual & API Testing for TaskPro application.

Bu proje, verilen şartname ve Figma tasarımlarına göre UI (kullanıcı arayüzü) ve API testlerinin manuel olarak hazırlanması ve çalıştırılması sürecini kapsamaktadır. Test senaryoları TestRail üzerinde yazılmış ve koşulmuştur. API testleri ayrıca Postman ile çalıştırılmış, Newman ile raporlanmıştır.


## Proje Kaynakları

- 🌐 **UI Uygulaması (Test Edilen Web Uygulama)**: [TaskPro QA Web App](https://task-pro-qa.f.goit.study/welcome)
- 📚 **Swagger API Dokümantasyonu**: [Swagger Docs](https://task-pro-qa.b.goit.study/api-docs/#/)
- 🎨 **Figma Tasarımı**: [Figma UI Design](https://www.figma.com/design/eZAtuel003P5Cp8tALfO5z/TaskPro--QA-?node-id=0-1&p=f)

## Proje Kapsamı 

- UI ve API uç noktaları için **manuel test senaryoları** yazıldı ve uygulandı.  
- **Figma tasarımları** ve gereksinim dökümanlarına göre test senaryoları oluşturuldu.  
- API testleri için **Postman koleksiyonu** hazırlandı ve çalıştırıldı.  
- **Newman** kullanılarak API testleri otomatikleştirildi ve detaylı test raporları alındı.  
- Tüm test senaryoları **TestRail** üzerinden dokümante edildi ve takip edildi.
   
## 🔧 Kullanılan Araçlar ve Teknolojiler

- **Test Yönetimi:** TestRail  
- **API Testleri:** Postman, Newman  
- **Dokümantasyon:** Swagger  
- **Raporlama:** Newman HTML & PDF Raporları
  
## 📁 - Proje Yapısı 
```
taskpro-qa-project/
├── documents/
│   ├── testplan.pdf              # Test plan dokümanı (PDF)
│   ├── manual-tests/             # Manuel test senaryoları klasörü
│   └── taskpro.xml               # Manuel test senaryoları (XML formatında)
├── postman/
│   ├── environment.json          # Environment ayarları
│   ├── swagger.json              # Swagger API tanımı
│   └── taskpro.json              # Postman koleksiyonu
├── reports/
│   ├── Newman Summary Report.pdf         # API test özeti (PDF)
│   ├── newman-taskpro-report-2025-06-30.html  # HTML API test raporu
│   ├── testrail-report-apitests.pdf      # API test senaryoları raporu
│   └── testrail-report-ui.pdf            # UI test senaryoları raporu
└── README.md                     # Proje açıklamaları
```


## Raporlar

TestRail ve Newman ile oluşturduğum raporları `reports/` klasörü altında görüntüleyebilirsiniz. TestRail'de yazılmış manuel test senaryoları da `manual-tests/` klasörüne eklenmiştir.

## Otomasyon Testleri Hakkında

Otomasyon testleri öğrenme sürecim **henüz yeni başlamış olup**, Java dili ve Selenium framework’ü kullanarak IntelliJ IDEA ortamında geliştirmeye devam ediyorum. Proje kapsamında Selenium tabanlı otomasyon testlerini zamanla geliştirmeyi ve mevcut çalışmaları repoya eklemeyi planlıyorum.



## Proje Sahibi
Zuhal Şeker  
📧 skrzhl@gmail.com
💼 [GitHub Profilim](https://github.com/zzuhal)

