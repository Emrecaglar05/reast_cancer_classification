🚀 Proje Başlığı
Meme Kanseri Teşhisi için Makine Öğrenimi Modellerinin Geliştirilmesi

🔍 Proje Özeti
Bu proje, makine öğrenimi teknikleri kullanarak meme kanserinin erken teşhisini hedeflemektedir. Hücre çekirdeği özellikleri gibi medikal verilerden yararlanarak, tümörün iyi huylu (benign) veya kötü huylu (malignant) olup olmadığını yüksek doğrulukla sınıflandıran modeller geliştirilmiştir. Böylece, tanı sürecinde doktorlara destek olacak güçlü ve otomatik bir teşhis aracı ortaya konmuştur.

🎯 Proje Amacı
Meme kanserinde erken teşhis, tedavi başarısı için hayati önem taşır. Bu proje kapsamında, tıbbi veri setleri üzerinde makine öğrenimi algoritmaları uygulanarak, kanserli hücrelerin otomatik tespiti ve doğru sınıflandırılması sağlanmıştır. Amaç, doktorların tanı sürecini hızlandırmak ve hata payını minimize etmek için güvenilir modeller geliştirmektir.

📊 Veri Seti
Kullanılan veri seti: Breast cancer dataset

İçerik: Her bir tümör için 30 farklı sayısal özellik (yarıçap, doku, çevre, pürüzsüzlük vb.)

Hedef değişken: diagnosis (iyi huylu: B, kötü huylu: M)

🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Pandas & NumPy: Veri işleme ve sayısal analiz

Matplotlib & Seaborn: Veri görselleştirme

Scikit-learn: Makine öğrenimi modelleme, ön işleme ve değerlendirme

🔄 Proje Süreci
Veri Yükleme & Keşif Analizi
Veri seti incelenmiş, eksik veri kontrolü yapılmış ve hedef değişken dağılımı görselleştirilmiştir.

Veri Ön İşleme

Gereksiz sütunlar (id) çıkarılmıştır.

Kategorik diagnosis sütunu sayısal (M=1, B=0) hale getirilmiştir.

Veri Görselleştirme

Tanı dağılımı çubuk grafiklerle gösterildi.

Özellikler arası korelasyon matrisi ile ilişkiler analiz edildi.

Seçilen özelliklerin tanıya göre dağılımı kutu grafikleriyle incelendi.

Özellik Seçimi
Random Forest algoritmasıyla en etkili özellikler belirlendi ve model performansı bu özelliklere odaklanarak artırıldı.

Veri Hazırlığı

Veri, eğitim ve test olarak ikiye ayrıldı.

Farklı ölçeklere sahip özellikler için StandardScaler ile ölçeklendirme uygulandı.

Model Eğitimi & Değerlendirme
Üç farklı model eğitildi ve karşılaştırıldı:

Random Forest

Destek Vektör Makinesi (SVM)

Yapay Sinir Ağı (MLPClassifier)

Sonuçların Karşılaştırılması
Modellerin doğruluk, sınıflandırma raporu ve karışıklık matrisi performansları detaylıca sunuldu ve başarıları grafiklerle görselleştirildi.

🌟 Proje Çıktısı
Bu çalışma, meme kanseri teşhisinde doktorlara destek sağlayabilecek doğru ve güvenilir makine öğrenimi modelleri geliştirilmesini sağlamış ve erken teşhiste kullanılabilecek pratik bir çözüm sunmuştur.
