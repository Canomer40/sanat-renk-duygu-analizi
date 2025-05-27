# sanat-renk-duygu-analizi
ENM421 Projesi - Sanat Akımlarında Renk ve Duygu Analizi
## 📌 Proje Açıklaması
Bu proje, farklı sanat akımlarının renk paletlerinin izleyicilerde oluşturduğu duygularla ilişkisini analiz etmeyi amaçlar. Renk tonu (Hue), doygunluk (Saturation) ve parlaklık (Lightness) gibi HSL özellikleri kullanılarak duygusal kümeler belirlenmiştir.

## ⚙️ Kullanılan Yöntemler
- **Veri seti:** WikiArt (13 sanat akımı)
- **Ön işleme:** Görsellerin boyutlandırılması ve baskın 3 rengin çıkarılması
- **Renk uzayı dönüşümü:** RGB'den HSL'ye
- **Kümeleme:** K-Means (K=5)
- **İstatistiksel analiz:** Ki-Kare Testi

## 🗂️ Kullanılan Veri Setleri

1. 📄 `wikiart_rgb_3colors_per_image.csv`  
   → Her sanat eseri için çıkarılmış 3 baskın rengin RGB değerlerini içeren dosya. Bu dosya bu repoya dahil edilmiştir.

2. 🌐 WikiArt Sanat Akımları – Kaggle Veri Seti  
   → Sanatçı adı, sanat akımı, başlık, tarih gibi meta veriler içeren geniş veri kümesi.  
   → Veri bağlantısı: https://www.kaggle.com/datasets/sivarazadi/wikiart-art-movementsstyles  
   → Bu veri seti, wikiart.org sitesinden farklı sanat akımlarına ait sanatçıların eserleri web kazıma yöntemiyle toplanarak oluşturulmuştur.  
   → Not: Dosya boyutu nedeniyle GitHub'a yüklenmemiştir, ancak analizlerde kullanılmıştır.

## 📈 Özet Sonuçlar
- Farklı sanat akımlarının belirgin renk-duygu eğilimleri ortaya kondu.
- Kümeleme ile benzer duygusal renk grupları elde edildi.
- Ki-Kare testi ile sanat akımı-duygu kümesi ilişkisi anlamlı bulundu.

## 👥 Ekip
- Hanife Nur Tınaz
- Yusuf Karakaya
- Ömer Can
