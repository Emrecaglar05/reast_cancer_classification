🎗️ Meme Kanseri Teşhis Tahmin Modeli
https://via.placeholder.com/1200x400?text=Breast+Cancer+Diagnosis+ML+Model

📌 Proje Özeti
Bu proje, makine öğrenmesi teknikleri kullanarak meme kanseri teşhisini otomatikleştirmeyi amaçlamaktadır. Wisconsin Diagnostic veri setindeki hücre özelliklerine dayanarak tümörlerin iyi huylu (benign) veya kötü huylu (malignant) olarak sınıflandırılmasını sağlar.

🔍 Öne Çıkan Özellikler
✔ %97.1 doğruluk oranıyla yüksek performans
✔ 3 farklı makine öğrenmesi algoritmasının karşılaştırması
✔ SHAP değerleriyle model interpretability analizi
✔ Temiz ve modüler kod yapısı

📊 Veri Seti Bilgileri
Özellik	Değer
Kaynak	Kaggle
Örnek Sayısı	569
Özellik Sayısı	30
Hedef Değişken	Diagnosis (Benign/Malignant)
🛠️ Teknik Detaylar
⚙️ Kullanılan Teknolojiler
python
# Temel Kütüphaneler
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Makine Öğrenmesi
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import classification_report

# Model Interpretability
import shap
📈 Model Performansları
Model	Doğruluk	Precision	Recall	F1-Score
Random Forest	97.1%	0.96	0.98	0.97
SVM	95.2%	0.94	0.96	0.95
MLP	96.3%	0.95	0.97	0.96
🔬 Analiz Adımları
Veri Keşfi ve Temizleme

Eksik veri analizi

Aykırı değer tespiti

Korelasyon matrisi

Özellik Mühendisliği

StandardScaler ile normalizasyon

Özellik önem sıralaması

Model Eğitimi

Hiperparametre optimizasyonu

Çapraz doğrulama (5-fold)

Sonuç Değerlendirme

Karışıklık matrisi

Sınıflandırma raporu

SHAP analizi
