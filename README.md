# 🌦️ Flutter Hava Durumu Uygulaması

Bu proje, **Flutter** ile geliştirilmiş bir **hava durumu uygulamasıdır**.  
Uygulama, **OpenWeatherMap API** üzerinden gerçek zamanlı hava durumu verilerini **Dio** paketiyle çekerek kullanıcıya gösterir.  
Kullanıcı, şehir adını yazarak o bölgenin anlık hava durumu bilgilerini görüntüleyebilir.

---

## 🖥️ Uygulama Özeti

- Şehir seçilerek anlık hava durumu görüntülenir  
- **Dio paketi** ile REST API üzerinden veri çekilir  
- Gelen JSON verileri **model sınıflarıyla parse edilir**  
- Basit, sade ve kullanıcı dostu bir **Flutter arayüzü**  
- Responsive yapı (farklı ekran boyutlarına uyumlu)

---

## 🚀 Özellikler

✅ Şehir ismine göre hava durumu sorgulama  
✅ Sıcaklık, hissedilen sıcaklık, nem, rüzgar hızı gibi bilgiler  
✅ OpenWeatherMap API kullanımı  
✅ Temiz ve anlaşılır Flutter UI  
✅ Asenkron veri çekme (FutureBuilder ile)  
✅ Hata yakalama ve yüklenme animasyonu  

---

## 🧰 Kullanılan Teknolojiler

| Teknoloji | Açıklama |
|------------|-----------|
| **Flutter** | Mobil uygulama geliştirme framework'ü |
| **Dart** | Flutter programlama dili |
| **Dio** | HTTP istekleri ve hata yönetimi için kullanıldı |
| **OpenWeatherMap API** | Hava durumu verilerini sağlayan API |

---

## ⚙️ Kurulum ve Çalıştırma

1. **Projeyi klonla:**
   ```bash
   git clone https://github.com/MustafaCalbak42/Hava-Durumu.git
Proje dizinine gir:
cd Hava-Durumu
Gerekli paketleri yükle:

flutter pub get

OpenWeatherMap API anahtarını ekle:

lib/services/weather_service.dart dosyasına git

Aşağıdaki şekilde kendi API anahtarını gir:
const String apiKey = 'YOUR_API_KEY';

Uygulamayı başlat:

flutter run

🧩 Dosya Yapısı
lib/
│
├── main.dart                # Giriş noktası
├── models/
│   └── weather_model.dart   # JSON verisini parse eden model
├── services/
│   └── weather_service.dart # Dio ile API’den veri çeken servis
└── widgets/
    └── weather_card.dart    # Arayüzde hava durumu gösterimi
  

💡 Öğrenilenler
Flutter'da HTTP istekleri atmak için Dio kullanımı

Asenkron programlama (async/await, FutureBuilder)

JSON verilerini model sınıflarına dönüştürme

API’den gelen hataları yakalama ve yönetme

Flutter UI yapısında veri tabanlı güncellemeler

📸 Ekran Görüntüleri
![WhatsApp Görsel 2025-10-07 saat 17 05 21_b807f7ed](https://github.com/user-attachments/assets/2f892cbd-acde-4ab8-a831-39f329db3434)

![WhatsApp Görsel 2025-10-07 saat 17 05 21_522b4163](https://github.com/user-attachments/assets/925066a6-9d47-468a-b271-5e8449e653ee)

![WhatsApp Görsel 2025-10-07 saat 17 05 21_2982ea6e](https://github.com/user-attachments/assets/8471705d-1197-442d-9799-8826a8821e2c)





👨‍💻 Geliştirici
Mustafa Çalbak
🎓 Fırat Üniversitesi – Yazılım Mühendisliği
[🔗 LinkedIn](https://www.linkedin.com/in/mustafa-calbak/)
