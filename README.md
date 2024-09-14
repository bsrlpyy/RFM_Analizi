# CRM Analitiği - RFM Modeli 

## Proje Açıklaması ✨
Bu proje, Miuul'un CRM analitiği dersi kapsamında geliştirilmiş bir case study'dir. Online ayakkabı mağazası olan FLO'nun müşteri segmentlerini analiz ederek pazarlama stratejilerini optimize etmeyi amaçlamaktadır. RFM (Recency, Frequency, Monetary) modeli kullanılarak müşterilerin davranışları detaylı bir şekilde analiz edilecek ve bu analizler doğrultusunda stratejik kararlar alınacaktır.

## Kullanılan Teknolojiler 🛠️
- Python: Genel programlama ve veri işleme için.
- Pandas: Veri manipülasyonu ve analizi için.
- NumPy: Sayısal işlemler ve veri yapılandırması için.
- Matplotlib/Seaborn: Verilerin görselleştirilmesi için.

## Proje Adımları ⚙️

### Görev 1: Veriyi Anlama ve Hazırlama 🤔
1. flo_data_20K.csv veri dosyasını okuyun ve bir DataFrame kopyası oluşturun.
2. Veri setinde:
   - İlk 10 gözlemi inceleyin.
   - Değişken isimlerini gözden geçirin.
   - Betimsel istatistikleri analiz edin.
   - Boş değerleri tespit edin.
   - Değişken tiplerini kontrol edin.
3. Omnichannel müşterilerin hem online hem de offline platformlardan alışveriş yaptığını belirten yeni değişkenler oluşturun.
4. Tarih değişkenlerinin tipini date olarak değiştirin.
5. Alışveriş kanallarındaki müşteri sayısı, toplam ürün sayısı ve toplam harcamaların dağılımını analiz edin.
6. En yüksek kazancı getiren ilk 10 müşteriyi sıralayın.
7. En fazla siparişi veren ilk 10 müşteriyi sıralayın.
8. Veri ön hazırlık sürecini bir fonksiyon haline getirin.

### Görev 2: RFM Metriklerinin Hesaplanması
1. Recency, Frequency ve Monetary metriklerinin tanımlarını yapın.
2. Müşteri bazında Recency, Frequency ve Monetary metriklerini hesaplayın.
3. Hesaplanan metrikleri rfm isimli bir DataFrame'e atayın.
4. Metriklerin isimlerini recency, frequency, ve monetary olarak değiştirin.
5. Recency değerini hesaplamak için analiz tarihini maksimum tarihten 2 gün sonrası olarak seçebilirsiniz.

### Görev 3: RF Skorunun Hesaplanması 
1. Recency, Frequency ve Monetary metriklerini qcut yardımıyla 1-5 arasında skorlara çevirin.
2. Bu skorları recency_score, frequency_score ve monetary_score olarak kaydedin.
3.  recency_score ve frequency_score'u tek bir değişken olarak ifade edin ve `RF_SCORE olarak kaydedin.

### Görev 4: RF Skorunun Segment Olarak Tanımlanması🙂
1. Oluşturulan RF skorları için segment tanımlamaları yapın.
2. Skorları segmentlere çeviren seg_map fonksiyonunu kullanın.

### Görev 5: Aksiyon Zamanı!🚀
1. Segmentlerin Recency, Frequency ve Monetary ortalamalarını inceleyin.
2. RFM analizi yardımıyla aşağıdaki iki case için uygun müşteri profillerini bulun ve müşteri ID'lerini CSV dosyasına kaydedin:
   - Case A: Yeni bir kadın ayakkabı markası için sadık müşteriler ve kadın kategorisinden alışveriş yapan müşteriler.
   - Case B: Erkek ve çocuk ürünlerinde indirim planlanan uykuda olan, kaybedilmemesi gereken ve yeni gelen müşteriler.

## Veri Seti Bilgileri 📊
Veri seti, FLO'nun müşteri davranışlarını analiz etmek için kullanılan bilgileri içermektedir. Toplamda 12 değişken ve 19.945 gözlem içermektedir. Değişkenler alışveriş kanalları, alışveriş tarihleri ve toplam harcamalar gibi bilgileri kapsamaktadır.

## Lisans 📜
Copyright © Miuul, Inc. All Rights Reserved

---
