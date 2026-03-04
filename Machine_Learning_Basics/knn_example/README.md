# 🔍 KNN & Decision Tree Comparative Examples

Bu klasör, K-Nearest Neighbors (KNN) ve Karar Ağaçları (Decision Trees) algoritmalarının pratik uygulamalarını ve birbirleriyle olan performans karşılaştırmalarını içermektedir.

---

## 📂 Dosya İçerikleri

### 1. Model Karşılaştırmaları (Comparison)
* **`comparison_knn_vs_tree.ipynb`**: Aynı veri seti üzerinde KNN ve Decision Tree modellerinin doğruluk (accuracy) ve hız performanslarının kıyaslandığı analiz notebook'u.
* **`comparison_advanced_metrics.ipynb`**: Modellerin Precision, Recall ve F1-Score gibi daha ileri düzey metriklerle değerlendirilmesi.

### 2. Uygulama Örnekleri
* **`knn_basic_implementation.py`**: KNN algoritmasının saf Python scripti üzerinde temel akış (veri yükleme, eğitim, tahmin) gösterimi.
* **`knn_interactive_analysis.ipynb`**: Görselleştirmeler ve adım adım veri analizi içeren interaktif çalışma dosyası.

---

## 🛠 Kurulum ve Gereksinimler

Analizlerin çalışması için Jupyter Notebook ortamı ve aşağıdaki kütüphaneler gereklidir:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

🚀 Nasıl Kullanılır?
Notebook'ları incelemek için terminale jupyter notebook yazarak tarayıcıdan ilgili .ipynb dosyasını açın.

Temel scripti çalıştırmak için:
python knn_basic_implementation.py

📌 Temel Kazanımlar
Mesafe tabanlı (KNN) ve kural tabanlı (Decision Tree) iki farklı yaklaşımın avantaj ve dezavantajlarını gözlemlemek.

Hiperparametrelerin (K sayısı, ağaç derinliği vb.) model başarısına etkisini analiz etmek.