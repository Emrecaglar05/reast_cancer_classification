Proje Başlığı: Meme Kanseri Teşhisi İçin Makine Öğrenimi Modelleri
Bu proje, meme kanseri teşhisi için makine öğrenimi modellerini kullanarak hasta verilerini analiz eder. Amacımız, hücre çekirdeği özellikleri gibi verilerden yola çıkarak bir tümörün iyi huylu (benign) mu yoksa kötü huylu (malignant) mu olduğunu doğru bir şekilde tahmin edebilen modeller oluşturmaktır.

Proje Amacı
Meme kanseri erken teşhisi, tedavi başarısı için kritik öneme sahiptir. Bu proje, elde edilen tıbbi verileri kullanarak makine öğrenimi algoritmalarıyla potansiyel olarak kanserli hücreleri otomatik olarak tespit etmeyi hedefler. Bu sayede, doktorlara tanı sürecinde yardımcı olabilecek güçlü bir araç sunulması amaçlanmaktadır.

Veri Seti
Bu proje, Wisconsin Meme Kanseri Veri Seti (Diagnosis) üzerinde çalışmaktadır. Veri seti, her bir tümörün çeşitli özelliklerini (yarıçap, doku, çevre, pürüzsüzlük vb.) içeren 30 farklı sayısal özniteliğe sahiptir. Veri setindeki temel hedef değişken diagnosis sütunudur, bu sütun tümörün iyi huylu (B) veya kötü huylu (M) olduğunu belirtir.

Kullanılan Kütüphaneler
Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

Pandas: Veri işleme ve manipülasyonu için.

NumPy: Sayısal hesaplamalar ve dizi işlemleri için.

Matplotlib & Seaborn: Veri görselleştirme ve grafik çizimi için.

Scikit-learn: Makine öğrenimi algoritmaları, model eğitimi, değerlendirme ve veri ön işleme adımları için.

Proje Akışı
Proje, aşağıdaki adımları içeren kapsamlı bir analiz süreci sunar:

Veri Yükleme ve Keşif: Veri seti yüklenir, temel istatistikleri, eksik verileri ve hedef değişkenin dağılımı incelenir.

Veri Ön İşleme:

Gereksiz sütunlar (id) veri setinden çıkarılır.

Kategorik diagnosis sütunu (M, B) sayısal değerlere (1, 0) dönüştürülür.

Veri Görselleştirme:

Tanı dağılımını gösteren çubuk grafikler oluşturulur.

Özellikler arasındaki ilişkileri anlamak için korelasyon matrisi çizilir.

Belirli özelliklerin tanıya göre dağılımını incelemek için kutu grafikleri (boxplot) kullanılır.

Özellik Seçimi: Rastgele Orman (Random Forest) algoritması kullanılarak, tahminde en yüksek öneme sahip özellikler belirlenir ve modelin performansını artırmak için bu özellikler kullanılır.

Veri Hazırlığı:

Veri seti, eğitim ve test olmak üzere iki parçaya ayrılır.

Farklı ölçeklere sahip özelliklerin etkisini dengelemek için StandardScaler ile veriler ölçeklendirilir.

Model Eğitimi ve Değerlendirme: Üç farklı makine öğrenimi modeli eğitilir ve performansları karşılaştırılır:

Rastgele Orman (Random Forest)

Destek Vektör Makinesi (SVM)

Yapay Sinir Ağı (MLPClassifier)

Sonuçların Karşılaştırılması: Eğitilen her modelin doğruluk (accuracy), sınıflandırma raporu ve karışıklık matrisi gibi performans metrikleri sunulur. Son olarak, modellerin doğruluk puanlarını karşılaştıran bir grafik oluşturulur.
