# ColabRNN
This is a regression model applied on the Metro Interstate Traffic Volume Dataset using RNNs (via tensorflow 2.17.0).

The dataset has the 8 features and 1 target (traffic volume). In addition, there are 48204 observations. 

                 name     role         type      demographic  Unit
0              holiday  Feature  Categorical        None      None
1                 temp  Feature   Continuous        None      Kelvin
2              rain_1h  Feature   Continuous        None      mm
3              snow_1h  Feature   Continuous        None      mm
4           clouds_all  Feature      Integer        None      %
5         weather_main  Feature  Categorical        None      None
6  weather_description  Feature  Categorical        None      None
7            date_time  Feature         Date        None      None
8       traffic_volume   Target      Integer        None      None                                  

This project was inspired by the Deep Learning A-Z 2024 Course part 3 on Udemy.

Reference for the dataset: Hogue, J. (2019). Metro Interstate Traffic Volume [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5X60B.
