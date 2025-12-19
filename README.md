# 🏡 House Price Prediction with Machine Learning

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)

Bu proje, farklı makine öğrenmesi regresyon algoritmalarını kullanarak **konut fiyatlarını tahmin etmeyi** amaçlamaktadır.  
Amaç; modelleri karşılaştırmak, hiperparametre optimizasyonu uygulamak ve model performanslarını **RMSE metriği** üzerinden analiz etmektir.

---

## 🎯 Projenin Amacı

- Regresyon problemlerini pratik üzerinden öğrenmek  
- Farklı modellerin aynı problem üzerindeki performanslarını karşılaştırmak  
- Random Forest ve Gradient Boosting gibi **ensemble yöntemlerin gücünü** gözlemlemek  
- Hiperparametre optimizasyonunun modele etkisini görmek  

---

## 🧠 Kullanılan Modeller

Projede aşağıdaki regresyon algoritmaları kullanılmıştır:

- **Linear Regression**
- **Random Forest Regressor**
- **Tuned Random Forest (GridSearchCV)**
- **Gradient Boosting Regressor**

Her model aynı veri seti üzerinde eğitilmiş ve test edilmiştir.

---

## 📊 Performans Karşılaştırması

Model performansları **RMSE (Root Mean Squared Error)** metriği kullanılarak değerlendirilmiştir.

| Model | RMSE |
|------|------|
| Linear Regression | 82,993 |
| Random Forest Regressor | 29,275 |
| Tuned Random Forest | 29,129 |
| Gradient Boosting Regressor | **28,598** |

> **Analiz:** Linear Regression modeline kıyasla, **Gradient Boosting modeli hatayı yaklaşık %65 oranında düşürerek** veri setindeki lineer olmayan ilişkileri başarıyla yakalamıştır.
<br><br>
📌 **En iyi performans Gradient Boosting modelinde elde edilmiştir.**

---

## 📈Değerlendirme Metriği

Projede kullanılan metrik:

RMSE (Root Mean Squared Error)

RMSE, tahmin edilen değerler ile gerçek değerler arasındaki farkın karelerinin ortalamasının kareköküdür.
Düşük RMSE değeri, daha iyi model performansı anlamına gelir.

---

## 🧪 Proje Akışı

1- Veri setinin yüklenmesi <br>
2- Gerekli ön işleme adımları <br>
3- Train-test split <br>
4- Modellerin eğitilmesi <br>
5- Model performanslarının hesaplanması <br>
6- Hiperparametre optimizasyonu <br>
7- Modellerin karşılaştırılması <br>

---

## 🛠️ Kullanılan Kütüphaneler
Python <br>
Pandas <br>
NumPy <br>
Scikit-learn <br>
Matplotlib / Seaborn <br>

