# NSG Profile of OGC Geopackage encoding standard

NGA.STND.0051_2.1_GEOPKG



*2017-08-10*



![NGA Seal](https://github.com/royrathbun/nsg_geopkg/blob/master/media/image1.jpeg)

___________________________________________________________________



*NGA STANDARDIZATION DOCUMENT*



*National System for Geospatial-Intelligence (NSG) GeoPackage Encoding Standard 1.1*



*Interoperability Standard*

*(2017-08-10)*

*Version 2.1*

*Geospatial Intelligence Standards Center of Excellence*

# Table of Contents



1. Introduction 5  

2. Scope 5  

3. References 7  

4. Context of the Profile 10  

5. Compliance 10  

6. GeoPackages 12  

  6.1. File Names 12  

  6.2. Extensions 13  

7. Tiles and Features 13

  7.1. Coordinate Reference Systems 13

  7.2. Well Known Text 16

  7.3. Metadata 23

  7.4. Data Validity Constraints 31

8. Tiles 34

  8.1. Tile Size 34

  8.2. Zoom Levels 34

  8.3. Bounding Boxes 34

9. Features 35

  9.1. GeoPackage Extensions 35

Annex A GeoPackage to DoD DSE MDR CRS Dictionary Crosswalk 36

Annex B Metadata Reference Example 37

Annex C Implementation Guide for EPSG::3395 Tiles 46

Annex D Implementation Guide for UPS Tiles 51

Annex E Implementation Guide for EPSG::4326 Tiles 58

Annex F Rtree Spatial Index Extension (Normative) 64

# List of Tables 

Table 1: Profile / Standard Clause Crosswalk 7

Table 2: Normative References in NSG GeoPackage Interoperability Standard 8

Table 3: Informative References in NSG GeoPackage Interoperability Standard 9

Table 4: Raster Tile Pyramid Coordinate Reference Systems for 2D Map Applications 14

Table 5: Raster Tile Pyramid Coordinate Reference Systems for 3D Globe Applications 14

Table 6: Vector feature Coordinate Reference Systems 15

Table 7: WGS 84 Geographic 3D CRS Definition 16

Table 8: WGS 84 Geographic 2D CRS Definition 16]

Table 9: WGS 84 / World Mercator Projected CRS Definition 17

Table 10: WGS 84 / UPS North (E,N) Projected CRS Definition 18

Table 11: WGS 84 / UPS South (E,N) Projected CRS Definition 18

Table 12: EGM2008 geoid height vertical CRS Definition 19

Table 13: EGM2008 geoid depth vertical CRS definition 19

Table 14: EGM96 geoid height vertical CRS definition 20

Table 15: EGM96 geoid depth vertical CRS definition 20

Table 16: MSL height vertical CRS definition 21

Table 17: MSL depth vertical CRS definition 21

Table 18: Compound CRS Definition Template 22

Table 19: Compound CRS Template Parameter Values 23

Table 20: gpkg_metadata Table Contents - Entire GeoPackage 24

Table 21: gpkg_metadata_reference Table Contents - Entire GeoPackage 24

Table 22: NMIS v2.2 Metadata Values - Entire GeoPackage 24

Table 23: gpkg_metadata Table Contents - Partial GeoPackage 29

Table 24: gpkg_metadata_reference Table Contents - Partial GeoPackage 29

Table 25: GeoPackage and NMIS metadata scopes 30

Table 26: Data Validity Constraints 31

Table 27: GeoPackage to DoD DSE MDR CRS Crosswalk 36

Table 28: gpkg_metadata table sample contents 37

Table 29: gpkg_metadata_reference table sample contents 37

Table 30: World Mercator Zoom Level Scale Set and Matrix Dimensions 46

Table 31: World Mercator gpkg_tile_matrix_set 49

Table 32: World Mercator gpkg_tile_matrix 49

Table 33: World Mercator ‘tiles’ table 50

Table 34: WGS 84 Geodetic zoom level scale set and matrix dimensions 58

Table 35: WGS 84 Geodetic gpkg_tile_matrix table 61

Table 36: WGS 84 Geodetic tiles table 63

# List of Figures

Figure 1: GeoPackage Metadata References 37

Figure 2: World Mercator tile indexing 48

Figure 3: World Mercator zoom level 1 example 50

Figure 4: WGS 84 Geodetic tile indexing 60

Figure 5: WGS 84 Geodetic Zoom Level 2 Example 62
