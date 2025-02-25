# 15: South Asia East

Regions `13`, `14`, `15` comprise the region that is often referred to as High Mountain Asia. Region 15 encompasses (a) all the glaciers of western and central Himalaya that drain into the Ganges and Yarlung Tsango/ Brahmaputra, (b) all glaciers in the eastern Himalaya, apart from the glaciers on the north slope of the greater Himalaya that drain into Lake Puma Yumco (close to Bhutan) and on the northern slope of the Namcha Barwa Himal (the easternmost section of the Himalaya), and (c) all glaciers in the south-eastern part of the Nyainqntanglha (also “Nyenchen Tanglha”) Mountains and the Hengduan Shan. 

```{admonition} Subregions
:class: note, dropdown

- 15-01: Central Himalaya
- 15-02: East Himalaya
- 15-03: Hengduan Shan

```

:::{figure-md} rgi15-new-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI15/isrgi6_map.jpeg" alt="region map" class="bg-primary mb-1">

Regional glacier area.
:::

## Changes from version 6.0 to 7.0

All previous outlines have been replaced by the GAMDAM glacier inventory version 2 GGI {cite:p}`Sakai2019`, also named GGI18. The glaciers were manually mapped based on Landsat TM and ETM+ summer imagery with most scenes being from the years 1994, 1998, 1999, 2002 and 2005. Some scenes from the period 1992 - 2010 were used in case of unsuitable scenes within these years. In the Khumbu region outlines were manually mapped based on very-high resolution satellite imagery (WorldView, Pléiades, Ikonos) and DEM differencing results from {cite:t}`King2020`.

## Additional information 

```{admonition} Data sources and analysts
:class: important, dropdown

:::{figure-md} rgi15-source-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI15/inventory_map.jpeg" alt="region map" class="bg-primary mb-1">

Submission IDs used for this region.
:::

**Glacier outline providers to GLIMS**

*This list includes the providers of the outlines used in the RGI 7.0 as generated automatically from the GLIMS outlines metadata. We acknowledge that the list may be incomplete due to omissions in the GLIMS database.*

Submission 752
: **Submitter**: Sakai, Akiko.<br/>**Number of outlines**: 18578. **Area**: 15964.1km². **Release date**: 2018-08-24.<br/>**Analysts**: Sakai, Akiko.

Submission 765
: **Submitter**: Bolch, Tobias.<br/>**Number of outlines**: 9. **Area**: 85.3km². **Release date**: 2022-05-01.<br/>**Analysts**: Bolch, Tobias.

Reviewers
: Bolch, Tobias;

```

```{admonition} Outlines date distribution
:class: seealso, dropdown

:::{figure-md} rgi15-hist-fig
<img src="https://cluster.klima.uni-bremen.de/~fmaussion/misc/rgi7_data/l4_rgi7b0_plots/RGI15/date_hist.png" alt="region map" class="bg-primary mb-1">

Relative glacier area distribution per outline date.
:::

```

```{admonition} Version history
:class: note, dropdown

Changes from Version 5.0 to 6.0
: None.

Changes from Version 4.0 to 5.0
: Regions 13, 14 and 15 are entirely new in version 5.0. being taken from {cite:t}`Nuimura2015`, {cite:t}`Guo2015` and as-yet unpublished work at the Technical University of Dresden and University of Zürich. *Remark (2023): the outlines have now been published: {cite:t}`Molg2018`*. The Dresden/Zürich outlines cover the Karakoram in region 14.<br/>The GAMDAM inventory of {cite:t}`Nuimura2015` covers all of High Mountain Asia (including RGI region 10-04). The Second Chinese Glacier Inventory (CGI2) of {cite:t}`Guo2015` covers China and Arunachal Pradesh. The GAMDAM outlines are nearly all from 1999–2003 and thus conform with the recommendation of {cite:t}`Paul2009` to select imagery as close to 2000 as possible. However they exclude thin ice on headwalls and in that sense are not in conformance with GLIMS guidelines {cite:p}`Raup2007`. The CGI2 inventory has outlines mostly from a target period of 2006–2010, but includes older outlines from the First Chinese Glacier Inventory (CGI1) where suitable imagery could not be found within the target period.<br/>A final decision about selection for the RGI from these extensive sources awaits detailed intercomparison. RGI version 5.0 incorporates those CGI2 outlines that are not from CGI1, and GAMDAM outlines in areas of remaining CGI1 coverage as well as areas outside China.<br/>Glacier outlines retired from version 4.0 will be added to GLIMS if they are not in GLIMS already.<br/>Links were added to 5 glaciers in the WGMS mass-balance database.

Changes from Version 3.2 to 4.0
: Nine exterior GLIMSIds were replaced. Topographic and hypsometric attributes were added.<br/>Dates were recovered for as many glaciers as possible. For Bhutan, a polygon enclosing the glaciers inventoried by ICIMOD was created and subdivided into three polygons, one for each of the image sets from which the glaciers were identified. The RGI 3.2 glaciers within each polygon were assigned the date of the corresponding image, verified by comparison with the glacier-by-glacier lists in the source. Equivalent procedures were adopted for Sikkim and the basins of the Pum (upper Arun) and Poi and Rongxer (upper Bhote–Sun Koshi and Tama Koshi) rivers. Glaciers elsewhere in Nepal were assigned a date range from 2008 to 2009 (ICIMOD), consistent with those in earlier versions.<br/>See Region 13: Central Asia for the recovery of dates for Chinese glaciers. Where RGI glacier outlines from the first Chinese Glacier Inventory could be matched with confidence to their equivalents in GLIMS, their 12-character WGI identification codes were added to the Name field.

Changes from Version 3.0 to 3.2
: None.

Changes from Version 2.0 to Version 3.0
: Outlines of the glaciers of Burma, provided by S. Bajracharya, were added.

Changes from Version 1.0 to Version 2.0
: None.

Version 1.0
: Large parts of the Himalaya are covered by the GLIMS database. For the RGI, GLIMS was used as the source where no other was available, mainly on the northern slopes of the Himalayas. In these regions, the GLIMS database consists mostly of data from the first Chinese Glacier Inventory {cite:p}`Shi2009a` and is of heterogeneous and generally slightly lower quality than the other glacier data used here. Glacier outlines compiled by ICIMOD were used for the central and eastern Himalayas. For Nepal, more recent information from 2008 and 2009 is available and was used here (ICIMOD).

```
