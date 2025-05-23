# Teslimat_Tarihi_Tahmin_Projesi 


Bu proje, **Kaggle üzerinden alınan kargo teslim verileri** kullanılarak, kargonun **zamanında ulaşıp ulaşmayacağını tahmin etmek** amacıyla gerçekleştirilmiştir. 
Bu proje gözetimli öğrenme alanında yaptığım ilk projem bu nedenle gelişime açıktır.



## İçerik Detayları:

Veri seti üzerinde öncelikle veri temizleme, encoding ve standardizasyon işlemleri yaptım.

### Kullandığım algoritmalar:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machines (SVM)

Ardından farklı algoritmalar ile modelleme gerçekleştirdim. En iyi sonuç **Decision Tree algoritmasının hiperparametre optimizasyonu** ile geldiğinden bu algoritmayı ele alarak ilerledim.


## Değerlendirme:

Seçilen en iyi model: **Decision Tree (optimize edilmiş)**  
En iyi doğruluk (cross-validation): **%63.39**  
Test seti doğruluğu: **%65.64**

### Sınıflandırma Raporu:
| Metrik     | Sınıf 0 (geciken) | Sınıf 1 (zamanında) |
|------------|-------------------|---------------------|
| Precision  | 0.5728            | 0.7205              |
| Recall     | 0.6112            | 0.6874              |
| F1-Score   | 0.5914            | 0.7035              |

> Model, zamanında teslim edilen siparişleri daha başarılı tahmin etmekte; geciken siparişler için ise dengeli fakat daha düşük performans göstermektedir.


## Sonuç:

### Olası Geliştirmeler:
- Yeni özellikler türetilerek (feature engineering) model performansının artırılması
- XGBoost, LightGBM gibi güçlü algoritmalarla karşılaştırmalı denemeler


Çalışmaya ait Kaggle Linki: https:  www.kaggle.com/code/buraksisci/globalaihubproje    
Projede kullanılan veri seti linki:  www.kaggle.com/datasets/prachi13/customer-analytics/code    

## Geliştirici:

**Ahmet Burak Şişci**  
GitHub:  www.github.com/burak-sisci    
LinkedIn:  www.linkedin.com/in/burak-sisci   
Kaggle:  www.kaggle.com/buraksisci     
E-posta:  buraksisci32@gmail.com    

