# ♻️ RecycleByBits

RecycleByBits, Discord’da görsel tabanlı bir atık analiz ve geri dönüşüm öneri botudur.  
Google Teachable Machine Yapay Zeka entegrasyonu ile çalışır.  
Kullanıcıların yüklediği resimleri analiz eder.


## Botun Çalışma Prensibi

1️⃣ Kullanıcı /recycle komudu ile bir resim gönderir:

2️⃣ Bot şunları yapar:

- 📸 Resmi Google Teachable Machine modeli ile analiz eder.
- ✅ Atık türünü tespit eder (plastik, cam, kağıt, metal, elektronik vb.).
- 📊 Doğruluk oranını belirtir.
- ♻️ Geri dönüşüm yöntemini anlatır.
- 🎥 Eğlenceli yapım videosu linki paylaşır.


## Kurulum ve Çalıştırma

1. Discord bot tokeni alın (https://discord.com/developers/applications)  
2. Gerekli kütüphaneleri yükleyin:  

`pip install discord.py aiohttp`
`pip install tensorflow==2.3.1`
`pip install discord.py`

3. Bot kodunu yazın ve çalıştırın.
4. Model servisini başlatıp botu entegre edin.

## Desteklenen Atık Türleri
- 🧴 Plastik

- 🍾 Cam

- 📄 Kağıt / Karton

- 🥫 Metal

- 💻 Elektronik Atık

- 🥼 Eskimiş Kıyafet Ve Giysi

- 👟 Eskimiş Ayakkabı

### Bonus Kod: /categories

## Kaynaklar

- Google Teachable Machine

- ÇEVKO Geri Dönüşüm Bilgileri

- UNEP Gıda İsrafı ve İklim

## Geliştirici
### Proje: RecycleByBits
### Geliştirici: Melotyz(Melih)
#### Hackathon için yapılmış bir çevre bilinci kazandıran yapay zeka destekli atık analiz botu. 
