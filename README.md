# Customer Lifetime Value
müşteri yaşam döngüsü değeri hesaplama

## veriseti linki:
https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

## veriseti hakkında:
Bir e-ticaret şirketi müşterilerini segmentlere ayırıp bu segmentlere göre pazarlama stratejileri belirlemek istiyor.

## değişkenler:
- InvoiceNo: Fatura numarası. Her işleme yani faturaya ait eşsiz numara. C ile başlıyorsa iptal edilen işlem.
- StockCode: Ürün kodu. Her bir ürün için eşsiz numara.
- Description: Ürün ismi
- Quantity: Ürün adedi. Faturalardaki ürünlerden kaçar tane satıldığını ifade etmektedir.
- InvoiceDate: Fatura tarihi ve zamanı.
- UnitPrice: Ürün fiyatı (Sterlin cinsinden)
- CustomerID: Eşsiz müşteri numarası
- Country: Ülke ismi. Müşterinin yaşadığı ülke.

## hesaplamalar
- Customer Lifetime Value(CLTV) = ( Customer Value / Churn Rate ) * Profit Margin
- Customer Value = Average Order Value * Purchase Frequency
- Average Order Value = Total Price / Total Transaction
- Purchase Frequency = Total Transaction / Total Number of Customers
- Churn Rate = 1 - Repeat Rate
- Repeat Rate = Birden fazla kez alışveriş yapan müşteri sayısı / Tüm müşteriler
- Profit Margin = Total Price * 0.10

### notlar:
- average order value = ortalama sipariş değeri
- purchase frequency = sipariş sıklığı
- churn rate = müşterinin terk etme oranı
- repeat rate = tekrarlama oranı
- profit margin = kar marjı
- total transaction = toplam sipariş/işlem sayısı

