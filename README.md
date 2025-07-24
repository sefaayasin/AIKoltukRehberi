# 🎭 Tiyatro Koltuk Seçimi Rehberi

Bu proje, tiyatro salonlarında **kullanıcının kişisel tercih ve ihtiyaçlarına göre en uygun 5 koltuğu** öneren bir masaüstü uygulamasıdır. Kullanıcıdan alınan bilgiler doğrultusunda, makine öğrenmesi modelleri ile **tercih ve memnuniyet tahmini** yapılır ve sonuçlar görsel olarak sunulur.

---

## 🧩 Proje Özellikleri

### ✅ Kullanıcı Girdileri
- Yaş
- Cinsiyet
- Tiyatro Deneyimi
- Ses Kalitesi Tercihi
- Sahneye Yakınlık Tercihi
- Fiyat Tercihi

### 🧠 Makine Öğrenmesi Modelleri
- `tercih_modeli.pkl`: Kullanıcının bir koltuğu tercih etme ihtimalini tahmin eder.
- `memnuniyet_modeli.pkl`: Tercih edilen koltuktan alınacak memnuniyet puanını tahmin eder.

### 🖼️ Görsel Arayüz
- PyQt5 ile tasarlanmış modern kullanıcı arayüzü.
- Koltuk önerileri, salon yerleşimi üzerinde **yeşil renk** ile vurgulanarak gösterilir.
- Arka plan görselleri ve özel ikon desteğiyle estetik bir deneyim sunar.

---

## 📁 Proje Dosyaları

| Dosya Adı                      | Açıklama |
|-------------------------------|----------|
| `app_icon.png`                | Uygulama simgesi |
| `background1.png`             | Ana arayüz arka planı |
| `background2.png`             | Koltuk haritası arka planı |
| `koltuk_verisi.csv`           | Eğitim verisi (koltuk bilgileri) |
| `tercih_modeli.pkl`           | Tercih tahmin modeli |
| `memnuniyet_modeli.pkl`       | Memnuniyet tahmin modeli |
| `pyqt5_koltuk_rehberi.ipynb`  | Arayüz ve model entegrasyonunun anlatıldığı notebook |

---

## 🎯 Uygulama Akışı

1. Kullanıcı formu aracılığıyla tercihlerini belirtir.
2. Makine öğrenmesi modelleri en iyi 5 koltuğu belirler.
3. Önerilen koltuklar yazılı olarak ve **koltuk haritası görselinde yeşil renkle** sunulur.

---

## 🧠 Amaç

Bu proje, yapay zekâ destekli kişisel öneri sistemlerinin gerçek hayattaki bir senaryoya nasıl uygulanabileceğini göstermektedir. Eğitim verisi, modeller ve görsel bileşenler bu kapsamda bir araya getirilmiştir.

---

## 👤 Geliştirici

**Sefa Yasin Namlı**  
🔍 Veri Analizi & Uygulama Geliştirme  

---

