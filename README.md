# Customer Purchases Behaviour Dataset ile Keşifsel Veri Analizi

## Projenin Amacı
Bu projenin amacı, müşteri satın alma davranışları üzerine keşifsel veri analizi (EDA) yaparak, müşterilerin satın alma alışkanlıklarını ve demografik özelliklerini anlamaktır. Proje, veri setindeki çeşitli faktörlerin müşteri davranışları üzerindeki etkilerini inceleyerek, işletmelere pazarlama stratejileri, hedef kitle analizi ve müşteri segmentasyonu gibi alanlarda içgörüler sağlamak amacıyla gerçekleştirilmiştir.

Proje kapsamında müşteri verilerinin incelenmesi, satın alma alışkanlıklarına göre farklı müşteri segmentlerinin oluşturulması, demografik ve diğer faktörlere göre satın alma davranışlarının analiz edilmesi, veri görselleştirmeleri ile önemli desenlerin ve eğilimlerin ortaya konması hedeflenmiştir.

## Proje Özeti
-Müşterilerin demografik bilgileri ve satın alma alışkanlıkları içeren veri seti incelenmiştir.
-Eksik veriler tespit edilip düzeltilmiş ve aykırı değerler temizlenmiştir.
-Müşterilerin yaş, cinsiyet, gelir gibi demografik özellikleri ve bunların satın alma alışkanlıkları ile ilişkileri incelenmiştir.
-Satın alma alışkanlıkları üzerinde çeşitli istatistiksel analizler gerçekleştirilmiştir (örneğin, yaş ve gelir ile satın alma sıklığı arasındaki ilişki).

## Değişkenler
Değişkenlerin Açıklaması:
-age: Müşterinin yaşı.
-gender: Müşterinin cinsiyeti (Male Erkek, Female Kadın).
-income: Müşterinin yıllık geliri.
-education: Müşterinin eğitim seviyesi.
-region: Müşterinin yaşadığı bölge.
-loyalty_status: Müşterinin sadakat durumu.
-purchase_frequency: Müşterinin yaptığı satın alım sıklığı.
-purchase_amount: Müşterinin her satın alımda harcadığı tutar.
-product_category: Satın alınan ürün kategorisi.
-promotion_usage: Müşterinin promosyon tekliflerini kullanıp kullanmadığını gösterir (0 Hayır, 1 Evet).
-satisfaction_score: Müşterinin memnuniyet puanı.

## Verinin Genel Yapısı
Bu veri seti, müşteri satın alma davranışını temsil eden simüle edilmiş verileri içerir. Yaş, cinsiyet, gelir, eğitim, bölge, sadakat durumu, satın alma sıklığı, satın alma tutarı, ürün kategorisi, promosyon kullanımı ve memnuniyet puanı gibi çeşitli özellikleri içerir.

Dosya Bilgisi: 
Format: .csv
Satır Sayısı: 100000
Sütun Sayısı: 12 

     Sütun               Non-Null Sayısı  Veri Tipi  
---  ------              --------------  -----  
 0   id                  98084 non-null  float64
 1   age                 98042 non-null  float64
 2   gender              98005 non-null  object 
 3   income              98110 non-null  float64
 4   education           98047 non-null  object 
 5   region              98045 non-null  object 
 6   loyalty_status      97937 non-null  object 
 7   purchase_frequency  98050 non-null  object 
 8   purchase_amount     98051 non-null  float64
 9   product_category    97924 non-null  object 
 10  promotion_usage     97983 non-null  float64
 11  satisfaction_score  97990 non-null  float64
Veri tipi dağılımı: float64(6), object(6)
Bellek kullanımı: 9.2+ MB

## Öne Çıkan Bulgular
-En çok tercih edilen ürün kategorisi: Electronics
-En fazla satın alma yapan müşteri tipi: Female
-En çok alışveriş yapılan bölge: East 
-En yüksek memnuniyet skoruna sahip ürün kategorisi: Home
-En çok satın alma yapan yaş aralığı: 19-30


