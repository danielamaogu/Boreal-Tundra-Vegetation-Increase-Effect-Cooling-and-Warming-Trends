# Boreal-Tundra-Vegetation-Increase-Effect-Cooling-and-Warming-Trends


## Introduction

This Code and the associated ESRI File Geodatabase contain the code, workflows, and post-processed geospatial datasets developed for the study:

**Northward Expansion of High-Stature Vegetation Reveals Net Surface-Cooling Feedbacks in the Majority of Canadian Boreal–Tundra Ecozones**

**Authors:** Amaogu, D. C., Ofosu, E., Dsouza, K. B., Pigeon, J., Arenson, L. U., Boudreault, R., Moreno-Cruz, J., Leonenko, Y., & Maghoul, P. (2025)


## Data Availability and Description

All raster and gridded GeoTIFF datasets produced as **final outputs of this research**, and post-processed in **Google Earth Engine** and **ArcGIS Pro**, are stored in a single ESRI File Geodatabase (**Amaogu_et_al.gdb**). This geodatabase contains the complete set of vegetation, land-cover, NDVI, and surface energy flux trend products used in the analyses and figures presented in the manuscript.

The geodatabase is fully readable in **ESRI Geodatabase format**, can be opened directly in **ArcGIS Pro**, and can be downloaded from the following link:  
https://drive.google.com/file/d/1m7XNTTHN9X5HuFTkfKJBap4l30jRM0N4/view?usp=sharing

---

## Vegetation and Land-Cover Related Outputs

1. **COMBINEDVCGL**  
   Grid containing combined vegetation and land-cover greening/loss patterns derived from long-term land-cover transition analysis.

2. **linearslope_mosaic**  
   Linear slope of NDVI trends representing long-term vegetation change across the study domain. Pixel locations exhibiting non-significant monotonic trends were thresholded to zero.

---

## Net and Total Energy Trend Outputs

3. **Net_energy_trend**  
   Signed net surface energy trend raster obtained by summing warming trend grids with cooling trend grids.

4. **Cooling_total_trend**  
   Total cooling contribution from surface energy fluxes, representing all flux trends with negative values (dominant outward energy flow tendencies).

5. **Warming_total_trend**  
   Total warming contribution from surface energy fluxes, representing all flux trends with positive values (dominant inward energy flow or reduced negative flux magnitudes).

---

## Spring Season Energy Flux Trends

6. **spring_latent_cooling**  
   Spring latent heat flux trend contributing to surface cooling.

7. **spring_latent_warming**  
   Spring latent heat flux trend contributing to surface warming.

8. **spring_sens_cooling**  
   Spring sensible heat flux trend contributing to surface cooling.

9. **spring_sens_warming**  
   Spring sensible heat flux trend contributing to surface warming.

10. **spring_imb_cooling**  
    Spring ground heat flux trend contributing to cooling.

11. **spring_imb_warming**  
    Spring ground heat flux trend contributing to warming.

---

## Summer Season Energy Flux Trends

12. **sum_latent_cooling**  
    Summer latent heat flux trend contributing to surface cooling.

13. **sum_latent_warming**  
    Summer latent heat flux trend contributing to surface warming.

14. **sum_sens_cooling**  
    Summer sensible heat flux trend contributing to surface cooling.

15. **sum_sens_warming**  
    Summer sensible heat flux trend contributing to surface warming.

16. **sum_imb_cooling**  
    Summer ground heat flux trend contributing to cooling.

17. **sum_imb_warming**  
    Summer ground heat flux trend contributing to warming.

---

## Fall Season Energy Flux Trends

18. **fal_latent_cooling**  
    Fall latent heat flux trend contributing to surface cooling.

19. **fal_latent_warming**  
    Fall latent heat flux trend contributing to surface warming.

20. **fal_sens_cooling**  
    Fall sensible heat flux trend contributing to surface cooling.

21. **fal_sens_warming**  
    Fall sensible heat flux trend contributing to surface warming.

22. **fal_imb_cooling**  
    Fall ground heat flux trend contributing to cooling.

23. **fal_imb_warming**  
    Fall ground heat flux trend contributing to warming.

---

## Winter Season Energy Flux Trends

24. **wint_latent_cooling**  
    Winter latent heat flux trend contributing to surface cooling.

25. **wint_latent_warming**  
    Winter latent heat flux trend contributing to surface warming.

26. **wint_sens_cooling**  
    Winter sensible heat flux trend contributing to surface cooling.

27. **wint_sens_warming**  
    Winter sensible heat flux trend contributing to surface warming.

28. **wint_imb_cooling**  
    Winter ground heat flux  trend contributing to cooling.

29. **wint_imb_warming**  
    Winter ground heat flux trend contributing to warming.

---

## Spatial Reference Layer

30. **Study_ecozones**  
    Ecozone boundary layer used for spatial aggregation, comparison, and interpretation of vegetation and surface energy trends.

---

All datasets listed above represent **final processed results**, not intermediate files. They correspond directly to the analyses, maps, and interpretations presented in the manuscript and are provided to allow reviewers to easily locate, inspect, and reproduce the reported results.


## Code and Data Citation Guidance

If you use the code, workflows, or datasets provided in this Code Ocean capsule or the associated ESRI File Geodatabase, please cite the following paper:

**Northward Expansion of High-Stature Vegetation Reveals Net Surface-Cooling Feedbacks in the Majority of Canadian Boreal–Tundra Ecozones**

**Authors:** Amaogu, D. C., Ofosu, E., Dsouza, K. B., Pigeon, J., Arenson, L. U., Boudreault, R., Moreno-Cruz, J., Leonenko, Y., & Maghoul, P. (2025)

### BibTeX
```bibtex
@article{Amaogu2025BorealCooling,
  author = {Amaogu, Daniel Chukwuemeka and
            Ofosu, Enoch and
            Dsouza, Kevin Bradley and
            Pigeon, Jerome and
            Arenson, Lukas U. and
            Boudreault, Richard and
            Moreno-Cruz, Juan and
            Leonenko, Yuri and
            Maghoul, Pooneh},
  title = {Northward Expansion of High-Stature Vegetation Reveals Net Surface-Cooling Feedbacks in the Majority of Canadian Boreal--Tundra Ecozones},
  year = {2025},
  note = {Code and data used in this study}
}



