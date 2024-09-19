Aygaz-ML-Proje
Aygaz Makine Öğrenmesine Giriş Bootcampi kapsamında hazırlanan bir proje

Proje Açıklaması
  Bu proje, Wine Reviews veri seti üzerinde dört farklı makine öğrenmesi algoritmasının performansını değerlendirmeyi amaçlamaktadır. Projede şu algoritmalar tercih edilmiştir:

Gözetimli öğrenme algoritmaları:
  .Doğrusal Regresyon (Linear Regression)
  .Lojistik Regresyon (Logistic Regression)
  .Karar Ağaçları (Decision Trees)
Gözetimsiz öğrenme algoritmaları:
.  k-Ortalama (k-Means) Kümeleme
Veri Seti
  Projemizde kullanılan veri seti Wine Reviews'dir. Bu veri seti, çeşitli şarapların tadım testlerinin sonuçlarını içerir. Veri seti yaklaşık 280.000 örnek ve 25 farklı sütun barındırmaktadır. Bu sütunlar arasında fiyat, puan ve üretim merkezi gibi özellikler yer alır.

Veri setine buradan -> https://www.kaggle.com/datasets/zynicide/wine-reviews ulaşabilirsiniz.

Kullanılan Algoritmalar
  -Gözetimli Öğrenme-
  
1. Doğrusal Regresyon (Linear Regression)
Açıklama: Doğrusal regresyon, sürekli bir bağımlı değişkeni tahmin etmek için kullanılan bir algoritmadır.
Performans Sonuçları:
Mean Squared Error (MSE): 9.0802
Mean Absolute Error (MAE): 2.4521
R² Score: 0.2385

2. Lojistik Regresyon (Logistic Regression)
Açıklama: Lojistik regresyon, sınıflandırma problemlerinde yaygın olarak kullanılan bir algoritmadır.
Performans Sonuçları:
Doğruluk (Accuracy): 0.1579
Kesinlik (Precision): 0.1067
Duyarlılık (Recall): 0.1579
F1 Puanı (F1 Score): 0.1056

3. Karar Ağaçları (Decision Trees)
Açıklama: Karar ağaçları, veri noktalarını sınıflandırmak için kullanılan bir denetimli öğrenme yöntemidir. Bu projede, max_depth=4 parametresi ile karar ağaçları eğitilmiştir.
Performans Sonuçları:
Doğruluk (Accuracy): 0.1563
Kesinlik (Precision): 0.1217
Duyarlılık (Recall): 0.1563
F1 Puanı (F1 Score): 0.1139

-Gözetimsiz Öğrenme-

1. k-Ortalama (k-Means) Kümeleme
Açıklama: K-means, verileri benzer özelliklere sahip kümelere ayıran bir gözetimsiz öğrenme algoritmasıdır.
Sonuçlar: K-means kümeleme algoritması ile veri setinde 3 küme belirlenmiştir. Kümeleme sonuçları görselleştirilmiş ve kümelerin belirginleştiği gözlemlenmiştir.

Sonuçlar
İki gözetimli ve bir gözetimsiz algoritmanın performansları karşılaştırıldığında, Doğrusal Regresyon algoritması, özellikle regresyon bazlı performans kriterlerinde en başarılı sonuçları vermiştir. Lojistik Regresyon ve Karar Ağaçları, sınıflandırma bazlı problemler için uygun olsa da, özellikle doğruluk ve kesinlik açısından düşük performans göstermiştir. K-Means Kümeleme ise gözetimsiz öğrenme için veri setinin yapısını doğru bir şekilde analiz edebilmiş ve kümeler arasındaki farkları belirginleştirmiştir.

Final Çıktılar

Karar Ağaçları:

Doğruluk (Accuracy): 0.1563
Kesinlik (Precision): 0.1217
Duyarlılık (Recall): 0.1563
F1 Puanı (F1 Score): 0.1139
Lojistik Regresyon:

Doğruluk (Accuracy): 0.1579
Kesinlik (Precision): 0.1067
Duyarlılık (Recall): 0.1579
F1 Puanı (F1 Score): 0.1056
k-Ortalama (k-Means) Kümeleme:

3 Küme Belirlenmiştir.
Doğrusal Regresyon:
R² Skoru: 0.2385
MSE: 9.0802

Kaggle Notebook

Projenin Kaggle notebook'una buradan -> https://www.kaggle.com/code/enescanenginsoy/ml-project ulaşabilirsiniz. Notebook, veri setinin analizi, modelleme süreci ve sonuçların detaylı açıklamasını içermektedir.
