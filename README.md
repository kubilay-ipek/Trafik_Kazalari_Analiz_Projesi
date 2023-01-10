# Data-Analysis-Final-Case
* Notebook'un boyutu çok fazla olduğu için Release altında bulabilirsiniz.
* Bu projenin verisi, Birleşik Krallık hükümetinin 2000 ve 2016 yılları arasındaki trafik verilerini bir araya getirerek kayıt altına aldığı 1,6 milyondan fazla kazayı barındırır.

## Yanıtlamak İstediğimiz Sorular
Aşağıdaki sorular veride yaptığımız manipülasyon ve analizlerle yanıtlanmaya çalışılmıştır.

* Trafik akışının değişmesi kazaları nasıl etkiler?
* Kaza oranlarını ne artırır?
* Zaman içinde kaza oranlarını tahmin edebilir miyiz?
* Kırsal ve kentsel alanlar nasıl farklılaştı?

## Projenin Aşamaları

* Öncelikle yıllara göre dağılmış datasetleri bir araya getirildi.
* Missing Value Check ve çeşitli Data Manipulation'lar yapıldı.
* Time Column'u datetime objesine dönüştürüldü.
* Matplotlib ve seaborn ile çeşitli görselleştirmeler yapıldı.
* Kent ve Kırsal Bölgeleri saptamak için ``folium`` kütüphanesinden ve verisetindeki konum bilgilerinden faydalanıldı.
* Onehot Encodding ve Ordinal Encodding uygulandıktan sonra bir Decision Tree modeli geliştirildi.
