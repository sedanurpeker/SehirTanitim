# 🌆 Bursa Şehri Tanıtım Uygulaması

Bu proje, ASP.NET MVC 5 teknolojisi ile geliştirilen bir şehir tanıtım web sitesi ile, Android cihazlarda çalışan bir mobil uygulamadan oluşan **çok katmanlı** bir yazılım projesidir. Bursa şehrine ait turistik yerler, ilçeler, nüfus bilgileri gibi detaylar kullanıcı dostu bir arayüz ile sunulmaktadır.

---

## 🚀 Proje Özellikleri

### 🖥️ Web Uygulaması (ASP.NET MVC 5)

- ASP.NET MVC 5 ile geliştirildi
- Microsoft SQL Server veritabanı kullanıldı
- Kullanıcı giriş/kayıt sistemi mevcut
- Rol bazlı yetkilendirme (Admin / Üye)
- Admin panel üzerinden:
  - Slider yönetimi
  - Şehir tanıtım metni
  - Nüfus verileri
  - İlçeler
  - Turistik yerler yönetilebilmektedir.
- Mobil uyumlu (responsive) tasarım
- View'larda dinamik içerik görüntüleme

### 📱 Android Mobil Uygulama

- Android Studio ile geliştirildi
- WebView bileşeni kullanılarak web sitesi uygulama içinde gösterildi
- Uygulama çalıştığında doğrudan http://www.bursa0106.somee.com/ adresine bağlanır
- Kullanıcı dostu ve sade arayüz
- Web ile senkronize çalışan yapı

---

## 🧠 Kullanılan Teknolojiler

- ASP.NET MVC 5
- Microsoft SQL Server
- Entity Framework
- HTML / CSS / Bootstrap
- C#
- Android Studio
- Java
- WebView

---

## 📁 Klasör Yapısı

| Dosya/Klasör                | Açıklama                                 |
|----------------------------|------------------------------------------|
| `bin/`                     | Derlenmiş çalışma dosyaları              |
| `Content/`                 | CSS stilleri ve görseller                |
| `Scripts/`                 | JavaScript dosyaları                     |
| `Views/`                   | ASP.NET Razor View sayfaları             |
| `WebApp/`                  | Android mobil uygulama kaynak kodları    |
| `Global.asax`              | ASP.NET uygulama yaşam döngüsü dosyası   |
| `Web.config`               | Uygulama yapılandırma ayarları           |
| `favicon.ico`              | Site simgesi                             |
| `22010903060_sedanur_peker.pdf` | Detaylı PDF proje raporu            |

---

## 📸 Ekran Görüntüleri

📌 Web sitesi ekran görüntüleri, Android uygulama arayüzü ve admin paneli ekran görüntüleri için `22010903060_sedanur_peker.pdf` dosyasını inceleyebilirsiniz.

---

## 👩‍💻 Geliştirici

**👩 Sedanur Peker**  
📧 İletişim için: sedanurpeker05@gmail.com

---

## 📦 Kurulum & Kullanım

> Bu proje GitHub üzerinde sadece kaynak kodlarıyla paylaşılmıştır. Canlı demo: **[http://www.bursa0106.somee.com](http://www.bursa0106.somee.com)**

1. Web kısmı için Visual Studio ile açıp `SQL Server` bağlantısını güncelleyin.
2. Android kısmı için `WebApp/` klasörünü Android Studio ile açıp `MainActivity.java` içindeki URL’yi güncelleyerek kendi projenize entegre edebilirsiniz.
