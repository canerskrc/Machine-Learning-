Sınıflandırma (Classification)

Eğitmek için etiketlenmiş verileri kullanan makine öğrenmesinin bir parçasıdır.
Makine öğrenmeisnde ve istatistikte yeni bir gözlemin, (verinin) ya da gözlem kümesinin hangi alt kategoriye ait olduğu bilinen eğitim setlerine dayalı olarak çalışır.

Temel amacı özelliklerine dayalı olarak yeni bir gözleme doğru veri sunabilmek.

İki farklı sınıflandırma türü vardır;
1- İkili Sınıflandırma

Girdi verilerini iki sınıftan birine atayabilmek.

2- Çoklu Sınıflandırma

Girdiyi birkaç kategoriden bir tanesine atayabilmek.

Sınıflandırma Algoritmalarının Türleri

1- Doğrusal Sınıflandırıcılar

Basit ve daha verimli hesaplamalar yapılabilir. 
- Lojistik Regresyon
- SVM
- Tek Katmanlı Sinir Ağı ( Genellikle Tensorflow kullanılır.)

2- Doğrusal Olmayan Sınıflandırıcılar
Girdi verileri ile hedef değişken arasındaki daha karmaşık ilişkileri yakalamak için kullanılır.
- KNN
- Naive Bayes
- Karar Ağaçları
Topluluk Öğrenme Sınıflandırıcılar:
- Random Forest
- Ada Boost
- Oylama Sınıflandırması
- ExtraTrees Sınıflandırıcılar



Değerlendirme Ölçütleri 
- Sınıflandırma Doğruluğu
Doğru sınıflandırılmış verilerin test setindeki toplam örnek sayısına oranı.Sezgisel bir ölçüdür.

- Karışıklık Matrisi
  
TP(True Positive)
TN (True Negative)
FP
FN

Sayılarını gösteren bir tablo

- Kesinlik(Hassasiyet) ve Geri Çağırma
Hassasiyet=TP lerin  toplam pozitif sayısına oranı.

- F1 Score (Puanı)
F1=2*Hassasiyet*geri çağırma / Hassasiyet+ Geri Çağırma

Dengesiz Veri setleri için önemli bir terim.

- ROC Eğrisi ve AUC Alanı:
 Gerçek pozitiflerin Yanlış Pozitif oranına karşı grafiği.
Roc eğrisinin altında kalan alana AUC denir.

Tahmini değerle(0.5) ile 1 (mükemmel sınıflandırma) arasındaki değişen değerlerle sınıflandırıcının genel performansını ölçer.

- Çaprazlama Doğrusu

Modelin performansını daha sağlam (güvenilir) tahmin edebilmek için her bir veriyi birden çok bölüme ayırır, her bir katmanı eğitirken diğer katmanlarda test eden bir teknik.

Örnek Yapılabilecek Sınıflandırma Uygulamaları:

- Spam Tespiti
- Kredi Değerlendirme
- Sağlık Teşhisleri
- Duygu analizi
- Görüntü Sınıflandırması
- Müşteri Sınıflandırması
- Kalite Kontrol
- Öneri Sistemleri





