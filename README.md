# Excel Veri Analizi Projesi

## Genel Bakış

Bu proje, "data" adlı bir veri kümesini analiz ederek anlamlı bilgiler çıkarmayı ve bulguları Excel kullanarak görselleştirmeyi içerir. Veri kümesi, sipariş detayları, gönderim bilgileri, ürün kategorileri ve müşteri segmentleri gibi bilgileri içermektedir. Yapılan ana analizler arasında en yüksek karın sağlandığı yılın belirlenmesi, bu yıl içindeki en yüksek karın sağlandığı ayın tespiti, en fazla sipariş veren ülkenin belirlenmesi, 2012 yılı için birim başına en yüksek gönderim maliyetine sahip ürün kategorisinin bulunması ve 2013 yılında sıfır indirimler hariç en yüksek ortalama indirimi alan müşteri segmentinin belirlenmesi yer almaktadır.

## Veri Kümesi

`EmrahBas_ExcelProject.xlsx` dosyasında saklanan veri kümesi şu sütunları içermektedir:

- `order_id`: Sipariş kimliği, her sipariş için benzersiz bir tanımlayıcı.
- `order_date`: Siparişin verildiği tarih.
- `ship_date`: Siparişin gönderildiği tarih.
- `ship_mode_name`: Gönderim modu (örneğin, standart, hızlı, ekspres).
- `segment`: Müşteri segmenti (örneğin, tüketici, kurumsal, ev ofisi).
- `product_id`: Ürün kimliği, her ürün için benzersiz bir tanımlayıcı.
- `category`: Ürün kategorisi (örneğin, mobilya, teknoloji, ofis malzemeleri).
- `sub_category`: Ürün alt kategorisi (örneğin, sandalyeler, telefonlar, kağıt).
- `product_name`: Ürün adı.
- `quantity`: Sipariş edilen ürün miktarı.
- `discount`: Sipariş için uygulanan indirim oranı.
- `profit`: Siparişten elde edilen kar.
- `shipping_cost`: Siparişin gönderim maliyeti.
- `order_priority`: Sipariş önceliği (örneğin, yüksek, orta, düşük).
- `sale_month`: Satışın gerçekleştiği ay.
- `sale_year`: Satışın gerçekleştiği yıl.
- `state`: Siparişin gönderildiği eyalet/bölge.
- `country`: Siparişin gönderildiği ülke.
- `market`: Pazarı temsil eden alan (örneğin, global, yerel).
- `region`: Siparişin gönderildiği bölge.

## Ana Analizler

1. **En Yüksek Kar Sağlanan Yıl**
   - Yıllık kar verilerini analiz ederek en yüksek toplam karın sağlandığı yılı belirledik.

2. **En Yüksek Kar Sağlanan Yıldaki En Yüksek Kar Sağlanan Ay**
   - En yüksek karın sağlandığı yıl içinde, aylık kar verilerini analiz ederek en yüksek karın sağlandığı ayı belirledik.

3. **En Fazla Sipariş Veren Ülke**
   - Sipariş verilerini analiz ederek en fazla sipariş veren ülkeyi belirledik.

4. **2012 Yılında Birim Başına En Yüksek Gönderim Maliyetli Ürün Kategorisi**
   - 2012 yılı için her ürün kategorisinin birim başına gönderim maliyetini hesaplayarak en yüksek maliyete sahip kategoriyi belirledik.

5. **2013 Yılında En Yüksek Ortalama İndirimi Alan Müşteri Segmenti (0% İndirimler Hariç)**
   - 2013 yılı indirim verilerini analiz ederek, sıfır indirim hariç en yüksek ortalama indirimi alan müşteri segmentini belirledik.

## Gösterge Tablosu

`ExcelProjectDashboard.png` adlı kapsamlı bir gösterge tablosu oluşturulmuş ve bu analizlerin sonuçlarını görsel olarak sunmaktadır. Gösterge tablosu, bulguları etkili bir şekilde iletmek için çeşitli grafikler ve çizelgeler içermektedir.

## Depo İçeriği

- `EmrahBas_ExcelProject.xlsx`: Ham verileri, gerçekleştirilen analizleri ve oluşturulan dashboard ı içeren Excel dosyası.
- `ExcelProjectDashboard.png`: Analiz sonuçlarının görsel temsilini içeren gösterge tablosu.
- `README.md`: Projenin genel bakışını, veri kümesini, analizleri ve depo içeriğini açıklayan bu dokümantasyon dosyası.

## Kullanım Kılavuzu

1. **Depoyu İndirin**
   - Depoyu yerel bilgisayarınıza klonlayın veya indirin.

2. **Excel Dosyasını Açın**
   - `EmrahBas_ExcelProject.xlsx` dosyasını açarak veri kümesini inceleyin, gerçekleştirilen analizleri ve oluşturulan dashboard ı gözden geçirin.

3. **Gösterge Tablosunu Görüntüleyin**
   - `ExcelProjectDashboard.png` dosyasını açarak analiz sonuçlarının görsel temsilini inceleyin.

## Sonuç

Bu proje, bir veri kümesini Excel kullanarak analiz etme, ana iş analizlerini gerçekleştirme ve sonuçları interaktif bir gösterge tablosu aracılığıyla görselleştirme sürecini göstermektedir. Bu analizden elde edilen bilgiler, iş kararlarını ve stratejilerini bilgilendirmeye yardımcı olabilir.

Herhangi bir soru veya daha fazla bilgi için lütfen bas_emrah@hotmail.com.

---

Bu projeyi incelediğiniz için teşekkürler!
