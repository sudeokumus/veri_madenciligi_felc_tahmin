# 🩺 Stroke Prediction - Felç Tahmini 🔬

![alt text](https://miro.medium.com/max/1200/1*XklfbFzk7iMFEhLTk6QTpg.png)

## Veri Seti Hakkında 📖

Proje çalışması kapsamında “Diabetes, Hypertension and Stroke Prediction” isimli veri seti seçilmiştir. Bu, CDC*'nin BRFSS* 2015 verilerine göre 70.692'den fazla anket yanıtından oluşan temiz bir veri kümesidir. Toplamda 18 adet değişkenden oluşmaktadır. 

* *Centers for Disease Control and Prevention - ABD Hastalık Kontrol ve Korunma Merkezi*
* *Behavioral Risk Factor Surveillance System - Davranışsal Risk Faktörü Sürveyans Sistemi*

ABD’nin pek çok eyaletinde, sağlık davranışlarına ilişkin güncel ve ulaşılabilir veri BRFSS ile sağlanmaktadır.

Veri setinde 15 adet kategorik, 3 adet sayısal değişken bulunmaktadır.

## Hedef 🎯

Amaç; klinik parametreleri kullanarak insanların felç olup olmama durumlarını ve felcin diğer parametrelerle arasındaki ilişkiyi incelemektir.

Bir kişinin tıbbi özelliklerine göre felç olup olmadığını tahmin edebilen bir makine öğrenimi modeli oluşturmak için çeşitli makine öğrenimi algoritmaları ve veri bilimi kütüphaneleri kullanılmıştır.

## Kullanılan Kütüphaneler 📚

* NumPy
* Matplotlib
* Pandas
* Seaborn
* scikit-learn
* warnings

## Sonuç 📑

* Model üzerinde Lojistik Regresyon, Karar Ağacı, Destek Vektör Makinesi (SVM) ve K-En Yakın Komşu (KNN) algoritmaları uygulandı.
* Random Oversampling yöntemi uygulanmadan önce accuracy (doğruluk) değeri daha yüksek olmasına rağmen, model "felç olma" durumunu tespit etmekte başarılı değildi. (f1 score = 0.01) 
* Random Oversampling yöntemi sonrasında "felç olma" durumuna ait f1 score 0.25'e kadar yükseldi.
* f1 score'lara baktığımızda "felç olma" durumunu yakalamada Lojistik Regresyon en başarılıyken SVM ve KNN algoritmaları onu takip etti. Karar Ağacı algoritması "felç olmama" durumunu iyi tahmin etti. (f1 score = 0.83)



**Daha fazla detaya erişmek için: [islemler.ipynb](islemler.ipynb) 🪄**
