# 🎭 Tiyatro Koltuk Rehberi

Makine öğrenmesi destekli bu masaüstü uygulaması, tiyatro seyircilerinin kişisel tercihlerini analiz ederek en uygun koltukları önerir. PyQt5 ile geliştirilen uygulama, kullanıcıdan alınan bilgiler doğrultusunda en iyi 5 koltuğu belirler ve salon görseli üzerinde yeşil renkle gösterir.

## 🗂️ Proje Dosyaları

| Dosya Adı                    | Açıklama |
|-----------------------------|----------|
| `app_icon.png`              | Uygulama penceresi için ikon dosyası |
| `background1.png`           | Uygulamanın ana arka plan görseli |
| `background2.png`           | Koltuk haritası arka plan görseli |
| `koltuk_verisi.csv`         | Tiyatro salonu koltuklarına ait yapay veriseti |
| `memnuniyet_modeli.pkl`     | Kullanıcı memnuniyetini tahmin eden regresyon modeli |
| `tercih_modeli.pkl`         | Kullanıcının koltuğu tercih edip etmeyeceğini tahmin eden sınıflandırma modeli |
| `pyqt5_koltuk_rehberi.ipynb`| PyQt5 ile yazılmış arayüz uygulamasının notebook dosyası |

## ⚙️ Geliştirilen Özellikler

- 🎯 Kişisel tercihlere dayalı 5 ideal koltuğu önerir
- 🧠 ML modelleri ile tercih ve memnuniyet tahmini yapar
- 🎨 Modern ve kullanıcı dostu arayüz (PyQt5)
- 🖼️ Salon haritası üzerinde görsel geri bildirim sağlar
- 📁 Tüm dosyalar taşınabilir, aynı klasörde çalışacak şekilde yapılandırılmıştır

## 🧪 Kullanılan Teknolojiler

- Python 3.8+
- PyQt5
- scikit-learn
- pandas, numpy
- joblib

## 🚀 Başlatma Adımları

1. Gerekli kütüphaneleri kurun:
   ```bash
   pip install pyqt5 scikit-learn pandas numpy

2. Uygulamayı çalıştırmak için:

pyqt5_koltuk_rehberi.ipynb dosyasını Jupyter ile açarak adım adım çalıştırabilirsiniz.

👤 Geliştirici
Sefa Yasin Namlı
