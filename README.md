# 🩺 Diyabet Üzerine Keşifsel Veri Analizi (EDA)

Bu proje, **Pima Indians Diabetes Dataset** kullanılarak gerçekleştirilmiş bir **Keşifsel Veri Analizi (Exploratory Data Analysis)** çalışmasıdır. Amaç, diyabet hastalığını etkileyen faktörleri daha yakından incelemek, verideki önemli desenleri ve korelasyonları ortaya çıkarmaktır.

---

## 📌 Proje Amacı

- Sağlık verileri üzerinde çalışarak temel veri analizi becerilerini geliştirmek
- Diyabet hastalığı ile ilişkili faktörleri keşfetmek
- Veri görselleştirme ile sezgisel çıkarımlar yapmak
- Gerekirse ileride makine öğrenmesi modelleri için zemin hazırlamak

---

## 📁 Kullanılan Veri Seti

- **Kaynak:** [Kaggle - Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Dosya Adı:** `diabetes.csv`
- **Gözlem Sayısı:** 768
- **Sütun Sayısı:** 9 özellik + 1 hedef değişken

### 📋 Değişkenler:

| Sütun | Açıklama |
|-------|----------|
| Pregnancies | Gebelik sayısı |
| Glucose | Glikoz seviyesi |
| BloodPressure | Kan basıncı |
| SkinThickness | Cilt kalınlığı |
| Insulin | İnsülin seviyesi |
| BMI | Vücut kitle indeksi |
| DiabetesPedigreeFunction | Genetik risk |
| Age | Yaş |
| Outcome | 1 = Diyabet var, 0 = Yok |

---

## 🔍 Yapılan Analizler

- Genel veri ön incelemesi (`.info()`, `.describe()`)
- 0 değeri olan alanlar için eksik veri tespiti
- Hedef değişken (`Outcome`) dağılım analizi
- Yaş, glikoz, BMI gibi değişkenlerin görselleştirilmesi
- Cinsiyet ve yaşa göre dağılım karşılaştırmaları
- Korelasyon matrisi ve heatmap ile önemli ilişkiler
- Boxplotlar ile Outcome’a göre değişken karşılaştırması

---

## 📊 Elde Edilen Bazı Bulgular

- Glikoz seviyesi diyabetle en yüksek ilişkili değişkendir.
- Yaş ve BMI arttıkça diyabet riski yükselmektedir.
- İnsülin ve cilt kalınlığı verileri yüksek oranda eksik (sıfır), temizlenmesi gerekebilir.
- 0 olan veriler, bazı değişkenlerde eksiklik sinyali veriyor (özellikle sağlık metriklerinde).

---

## 🛠️ Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🚀 İleride Geliştirilebilir

- Eksik verilerin yerine istatistiksel dolgu yapılabilir.
- Lojistik regresyon, Random Forest gibi sınıflandırma modelleri uygulanabilir.
- `DiabetesPedigreeFunction` daha detaylı analiz edilebilir (genetik risk).
- Veri ön işleme sonrası modelleme yapılabilir.

---
