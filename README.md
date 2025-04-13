# Yapay-Zeka-Goruntu-isleme-Yol-Haritasi

# Talha'nın Yapay Zeka ve Görüntü İşleme Yol Haritası

✅ Her bölüm detaylı açıklamalar ve örnek kodlarla dolu

🎯 Projeler net ve uygulanabilir

📘 Yol haritan her an ulaşabileceğin biçimde düzenli tutulmuştur

Bu yol haritası, Talha'nın yapay zeka, görüntü işleme, YOLO, TensorFlow, UNet ve DeepStream gibi ileri düzey teknolojilerde uzmanlaşmasını sağlamak amacıyla adım adım planlanmıştır. Yolun başında olan bir öğrenci için en temelden başlayarak ileri düzeye kadar ulaşacak şekilde haftalara ayrılmıştır. Her konunun sonunda ✅ Tamamlandı kutucuğu ile ilerleme takip edilebilir. Kod blokları açıklayıcı yorum satırları ile desteklenmiştir.

---

## 🔹 AŞAMA 1: Python ve OpenCV Temelleri (Hafta 1–2)

### 🎯 Hedefler:

- Python programlama mantığını öğren
- OpenCV ile görüntü işlemenin temellerini kavra

### 📚 Konular:

- Python temel yapıları: değişkenler, döngüler, fonksiyonlar, sınıflar
- OpenCV ile:
    - Görüntü okuma/yazma
    - Yeniden boyutlandırma ve kırpma
    - Renk dönüşümleri: BGR ↔ Gray ↔ HSV
    - Filtreleme: GaussianBlur, MedianBlur
    - Kenar tespiti: Canny
    - Basit eşikleme ve morfolojik işlemler

### 🧪 Uygulamalar / Mini Projeler:

- Görüntüye daire ve metin çizen etkileşimli araç
- Canlı kamerada kenar tespiti
- Webcam görüntüsünde renkli nesne takibi (HSV ile filtreleme)

[AŞAMA 1: AYRINTILI KOD](https://www.notion.so/A-AMA-1-AYRINTILI-KOD-1d463383c36f80adb606e9dc0332d040?pvs=21)

---

## 🔹 AŞAMA 2: Gerçek Zamanlı Görüntü İşleme (Hafta 3–4)

### 🎯 Hedefler:

- Kamera görüntüsüyle canlı işlem yapmayı öğren
- Takip, hareket algılama gibi konuları kavra

### 📚 Konular:

- `cv2.VideoCapture` ile kamera bağlantısı
- Arka plan çıkarma: MOG2
- Centroid tracking mantığı
- Hareket algılama (frame farkı, thresholding)

### 🧪 Mini Projeler:

- Hareketli nesne takibi ve kutulama
- Belirli bölgeden geçen nesneleri sayma
- Basit güvenlik kamerası uygulaması

[AŞAMA 2: AYRINTILI KOD](https://www.notion.so/A-AMA-2-AYRINTILI-KOD-1d463383c36f805b9a20ef5f34277e26?pvs=21)

---

## 🔹 AŞAMA 3: Hazır YOLO Modelleri ile Nesne Tespiti (Hafta 5–6)

### 🎯 Hedefler:

- YOLO modeli ile nesne tespiti yapabilmek
- OpenCV ile birlikte çalıştırmak

### 📚 Konular:

- YOLOv5/v8 indirme ve çalıştırma
- Roboflow’dan hazır veri seti alma
- Sonuçların OpenCV ile görselleştirilmesi

### 🧪 Mini Projeler:

- Kamera görüntüsünde gerçek zamanlı YOLO nesne tespiti
- 'Kırık Cam' gibi nesneleri kutulama
- YOLO sonuçlarını ekran kaydıyla kaydetme

[AŞAMA 3: AYRINTILI KOD](https://www.notion.so/A-AMA-3-AYRINTILI-KOD-1d463383c36f80009c28e601676fdb61?pvs=21)

---

## 🔹 AŞAMA 4: Kendi YOLO Modelini Eğitme (Hafta 7–8)

### 🎯 Hedefler:

- Roboflow ile veri etiketleme
- YOLOv8 modeli eğitmek ve değerlendirmek

### 📚 Konular:

- Dataset oluşturma, augmentasyon (Roboflow)
- YOLOv8 ile model eğitimi (Google Colab)
- mAP, IoU gibi metriklerin değerlendirilmesi
- Modelin video/gerçek zamanlı test edilmesi

### 🧪 Mini Projeler:

- Kendi veri setinle model eğitimi (kırık cam, çizik vb.)
- GUI ile test uygulaması (Tkinter arayüzü)

[AŞAMA 4: AYRINTILI KOD](https://www.notion.so/A-AMA-4-AYRINTILI-KOD-1d463383c36f800f8797eeeeb2cfe1f9?pvs=21)

---

## 🔹 AŞAMA 5: Segmentasyon (UNet) ile Alan Tespiti (Hafta 9–10)

### 🎯 Hedefler:

- Kırık alanların maskelenmesi
- Segmentasyon ve bounding box farkını öğrenmek

### 📚 Konular:

- Semantic segmentation vs. instance segmentation
- UNet mimarisi ve eğitim süreci
- Labelme ile maskeleme

### 🧪 Mini Projeler:

- Cam üzerindeki kırık bölgeleri UNet ile maskele
- Isı haritası overlay ile görselleştirme

[AŞAMA 5: AYRINTLI KOD](https://www.notion.so/A-AMA-5-AYRINTLI-KOD-1d463383c36f8074807fd72d88f774a4?pvs=21)

---

## 🔹 AŞAMA 6: TensorFlow ve CNN ile Görüntü Sınıflandırma (Hafta 11–12)

### 🎯 Hedefler:

- Görüntüleri sınıflandıran CNN modelleri oluşturmak

### 📚 Konular:

- Keras ile model tanımlama, eğitim ve değerlendirme
- MNIST ile başlangıç, sonra kendi verinle deneme
- TensorBoard kullanımı

### 🧪 Mini Projeler:

- Kırık / sağlam cam sınıflandırması
- Farklı kırık türlerini sınıflandırma
- Modeli GUI üzerinde gösteren uygulama

[AŞAMA 6: AYRINTILI KOD](https://www.notion.so/A-AMA-6-AYRINTILI-KOD-1d463383c36f800a9904d811b9870a49?pvs=21)

---

## 🔹 AŞAMA 7: DeepStream ile Gerçek Zamanlı AI (Hafta 13–14)

### 🎯 Hedefler:

- NVIDIA destekli gerçek zamanlı sistemler geliştirmek

### 📚 Konular:

- DeepStream SDK kurulumu
- YOLO modelini entegre etmek
- Çoklu kamera desteği

### 🧪 Mini Projeler:

- İki kameradan gelen görüntüyü işleme
- Kırık varsa kayıt başlatan sistem
- Kamera görüntüsünden log tutma uygulaması

[AŞAMA 7: AYRINTILI KOD](https://www.notion.so/A-AMA-7-AYRINTILI-KOD-1d463383c36f80c5a505ec1ffa7f5be7?pvs=21)

---

## 📌 Ekstra Tavsiyeler:

- Her projenin kodunu GitHub’da paylaş
- Haftalık ilerlemeleri Notion/Excel ile takip et
- LinkedIn’de kısa postlarla öğrenmeni paylaş

## 📂 Kaynaklar:

- Python: RealPython, Python Crash Course
- OpenCV: PyImageSearch, docs.opencv.org
- YOLO: Ultralytics Docs, Roboflow Tutorials
- TensorFlow: tensorflow.org, Coursera Keras eğitimleri
- DeepStream: NVIDIA Metropolis & GitHub örnekleri
