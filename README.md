# Water Protection GIS 🌍

CBS tabanlı su kaynakları koruma zonları ve kirlilik riski haritalama projesi.  
Bu projede QGIS kullanılarak Bursa ve Ankara illeri üzerinde DEM, eğim analizi, tampon zon (buffer) analizi ve risk skorlaması gerçekleştirilmiştir.

---

## Technologies

- QGIS
- OpenStreetMap (QuickOSM)
- SRTM DEM
- Raster & Vector Analysis
- Buffer Analysis
- Intersection Analysis

---

# Workflow

## 1. Study Area Selection

Bursa ve Ankara çalışma alanı olarak seçildi ve idari sınırlar filtrelendi.

---

## 2. DEM Merge

SRTM DEM verileri birleştirildi ve çalışma alanına göre kırpıldı.

---

## 3. Slope Analysis

DEM verilerinden eğim haritaları üretildi.

---

## 4. Land Use Visualization

OpenStreetMap verileri kullanılarak sanayi, tarım ve su katmanları oluşturuldu.


---

## 5. Buffer Zone Analysis

Su kaynakları etrafında 300m, 1000m ve 2000m koruma zonları oluşturuldu.


---

## Findings

- Bursa Organize Sanayi Bölgesi (BOSB) çevresinde yüksek riskli alanlar tespit edildi.
- İznik Gölü çevresinde koruma zonu ihlalleri belirlendi.
- Ankara’da risk alanları daha dağınık bir dağılım gösterdi.

---

## Data Sources

- GADM
- USGS EarthExplorer
- OpenStreetMap
- QGIS
