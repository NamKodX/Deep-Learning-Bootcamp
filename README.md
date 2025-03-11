# Urban Sound Classification - Koç & Aygaz Bootcamp

## 📌 Proje Hakkında
Bu proje, **UrbanSound8K** veri seti kullanılarak seslerin sınıflandırılmasını amaçlamaktadır. Projede **derin öğrenme ve ses işleme teknikleri** kullanılarak, ses dosyalarının hangi türe ait olduğu tahmin edilmektedir. 

Bu çalışma, **Koç ve Aygaz için bir bootcamp projesi** olarak gerçekleştirilmiştir. Amaç, Şhir içindeki seslerin analiz edilerek farklı kategorilerde sınıflandırılmasıdır.

## 📂 Kullanılan Veri Seti
Projede **UrbanSound8K** veri seti kullanılmıştır. Bu veri seti, **10 farklı şehir sesi** kategorisinden oluşmaktadır:
- Air Conditioner
- Car Horn
- Children Playing
- Dog Bark
- Drilling
- Engine Idling
- Gun Shot
- Jackhammer
- Siren
- Street Music

Bu veri seti, şehir içinde yaygın olarak duyulan seslerin analiz edilmesi amacıyla kullanılmıştır.

## 🔧 Kullanılan Kütüphaneler
Proje geliştirilirken aşağıdaki Python kütüphaneleri kullanılmıştır:
- **Librosa** (Ses işleme ve MFCC özellikleri)
- **TensorFlow/Keras** (Derin öğrenme modeli)
- **OpenCV** (Görüntü işleme ve spektrogramlar)
- **NumPy, Pandas** (Veri manipülasyonu)
- **Matplotlib, Seaborn** (Görselleştirme)

## ⚙️ Kurulum & Çalıştırma
Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 1. Gerekli Kütüphaneleri Kurun:
```bash
pip install librosa tensorflow opencv-python numpy pandas matplotlib seaborn
```

### 2. Proje Dosyalarını \c013e indirip çalıştırın:
```bash
python onisleme.py  # Ses verisini işleme
python modelleme.py  # Modeli eğitme ve tahmin yapma
```

### 3. Sonuçları Gözlemleyin
- Model, verilen ses dosyalarını analiz edip, **tahmini sınıfı** ekrana yazdırır.
- Doğruluk oranları ve model performansı grafiklerle görüntülenebilir.

## 📊 Model Performansı & Çıktılar
Model eğitildikten sonra, **doğruluk oranı %86** olarak hesaplanmıştır. Test veri seti üzerinde yapılan tahminlerden bazısı:

| Gerçek Etiket | Model Tahmini |
|---------------|--------------|
| Dog Bark | Dog Bark |
| Car Horn | Engine Idling |
| Siren | Siren |
| Jackhammer | Drilling |

Modelin başarı oranını artırmak için daha fazla veri ve iyileştirilmiş bir sinir ağı mimarisi kullanılabilir.

## 📝 Lisans & Katkıda Bulunma
Bu proje, **Koç ve Aygaz Bootcamp** için geliştirilmiştir ve akademik/deneysel kullanım içindir. Katkıda bulunmak için lütfen pull request gönderin veya issue oluşturun!

---

🚀 **Hazırlayanlar:** NamKodX
