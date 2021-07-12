# Geospace Analytics

- [地理空間作業の開始](https://towardsdatascience.com/getting-started-with-geospatial-works-1f7b47955438)
  - 地理空間データとは何ですか？
  - GISデータの種類 (ベクターデータ, ポイントデータ, ラインデータ, ポリゴンデータ)
  - ベクターデータのフォーマット (Esri SHAPE, 地理JSON, Geography Markup Language(GML),Google Keyhole Markup Language)
  - ラスターデータ(GeoTIFF, ERDAS Imagine, IDRISIラスター)
  - データソース(Esriオープンデータ, 自然地球データ, USGD Earth Explorer,NASAの社会経済データおよびアプリケーションセンター,UNEP環境データエクスプローラー,DIVA-GIS)
  - 視覚化ツール
   　- パッケージ (Geoplot, Folium, Geopandas, PySAL, rworldmapとrworldxtraR)
   　- オープンソースソフトウェア(PostGIS, QGIS, GrassGIS, Kepler.gl(Deck/Luma/React map/React vis))
- [Walkthrough: Mapping GIS Data in Python](https://towardsdatascience.com/walkthrough-mapping-gis-data-in-python-92c77cd2b87a)
  -  
 
- Cartographic Boundary Files - Shapefile
 - USA | [Census Bureau’s MAF/TIGER geographic database](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)
    -  state-based and national congressional district cartographic boundary files for the 103rd through 110th Congresses,  
    -  shapefile and KML format.   
    -  cb_2018_ss_entity_rr.zip (rr=resolution leve ; 500k, 5m, 20m)
    -  Naton/Regions/Stetes/Urban Areas/ZIP Code Tabulation Areas (ZCTAs)
 -   [Country Shape Maps (DIVA-GIS)](https://www.diva-gis.org/gdata)
    - 国の行政区域（境界）GADM v1.0より
    - WORLD SHAPEFILE MAPS
        - [EUROSTAT](https://ec.europa.eu/eurostat/web/nuts/background)  
          - GISCO - the Geographic Information System of the COmmission - localise, analyse, visualise
        - [ARCGIS Hub](https://hub.arcgis.com/datasets/2b93b06dc0dc4e809d3c8db5cb96ba69_0/explore?location=-4.017884%2C0.000000%2C0.85) 
    　　-　[NATURAL EARTH](http://www.naturalearthdata.com/features/)
    　　  -  ESRI shapefile format / UTF-8 / 　TIFF format with a TFW world file /  Geographic coordinate system (projection), WGS84 datum
    　　-　[GADM data](https://gadm.org/data.html) = 386,735 administrative areas. The data are freely available for academic use. 
    　　  -　Geopackage
    　　  -　Shapefile
    　　  -　R (sp): level-0, level1, level2
    　　  -　R (sf): level-0, level1, level2
    　　  -　KMZ: level-0, level1, level2
    　　  -　GIDは、3文字のISO 3166-1alpha-3国コードで始まる。
    　　- [World Bank Official Boundaries Primary tabs](https://datacatalog.worldbank.org/dataset/world-bank-official-boundaries)　
   -　[ArcGis Tutorial - How to create shape files, labels and spatial reference](https://www.youtube.com/watch?v=uhdSGeFaVSo) 
- References
  - [Rによる地理空間データ解析入門](https://www.kyoritsu-pub.co.jp/bookdetail/9784320124394) [[Code]](https://bookdown.org/lexcomber/brunsdoncomber2e/)  'An Introduction to Spatial Analysis and Mapping in R', Chris Brunsdon and Lex Comber, 2019-04-16.


- Python library
  - geopandas = Pandas to allow spatial operations on geometric types
  - geoplot = a high-level geospatial plotting library
  - [
Visualizing Geospatial Data in Python: Tutorial](https://github.com/DerwenAI/ibm_dsc_articles/blob/master/2020_05/tutorial.ipynb)


- Open Data
 - Shape Models = there are so many open data sources for shapefiles.
   - the US Census Bureau TIGER database
   - Natural Earth
   - ESRI: ArcGIS Living Atlas
   - NOAA Weather Data 



- Glossary
  - GPS
  - GIS 
  - Remote Sensing (RS) 
  - Unmanned Aerial Vehicles (UAVS)
  - GeoSpatial Analytics
  - Shape Models
  - Raster and Vector images
  - Satellite Imagery  
  - Mobile Devices
  - Geo Database
  - Esri Japan
  - Smart Mapping
  - Disolve, Merge, Clip
  - references
    - Esri [GIS glossary](https://www.esrij.com/gis-guide/) 
    - Esri [Business Map glossary](https://www.esrij.com/business-map-glossary/)
    - 国土交通省 [地方公共団体向け地理空間情報に関するWebガイドブック](https://www.mlit.go.jp/kokudoseisaku/gis/gis/webguide/giswg_solsht/1065/)
    - 国土地理院 [用語集](https://www.gsi.go.jp/common/000213880.pdf)
    - 株式会社PASCO [用語集とGISの使い方](https://www.pasco.co.jp/recommend/word/)
    - 株式会社Informatics [GIS用語解説](https://club.informatix.co.jp/?page_id=1691)

---
- Amazon Location Service
  Use Cases
   1. ユーザーエンゲージメントとジオマーケティング＝小売業者が対象店舗の近くにいる顧客に割引コードやデジタルチラシを送信。
   2. 資産管理＝製品、人員、インフラの現在および過去の場所を特定。配置を最適化、輸送中貨物を安全に保護、発送効率最大化。
   3. 配達 ＝出発地、配達車両、目的地を保存、追跡、調整する。
