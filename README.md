🧠 Meme Kanseri Teşhis Tahmin Modeli
Bu proje, Kaggle'dan alınan Breast Cancer Wisconsin (Diagnostic) veri seti kullanılarak, iyi huylu (benign) ve kötü huylu (malignant) tümörleri sınıflandırmak için bir makine öğrenmesi modeli geliştirmeyi amaçlamaktadır.

🎯 Proje Konusu
Meme Kanseri Tanısı: Makine Öğrenmesi ile Kötü Huylu ve İyi Huylu Tümörlerin Sınıflandırılması

🧠 Açıklama:
Bu proje, Kaggle’daki "Breast Cancer Wisconsin (Diagnostic)" veri setini kullanarak, hastalardan alınan hücre ölçümlerine dayanarak tümörlerin iyi huylu (benign) mu yoksa kötü huylu (malignant) mu olduğunu otomatik olarak tahmin etmeyi amaçlar.
Makine öğrenmesi algoritmaları (özellikle sınıflandırma yöntemleri) kullanılarak erken teşhis için yardımcı bir sistem geliştirilmiştir.

🔬 Neden Önemli?
Meme kanseri, kadınlarda en sık görülen kanser türlerinden biridir.
Erken teşhis, tedavi başarısını ciddi oranda artırır.
Bu tür otomatik sistemler, doktorlara destek sağlamak için kullanılabilir

📊 Kullanılan Veri Seti
Veri Seti Adı: Breast Cancer Wisconsin (Diagnostic)
Kaynak: [Kaggle Dataset Linki](https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset)
Toplam Gözlem: 569 örnek
Özellikler: 30 nitelik + 1 hedef değişken (diagnosis)

⚙️ Kullanılan Kütüphaneler
pandas, numpy, scikit-learn, matplotlib, seaborn

🔬 Kullanılan Teknikler
Adım	Açıklama
Veri Temizleme	Eksik veriler kontrol edildi
Görselleştirme	Kutu grafikleri, korelasyon matrisi
Öznitelik Ölçekleme	StandardScaler kullanıldı
Modelleme	Logistic Regression, KNN, Random Forest denendi
Değerlendirme	Confusion matrix, accuracy, precision, recall, F1-score
