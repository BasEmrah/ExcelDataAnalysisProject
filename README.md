# Excel Data Analysis Project

## Overview

This project involves analyzing a dataset named "data" to extract meaningful insights and visualize the findings using Excel. The dataset includes information such as order details, shipping information, product categories, and customer segments. The main analyses conducted include determining the year with the highest profit, identifying the month with the highest profit within that year, identifying the country with the most orders, finding the product category with the highest shipping cost per unit in 2012, and determining the customer segment with the highest average discount (excluding zero discounts) in 2013.

## Dataset

The dataset stored in the `EmrahBas_ExcelProject.xlsx` file includes the following columns:

- `order_id`: Unique identifier for each order.
- `order_date`: Date the order was placed.
- `ship_date`: Date the order was shipped.
- `ship_mode_name`: Shipping mode (e.g., standard, expedited, express).
- `segment`: Customer segment (e.g., consumer, corporate, home office).
- `product_id`: Unique identifier for each product.
- `category`: Product category (e.g., furniture, technology, office supplies).
- `sub_category`: Product sub-category (e.g., chairs, phones, paper).
- `product_name`: Name of the product.
- `quantity`: Quantity of the product ordered.
- `discount`: Discount rate applied to the order.
- `profit`: Profit obtained from the order.
- `shipping_cost`: Shipping cost of the order.
- `order_priority`: Priority of the order (e.g., high, medium, low).
- `sale_month`: Month of the sale.
- `sale_year`: Year of the sale.
- `state`: State/region where the order was shipped.
- `country`: Country where the order was shipped.
- `market`: Market area (e.g., global, local).
- `region`: Region where the order was shipped.

## Main Analyses

1. **Year with the Highest Profit**
   - Analyzed annual profit data to determine the year with the highest total profit.

2. **Month with the Highest Profit in the Year with the Highest Profit**
   - Analyzed monthly profit data within the year with the highest profit to determine the month with the highest profit.

3. **Country with the Most Orders**
   - Analyzed order data to identify the country with the most orders.

4. **Product Category with the Highest Shipping Cost per Unit in 2012**
   - Calculated the shipping cost per unit for each product category in 2012 to determine the category with the highest cost.

5. **Customer Segment with the Highest Average Discount in 2013 (Excluding 0% Discounts)**
   - Analyzed discount data for 2013 to identify the customer segment with the highest average discount, excluding zero discounts.

## Dashboard

A visual representation of the dashboard named `ExcelProjectDashboard.png` has been created, showcasing the results of these analyses. To view the dashboard effectively, please refer to the "Dashboard" section in the `EmrahBas_ExcelProject.xlsx` file, which includes various charts and graphs.

## Repository Contents

- `EmrahBas_ExcelProject.xlsx`: Excel file containing the raw data, conducted analyses, and created dashboard.
- `ExcelProjectDashboard.png`: Visual representation of the analysis results in the form of a dashboard.
- `README.md`: This documentation file explaining the project overview, dataset, analyses, and repository contents.

## Usage Guide

1. **Download the Repository**
   - Clone or download the repository to your local computer.

2. **Open the Excel File**
   - Open the `EmrahBas_ExcelProject.xlsx` file to review the dataset, conducted analyses, and created dashboard.

3. **View the Dashboard**
   - Open the `ExcelProjectDashboard.png` file to review the visual representation of the analysis results.

## Conclusion

This project demonstrates the process of analyzing a dataset using Excel, performing key business analyses, and visualizing the results through an interactive dashboard. The insights gained from this analysis can help inform business decisions and strategies.

For any questions or further information, please contact bas_emrah@hotmail.com.

---

Thank you for reviewing this project!

---

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

`ExcelProjectDashboard.png` adlı gösterge tablosunun temsili bir görseli oluşturulmuş ve bu analizlerin sonuçlarını görsel olarak sunmaktadır. Gösterge tablosu, bulguları etkili bir şekilde elde etmek için çeşitli grafikler ve çizelgeler içeren `EmrahBas_ExcelProject.xlsx` dosyasında "Dashboard" kısmını inceleyebilirsiniz.

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

---
