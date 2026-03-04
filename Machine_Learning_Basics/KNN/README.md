# 📍 K-Nearest Neighbors (KNN) Projects

Bu klasör, KNN (K-En Yakın Komşu) algoritmasının hem **Sınıflandırma** hem de **Regresyon** problemlerindeki uygulamalarını ve model optimizasyon süreçlerini içermektedir.

---

## 📂 Proje İçeriği ve Dosya Yapısı

### 1. KNN Sınıflandırma (Göğüs Kanseri Teşhisi)
* **Dosya:** `knn_classification.py`
* **Veri Seti:** Scikit-learn Breast Cancer veri seti.
* **İşlem:** Veriler `StandardScaler` ile ölçeklendirilmiş ve $k=3$ komşu sayısı ile model eğitilmiştir.
* **Çıktı:** Modelin doğruluk (accuracy) skoru ve Karmaşıklık Matrisi (Confusion Matrix) terminale yazdırılır.

### 2. K-Değeri Optimizasyonu (K-Value Optimization)
* **Dosya:** `knn_k_optimization.py`
* **İşlem:** $k=1$’den $k=20$’ye kadar farklı komşu değerleri denenerek modelin başarısı analiz edilmiştir.
* **Görselleştirme:** Farklı K değerlerine karşılık gelen doğruluk oranlarını gösteren bir çizgi grafiği üretilir.

### 3. KNN Regresyon (KNN Regressor)
* **Dosya:** `knn_regression.py`
* **İşlem:** Sinüs dalgası üzerine eklenen rastgele gürültülü (noise) veriler üzerinde tahmin yürütülür.
* **Karşılaştırma:** `uniform` ve `distance` ağırlıklandırma yöntemlerinin tahmin sonuçları üzerindeki etkisi görselleştirilir.
* **Çıktı:** Regresyon grafikleri `learning1.png` dosyası olarak kaydedilir.

---

## 🛠 Kurulum ve Gereksinimler

Kodların çalışması için aşağıdaki kütüphanelerin yüklü olması gerekir:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn


🚀 Kullanım
Herhangi bir analizi çalıştırmak için terminalden ilgili dosyayı çağırın:
python knn_classification.py

📊 Önemli Notlar
Ölçeklendirme: KNN mesafe tabanlı bir algoritma olduğu için StandardScaler kullanımı model performansını ciddi oranda artırmıştır.

Hiperparametreler: En iyi $k$ değerini seçmek, modelin "overfitting" (aşırı öğrenme) veya "underfitting" (eksik öğrenme) yapmasını engellemek için kritiktir.