# ♻️ RecycleByBits

RecycleByBits, Discord’da görsel tabanlı bir atık analiz ve geri dönüşüm öneri botudur.  
Google Teachable Machine + Google Colab entegrasyonu ile çalışır.  
Kullanıcıların yüklediği resimleri analiz eder.


## Botun Çalışma Prensibi

1️⃣ Kullanıcı botu etiketleyip bir resim gönderir:

2️⃣ Bot şunları yapar:

- 📸 Resmi Google Teachable Machine modeli ile analiz eder.
- ✅ Atık türünü tespit eder (plastik, cam, kağıt, metal, elektronik vb.).
- 📊 Doğruluk oranını belirtir.
- ♻️ Geri dönüşüm yöntemini anlatır.
- 🎥 Eğlenceli yapım videosu linki paylaşır.
- ⏰ Kaç saniyede cevap verdiğini gösterir.


## Kurulum ve Çalıştırma

1. Discord bot tokeni alın (https://discord.com/developers/applications)  
2. Gerekli kütüphaneleri yükleyin:  

`pip install discord.py aiohttp`

3. Bot kodunu yazın ve çalıştırın.
4. Google Colab üzerinde model servisini başlatıp botu entegre edin.

## Desteklenen Atık Türleri
- 🧴 Plastik

- 🍾 Cam

- 📄 Kağıt / Karton

- 🥫 Metal

- 💻 Elektronik Atık

## Kaynaklar

- Google Teachable Machine

- Google Colab

- ÇEVKO Geri Dönüşüm Bilgileri

- UNEP Gıda İsrafı ve İklim

## Geliştirici
### Proje: RecycleByBits
### Geliştirici: Melotyz(Melih)
#### Hackathon için çevre bilinci kazandıran yapay zeka destekli atık analiz botu. 
