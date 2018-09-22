# nsg_geopkg
NSG Profile of OGC Geopackage encoding standard

NGA.STND.0051_2.1_GEOPKG



*2017-08-10*



media/media/image1.jpeg[image,width=117,height=116]

___________________________________________________________________



*NGA STANDARDIZATION DOCUMENT*



*National System for Geospatial-Intelligence (NSG) GeoPackage Encoding Standard 1.1*



*Interoperability Standard*



*(2017-08-10)*



*Version 2.1*



*Geospatial Intelligence Standards Center of Excellence*



= Table of Contents



link:#introduction[1. Introduction 5]



link:#scope[2. Scope 5]



link:#references[3. References 7]



link:#_Toc322708287[4. Context of the Profile 10]



link:#compliance[5. Compliance 10]



link:#geopackages[6. GeoPackages 12]



link:#file-names[6.1. File Names 12]



link:#extensions[6.2. Extensions 13]



link:#tiles-and-features[7. Tiles and Features 13]



link:#coordinate-reference-systems[7.1. Coordinate Reference Systems 13]



link:#well-known-text[7.2. Well Known Text 16]



link:#_Toc485024098[7.3. Metadata 23]



link:#data-validity-constraints[7.4. Data Validity Constraints 31]



link:#tiles[8. Tiles 34]



link:#tile-size[8.1. Tile Size 34]



link:#zoom-levels[8.2. Zoom Levels 34]



link:#bounding-boxes[8.3. Bounding Boxes 34]



link:#features[9. Features 35]



link:#geopackage-extensions[9.1. GeoPackage Extensions 35]



link:#_Ref409435366[Annex A GeoPackage to DoD DSE MDR CRS Dictionary Crosswalk 36]



link:#_Ref409693812[Annex B Metadata Reference Example 37]



link:#_Ref455141106[Annex C Implementation Guide for EPSG::3395 Tiles 46]



link:#_Ref456943402[Annex D Implementation Guide for UPS Tiles 51]



link:#_Ref456947149[Annex E Implementation Guide for EPSG::4326 Tiles 58]



link:#_Ref455144358[Annex F Rtree Spatial Index Extension (Normative) 64]



*List of Tables*



link:#_Ref455132081[Table 1: Profile / Standard Clause Crosswalk 7]



link:#_Ref455132110[Table 2: Normative References in NSG GeoPackage Interoperability Standard 8]



link:#_Ref455132145[Table 3: Informative References in NSG GeoPackage Interoperability Standard 9]



link:#_Ref408828132[Table 4: Raster Tile Pyramid Coordinate Reference Systems for 2D Map Applications 14]



link:#_Ref455140050[Table 5: Raster Tile Pyramid Coordinate Reference Systems for 3D Globe Applications 14]



link:#_Ref455140055[Table 6: Vector feature Coordinate Reference Systems 15]



link:#_Ref393350247[Table 7: WGS 84 Geographic 3D CRS Definition 16]



link:#_Ref408829572[Table 8: WGS 84 Geographic 2D CRS Definition 16]



link:#_Ref408829679[Table 9: WGS 84 / World Mercator Projected CRS Definition 17]



link:#_Ref455140485[Table 10: WGS 84 / UPS North (E,N) Projected CRS Definition 18]



link:#_Ref408830316[Table 11: WGS 84 / UPS South (E,N) Projected CRS Definition 18]



link:#_Ref408831979[Table 12: EGM2008 geoid height vertical CRS Definition 19]



link:#_Ref408832051[Table 13: EGM2008 geoid depth vertical CRS definition 19]



link:#_Ref408832130[Table 14: EGM96 geoid height vertical CRS definition 20]



link:#_Ref408832201[Table 15: EGM96 geoid depth vertical CRS definition 20]



link:#_Ref408832321[Table 16: MSL height vertical CRS definition 21]



link:#_Ref408832391[Table 17: MSL depth vertical CRS definition 21]



link:#_Ref408832659[Table 18: Compound CRS Definition Template 22]



link:#_Ref409172408[Table 19: Compound CRS Template Parameter Values 23]



link:#_Ref396904608[Table 20: gpkg_metadata Table Contents - Entire GeoPackage 24]



link:#_Ref396906174[Table 21: gpkg_metadata_reference Table Contents - Entire GeoPackage 24]



link:#_Ref396906896[Table 22: NMIS v2.2 Metadata Values - Entire GeoPackage 24]



link:#_Ref396910961[Table 23: gpkg_metadata Table Contents - Partial GeoPackage 29]



link:#_Ref396911551[Table 24: gpkg_metadata_reference Table Contents - Partial GeoPackage 29]



link:#_Ref396912147[Table 25: GeoPackage and NMIS metadata scopes 30]



link:#_Ref394929299[Table 26: Data Validity Constraints 31]



link:#_Toc461632053[Table 27: GeoPackage to DoD DSE MDR CRS Crosswalk 36]



link:#_Ref455144778[Table 28: gpkg_metadata table sample contents 37]



link:#_Ref455144848[Table 29: gpkg_metadata_reference table sample contents 37]



link:#_Ref455144569[Table 30: World Mercator Zoom Level Scale Set and Matrix Dimensions 46]



link:#_Ref455144731[Table 31: World Mercator gpkg_tile_matrix_set 49]



link:#_Toc461632058[Table 32: World Mercator gpkg_tile_matrix 49]



link:#_Ref455145242[Table 33: World Mercator ‘tiles’ table 50]



link:#_Ref455145462[Table 34: WGS 84 Geodetic zoom level scale set and matrix dimensions 58]



link:#_Ref455145681[Table 35: WGS 84 Geodetic gpkg_tile_matrix table 61]



link:#_Ref455145719[Table 36: WGS 84 Geodetic tiles table 63]



*List of Figures*



link:#_Ref455144485[Figure 1: GeoPackage Metadata References 37]



link:#_Ref455144675[Figure 2: World Mercator tile indexing 48]



link:#_Ref455145372[Figure 3: World Mercator zoom level 1 example 50]



link:#_Ref455145615[Figure 4: WGS 84 Geodetic tile indexing 60]



link:#_Ref485806152[Figure 5: WGS 84 Geodetic Zoom Level 2 Example 62]
