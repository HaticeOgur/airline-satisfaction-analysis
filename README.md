# Airline Passenger Satisfaction - Veri Analizi Projesi

Bu proje, **Kız Başına Veri Analizi Bootcamp** kapsamında gerçekleştirilmiştir.  
Proje kapsamında, havayolu yolcularının memnuniyet düzeylerini etkileyen faktörler analiz edilmiş, eksik ve aykırı veriler tespit edilmiş, sayısal ve kategorik değişkenler görselleştirilmiş ve bulgular detaylı şekilde raporlanmıştır.

---

## 📁 Kullanılan Veri Seti

- **Airline Passenger Satisfaction Dataset**  
- Kaynak: [Kaggle - Teej Mahal](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction)

---

## Projede Gerçekleştirilen Adımlar

### 1. Veri Ön İşleme
- Veri setinin incelenmesi (`.info()`, `.describe()`)
- Sayısal ve kategorik değişkenlerin ayrıştırılması
- Gereksiz sütunların kaldırılması (`Unnamed: 0`, `id`)

### 2. İstatistiksel Özetleme
- Ortalama, medyan, standart sapma, min, max gibi temel istatistiklerin hesaplanması
- Kategorik değişkenlerin frekanslarının çıkarılması

### 3. Eksik Değer Analizi
- `Arrival Delay in Minutes` sütununda eksik değerler tespit edildi
- Eksik değerler medyan ile doldurularak tamamlandı

### 4. Aykırı Değer Analizi
- Boxplot ve IQR yöntemi kullanılarak aykırı değerler belirlendi
- Özellikle gecikme süreleri ve uçuş mesafelerinde uç değerler gözlemlendi

### 5. Görselleştirme
- Sayısal değişkenler için: histogram, boxplot
- Kategorik değişkenler için: bar chart (countplot)
- `satisfaction` değişkenine göre: memnuniyet kırılımı ile gruplu grafikler

### 6. Sonuç ve Değerlendirme
- Sadık müşteriler, iş seyahati yapanlar ve business class yolcuların daha yüksek memnuniyet bildirdiği gözlemlendi
- Online rezervasyon kolaylığı gibi dijital deneyim unsurlarının memnuniyeti doğrudan etkilediği ortaya konuldu

---

## 🧠 Kullanılan Kütüphaneler

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## Katılımcı

- **Adı:** Hatice Ogur  
- **Proje Türü:** Bireysel Bitirme Projesi  
- **Bootcamp:** Kız Başına Veri Analizi Bootcamp  
- **Yıl:** 2025
