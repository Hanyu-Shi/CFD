# CFD
Canopy chlorophyll Fluorescence with leaf Dorsiventrality

### A canopy-level radiative transfer model for simulating fluorescence with leaf dorsiventrality considered.

### 1. Leaf dorsiventrality 

See the LFD model (https://github.com/Hanyu-Shi/LFD) for leaf dorsiventrality 

### 2. Input

* Geometry and solar
```
Solar zenith angle                    
Solar azimuth angle                    
View zenith angle                      
View azimuth angle 
Direct solar radiation                 
Diffuse solar radiation  
```

* Canopy
``` 
Number of leaf zenith angles         
Leaf inclination distribution function                       
Leaf area index                        
Hotspot parameter
```

* Leaf (see LFD: https://github.com/Hanyu-Shi/LFD)
``` 
Leaf reflectance and transmittance         
Leaf PS-I fluorescnece matrix       
Leaf PS-II fluorescnece matrix 
```

* Soil
``` 
SOIL(1): bi-directional reflectance
SOIL(2): directional-hemispherical reflectance
SOIL(3): hemispherical-directional reflectance
SOIL(4): bi-hemispherical reflectance
```




### 3. Output

* cfluo
```
cfluo(:,1): directional fluorescence 
cfluo(:,2): hemispherical fluorescence 
cfluo(:,3): emitted fluorescence 
```

### 4. Citation

* Shi H. (2024). Exploring vegetation chlorophyll fluorescence with leaf dorsiventrality. (under review)
* Shi H., Xiao Z. (2022). A Canopy Radiative Transfer Model Considering Leaf Dorsoventrality. IEEE Trans. Geosci. Remote Sens. 60, 2002711. https://doi.org/10.1109/TGRS.2021.3119315
