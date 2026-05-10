# Capstone Readme

## Data Sources (Appendix)

2024 United States NOAA billion-dollar disaster location and type map
“2024-NOAA-Billion-Dollar-Disaster-Map-Final.png.” NOAA Climate.gov, 2024, www.climate.gov/media/16724.
  Pinellas County GIS (open data)
    “Pinellas County Enterprise GIS.” Arcgis.com, 2025, new-pinellas-egis.opendata.arcgis.com/search?q=zoning&sort=Date%20Updated%7Cmodified%7Cdesc. Accessed 10 May 2026.
    Pinellas County boundary (import) 
    “ArcGIS.” Arcgis.com, 2026, www.arcgis.com/home/item.html?id=aba72d66b4774235ab07fcada57aa8e6. Accessed 10 May 2026.
  Pinellas County parcel data
    “Pinellas_ParcelPropertyInfo (FeatureServer).” Arcgis.com, 2026, services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_ParcelPropertyInfo/FeatureServer. Accessed 10 May 2026.
    Key fields utilized:
      •	LAND_USE or USE_CODE
      •	JUST_VALUE or property value
      •	ACRES
  Pinellas County land use planning
    “Pinellas_LandUseProposed_view (FeatureServer).” Arcgis.com, 2026, services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_LandUseProposed_view/FeatureServer. Accessed 10 May 2026.
  Pinellas County Park boundaries
    “Pinellas_ParkBoundaries_view (FeatureServer).” Arcgis.com, 2026, services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_ParkBoundaries_view/FeatureServer. Accessed 10 May 2026.
  Emergency Management Shelters
    “Pinellas_PCEM_Shelters_view (FeatureServer).” Arcgis.com, 2026, services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_PCEM_Shelters_view/FeatureServer. Accessed 10 May 2026.
  Planning Unincorporated Zoning (2019)
    “Pinellas_Zoning2019_view (FeatureServer).” Arcgis.com, 2019, services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_Zoning2019_view/FeatureServer. Accessed 10 May 2026.
  Pinellas County municipality map
    “Map of Municipalities & Unincorporated Areas - Pinellas County.” Pinellas County, 28 Feb. 2022, pinellas.gov/map-of-municipalities-unincorporated-areas/. Accessed 10 May 2026.
  FEMA Flood Map Service Center
    “FEMA Flood Map Service Center | Search All Products.” Msc.fema.gov, msc.fema.gov/portal/advanceSearch#searchresultsanchor.
      Key fields utilized:
      o	S_FLD_HAZ_AR (Flood Hazard Areas)
        	Includes:
        •	AE (100-year floodplain)
        •	VE (coastal high hazard)
        •	X (low risk)
      •	Clip flood zones
        •	Symbology: unique, deselected X and Open Water layers for visual clarity Select by Attributes inverted where  clause FLD_ZONME is equal to OPEN WATER OR FLD_ZONE is equal to X
  CDC Social Vulnerability Index (SVI)
    “The Social Vulnerability Index (SVI): Data and Tools Download for Place and Health | CDC.” Cdc.gov, 2022, svi.cdc.gov/dataDownloads/data-download.html.
  Post Storm imagery
    “ArcGIS.” Arcgis.com, 2026, www.arcgis.com/home/item.html?id=2dc2428b306d4ec1bf2a9cf747270d09. Accessed 10 May 2026.
