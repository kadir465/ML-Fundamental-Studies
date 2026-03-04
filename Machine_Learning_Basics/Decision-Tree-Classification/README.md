Decision Tree Classification with Iris Dataset
Bu proje, Scikit-learn kütüphanesini kullanarak klasik Iris veri seti üzerinde bir Karar Ağacı (Decision Tree) sınıflandırıcısı eğitmek ve sonuçları görselleştirmek amacıyla hazırlanmıştır.

Proje İçeriği
Model: DecisionTreeClassifier (Gini kriteri ve derinlik sınırı: 5).

Veri Seti: Iris (Çiçek türü sınıflandırma).

Görselleştirme: - Modelin performansını gösteren Confusion Matrix (Karmaşıklık Matrisi).

Karar mekanizmasını açıklayan Decision Tree Diagram (Karar Ağacı Şeması).

Gereksinimler
Kodun çalışması için aşağıdaki kütüphanelerin yüklü olması gerekir:
pip install scikit-learn matplotlib seaborn


Kullanım
Klasör içindeki scripti çalıştırmak için:
python machine_learning_DT1.py

Sonuçlar
Kod çalıştırıldığında modelin doğruluk (accuracy) değerini terminale basar ve aşağıdaki dosyaları çıktı olarak kaydeder:

learn_DT0.png: Karmaşıklık matrisi grafiği.

learn_DT1.png: Karar ağacı yapısının görsel şeması.