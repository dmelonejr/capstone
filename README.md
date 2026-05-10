# Capstone Readme

## Data Sources (Appendix)

### NOAA Disaster Data

- “2024 United States NOAA Billion-Dollar Disaster Location and Type Map.” *NOAA Climate.gov*, 2024.  
  `2024-NOAA-Billion-Dollar-Disaster-Map-Final.png`  
  <https://www.climate.gov/media/16724>

---

### Pinellas County GIS (Open Data)

- “Pinellas County Enterprise GIS.” *ArcGIS Open Data*, 2025.  
  <https://new-pinellas-egis.opendata.arcgis.com/search?q=zoning&sort=Date%20Updated%7Cmodified%7Cdesc>  
  Accessed 10 May 2026.

#### Pinellas County Boundary (Import)

- “ArcGIS.” *ArcGIS Online*, 2026.  
  <https://www.arcgis.com/home/item.html?id=aba72d66b4774235ab07fcada57aa8e6>  
  Accessed 10 May 2026.

---

### Pinellas County Parcel Data

- “Pinellas_ParcelPropertyInfo (FeatureServer).” *ArcGIS REST Services*, 2026.  
  <https://services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_ParcelPropertyInfo/FeatureServer>  
  Accessed 10 May 2026.

#### Key Fields Utilized

- `LAND_USE` or `USE_CODE`
- `JUST_VALUE` (property value)
- `ACRES`

---

### Pinellas County Land Use Planning

- “Pinellas_LandUseProposed_view (FeatureServer).” *ArcGIS REST Services*, 2026.  
  <https://services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_LandUseProposed_view/FeatureServer>  
  Accessed 10 May 2026.

---

### Pinellas County Park Boundaries

- “Pinellas_ParkBoundaries_view (FeatureServer).” *ArcGIS REST Services*, 2026.  
  <https://services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_ParkBoundaries_view/FeatureServer>  
  Accessed 10 May 2026.

---

### Emergency Management Shelters

- “Pinellas_PCEM_Shelters_view (FeatureServer).” *ArcGIS REST Services*, 2026.  
  <https://services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_PCEM_Shelters_view/FeatureServer>  
  Accessed 10 May 2026.

---

### Planning Unincorporated Zoning (2019)

- “Pinellas_Zoning2019_view (FeatureServer).” *ArcGIS REST Services*, 2019.  
  <https://services.arcgis.com/f5HgUpxURgEzTccH/arcgis/rest/services/Pinellas_Zoning2019_view/FeatureServer>  
  Accessed 10 May 2026.

---

### Pinellas County Municipality Map

- “Map of Municipalities & Unincorporated Areas - Pinellas County.” *Pinellas County*, 28 Feb. 2022.  
  <https://pinellas.gov/map-of-municipalities-unincorporated-areas/>  
  Accessed 10 May 2026.

---

### FEMA Flood Map Service Center

- “FEMA Flood Map Service Center | Search All Products.” *FEMA MSC*.  
  <https://msc.fema.gov/portal/advanceSearch#searchresultsanchor>

#### Key Fields Utilized

- `S_FLD_HAZ_AR` (Flood Hazard Areas)

Includes:

- `AE` — 100-year floodplain
- `VE` — coastal high hazard
- `X` — low risk

#### Flood Zone Processing Notes

- Flood zones clipped to study area
- Symbology set to **Unique Values**
- `X` and `OPEN WATER` layers deselected for visual clarity
- *Select By Attributes* used with inverted query:

```sql
FLD_ZONE = 'OPEN WATER'
OR FLD_ZONE = 'X'
  Post Storm imagery
    “ArcGIS.” Arcgis.com, 2026, www.arcgis.com/home/item.html?id=2dc2428b306d4ec1bf2a9cf747270d09. Accessed 10 May 2026.
