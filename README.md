# 🌸 Iris Veri Seti ile Sınıflandırma Modelleri Karşılaştırması

## 📌 Proje Özeti
Bu projede, scikit-learn kütüphanesindeki Iris veri seti kullanılarak farklı sınıflandırma algoritmalarının başarıları karşılaştırılmıştır. Amaç, veri setini eğitim ve test olarak ayırarak en az üç farklı sınıflandırma modeliyle eğitmek ve modellerin performanslarını karşılaştırmaktır.

---

## 🔧 Kullanılan Adımlar

### 1. Veri Setini Yükleme ve Ayırma
- Iris veri seti `scikit-learn` içinden yüklendi.
- %80 eğitim, %20 test oranında ayrım yapıldı.
- Tekrarlanabilir sonuçlar için `random_state=42` parametresi kullanıldı.

### 2. Modellerin Eğitimi
Aşağıdaki 3 sınıflandırma algoritması kullanıldı:
- **Lojistik Regresyon**
- **Karar Ağacı**
- **Random Forest** *(veya SVM, tercihe göre)*

Her model için test verisi üzerinde **accuracy (doğruluk oranı)** hesaplandı.

### 3. Model Karşılaştırması
- Accuracy sonuçları tablo halinde sunuldu.
- En iyi performans gösteren model belirlendi ve yorumlandı.

---

## 📊 Sonuçlar
| Model              | Accuracy |
|--------------------|----------|
| Lojistik Regresyon | 1.00     |
| Karar Ağacı        | 1.00     |
| Random Forest      | 1.00     |

> Not: Iris veri seti kolay ayrılabilir özelliklere sahip olduğundan tüm modeller mükemmel sonuç vermiştir.

---

## 💬 Sonuçların Yorumlanması

Bu mükemmel skorlar bize şunları gösteriyor:

### 1. Iris veri seti çok iyi ayrılabilir özelliklere sahip
- 🌼 Çiçek türleri, ölçümleri kullanarak net bir şekilde ayrılabilir  
- 📏 Özellikler arasındaki ilişkiler belirgin ve tutarlı

### 2. Tüm modeller bu problemi çözmede başarılı
- 🔹 **Lojistik Regresyon**: En basit model bile mükemmel sonuç veriyor  
- 🌳 **Karar Ağacı**: Sınıfları tamamen ayırabilen kurallar bulabildi  
- 🌲 **Rastgele Orman**: Birden fazla ağaç kullanarak güvenilir tahminler yapıyor  
- 🧠 **SVM**: Veri noktaları arasında optimum ayırma çizgileri buluyor

### 3. Detaylı raporlarda da mükemmellik görülüyor
- 🎯 **Precision (Kesinlik)**: Tüm sınıflar için 1.00  
- 📡 **Recall (Duyarlılık)**: Tüm sınıflar için 1.00  
- 🧮 **F1-Score**: Tüm sınıflar için 1.00


---

## 🧑‍💻 Geliştirici Notu
Bu proje, temel sınıflandırma modelleriyle çalışmayı ve model karşılaştırmayı öğrenmek için uygundur. Farklı veri setlerinde bu modellerin nasıl farklı sonuçlar vereceğini görmek için aynı yöntemi uygulayabilirsiniz.




