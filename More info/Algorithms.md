Algorithms of raster calculator DEM, Slope and wind data
```
   (("DEM files@1" > 603)*1) + (("DEM files@1" > 1207)*1) + (("DEM files@1" > 1809)*1) + (("DEM files@1" > 2412)*1)
   (("Slope@1" <= 48.6)*1)+(("Slope@1" <= 38.9)*1)+(("Slope@1" <= 29.2)*1)+(("Slope@1" <= 19.4)*1)+(("Slope@1" <= 9.72)*1)
   (("Wind data MS band 1 reclassified@1" <= 199)*1)+(("Wind data MS band 1 reclassified@1" <= 177)*1)+(("Wind data MS band 1 reclassified@1" <= 155)*1)+(("Wind data MS band 1 reclassified@1" <= 133)*1)+(("Wind data MS band 1 reclassified@1" <= 110)*1)
   (("Wind data MS band 2 reclassified@1" <= 214)*1)+(("Wind data MS band 2 reclassified@1" <= 198)*1)+(("Wind data MS band 2 reclassified@1" <= 182)*1)+(("Wind data MS band 2 reclassified@1" <= 166)*1)+(("Wind data MS band 2 reclassified@1" <= 149)*1)
   (("Wind data MS band 3 reclassified@1" <= 199)*1)+(("Wind data MS band 3 reclassified@1" <= 177)*1)+(("Wind data MS band 3 reclassified@1" <= 155)*1)+(("Wind data MS band 3 reclassified@1" <= 133)*1)+(("Wind data MS band 3 reclassified@1" <= 110)*1)

```

##### Weighting of DEM, slope and wind data:
##### wind = 70% (most important at our chosen area at the coast)
##### DEM = 10% (doesn´t really matter because at our chosen area at the cost the elevation is nearly the same at any place at a low level)
##### slope = 20% (less weight, because 1.) at the cost less slope and 2.) mainly affects „just“ the costs of installation)

