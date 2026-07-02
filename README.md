# veriBilimiProjesi
# Meme Kanseri (Breast Cancer) Teşhis ve Sınıflandırma Projesi

Bu proje, dönem boyunca öğrenilen veri bilimi iş akışını (veri yükleme, temizleme, keşifsel veri analizi, görselleştirme ve temel makine öğrenmesi modellemesi) gerçek bir klinik veri seti üzerinde uygulamak amacıyla geliştirilmiştir. Proje geliştirme sürecinde "Vibe Coding" yaklaşımı benimsenerek, yapay zeka kodlama asistanları birincil geliştirme ortağı olarak kullanılmıştır.

## Genel Bilgiler
* **Öğrenci Numarası:** [1306230115]
* **Adı Soyadı:** [Walaa Alsabuni ]
* **Ders:** Veri Bilimi / Dönem Projesi (Final Ödevi)
* **ipynb linki** https://colab.research.google.com/drive/198mQy6lR9qbOI6eJYyUzdhPmoyLPNVPB?usp=sharing

## Veri Seti ve Kaynağı 
* **Veri Seti Adı:** Breast Cancer Wisconsin (Diagnostic) Dataset
* **Veri Kaynağı:** `sklearn.datasets.load_breast_cancer` (Aslı: UCI Machine Learning Repository)
* **Veri Boyutu:** 569 Gözlem (Satır), 30 Özellik (Sütun)
* **Hedef Değişken (Target):** `malignant` (Kötü Huylu - 0) ve `benign` (İyi Huylu - 1)
* **Lisans:** Creative Commons Attribution 4.0 International (CC BY 4.0)

##  Kullanılan Kütüphaneler
Projenin çalıştırılması ve analizlerin yapılması için aşağıdaki Python kütüphaneleri kullanılmıştır:
* `numpy` (Sayısal hesaplamalar ve matris işlemleri)
* `pandas` (Veri manipülasyonu ve DataFrame yönetimi)
* `matplotlib` (Temel grafik ve görselleştirme çizimleri)
* `seaborn` (Gelişmiş istatistiksel veri görselleştirme)
* `scikit-learn` (Veri kümesi yükleme, model eğitimi ve başarı metrikleri)

### PROJE ÇALIŞMA TALİMATLARI 
* **colab notebook açmak**
* **veri seti ve kütüphaneler yüklemesi** 
* **veri setini dataframe'e dönüştürmek** 
* **temel istasitik ve eksik değer kontrolü** 
* **sınıf dağılımı(yüzdelik)**
* **Visiualisation** 
    1. kutu grafiği(boxplot)
    2. heat map ile korelasyon 
    3. histogram (dağılım grafiği)
    4. scatter plot (saçılım grafiği)
* **testler ve dağılımlar** 
* **EĞİTİM MODELLERİ** 
    - LOJİSTİK REGRESYON
    - KARAR AĞACI
    - RANDOM FOREST
* **karışıklık matrisi (confusion)**
* **modeller arası metrik değerler karşılaştırması** 
    - accuracy değerleri karşılaştırması 
    - recall değerleri karşılaştırılması
    - güvenirlik değerleri karşılaştırılması(precision)
    - F1 score değerleri karşılaştırılması
* SON 