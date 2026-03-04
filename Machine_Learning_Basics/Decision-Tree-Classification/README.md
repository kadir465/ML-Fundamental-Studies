# 🌿 Decision Tree Classification (Iris Dataset)

Bu proje, **Scikit-learn** kütüphanesini kullanarak klasik Iris veri seti üzerinde bir Karar Ağacı (Decision Tree) sınıflandırıcısı eğitmek ve modelin karar mekanizmasını görselleştirmek amacıyla hazırlanmıştır.

---

## 📊 Proje İçeriği
* **Model:** `DecisionTreeClassifier` algoritması kullanılmıştır.
* **Hiperparametreler:** Gini kriteri ve maksimum 5 derinlik sınırı (`max_depth=5`) belirlenmiştir.
* **Veri Seti:** Iris çiçek türü sınıflandırma veri seti (Setosa, Versicolor, Virginica).



## 📈 Görselleştirme ve Çıktılar
Kod çalıştırıldığında aşağıdaki analizleri otomatik olarak üretir:
* **Karmaşıklık Matrisi (Confusion Matrix):** Modelin tahmin başarısını sınıf bazında gösterir.
* **Karar Ağacı Şeması:** Algoritmanın hangi özelliklere (petal length, width vb.) göre karar verdiğini hiyerarşik olarak sunar.

---

## 🛠 Gereksinimler
Projenin çalışması için gerekli kütüphaneleri aşağıdaki komutla yükleyebilirsiniz:

```bash
pip install scikit-learn matplotlib seaborn

📂 Çıktı Dosyaları
İşlem tamamlandığında modelin doğruluk (accuracy) değeri terminale basılır ve şu görseller kaydedilir:

confusion_matrix.png: Karmaşıklık matrisi grafiği.

tree_visualization.png: Karar ağacı yapısının görsel şeması.
