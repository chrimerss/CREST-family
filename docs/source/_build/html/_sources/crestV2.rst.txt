CREST V2.x
===============

.. contents::

.. Note:: CREST model V2.x supports a set of new features compared to CREST V1.x, including:

    1. activating distributed parameters over regions where remotely sensed data is available

    2. the replacement of three soil layers to one bulk soil layer

    3. including impervious area ratio parameter to emulate fast runoff generation

    4. including a rainfall multiplier parameter to overcome bias

    5. automatic calibration using the SCE-UA algorithm (Duan et al., 1992)

    6. parallel computing

    7. modular design framework.

__

.. figure:: images/CRESTV2x.png
   :alt: CREST V2.x structure

   Figure 2. CREST V2.x model structure

.. csv-table:: Table 1. CREST V2.x parameters table
   :file: tables/parametersV2.csv
   :widths: 30, 30, 30, 30
   :header-rows: 1
__
CREST V2.0
---------
:Author: Xianwu Xue, Yang Hong,
:Year of publication: 2013
:Software repo: `HyDROS`_
:Program language: Fortran

.. _HyDROS: http://hydro.ou.edu/research/crest/

Applications
~~~~~~~~~~~~~~
1. Description of CREST V2.0 [`link1`_] [Xue2013]_
2. Hydrologic utility of satellite precipitation products [`link2`_] [Tang2016]_

.. _link1: https://doi.org/10.1016/j.jhydrol.2013.06.042
.. _link2: https://doi.org/10.1175/JHM-D-15-0059.1


__
CREST V2.1
---------
:Author: Xinyi Shen, J.J. Gourley, Yang Hong, 
:Year of publication: 2017
:Software repo: `HyDROS`_
:Program language: Matlab

.. _HyDROS: http://hydro.ou.edu/research/crest/

.. Note:: CREST V2.1 improves routing scheme in CREST V2.0, from its original Quasi-Distributed Linear Reservoir Routing (QDLRR) to Fully-Distributed Linear Reservoir Routing (FDLRR)


Applications
~~~~~~~~~~~~~
1. Description of CREST V2.1 [`link3`_] [Shen2017]_
2. Parameter uncertainties in CREST V2.1 [`link4`_] [Gan2018]_
3. Water resources management [`link5`_] [Lakew2020]_
4. Flood simulation [`link6`_] [Blanton2020]_

.. _link3: https://doi.org/10.1175/JHM-D-15-0059.1
.. _link4: https://doi.org/10.1016/j.jhydrol.2018.07.055
.. _link5: https://link.springer.com/article/10.1007/s11269-019-2190-y
.. _link6: https://doi.org/10.1111/risa.13004

References
--------------

.. [Xue2013] Xue, X., Hong, Y., Limaye, A. S., Gourley, J. J., Huffman, G. J., Khan, S. I., ... & Chen, S. (2013). Statistical and hydrological evaluation of TRMM-based Multi-satellite Precipitation Analysis over the Wangchu Basin of Bhutan: Are the latest satellite precipitation products 3B42V7 ready for use in ungauged basins?. Journal of Hydrology, 499, 91-99.
.. [Tang2016] Tang, G., Zeng, Z., Long, D., Guo, X., Yong, B., Zhang, W., & Hong, Y. (2016). Statistical and hydrological comparisons between TRMM and GPM level-3 products over a midlatitude basin: Is day-1 IMERG a good successor for TMPA 3B42V7?. Journal of Hydrometeorology, 17(1), 121-137.
.. [Shen2017] Shen, X., Hong, Y., Zhang, K., & Hao, Z. (2017a). Refining a distributed linear reservoir routing method to improve performance of the CREST model. Journal of hydrologic engineering, 22(3), 04016061.
.. [Gan2018] Gan, Y., Liang, X. Z., Duan, Q., Ye, A., Di, Z., Hong, Y., & Li, J. (2018). A systematic assessment and reduction of parametric uncertainties for a distributed hydrological model. Journal of hydrology, 564, 697-711.
.. [Lakew2020] Lakew, H. B., Moges, S. A., Anagnostou, E. N., Nikolopoulos, E. I., & Asfaw, D. H. (2020). Evaluation of global water resources reanalysis runoff products for local water resources applications: case study-upper Blue Nile basin of Ethiopia. Water Resources Management, 34(7), 2157-2177.
.. [Blanton2020] Blanton, B., Dresback, K., Colle, B., Kolar, R., Vergara, H., Hong, Y., ... & Wachtendorf, T. (2020). An Integrated Scenario Ensemble‐Based Framework for Hurricane Evacuation Modeling: Part 2—Hazard Modeling. Risk analysis, 40(1), 117-133.