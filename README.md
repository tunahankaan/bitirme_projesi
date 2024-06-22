# bitirme_projesi
## Konu
VESTEL hisse senedinin 10 yıllık kapanış verilerinden yola çıkılarak belirli algoritmalarla model kurma ve tahmin performansı karşılaştırılması
## Temel Bilgiler
Korelasyon Analizi : İki veya daha fazla değişken arasındaki doğrusal ilişkiyi belirlemeye yönelik bir istatistiksel tekniktir. Bu çalışmada şirketin KAP'a  Mart, Haziran, Eylül ve Aralık aylarında açıklanan bilanço verilerinden, hacim dğerlerinden ve gelir tablosundan yola çıkılarak hisse fiyatı verileri ile karşılaştırma yapılmıştır. Buradaki amaç LSTM algoritmasının kararlılığının artırılmasıdır.
## Materyal
- Yapay Sinir Ağları : Öğrenme süreci boyunca ağırlıkları ve eğimleri ayarlayarak veriler arasındaki ilişkileri öğrenir.
- LSTM : Özellikle uzun vadeli bağımlılıkları ele alabilen ve aynı zamanda kısa vadeli dalgalanmalara da duyarlı olan bir yapıya sahiptir.
- Random Forest : Birden çok karar ağacının bir araya getirilerek değerlendirilmesini kapsar.
- ExtraTrees : Karar ağaçlarının bir araya getirilmesini sağlar ve bu ağaçların varlığını birleştirerek daha güçlü ve genel yapılabilir modeller üretir.
## Sonuç
Yapılan tahmin çalışmasında LSTM algoritmasının model doğruluk (accuracy) değeri 0,9587 ExtraTrees algoritmasının 0,9761 olarak hesaplanmıştır. Buradan ExtraTrees algoritmasının daha doğru tahmin yaptığı öngörülür.


