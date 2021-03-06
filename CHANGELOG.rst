
Changelog
=========

0.6.3 (2020-04-11)
------------------

* Fixed error in calculation adaptive ASHRAE
* Added some examples

0.6.3 (2020-03-17)
------------------

* Renamed function to_calc to t_o
* Fixed error calculation of relative air velocity
* renamed input parameter ta to tdb
* Added function to calculate mean radiant temperature from black globe temperature
* Added function to calculate solar gain on people
* Added functions to calculate vapour pressure, wet-bulb temperature, dew point temperature, and psychrometric data from dry bulb temperature and RH
* Added authors
* Added dictionaries with reference clo and met values
* Added function to calculate enthalpy

0.5.2 (2020-03-11)
------------------

* Added function to calculate the running mean outdoor temperature

0.5.1 (2020-03-06)
------------------

* There was an error in version 0.4.2 in the calculation of PMV and PPD with elevated air speed, i.e. vr > 0.2 which has been fixed in this version
* Added function to calculate the cooling effect in accordance with ASHRAE

0.4.1 (2020-02-17)
------------------

* Removed compatibility with python 2.7 and 3.5

0.4.0 (2020-02-17)
------------------

* Created adaptive_EN, v_relative, t_clo, vertical_tmp_gradient, ankle_draft functions and wrote tests.
* Added possibility to decide with measuring system to use SI or IP.

0.3.0 (2020-02-13)
------------------

* Created set_tmp, adaptive_ashrae, UTCI functions and wrote tests.
* Added warning to let the user know if inputs entered do not comply with Standards applicability limits.

0.1.0 (2020-02-11)
------------------

* Created pmv, pmv_ppd functions and wrote tests.
* Documented code.

0.0.0 (2020-02-11)
------------------

* First release on PyPI.
