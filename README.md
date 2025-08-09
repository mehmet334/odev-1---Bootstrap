# Mehmet Ali'nin Kamp Blogu

Bootstrap 4.5 ile hazırlanmış, doğa ve kamp temalı bir blog sayfası.  
Projede jumbotron tanıtım alanı, kamp alanları kartları ve isteğe bağlı kayan bilgilendirme kartı (floating card) bulunuyor.

## 📸 Özellikler

- **Responsive Tasarım** – Mobil, tablet ve masaüstü uyumlu.
- **Bootstrap 4.5** – Grid sistemi, navbar, kart ve jumbotron bileşenleri.
- **Kamp Alanı Kartları** – Sülüklü Göl, Pürenli Yaylası, Erikli Yaylası, Torkul Göleti.
- **Floating Card** – Sağ altta kayan kısa bilgi kutusu (örnek: Green Card başvuru).
- **Kolay Özelleştirme** – Görseller ve metinler kolayca değiştirilebilir.

## 🛠️ Kullanılan Teknolojiler

- **HTML5**
- **CSS3**
- **Bootstrap 4.5 (CDN)**
- **JavaScript (Bootstrap JS + jQuery)**

## 📂 Proje Yapısı

proje/<br>
│<br>
├── index.html # Ana HTML sayfası <br>
├── img/ # Görseller<br>
│ ├── suluklu-gol-yansima-fotograflari.jpg<br>
│ ├── purenli_kamp.jpg<br>
│ ├── erikli-selalesi-kamp-alani.png<br>
│ ├── torkul goleti.jpg<br>
│ └── greencard.jpg<br>



## 🚀 Kurulum ve Çalıştırma

1. Depoyu klonla veya ZIP olarak indir:
   ```bash
   git clone https://github.com//mehmet334/odev-1---Bootstrap.git
index.html dosyasını tarayıcıda aç.

Görselleri img/ klasöründe değiştir.

style.css dosyasını düzenleyerek tasarımı özelleştir.

📌 Geliştirme Notları
Jumbotron bölümü Bootstrap 4.5 ile .jumbotron veya Bootstrap 5 uyumlu bg-light p-5 rounded-3 sınıfları ile yapılabilir.

Kart yükseklikleri .card-img-top ve .card CSS tanımları ile kontrol edilir.

Floating card, isteğe bağlı olarak kaldırılabilir veya farklı bilgilerle güncellenebilir.
