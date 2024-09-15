# ColabRNN
This is a regression model applied on the Metro Interstate Traffic Volume Dataset using RNNs (via tensorflow 2.17.0).

The dataset has the 8 features and 1 target (traffic volume). In addition, there are 48204 observations. 

	name	role	type	unit
0	holiday	Feature	Categorical	None
1	temp	Feature	Continuous	Kelvin
2	rain_1h	Feature	Continuous	mm
3	snow_1h	Feature	Continuous	mm
4	clouds_all	Feature	Integer	%
5	weather_main	Feature	Categorical	None
6	weather_description	Feature	Categorical	None
7	date_time	Feature	Date	None
8	traffic_volume	Target	Integer	None
![image](https://github.com/user-attachments/assets/0ca34494-29cf-4748-acf9-f787c5fc5691)
                               

This project was inspired by the Deep Learning A-Z 2024 Course part 3 on Udemy.

Reference for the dataset: Hogue, J. (2019). Metro Interstate Traffic Volume [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5X60B.
