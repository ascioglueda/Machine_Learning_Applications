# Makine Öğrenimi Çalışma ve Analiz Projesi

## Genel Bakış
Bu depoda, makine öğrenimi algoritmaları, teknikleri ve süreçleri üzerine kapsamlı bir çalışma yer almaktadır. Gözetimli, gözetimsiz ve pekiştirmeli öğrenme yöntemlerinin uygulamaları, karşılaştırmaları ve değerlendirmeleri bulunmaktadır. Proje, makine öğrenimi kavramlarını kod, Jupyter not defterleri ve açıklayıcı görseller aracılığıyla anlamak, uygulamak ve görselleştirmek için bir kaynak olarak tasarlanmıştır.

Proje, sınıflandırma, regresyon, kümeleme, boyut indirgeme (LDA, PCA, t-SNE), model seçimi, hiperparametre ayarı ve çapraz doğrulama gibi geniş bir yelpazeyi kapsar ve pratik örnekler ile vaka çalışmalarını içerir. Sonuçlar ve karşılaştırmalara dair içgörüler sunmak için grafikler, diyagramlar ve çizelgeler (örneğin, `image.png`, `\Gozetimli_Ogrenme\output.png`, `\Boyut_İndirgeme\LDA.png`, `\Boyut_İndirgeme\PCA.png`, `\Boyut_İndirgeme\TSNE.png`, `\Gozetimsiz_Ogrenme\Kmeans.png`, `\Gozetimsiz_Ogrenme\Kmeans1.png`, `\Gozetimsiz_Ogrenme\DBSCAN.png`, `\Gozetimsiz_Ogrenme\HierarchicalClustering.png`) kullanılmıştır.

## Proje Yapısı
Depo, kolay gezinme ve kullanım için düzenli bir şekilde yapılandırılmıştır:

- **/not_defterleri**: Makine öğrenimi algoritmalarının uygulamalarını ve gösterimlerini içeren Jupyter not defterleri.
  - `KararAgaci.ipynb`, `KararAgaci2.ipynb`, `KararAgaci3.ipynb`, `KararAgaci4.ipynb`: Karar Ağacı modelleri ve vaka çalışmaları.
  - `knn.ipynb`: K-En Yakın Komşu (KNN) uygulaması.
  - `LinearRegression.ipynb`, `MultiVariableLinearRegression.ipynb`, `MultiVariableLinearRegression2.ipynb`: Doğrusal ve çok değişkenli regresyon modelleri.
  - `LogisticRegression.ipynb`: Sınıflandırma için lojistik regresyon.
  - `NaiveBayes.ipynb`: Naive Bayes sınıflandırıcısı.
  - `PolynomialRegression.ipynb`: Polinom regresyon modelleri.
  - `RandomForest.ipynb`, `RandomForest2.ipynb`, `RandomForest3.ipynb`: Rastgele Orman modelleri ve karşılaştırmaları.
  - `SVM.ipynb`: Destek Vektör Makineleri (SVM) uygulaması.
  - `ClusteringAlgorithmsComparison.ipynb`: Kümeleme algoritmalarının karşılaştırması (K-Means, DBSCAN, Hiyerarşik).
  - `KMeansClustering.ipynb`, `Kmeans.ipynb`, `Kmeans1.ipynb`: K-Means kümeleme örnekleri.
  - `DBSCAN.ipynb`, `HierarchicalClustering.ipynb`: Diğer kümeleme teknikleri.
  - `LDA.ipynb`, `PCA.ipynb`, `TSNE.ipynb`: Boyut indirgeme teknikleri (Lineer Diskriminant Analizi, Temel Bileşen Analizi, t-Dağıtımlı Stokastik Komşu Yerleştirme).
  - `Qlearning.ipynb`: Pekiştirmeli öğrenme için Q-öğrenme uygulaması.
  - `GridSearchRandomSearchHyperparameterTuning.ipynb`, `CrossValidation.ipynb`, `FoldLeaveOneOutCrossValidation.ipynb`: Model değerlendirme ve hiperparametre ayarı.

- **/kodlar**: Yeniden kullanılabilir kodlar ve işlevler için Python betikleri.
  - `Vectorizer.py`: Özellik vektörizasyon araçları.
  - Veri ön işleme, model eğitimi ve değerlendirme için diğer betikler.

- **/sonuclar**: Görselleştirmeler ve çıktılar.
  - `image.png`: Model karşılaştırmaları veya veri içgörülerini gösteren örnek bir görselleştirme.
  - `output.png`: Genel model çıktıları veya analiz sonuçlarını görselleştiren grafik/diyagram.
  - `LDA.png`: Lineer Diskriminant Analizi sonuçlarını gösteren görselleştirme (örn. sınıflandırma veya boyut indirgeme).
  - `PCA.png`: Temel Bileşen Analizi ile veri dağılımını veya varyans açıklamasını gösteren grafik.
  - `TSNE.png`: t-SNE ile yüksek boyutlu verinin iki veya üç boyutlu görselleştirilmesi.
  - `Kmeans.png`, `Kmeans1.png`: K-Means kümeleme sonuçlarını gösteren grafikler (örn. küme atamaları veya merkezler).
  - `DBSCAN.png`: DBSCAN kümeleme sonuçlarını gösteren görselleştirme.
  - `HierarchicalClustering.png`: Hiyerarşik kümelemenin dendrogramı veya küme yapısını gösteren diyagram.

- **/belgeler**: Kılavuzlar ve dokümantasyon.
  - Her algoritma ve teknik için öğreticiler ve özetler.

## Temel Özellikler
- **Gözetimli Öğrenme**: Karar Ağaçları, KNN, Doğrusal Regresyon, Lojistik Regresyon, Naive Bayes, Rastgele Orman, SVM ve Polinom Regresyon uygulamaları.
- **Gözetimsiz Öğrenme**: K-Means, DBSCAN ve Hiyerarşik Kümeleme teknikleri ile karşılaştırmalar; LDA, PCA ve t-SNE ile boyut indirgeme.
- **Pekiştirmeli Öğrenme**: Q-öğrenme ile sıralı karar verme görevleri.
- **Model Değerlendirme**: Çapraz doğrulama (örn. Fold, Leave-One-Out), Izgara Arama ve Rastgele Arama ile hiperparametre ayarı.
- **Görselleştirmeler**: Model performansını, kümeleme sonuçlarını, boyut indirgeme çıktılarını ve veri içgörülerini gösteren çizelgeler, grafikler ve diyagramlar (örn. `image.png`, `output.png`, `LDA.png`, `PCA.png`, `TSNE.png`, `Kmeans.png`, `Kmeans1.png`, `DBSCAN.png`, `HierarchicalClustering.png`).
- **Vaka Çalışmaları**: Algoritmaların gerçek dünya problemlerine uygulanmasını gösteren pratik örnekler.

## Başlangıç

### Ön Koşullar
- Python 3.9 veya 3.12
- Gerekli kütüphaneler: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `jupyter`
- Bağımlılıkları yüklemek için:
  ```bash
  pip install -r requirements.txt
  ```

1. **Görselleştirmeleri İnceleme**:
   - `/sonuclar` dizinindeki görselleri kontrol edin:
     - `image.png`: Genel model karşılaştırmaları veya veri içgörüleri.
     - `output.png`: Analiz veya model çıktılarının görselleştirilmesi.
     - `LDA.png`: Sınıflandırma veya boyut indirgeme sonuçları.
     - `PCA.png`: Varyans açıklaması veya veri dağılımı.
     - `TSNE.png`: Yüksek boyutlu verinin düşük boyutlu görselleştirilmesi.
     - `Kmeans.png`, `Kmeans1.png`: K-Means kümeleme sonuçları.
     - `DBSCAN.png`: DBSCAN kümeleme çıktıları.
     - `HierarchicalClustering.png`: Hiyerarşik kümeleme dendrogramı veya küme yapısı.

2. **Betikleri Çalıştırma**:
   - `/kodlar` dizinindeki Python betiklerini belirli görevler için çalıştırın, örneğin:
     ```bash
     python Vectorizer.py
     ```

3. **Belgeleri İnceleme**:
   - Her algoritma ve teknik için öğreticiler, özetler ve kılavuzlar için `/belgeler` dizinine bakın.

## Görselleştirmeler
Proje, anlamayı kolaylaştırmak için zengin görselleştirmeler içerir:
- **image.png**: Model karşılaştırmaları, performans metrikleri veya veri içgörülerini gösteren genel bir görselleştirme.
- **output.png**: Analiz sonuçlarını veya model çıktılarını temsil eden grafik/diyagram.
- **LDA.png**: Lineer Diskriminant Analizi ile sınıflandırma veya boyut indirgeme sonuçlarını görselleştirir.
- **PCA.png**: Temel Bileşen Analizi ile veri varyansını veya bileşen dağılımını gösterir.
- **TSNE.png**: t-SNE ile yüksek boyutlu verinin 2D/3D görselleştirilmesi.
- **Kmeans.png**, **Kmeans1.png**: K-Means kümeleme algoritmasının küme atamalarını veya merkezlerini gösterir.
- **DBSCAN.png**: DBSCAN algoritmasının kümeleme sonuçlarını görselleştirir.
- **HierarchicalClustering.png**: Hiyerarşik kümelemenin dendrogramını veya küme yapısını temsil eder.
- Görsellerin nasıl oluşturulduğuna dair detaylar için ilgili not defterlerine (örn. `LDA.ipynb`, `Kmeans.ipynb`) bakın.

