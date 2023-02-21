# Data

Data in the `data` folder includes (to be shared):

* `inventories/`
  * `Paracou_P16_2020.csv`: Guyafor inventory in the plot 16 from Paracou in 2020.
  * `Plantules répertoriées.tsv`: Seedling inventory by FTH.
  * `UnderstoryDatabase.xlsx`: Inventory data from the understory project (Giacomo Sellan) with trees between 1 and 10 cm in diameter (DBH).
* `rasters/`
  * `ChnlDist_FTH22.tif`: Distance to the nearest creek via (1) obtaining the hydrographic network derived from the 2016 Digital Terrain Model (DTM) through the SAGA module "channel network" and (2) the distance to the nearest creek through the SAGA module "Overland flow distance to channel network". The data were validated for the 1/6/11 plots using the hydromorphic/water table depth maps from (Morneau, 2007).
  * `DCM2016_FTH22.tif`: Digital canopy model from lidar data issues des relevés de 2016.
  * `DEM2016_FTH22.tif`: Digital elevation model from lidar data from 2016 surveys.
  * `Transmittance4ha10mP16C14-15-19-20.tif`: Transmittance map obtained with lidar data (see Lisa Moreno's internship report and code).
  * `TWI_1m.tif`: Topogrpahic Wetness Index derived from 1m DEM.
* `shapefiles/`
  * `OverallPlots`: Limits of Paracou plots in shapefile.
  * `ContourLinesPlots`: Elevation contour lines of Paracou plots in shapefile.
  * `TopographicLevels`: Topographic levels of Paracou plots in shapefile.
* `fth/`: Raw data from FTH's field (picture and tables).
