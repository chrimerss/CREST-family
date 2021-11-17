CREST Version 1.x
=========================

.. contents::

CREST model V1.x, a distributed hydrologic model, is jointly developed at the University of Oklahoma and NASA.

.. Note:: CREST model V1.x is an initial publication, featuring hydrologic processes including
   canopy interception, Variable Infiltration Curve for soil infiltration, three cascading soil layers,
   Linear Reservoir Routing for surface flow and subsurface flow

__

.. figure:: images/CRESTV1x.png
   :alt: CREST V1.x structure

   Figure 1. CREST V1.x model structure
__

.. csv-table:: Table 1. CREST V1.x parameters table
   :file: tables/parametersV1.csv
   :widths: 30, 30, 30, 30
   :header-rows: 1


__
CREST V1.0
---------

:Author: Jiahu Wang, Sadiq Khan, Yang Hong
:Year of publication: 2011
:Software repo: http://hydro.ou.edu/research/crest/
:Program language: Fortran

Applications
~~~~~~~~~~
1. Description of initial version of CREST model [`link1`_] [Wang2011]_
2. Microwave Satellite Data for Hydrologic Modeling in Ungauged Basins [`link2`_] [Khan2010]_
3. Hydroclimatology of Lake Victoria region using hydrologic model and satellite remote sensing [`link3`_] [Khan2011]_


.. _link1: https://www.tandfonline.com/doi/full/10.1080/02626667.2010.543087
.. _link2: https://ieeexplore.ieee.org/document/5559412
.. _link3: https://hess.copernicus.org/articles/15/107/2011/



CREST V1.6
-----------
:Author: Huan Wu, Sadiq Khan, Xianwu Xue, Yang Hong
:Year of publication: 2012
:Software repo: http://hydro.ou.edu/research/crest/
:Program language: Fortran

Applications
~~~~~~~~~~~~~
1. Flood simulation [`link4`_] [Anagnostou2015]_
2. Global Flood Detection [`link5`_] [Wu2012]_
3. Evaluation of hydrologic utility of the Satellite precipitation dataset [`link6`_] [Meng2014]_
4. Global Flood Forecast [`link7`_] [Zhang2015]_

.. _link4: https://www.researchgate.net/profile/Muhammet-Dis/publication/281618104_Evaluating_Multi-Scale_Flow_Predictions_for_the_Connecticut_River_Basin/links/569772ee08aea2d7437568d6/Evaluating-Multi-Scale-Flow-Predictions-for-the-Connecticut-River-Basin.pdf
.. _link5: https://doi.org/10.1175/JHM-D-11-087.1
.. _link6: https://www.sciencedirect.com/science/article/pii/S0022169413008731
.. _link7: https://doi.org/10.1175/JHM-D-14-0048.1

Publications
-----
.. [Wang2011] Wang, J., Hong, Y., Li, L., Gourley, J. J., Khan, S. I., Yilmaz, K. K., ... & Okello, L. (2011). The coupled routing and excess storage (CREST) distributed hydrological model. Hydrological sciences journal, 56(1), 84-98.
.. [Khan2010] Khan, S. I., Hong, Y., Wang, J., Yilmaz, K. K., Gourley, J. J., Adler, R. F., ... & Irwin, D. (2010). Satellite remote sensing and hydrologic modeling for flood inundation mapping in Lake Victoria basin: Implications for hydrologic prediction in ungauged basins. IEEE Transactions on Geoscience and Remote Sensing, 49(1), 85-95.
.. [Khan2011] Khan, S. I., Adhikari, P., Hong, Y., Vergara, H., F Adler, R., Policelli, F., ... & Okello, L. (2011). Hydroclimatology of Lake Victoria region using hydrologic model and satellite remote sensing data. Hydrology and Earth System Sciences, 15(1), 107-117.
.. [Anagnostou2015] Anagnostou, E., Zac, F., Vergara, H., & Hong, Y. (2015). Evaluating multi-scale flow predictions for the Connecticut River Basin. Hydrology: Current Research, 6(2), 1.
.. [Wu2012] Wu, H., Adler, R. F., Hong, Y., Tian, Y., & Policelli, F. (2012). Evaluation of global flood detection using satellite-based rainfall and a hydrologic model. Journal of Hydrometeorology, 13(4), 1268-1284.
.. [Meng2014] Meng, J., Li, L., Hao, Z., Wang, J., & Shao, Q. (2014). Suitability of TRMM satellite rainfall in driving a distributed hydrological model in the source region of Yellow River. Journal of Hydrology, 509, 320-332.
.. [Zhang2015] Zhang, Y., Hong, Y., Wang, X., Gourley, J. J., Xue, X., Saharia, M., ... & Tang, G. (2015). Hydrometeorological analysis and remote sensing of extremes: Was the July 2012 Beijing flood event detectable and predictable by global satellite observing and global weather modeling systems?. Journal of hydrometeorology, 16(1), 381-395.